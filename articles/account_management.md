# Account Management
{:.no_toc}

- TOC
{:toc}

OAQ is designed to be a multi-tenant platform, which means multiple publishers can use it simultaneously with their own users and branding. This means your organization's data will remain invisible to other publishers.

Note that when we say "publisher" in this documentation, we mean an organization with an [organization type](organizations) of **publisher**. The other organization type available is [**library**](https://oaq-docs.github.io/library-workflow).

## Types of account roles

The OAQ application supports several types of **account roles**, each with different views and permissions. Here they are in order from most to least access:

| Account role | Permissions |
|--|--|
|Site admin| Can see and manage all organizations, including creating organizations and inviting users to an organization. Currently limited to Harvard library staff. |
|Organization admin | Can [invite staff to the organization](#inviting-others-to-the-organization), [manage organization users](organizations#managing-organization-users), [edit organization details](organizations#editing-organization-details), [create new questionnaires](questionnaires#creating-a-new-questionnaire), [manage questionnaires](questionnaires#actions-you-can-perform-on-a-questionnaire), [send questionnaires to authors](questionnaires#sending-a-questionnaire-to-an-author), and [manage author responses](responses#managing-author-responses). |
|Organization staff | Can [create new questionnaires](questionnaires#creating-a-new-questionnaire), [manage questionnaires](questionnaires#actions-you-can-perform-on-a-questionnaire), [send questionnaires to authors](questionnaires#sending-a-questionnaire-to-an-author), and [manage author responses](responses#managing-author-responses). |
|Author | Can view, save, and submit questionnaires. |

## Getting started as an organization admin

Before anyone from your organization can do anything in OAQ, a site admin will need to create your organization with some preliminary information that your staff can [edit later](organizations#editing-organization-details).

Your experience as a publisher in OAQ begins when the site admin invites the first member (or members) to the organization to be an  **organization admin**.

Each invited organization admin will receive an email that contains an invitation link. If you receive one of these emails and click the link, you will be taken to a page in OAQ where you can confirm your account and create a password. Note that you can always [change your password](account_management#changing-your-password) later.

## Partnering with libraries

OAQ facilitates the sharing of questionnaire data between publishers and libraries. As a publisher, you can [share author responses](responses#accepting-a-response) with any library of your choosing. Only OAQ [site admins](#types-of-account-roles) can set up publisher–library partnerships, so talk to the site admin who creates your organization about the libraries you wish to work with.

## Inviting others to the organization

If you are an organization admin, once you have confirmed your account, you will have the ability to invite additional members to the organization and set their [roles](#types-of-account-roles) as either **admin** or **staff**. You can also [delete and restore users](organizations#managing-organization-users) as needed.

## Logging in and out

To log out of OAQ, simply click the user icon in the top bar and click **Logout**.

To log in again, click **Sign In** in the top bar.

## Changing your password

You can change your password at any time by clicking the user icon in the top bar and selecting **Change Password**.
