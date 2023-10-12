---
title: LoadOptions
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/loadoptions/
---

## LoadOptions class

 Allows to specify additional options (such as format or default font) when loading a presentation.
 
| Name | Description |
| --- | --- |
| LoadOptions() | Creates new default load options. |

### Result
LoadOptions


---


| Name | Description |
| --- | --- |
| LoadOptions(int) | Creates new load options. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| loadFormat | int | Format of a presentation to load. |

### Result
LoadOptions


---


| Name | Description |
| --- | --- |
| getBlobManagementOptions () | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements. A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. |

### Result
BlobManagementOptions(../../blobmanagementoptions)


---


| Name | Description |
| --- | --- |
| getDefaultAsianFont () | Returns or sets Asian font used in case source font is not found. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getDefaultRegularFont () | Returns or sets Regular font used in case source font is not found. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getDefaultSymbolFont () | Returns or sets Symbol font used in case source font is not found. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getDefaultTextLanguage () | Returns or sets the default language for presentation text. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getDocumentLevelFontSources () | Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |

### Result
FontSources(../../fontsources)


---


| Name | Description |
| --- | --- |
| getInterruptionToken () | The token to monitor for interruption requests. This token manages the whole IPresentation instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the InterruptionTokenSource#interrupt function of the InterruptionTokenSource. |

### Result
InterruptionToken(../../interruptiontoken)


---


| Name | Description |
| --- | --- |
| getLoadFormat () | Returns or sets format of a presentation to load. Read/write LoadFormat. |

### Result
int


---


| Name | Description |
| --- | --- |
| getOnlyLoadDocumentProperties () | This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getPassword () | Gets or sets the password. Read/write String. Value: The password. |

### Result
String


---


| Name | Description |
| --- | --- |
| getResourceLoadingCallback () | Returns or sets callback interface which manages external resources loading. Read/write IResourceLoadingCallback. |

### Result
SvgResourceResolver, ResourceLoadingAdapter


---


| Name | Description |
| --- | --- |
| getSpreadsheetOptions () | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |

### Result
SpreadsheetOptions(../../spreadsheetoptions)


---


| Name | Description |
| --- | --- |
| getWarningCallback () | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |

### Result
IWarningCallback


---


| Name | Description |
| --- | --- |
| setBlobManagementOptions (BlobManagementOptions(../blobmanagementoptions)) | Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements. A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. |


---


| Name | Description |
| --- | --- |
| setDefaultAsianFont (String) | Returns or sets Asian font used in case source font is not found. Read/write String. |


---


| Name | Description |
| --- | --- |
| setDefaultRegularFont (String) | Returns or sets Regular font used in case source font is not found. Read/write String. |


---


| Name | Description |
| --- | --- |
| setDefaultSymbolFont (String) | Returns or sets Symbol font used in case source font is not found. Read/write String. |


---


| Name | Description |
| --- | --- |
| setDefaultTextLanguage (String) | Returns or sets the default language for presentation text. Read/write String. |


---


| Name | Description |
| --- | --- |
| setDocumentLevelFontSources (FontSources(../fontsources)) | Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations |


---


| Name | Description |
| --- | --- |
| setInterruptionToken (InterruptionToken(../interruptiontoken)) | The token to monitor for interruption requests. This token manages the whole IPresentation instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the InterruptionTokenSource#interrupt function of the InterruptionTokenSource. |


---


| Name | Description |
| --- | --- |
| setLoadFormat (int) | Returns or sets format of a presentation to load. Read/write LoadFormat. |


---


| Name | Description |
| --- | --- |
| setOnlyLoadDocumentProperties (boolean) | This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn't encrypted then property value is always ignored. If document properties of an encrypted file aren't public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setPassword (String) | Gets or sets the password. Read/write String. Value: The password. |


---


| Name | Description |
| --- | --- |
| setResourceLoadingCallback (IResourceLoadingCallback(../iresourceloadingcallback)) | Returns or sets callback interface which manages external resources loading. Read/write IResourceLoadingCallback. |


---


| Name | Description |
| --- | --- |
| setSpreadsheetOptions (SpreadsheetOptions(../spreadsheetoptions)) | Gets options for spreadsheets. For example, these options affect calculating formulas for charts. |


---


| Name | Description |
| --- | --- |
| setWarningCallback (IWarningCallback(../iwarningcallback)) | Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write IWarningCallback. |


---


