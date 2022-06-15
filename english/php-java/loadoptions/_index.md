---
title: LoadOptions
type: docs
weight: 0
url: /php-java/loadoptions/
---

# LoadOptions class

 Allows to specify additional options (such as format or default font) when loading a presentation.
 

## Constructors

| name | description |
| --- | --- |
| [LoadOptions](/php-java/loadoptions/loadoptions/)() | Creates new default load options. |
| [LoadOptions](/php-java/loadoptions/loadoptions/)(int) | Creates new load options. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getBlobManagementOptions](/php-java/loadoptions/getblobmanagementoptions/)() | IBlobManagementOptions | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements. A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. |
| [getDefaultAsianFont](/php-java/loadoptions/getdefaultasianfont/)() | String | Returns or sets Asian font used in case source font is not found. Read/write String. |
| [getDefaultRegularFont](/php-java/loadoptions/getdefaultregularfont/)() | String | Returns or sets Regular font used in case source font is not found. Read/write String. |
| [getDefaultSymbolFont](/php-java/loadoptions/getdefaultsymbolfont/)() | String | Returns or sets Symbol font used in case source font is not found. Read/write String. |
| [getDocumentLevelFontSources](/php-java/loadoptions/getdocumentlevelfontsources/)() | IFontSources | Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |
| [getInterruptionToken](/php-java/loadoptions/getinterruptiontoken/)() | IInterruptionToken | The token to monitor for interruption requests. This token manages the whole IPresentation instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the InterruptionTokenSource#interrupt method of the InterruptionTokenSource. |
| [getLoadFormat](/php-java/loadoptions/getloadformat/)() | int | Returns or sets format of a presentation to load. Read/write LoadFormat. |
| [getOnlyLoadDocumentProperties](/php-java/loadoptions/getonlyloaddocumentproperties/)() | boolean | This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean. |
| [getPassword](/php-java/loadoptions/getpassword/)() | String | Gets or sets the password. Read/write String. Value: The password. |
| [getResourceLoadingCallback](/php-java/loadoptions/getresourceloadingcallback/)() | IResourceLoadingCallback | Returns or sets callback interface which manages external resources loading. Read/write IResourceLoadingCallback. |
| [getSpreadsheetOptions](/php-java/loadoptions/getspreadsheetoptions/)() | ISpreadsheetOptions | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |
| [getWarningCallback](/php-java/loadoptions/getwarningcallback/)() | IWarningCallback | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |
| [setBlobManagementOptions](/php-java/loadoptions/setblobmanagementoptions/)(IBlobManagementOptions) | void | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements. A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. |
| [setDefaultAsianFont](/php-java/loadoptions/setdefaultasianfont/)(String) | void | Returns or sets Asian font used in case source font is not found. Read/write String. |
| [setDefaultRegularFont](/php-java/loadoptions/setdefaultregularfont/)(String) | void | Returns or sets Regular font used in case source font is not found. Read/write String. |
| [setDefaultSymbolFont](/php-java/loadoptions/setdefaultsymbolfont/)(String) | void | Returns or sets Symbol font used in case source font is not found. Read/write String. |
| [setDocumentLevelFontSources](/php-java/loadoptions/setdocumentlevelfontsources/)(IFontSources) | void | Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |
| [setInterruptionToken](/php-java/loadoptions/setinterruptiontoken/)(IInterruptionToken) | void | The token to monitor for interruption requests. This token manages the whole IPresentation instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the InterruptionTokenSource#interrupt method of the InterruptionTokenSource. |
| [setLoadFormat](/php-java/loadoptions/setloadformat/)(int) | void | Returns or sets format of a presentation to load. Read/write LoadFormat. |
| [setOnlyLoadDocumentProperties](/php-java/loadoptions/setonlyloaddocumentproperties/)(boolean) | void | This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean. |
| [setPassword](/php-java/loadoptions/setpassword/)(String) | void | Gets or sets the password. Read/write String. Value: The password. |
| [setResourceLoadingCallback](/php-java/loadoptions/setresourceloadingcallback/)(IResourceLoadingCallback) | void | Returns or sets callback interface which manages external resources loading. Read/write IResourceLoadingCallback. |
| [setSpreadsheetOptions](/php-java/loadoptions/setspreadsheetoptions/)(ISpreadsheetOptions) | void | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |
| [setWarningCallback](/php-java/loadoptions/setwarningcallback/)(IWarningCallback) | void | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |
