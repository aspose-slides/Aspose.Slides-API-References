---
title: LoadOptions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/loadoptions/
---

## LoadOptions class

 Allows to specify additional options (such as format or default font) when loading a presentation.
 

## Constructors

| Name | Description |
| --- | --- |
| [LoadOptions](loadoptions)() | Creates new default load options. |
| [LoadOptions](loadoptions)(int) | Creates new load options. |

## Methods

| Name | Description |
| --- | --- |
| [getBlobManagementOptions](getblobmanagementoptions)() | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements. A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. |
| [getDefaultAsianFont](getdefaultasianfont)() | Returns or sets Asian font used in case source font is not found. Read/write String. |
| [getDefaultRegularFont](getdefaultregularfont)() | Returns or sets Regular font used in case source font is not found. Read/write String. |
| [getDefaultSymbolFont](getdefaultsymbolfont)() | Returns or sets Symbol font used in case source font is not found. Read/write String. |
| [getDocumentLevelFontSources](getdocumentlevelfontsources)() | Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |
| [getInterruptionToken](getinterruptiontoken)() | The token to monitor for interruption requests. This token manages the whole IPresentation instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the InterruptionTokenSource#interrupt method of the InterruptionTokenSource. |
| [getLoadFormat](getloadformat)() | Returns or sets format of a presentation to load. Read/write LoadFormat. |
| [getOnlyLoadDocumentProperties](getonlyloaddocumentproperties)() | This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean. |
| [getPassword](getpassword)() | Gets or sets the password. Read/write String. Value: The password. |
| [getResourceLoadingCallback](getresourceloadingcallback)() | Returns or sets callback interface which manages external resources loading. Read/write IResourceLoadingCallback. |
| [getSpreadsheetOptions](getspreadsheetoptions)() | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |
| [getWarningCallback](getwarningcallback)() | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |
| [setBlobManagementOptions](setblobmanagementoptions)([../BlobManagementOptions]BlobManagementOptions) | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements. A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. |
| [setDefaultAsianFont](setdefaultasianfont)(String) | Returns or sets Asian font used in case source font is not found. Read/write String. |
| [setDefaultRegularFont](setdefaultregularfont)(String) | Returns or sets Regular font used in case source font is not found. Read/write String. |
| [setDefaultSymbolFont](setdefaultsymbolfont)(String) | Returns or sets Symbol font used in case source font is not found. Read/write String. |
| [setDocumentLevelFontSources](setdocumentlevelfontsources)([../FontSources]FontSources) | Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |
| [setInterruptionToken](setinterruptiontoken)([../InterruptionToken]InterruptionToken) | The token to monitor for interruption requests. This token manages the whole IPresentation instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the InterruptionTokenSource#interrupt method of the InterruptionTokenSource. |
| [setLoadFormat](setloadformat)(int) | Returns or sets format of a presentation to load. Read/write LoadFormat. |
| [setOnlyLoadDocumentProperties](setonlyloaddocumentproperties)(boolean) | This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean. |
| [setPassword](setpassword)(String) | Gets or sets the password. Read/write String. Value: The password. |
| [setSpreadsheetOptions](setspreadsheetoptions)([../SpreadsheetOptions]SpreadsheetOptions) | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |
