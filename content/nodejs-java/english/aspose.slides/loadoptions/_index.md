---
title: LoadOptions
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/loadoptions/
---

## LoadOptions class

 Allows to specify additional options (such as format or default font) when loading a presentation.
 
### LoadOptions {#LoadOptions}

| Name | Description |
| --- | --- |
| LoadOptions() | Creates new default load options. |

 **Returns:**
LoadOptions


---


### LoadOptions {#LoadOptions}

| Name | Description |
| --- | --- |
| LoadOptions(int) | Creates new load options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| loadFormat | int | Format of a presentation to load. |

 **Returns:**
LoadOptions


---


### getBlobManagementOptions {#getBlobManagementOptions}

| Name | Description |
| --- | --- |
| getBlobManagementOptions () | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements. A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. |

 **Returns:**
[BlobManagementOptions](../blobmanagementoptions)


---


### getDefaultAsianFont {#getDefaultAsianFont}

| Name | Description |
| --- | --- |
| getDefaultAsianFont () | Returns or sets Asian font used in case source font is not found. Read/write String. |

 **Returns:**
String


---


### getDefaultRegularFont {#getDefaultRegularFont}

| Name | Description |
| --- | --- |
| getDefaultRegularFont () | Returns or sets Regular font used in case source font is not found. Read/write String. |

 **Returns:**
String


---


### getDefaultSymbolFont {#getDefaultSymbolFont}

| Name | Description |
| --- | --- |
| getDefaultSymbolFont () | Returns or sets Symbol font used in case source font is not found. Read/write String. |

 **Returns:**
String


---


### getDefaultTextLanguage {#getDefaultTextLanguage}

| Name | Description |
| --- | --- |
| getDefaultTextLanguage () | Returns or sets the default language for presentation text. Read/write String. |

 **Returns:**
String


---


### getDeleteEmbeddedBinaryObjects {#getDeleteEmbeddedBinaryObjects}

| Name | Description |
| --- | --- |
| getDeleteEmbeddedBinaryObjects () | Determines if Aspose.Slides will delete all embedded binary objects while presentation loading. The types of the embedded binary objects: Read/write boolean. Default is false. |

 **Returns:**
boolean


---


### getDocumentLevelFontSources {#getDocumentLevelFontSources}

| Name | Description |
| --- | --- |
| getDocumentLevelFontSources () | Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |

 **Returns:**
[FontSources](../fontsources)


---


### getInterruptionToken {#getInterruptionToken}

| Name | Description |
| --- | --- |
| getInterruptionToken () | The token to monitor for interruption requests. This token manages the whole IPresentation instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the InterruptionTokenSource#interrupt function of the InterruptionTokenSource. |

 **Returns:**
[InterruptionToken](../interruptiontoken)


---


### getLoadFormat {#getLoadFormat}

| Name | Description |
| --- | --- |
| getLoadFormat () | Returns or sets format of a presentation to load. Read/write LoadFormat. |

 **Returns:**
int


---


### getOnlyLoadDocumentProperties {#getOnlyLoadDocumentProperties}

| Name | Description |
| --- | --- |
| getOnlyLoadDocumentProperties () | This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean. |

 **Returns:**
boolean


---


### getPassword {#getPassword}

| Name | Description |
| --- | --- |
| getPassword () | Gets or sets the password. Read/write String. Value: The password. |

 **Returns:**
String


---


### getResourceLoadingCallback {#getResourceLoadingCallback}

| Name | Description |
| --- | --- |
| getResourceLoadingCallback () | Returns or sets callback interface which manages external resources loading. Read/write IResourceLoadingCallback. |

 **Returns:**
SvgResourceResolver, ResourceLoadingAdapter


---


### getSpreadsheetOptions {#getSpreadsheetOptions}

| Name | Description |
| --- | --- |
| getSpreadsheetOptions () | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |

 **Returns:**
[SpreadsheetOptions](../spreadsheetoptions)


---


### getWarningCallback {#getWarningCallback}

| Name | Description |
| --- | --- |
| getWarningCallback () | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

 **Returns:**
IWarningCallback


---


### setBlobManagementOptions {#setBlobManagementOptions}

| Name | Description |
| --- | --- |
| setBlobManagementOptions ([BlobManagementOptions](../blobmanagementoptions)) | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements. A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. |


---


### setDefaultAsianFont {#setDefaultAsianFont}

| Name | Description |
| --- | --- |
| setDefaultAsianFont (String) | Returns or sets Asian font used in case source font is not found. Read/write String. |


---


### setDefaultRegularFont {#setDefaultRegularFont}

| Name | Description |
| --- | --- |
| setDefaultRegularFont (String) | Returns or sets Regular font used in case source font is not found. Read/write String. |


---


### setDefaultSymbolFont {#setDefaultSymbolFont}

| Name | Description |
| --- | --- |
| setDefaultSymbolFont (String) | Returns or sets Symbol font used in case source font is not found. Read/write String. |


---


### setDefaultTextLanguage {#setDefaultTextLanguage}

| Name | Description |
| --- | --- |
| setDefaultTextLanguage (String) | Returns or sets the default language for presentation text. Read/write String. |


---


### setDeleteEmbeddedBinaryObjects {#setDeleteEmbeddedBinaryObjects}

| Name | Description |
| --- | --- |
| setDeleteEmbeddedBinaryObjects (boolean) | Determines if Aspose.Slides will delete all embedded binary objects while presentation loading. The types of the embedded binary objects: Read/write boolean. Default is false. |


---


### setDocumentLevelFontSources {#setDocumentLevelFontSources}

| Name | Description |
| --- | --- |
| setDocumentLevelFontSources ([FontSources](../fontsources)) | Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |


---


### setInterruptionToken {#setInterruptionToken}

| Name | Description |
| --- | --- |
| setInterruptionToken ([InterruptionToken](../interruptiontoken)) | The token to monitor for interruption requests. This token manages the whole IPresentation instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the InterruptionTokenSource#interrupt function of the InterruptionTokenSource. |


---


### setLoadFormat {#setLoadFormat}

| Name | Description |
| --- | --- |
| setLoadFormat (int) | Returns or sets format of a presentation to load. Read/write LoadFormat. |


---


### setOnlyLoadDocumentProperties {#setOnlyLoadDocumentProperties}

| Name | Description |
| --- | --- |
| setOnlyLoadDocumentProperties (boolean) | This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean. |


---


### setPassword {#setPassword}

| Name | Description |
| --- | --- |
| setPassword (String) | Gets or sets the password. Read/write String. Value: The password. |


---


### setResourceLoadingCallback {#setResourceLoadingCallback}

| Name | Description |
| --- | --- |
| setResourceLoadingCallback ([IResourceLoadingCallback](../iresourceloadingcallback)) | Returns or sets callback interface which manages external resources loading. Read/write IResourceLoadingCallback. |


---


### setSpreadsheetOptions {#setSpreadsheetOptions}

| Name | Description |
| --- | --- |
| setSpreadsheetOptions ([SpreadsheetOptions](../spreadsheetoptions)) | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |


---


### setWarningCallback {#setWarningCallback}

| Name | Description |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |


---


