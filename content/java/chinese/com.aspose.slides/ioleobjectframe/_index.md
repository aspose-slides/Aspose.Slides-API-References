---
title: IOleObjectFrame
second_title: Aspose.Slides Java API 参考
description: 表示幻灯片上的 OLE 对象。
type: docs
url: /zh/com.aspose.slides/ioleobjectframe/
---
**所有实现的接口：**
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
| [getEmbeddedData()](#getEmbeddedData--) | 获取 OLE 嵌入数据的信息。 |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | 设置 OLE 嵌入数据的信息。 |
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

获取 OLE 嵌入数据的信息。只读 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)。

**返回：**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

设置 OLE 嵌入数据的信息。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入数据 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

--------------------

此方法更改对象的属性以反映新数据，并将 IsObjectLink 标志设为 false，表示 OLE 对象已嵌入。 |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

返回对象的 ProgID。只读 String。

**返回：**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

返回对象的 ProgID。只读 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

返回链接文件的完整路径。将使用短文件名。只读 String。

**返回：**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

返回链接文件的完整路径。将使用长文件名。可读写 String。

**返回：**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

返回链接文件的完整路径。将使用长文件名。可读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

如果存在，则返回链接文件的相对路径；否则返回空字符串。只读 String。

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

在 PPT 演示文稿中，某些 Ole 对象链接可能具有相对表示形式。

**返回：**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

返回嵌入 OLE 对象的文件名

**返回：**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

返回嵌入 OLE 对象的路径

**返回：**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

确定对象是否以图标形式可见。可读写 boolean。

**返回：**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

确定对象是否以图标形式可见。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

确定对象是否链接到外部文件。只读 boolean。

**返回：**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

确定在打开或打印演示文稿时，是否自动更新链接的嵌入对象。可读写 boolean。

**返回：**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

确定在打开或打印演示文稿时，是否自动更新链接的嵌入对象。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

返回或设置 OleObject 图标的标题。可读写 String。

--------------------

当 IsObjectIcon == false 时，此值将被忽略。该字符串可根据 OLE 图标的大小进行截断。

**返回：**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

返回或设置 OleObject 图标的标题。可读写 String。

--------------------

当 IsObjectIcon == false 时，此值将被忽略。该字符串可根据 OLE 图标的大小进行截断。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |