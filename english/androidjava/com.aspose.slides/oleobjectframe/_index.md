---
title: OleObjectFrame
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an OLE object on a slide.
type: docs
weight: 387
url: /androidjava/com.aspose.slides/oleobjectframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Represents an OLE object on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Returns OleObject image fill properties object. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Returns or sets the title for OleObject icon. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Returns or sets the title for OleObject icon. |
| [getObjectName()](#getObjectName--) | Returns or sets the name of an object. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Returns or sets the name of an object. |
| [getObjectProgId()](#getObjectProgId--) | Returns the ProgID of an object. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Returns the ProgID of an object. |
| [getLinkFileName()](#getLinkFileName--) | Returns the full path to a linked file. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns the full path to a linked file. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns the full path to a linked file. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Returns the file name of embedded OLE object |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Returns the path of embedded OLE object |
| [getEmbeddedData()](#getEmbeddedData--) | Gets or sets information about OLE embedded data. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Sets information about OLE embedded data. |
| [isObjectIcon()](#isObjectIcon--) | Determines whether an object is visible as icon. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Determines whether an object is visible as icon. |
| [isObjectLink()](#isObjectLink--) | Determines whether an object is linked to external file. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


Returns OleObject image fill properties object. Read-only [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returns:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```


Returns or sets the title for OleObject icon. Read/write String.

--------------------

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon.

**Returns:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```


Returns or sets the title for OleObject icon. Read/write String.

--------------------

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the Ole icon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```


Returns or sets the name of an object. Read/write String.

**Returns:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```


Returns or sets the name of an object. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```


Returns the ProgID of an object. Read only String.

**Returns:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```


Returns the ProgID of an object. Read only String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```


Returns the full path to a linked file. Short file name will be used. Read-only String.

**Returns:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Returns the full path to a linked file. Long file name will be used. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Returns the full path to a linked file. Long file name will be used. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```


Returns the file name of embedded OLE object

**Returns:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```


Returns the path of embedded OLE object

**Returns:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```


Gets or sets information about OLE embedded data. Read/write [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Returns:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Sets information about OLE embedded data.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```


Determines whether an object is visible as icon. Read/write  boolean .

**Returns:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```


Determines whether an object is visible as icon. Read/write  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```


Determines whether an object is linked to external file. Read-only  boolean .

**Returns:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```


Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write  boolean .

**Returns:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```


Determines if the linked embedded object is automatically updated when the presentation is opened or printed. Read/write  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

