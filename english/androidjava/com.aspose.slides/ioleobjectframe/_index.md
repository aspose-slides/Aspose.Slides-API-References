---
title: IOleObjectFrame
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents an OLE object on a slide.
type: docs
weight: 938
url: /androidjava/com.aspose.slides/ioleobjectframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Represents an OLE object on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returns OleObject image fill properties object. |
| [getObjectName()](#getObjectName--) | Returns or sets the name of an object. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Returns or sets the name of an object. |
| [getEmbeddedData()](#getEmbeddedData--) | Gets information about OLE embedded data. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Sets information about OLE embedded data. |
| [getObjectProgId()](#getObjectProgId--) | Returns the ProgID of an object. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Returns the ProgID of an object. |
| [getLinkFileName()](#getLinkFileName--) | Returns the full path to a linked file. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns the full path to a linked file. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns the full path to a linked file. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Returns the file name of embedded OLE object |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Returns the path of embedded OLE object |
| [isObjectIcon()](#isObjectIcon--) | Determines whether an object is visible as icon. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Determines whether an object is visible as icon. |
| [isObjectLink()](#isObjectLink--) | Determines whether an object is linked to external file. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Returns or sets the title for OleObject icon. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Returns or sets the title for OleObject icon. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Returns OleObject image fill properties object. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


Returns or sets the name of an object. Read/write String.

**Returns:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


Returns or sets the name of an object. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


Gets information about OLE embedded data. Read only [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Returns:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Sets information about OLE embedded data.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

This method changes the properties of the object to reflect the new data and sets the IsObjectLink flag to false, indicating that the OLE object is embedded. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


Returns the ProgID of an object. Read olny String.

**Returns:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


Returns the ProgID of an object. Read olny String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Returns the full path to a linked file. Short file name will be used. Read-only String.

**Returns:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Returns the full path to a linked file. Long file name will be used. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Returns the full path to a linked file. Long file name will be used. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


Returns the file name of embedded OLE object

**Returns:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


Returns the path of embedded OLE object

**Returns:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


Determines whether an object is visible as icon. Read/write boolean.

**Returns:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


Determines whether an object is visible as icon. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


Determines whether an object is linked to external file. Read-only boolean.

**Returns:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean.

**Returns:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Returns or sets the title for OleObject icon. Read/write String.

--------------------

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the OLE icon.

**Returns:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Returns or sets the title for OleObject icon. Read/write String.

--------------------

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the OLE icon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

