---
title: OleObjectFrame
second_title: Aspose.Slides Java API 参考
description: 表示幻灯片上的 OLE 对象。
type: docs
url: /zh/com.aspose.slides/oleobjectframe/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有实现的接口:**  
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)  
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

表示幻灯片上的 OLE 对象。

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // 将 PPTX 加载到演示文稿对象
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // 访问第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 将形状强制转换为 OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // 读取 OLE 对象并写入磁盘
>      if (oleObjectFrame != null) {
>          // 获取嵌入文件数据
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // 获取嵌入文件扩展名
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // 创建保存提取文件的路径
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // 保存提取的数据
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | 返回 OleObject 图像填充属性对象。 |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | 返回或设置 OleObject 图标的标题。 |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | 返回或设置 OleObject 图标的标题。 |
| [getObjectName()](#getObjectName--) | 返回或设置对象的名称。 |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | 返回或设置对象的名称。 |
| [getObjectProgId()](#getObjectProgId--) | 返回对象的 ProgID。 |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | 返回对象的 ProgID。 |
| [getLinkFileName()](#getLinkFileName--) | 返回链接文件的完整路径。 |
| [getLinkPathLong()](#getLinkPathLong--) | 返回链接文件的完整路径。 |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 返回链接文件的完整路径。 |
| [getLinkPathRelative()](#getLinkPathRelative--) | 如果存在，则返回链接文件的相对路径；否则返回空字符串。 |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | 返回嵌入式 OLE 对象的文件名 |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | 返回嵌入式 OLE 对象的路径 |
| [getEmbeddedData()](#getEmbeddedData--) | 获取或设置 OLE 嵌入数据的信息。 |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | 设置 OLE 嵌入数据的信息。 |
| [isObjectIcon()](#isObjectIcon--) | 确定对象是否以图标形式可见。 |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | 确定对象是否以图标形式可见。 |
| [isObjectLink()](#isObjectLink--) | 确定对象是否链接到外部文件。 |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | 确定在打开或打印演示文稿时是否自动更新链接的嵌入对象。 |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | 确定在打开或打印演示文稿时是否自动更新链接的嵌入对象。 |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

返回 OleObject 图像填充属性对象。只读 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

返回或设置 OleObject 图标的标题。可读写 String。

--------------------

当 IsObjectIcon == false 时，此值被忽略。该字符串可根据 Ole 图标的大小进行截断。

**返回:**  
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

返回或设置 OleObject 图标的标题。可读写 String。

--------------------

当 IsObjectIcon == false 时，此值被忽略。该字符串可根据 Ole 图标的大小进行截断。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

返回或设置对象的名称。可读写 String。

**返回:**  
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

返回或设置对象的名称。可读写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

返回对象的 ProgID。只读 String。

**返回:**  
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

返回对象的 ProgID。只读 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

返回链接文件的完整路径。将使用短文件名。只读 String。

**返回:**  
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

返回链接文件的完整路径。将使用长文件名。可读写 String。

**返回:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

返回链接文件的完整路径。将使用长文件名。可读写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
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

在 Ppt 演示文稿中，某些 Ole 对象链接可能具有相对表示形式。

**返回:**  
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

返回嵌入式 OLE 对象的文件名

**返回:**  
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

返回嵌入式 OLE 对象的路径

**返回:**  
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

获取或设置 OLE 嵌入数据的信息。可读写 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)。

**返回:**  
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

设置 OLE 嵌入数据的信息。

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

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入数据 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

此方法更改对象的属性以反映新数据，并将 IsObjectLink 标志设为 false，表示 OLE 对象已嵌入。 |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

确定对象是否以图标形式可见。可读写 boolean 。

**返回:**  
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

确定对象是否以图标形式可见。可读写 boolean 。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

确定对象是否链接到外部文件。只读 boolean 。

**返回:**  
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

确定在打开或打印演示文稿时是否自动更新链接的嵌入对象。可读写 boolean 。

**返回:**  
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

确定在打开或打印演示文稿时是否自动更新链接的嵌入对象。可读写 boolean 。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |