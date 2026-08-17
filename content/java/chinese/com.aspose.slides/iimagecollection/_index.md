---
title: IImageCollection
second_title: Aspose.Slides for Java API 参考
description: 表示 PPImage 的集合。
type: docs
url: /zh/com.aspose.slides/iimagecollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

表示 PPImage 的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回 image 按其索引。 |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | 将 image 添加到演示文稿。 |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | 从流将 image 添加到演示文稿。 |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | 从流创建并将 image 添加到演示文稿。 |
| [addImage(byte[] buffer)](#addImage-byte---) | 从指定的缓冲区将 image 添加到演示文稿。 |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 从另一个演示文稿添加 image 的副本。 |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | 从 SVG 对象将 image 添加到演示文稿。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

返回 image 按其索引。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 索引。 |

**返回：**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

将 image 添加到演示文稿。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 要添加的 image。 |

--------------------

此方法在将 WMF/EMF 元文件插入演示文稿之前，将其转换为光栅 PNG 图像。

**返回：**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

将 image 添加到演示文稿，从流中读取。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要从中添加 image 的流。 |

--------------------

此方法可以在不将 WMF/EMF 元文件转换为光栅 PNG 图像的情况下，将其添加到演示文稿中。

**返回：**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

从流创建并将 image 添加到演示文稿。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| stream | java.io.InputStream | 要从中添加 image 文件的流。 |
| loadingStreamBehavior | int | 将应用于该流的行为。 |

**返回：**
[IPPImage](../../com.aspose.slides/ippimage) - Added [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

从指定的缓冲区将 image 添加到演示文稿。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | byte[] | 缓冲区。 |

**返回：**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

从另一个演示文稿添加 image 的副本。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | 源 image。 |

**返回：**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

将 image 添加到演示文稿，从 SVG 对象读取。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG 图像对象 [ISvgImage](../../com.aspose.slides/isvgimage) |

**返回：**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.