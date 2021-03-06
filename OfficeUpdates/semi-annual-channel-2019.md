---
title: "Release notes for Semi-Annual Channel releases in 2019"
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 1/29/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: "Provides IT Pros with release notes for Semi-Annual Channel releases for Office 365 ProPlus in 2019"
---

# Release notes for Semi-Annual Channel releases in 2019

These release notes provide information about new features, security updates, and non-security updates that are included in Semi-Annual Channel updates to Office 365 ProPlus in 2019. 

> [!NOTE]
> - The following also provides information about new features, security updates, and non-security updates for Visio Pro for Office 365 and Project Online Desktop Client.
> - This information also applies to Office 365 Business, which is the version of Office that comes with some Office 365 plans, such as Business Premium.
> - Semi-Annual Channel was named Deferred Channel prior to January 2019.

> [!NOTE]
> - The security updates information for each update channel of Office 365 ProPlus will start being listed separately at [Security Updates](office365-proplus-security-updates.md).

## Version 1708: June 07
*Version 1708 (Build 8431.2372)*

Security updates listed [here](https://docs.microsoft.com/en-us/officeupdates/office365-proplus-security-updates)

## Version 1803: June 07
*Version 1803 (Build 9126.2356)*

Security updates listed [here](https://docs.microsoft.com/en-us/officeupdates/office365-proplus-security-updates)

## Version 1808: June 07
*Version 1808 (Build 10730.20280)*

## Version 1803: June 07
*Version 1803 (Build 9126.2387)*

## Version 1808: June 07
*Version 1808 (Build 10730.20344)*

## Version 1808: January 8
*Version 1808 (Build 10730.20264)*

### Access: Feature Updates

 - **Visualize data with new charts:** Choose from 11 charts and add one to your forms and reports to better visualize the data and make informed decisions. [Learn more](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)


### Excel: Feature updates
 - **Collaborative editing:** Work with others at the same time in your workbook. [Learn more](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **AutoSave for cloud files is now enabled by default:** This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to documents. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your workbooks more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only

### Excel: Non-Security updates 

- Fixed an issue in coauthoring sessions where a slicer is not properly updated after another user applies a column filter to the data in that slicer.
- Fixed an issue in a coauthoring session where one of the users clears the caption for a slicer and this causes another user in the coauthoring session to experience an Excel crash.
- Fixed possible crash when creating multiple table slicers bound to the same column of data and then deleting that column of data.
- Fixed an issue where Excel would sometimes crash while refreshing a filtered query table that contains wrapped text in cells when the option to automatically adjust column widths was off.
- Fixed an issue where slicers saved in Excel 2007 can trigger a crash when opened in newer versions of Excel if the number of items shown in the slicer changes.
- Introduces support for the Get Diagnostics button to simplify the investigation of support requests.
- Fixed a bug where Power Pivot did not appear in some builds/versions.
- Fixed the issue in Excel wherein Excel may become unresponsive when the user hovers over formatting options in a workbook with many defined names, and where Excel may become unresponsive in the Quick Analysis tool even when Live Preview was disabled in options.
- We are currently investigating slow performance when moving the Excel Application Window from one desktop to another. In the meantime, if you do notice this slowness then a work around to consider is to select "Optimize for compatibility" for "When using multiple displays" in the "General" tab in the File Options dialog.
- Fixed an issue where Excel may crash when changing a chart's source data from its original set of cells.
- Fixed an issue where recalculation may not happen on open even if the FullCalcOnLoad property is set.  
- Fixed an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.
- When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.
- Fixed an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.
- Fixed an issue where charting actions could cause Excel to crash.
- Fixed an issue where the Power View add-in is inadvertently disabled for some users.
- Fixed an issue where temporary auto-recovery files created during document recovery are never cleaned up.
- Fixed an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.
- Fixed an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.
- Fixed an issue where clicking on a hyperlink may cause Excel to crash.
- Fixed an issue where using cube functions causes Excel to crash.

### Outlook: Feature updates
 - **Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your messages more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Manage Profiles from the Profile Picker:** If you use the Profile Picker when Outlook starts up, you can now make changes without going to the control panel. Create and delete profiles, change settings, all from the Profile Picker.
- **Accessibility built right in:** Make your messages accessible to everyone by adding descriptive alt text to your images.
- **Outlook add-in warnings:** Occasionally an Outlook COM add-in can encounter problems that slows down the rest of Outlook. These problems could be due to latency of events such as switching between Outlook folders, arrival of new emails, opening Calendar items, etc. When such issues arise, Outlook will display a warning in the notification bar.
- **Know who you'll be meeting with:** You can see other people's responses to a meeting request, even if you aren't the organizer.
- **Never miss a reminder:** Set reminders to pop up over windows you're working in. Otherwise, Outlook will blink in the taskbar to get your attention. [Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Mark deleted items as read:** You can now set any message that you delete as read. Opt in by going to File \> Options \> Mail \> Other.
- **View three time zones:** Need to schedule a meeting across time zones? Add multiple time zones to your calendar to easily see everyone's availability and pick a time that works for all. [Learn more](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Refined user experience for creating a group:** We have refined the user experience for the create group to make it look more modern and clutter-free. [Learn more](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### Outlook: Non-Security updates
- Fixed an issue that caused users to experience calendar synchronization errors.
- Fixed an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.
- Fixed an issue that caused users to be unable to connect to their mailboxes over DirectAccess when using a metered connection.
- Fixed an issue that caused users to see free docs stored in Public Folders erroneously open in "Protected View".
- Fixed an issue that caused users to see unexpected attachments when forwarding items with inline attachments.
- Fixed an issue that caused OFT files to render poorly after being sent as an attachment.
- Fixed an issue that caused some add in users to experience crashes when adding a meeting to a shared calendar.
- Fixed an issue that caused users to experience hangs when opening the Conversation History folder.
- Fixed an issue where if you switch the system language to Japanese and attempt to type Japanese characters into the VBA IDE when loaded within Outlook, it freezes.
- Fixed an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.
- Fixed an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.
- Fixed an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.
- Fixed an issue where a meeting location update to attendees shows the old location instead of the new location.
- Fixed an issue where the user sees an error when previewing an attachment in the reading pane.
- Fixed an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.
- Fixed an issue where some users don't receive support features that have been enabled by their tenant admin.

### OneNote: Non-security updates 

- Fixed a stability issue that can occur involving sync and navigating to a deleted section.

### PowerPoint: Feature updates 
- **AutoSave for cloud files is now enabled by default:** This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Convert your ink:** Take scribbled notes and drawings, and convert them into readable text and crisp shapes to create a polished presentation. [Learn more](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Title your slides with a pen:** Use your pen to ink in a title, and watch PowerPoint convert it to text. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only
- **Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your presentations more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)


### PowerPoint: Non-Security updates
- Fixed an issue of potential file corruptions when saving files with ActiveX content.
- Fixed an issue where tables are rendered incorrectly with thick borders.
- Fixed an issue where a potential crash could occur when changing the Shape.Visibile property.
- Fixed an issue where changes in co-authored documents fail to merge.
- Fixed an issue where documents containing ActiveX controls would cause co-authoring to fail.
- Fixed an issue where spelling correction in shapes causes PowerPoint to crash.
- Fixed an issue where PowerPoint crashes when opening a file from SharePoint Online.
- Fixed an issue where the Recovery Pane incorrectly appears when AutoSave is on.
- Fixed an issue where sign-in isn't shown preventing a user from accessing a file.
- Fixed an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.
- Fixed an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.

### Project: Feature updates 
- **Sprint management:** Quickly add, update, or delete agile sprints.
- **Task board filtering:** Streamline your task boards by filtering on key resources or summary tasks.
- **Set percent complete from a task board:** Choose a percent complete for each column, and then update task completion with drag-and-drop.
- **Sprint navigation:** Switch from one sprint view to another, and quickly move tasks between sprints.
- **A new way to manage sprints:** Take an agile approach to working with Task Boards. Go to Manage Sprints to add and remove sprints as your project evolves.
- **Stay organized with Recent save locations:** Project keeps a running list of where you've saved other projects. When you're ready to save your project, just choose one of your Recent save locations and get on with your day.

### Project: Non-Security updates

- Fixed an issue around supporting a new Venezuelan currency in Project.
- Fixed an issue where Project may hang when using a Surface 4 that is connected to an external monitor.
- Fixed an issue where Project may crash when saving the project to the XML format.
- Fixed an issue where enterprise resource custom fields may be deleted after editing a resource's calendar.
- Fixed an issue that caused users to experience crashes when searching for Korean display names.
- Fixed an issue where you are blocked from saving a sub project when working with them through the context of a master project.

### Word: Feature updates
- **AutoSave for cloud files is now enabled by default:** This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) and [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your documents more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

### Word: Non-Security updates
- Fix an issue that causes an insufficient memory message to appear.
- Fixed a set of issues that prevented some users from opening IRM-protected documents & emails that were shared with them by people in other organizations.
- Fixed some performance issues.
- Improve open performance.

### Skype for Business: Non-security updates
- Fix an issue related to TLS 1.2 support. (Note: This is the same fix that was mentioned in the April 10 notes and is mentioned here again as part of the September rollup.)
- Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.
- Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.
- Fix an issue where location is populated even when UseLocationForE911Only is set to true.
- Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.
- Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.
- Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.

### Visio: Feature updates
- **Keep your diagram and source in sync:** When you edit a Data Visualizer diagram in Visio, you have the option to update the linked Excel source data with the latest diagram content.
- **Data Visualizer audit template:** Import content from Excel and create audit diagrams for financial transactions, inventory management, and more.
- **Starter diagrams:** The Organization Chart, Brainstorming, and SDL templates have new starter diagrams to get you up and running quickly.
 - **Build a Word document out of Visio shapes** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

 
### Office Suite: Non-Security updates
- Fixed an issue that caused update install to take a long time in certain scenarios.
- Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.
- Fixed some performance issues.


## Version 1803: January 8
*Version 1803 (Build 9126.2351)*

*This is the Semi-Annual Channel release that's been available since July 2018. It will continue to be supported and receive security updates until September 2019. But, a new Semi-Annual Channel release is now available — Version 1808 — which contains new features, security updates, and non-security updates.*

### PowerPoint: Non-Security updates
- Fixed an issue to ensure feature parity of the LinkedIn option between Office applications.


> [!NOTE]
> If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).
