---
title: Output
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示 IWebDocument 的输出元素集合。
type: docs
url: /zh/com.aspose.slides/output/
---
**继承：**
java.lang.Object
```
public final class Output
```

表示 IWebDocument 的输出元素集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | 为上下文对象添加输出元素。 |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | 为图像添加输出元素。 |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | 为图像添加输出元素。 |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | 为视频添加输出元素。 |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | 为指定字体创建并添加输出文件元素。 |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | 为文本内容添加输出元素。 |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | 将资源绑定到输出文件。 |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | 返回给定资源的路径。 |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

为上下文对象添加输出元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 输出路径。 |
| templateKey | java.lang.String | 在输出之前用于上下文对象转换的模板键。 |
| contextObject | TContextObject | 上下文对象。 |

**返回值:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用于上下文对象的对象。
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

为图像添加输出元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 输出路径。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要输出的图像。 |

**返回值:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用于图像的对象。
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

为图像添加输出元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 输出路径。 |
| image | [IImage](../../com.aspose.slides/iimage) | 要输出的图像。 |

**返回值:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用于图像的对象。
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

为视频添加输出元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 输出路径。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | 要输出的视频。 |

**返回值:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用于视频的对象。
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

为指定字体创建并添加输出文件元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 保存字体输出的文件路径。 |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | 要写入输出的字体数据。 |
| fontStyle | int | 字体样式（例如 Regular、Bold、Italic）。 |

**返回值:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - 一个 [IOutputFile](../../com.aspose.slides/ioutputfile) 实例，用于生成的字体。
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

为文本内容添加输出元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 输出路径。 |
| textContent | java.lang.String | 要输出的内容。 |

**返回值:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) 用于文本内容的对象。
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

将资源绑定到输出文件。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | 输出文件。 |
| obj | java.lang.Object | 资源对象。 |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

返回给定资源的路径。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 资源对象。 |

**返回值:**
java.lang.String - 资源路径。