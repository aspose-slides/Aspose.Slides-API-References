---
title: IOleObjectFrame
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示幻灯片上的 OLE 对象。
type: docs
url: /zh/com.aspose.slides/ioleobjectframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

表示幻灯片上的 OLE 对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 返回 OleObject 图像填充属性对象。 |
| [getObjectName()](#getObjectName--) | 返回或设置对象的名称。 |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | 返回或设置对象的名称。 |
| [getEmbeddedData()](#getEmbeddedData--) | 获取有关 OLE 嵌入数据的信息。 |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | 设置有关 OLE 嵌入数据的信息。 |
| [getObjectProgId()](#getObjectProgId--) | 返回对象的 ProgID。 |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | 返回对象的 ProgID。 |
| [getLinkFileName()](#getLinkFileName--) | 返回链接文件的完整路径。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回链接文件的完整路径。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回链接文件的完整路径。 |
| [getLinkPathRelative()](#getLinkPathRelative--) | 如果存在，则返回链接文件的相对路径；否则返回空字符串。 |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | 返回嵌入 OLE 对象的文件名 |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | 返回嵌入 OLE 对象的路径 |
| [isObjectIcon()](#isObjectIcon--) | 确定对象是否以图标形式可见。 |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | 确定对象是否以图标形式可见。 |
| [isObjectLink()](#isObjectLink--) | 确定对象是否链接到外部文件。 |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | 确定在打开或打印演示文稿时，是否自动更新链接的嵌入对象。 |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | 确定在打开或打印演示文稿时，是否自动更新链接的嵌入对象。 |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | 返回或设置 OleObject 图标的标题。 |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | 返回或设置 OleObject 图标的标题。 |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


返回 OleObject 图像填充属性对象。只读 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


返回或设置对象的名称。可读写 String。

**返回：**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


返回或设置对象的名称。可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


获取有关 OLE 嵌入数据的信息。只读 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)。

**返回：**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


设置有关 OLE 嵌入数据的信息。

--------------------

> ```
> 以下示例演示如何更改 OLE 嵌入数据
> 以及其类型，以用于现有的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) 对象 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
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

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Returns the relative path to a linked file if present, otherwise returns an empty string. Readonly String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

In the Ppt presentations, some Ole object links may have a relative representation.

**Returns:**
java.lang.String
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


返回或设置 OleObject 图标的标题。可读写 String。

--------------------

当 IsObjectIcon == false 时，此值被忽略。根据 OLE 图标的大小，字符串可能会被截断。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |