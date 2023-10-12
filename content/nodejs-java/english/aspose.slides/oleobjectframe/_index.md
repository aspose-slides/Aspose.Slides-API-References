---
title: OleObjectFrame
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/oleobjectframe/
---

## OleObjectFrame class

 Represents an OLE object on a slide.
 
| Name | Description |
| --- | --- |
| getEmbeddedData () | Gets or sets information about OLE embedded data. Read/write IOleEmbeddedDataInfo. |

### Result
OleEmbeddedDataInfo(../../oleembeddeddatainfo)


---


| Name | Description |
| --- | --- |
| getEmbeddedFileLabel () | Returns the file name of embedded OLE object |

### Result
String


---


| Name | Description |
| --- | --- |
| getEmbeddedFileName () | Returns the path of embedded OLE object |

### Result
String


---


| Name | Description |
| --- | --- |
| getLinkFileName () | Returns the full path to a linked file. Short file name will be used. Read-only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getLinkPathLong () | Returns the full path to a linked file. Long file name will be used. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getLinkPathRelative () | Returns the relative path to a linked file if present, otherwise returns an empty string. Readonly String. In the Ppt presentations, some Ole object links may have a relative representation. |

### Result
String


---


| Name | Description |
| --- | --- |
| getObjectName () | Returns or sets the name of an object. Read/write String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getObjectProgId () | Returns the ProgID of an object. Read only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getSubstitutePictureFormat () | Returns OleObject image fill properties object. Read-only IPictureFillFormat. |

### Result
PictureFillFormat(../../picturefillformat)


---


| Name | Description |
| --- | --- |
| getSubstitutePictureTitle () | Returns or sets the title for OleObject icon. Read/write String. When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon. |

### Result
String


---


| Name | Description |
| --- | --- |
| getUpdateAutomatic () | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isObjectIcon () | Determines whether an object is visible as icon. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| isObjectLink () | Determines whether an object is linked to external file. Read-only boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setEmbeddedData (OleEmbeddedDataInfo(../oleembeddeddatainfo)) | Sets information about OLE embedded data. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| embeddedData | OleEmbeddedDataInfo(../../oleembeddeddatainfo) | Embedded data IOleEmbeddedDataInfo This function changes the properties of the object to reflect the new data and sets the IsObjectLink flag to false, indicating that the OLE object is embedded. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | When embeddedData parameter is null. |


---


| Name | Description |
| --- | --- |
| setLinkPathLong (String) | Returns the full path to a linked file. Long file name will be used. Read/write String. |


---


| Name | Description |
| --- | --- |
| setObjectIcon (boolean) | Determines whether an object is visible as icon. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setObjectName (String) | Returns or sets the name of an object. Read/write String. |


---


| Name | Description |
| --- | --- |
| setObjectProgId (String) | Returns the ProgID of an object. Read only String. |


---


| Name | Description |
| --- | --- |
| setSubstitutePictureTitle (String) | Returns or sets the title for OleObject icon. Read/write String. When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon. |


---


| Name | Description |
| --- | --- |
| setUpdateAutomatic (boolean) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean. |


---


