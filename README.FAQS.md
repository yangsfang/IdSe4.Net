# IdSe4.Net FAQS

## What is IdSe4.Net?

IdSe4.Net is an open source fork of IdentityServer4 for .NET 6 and beyond. Note the 4 in the name is a stylized "for" (in the same spirit as log4net).

## Who are you

I'm an entrepreneur currently working on a shopping related project (not public yet, but my team will update at [ritenext.com](https://ritenext.com) soon!). I previously worked at Google and JP Morgan. 

## Why

Since the original authors of IdentityServer4 moved on to create Duende, IdentityServer4 will be archived at .NET Core 3.1. Duende is under RPL, a source available license with severe commercial use restrictions. 
My project needs a identity management library for our new backend application. As .NET Core 3.1's end of life is rapidly approaching, starting with IdentityServer4 on .NET Core 3.1 isn't an option. 
My project team also determined that Duende isn't for us. So we decided to port IdentityServer4 to .NET 6 under a new name. 

## What is the license?

IdSe4.Net will continue to be licensed under Apache 2.0. 

## Can't you contribute to IdentityServer4?

The original authors of IdentityServer4 has made it clear [they don't intend to accept contributions](https://github.com/IdentityServer/IdentityServer4/issues/5354).

## Can you call it IdentityServer 4/5/6?

we can't continue using its old name because we don't own it. That also means we will rename the package and namespace.

## Are you trying to compete with Duende?

No. My project is not about making identity frameworks. I do not intend to make money from this. I'm simply maintaining this project for my own use and sharing it with the open source community.

## What is the current status? 

As of September 2022, the project currently builds under .NET6. There are a few bugs. Also the project is still using Newtonsoft.Json rather than System.Text.Json. Since .NET 6 and all supporting libraries are moving to System.Text.Json, we also intend to complete the migration.

## Do you have a Nuget.org link?

Not currently. We are not release ready yet. And we also do not intend to pay for a code signing certificate (~$100). That means we may provide downloads on github rather than nuget.org. 
Please contact me if you're willing to sponsor a code signing certificate, or you have an existing code signing certificate willing to sign for this project. 

## Can I use this today?

Yes. You can clone this project as a submodule in your project and use it as a project reference. The are a few bugs though. Plesae use at your own risk.

## Can you add X feature?

No. As my project is not in the business of providing identity solutions, I do not intend to add extra features. The intention is to keep the existing code alive and compatible with the latest .NET LTS SDK. There are companies that specialize in identity solutions including Duende. Please feel free to investigate alternative or fork this code. 

## What if I send you merge requests

I appreciate the help. I certainly welcome community help to maintain IdSe4.Net. Bugfixes are welcomed. 
But new features tend to introduce new bugs and this project tries to maintain stability of the existing code. So unless I understand your code very well and it has been proven flawless, I'm unlikely to merge it. Please feel free to discuss on the issue tracker before starting the feature work. 

## What is your current road map for IdSe4Net?

I intend to fix breaking bugs and make a release before December 2022 (end of support for .NET Core 3.1). Feel free to report any bugs on github. 
