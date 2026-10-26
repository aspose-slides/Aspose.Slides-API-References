---
title: IImageCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示 PPImage 的集合。
type: docs
url: /zh/com.aspose.slides/iimagecollection/
---
**所有实现的接口:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

表示 PPImage 的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根据索引返回图像。 |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | 向演示文稿添加图像。 |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | 从流向演示文稿添加图像。 |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | 从流创建并添加图像到演示文稿。 |
| [addImage(byte[] buffer)](#addImage-byte---) | Adds an image to a presentation from specified buffer. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | 从另一个演示文稿添加图像的副本。 |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | 从 SVG 对象向演示文稿添加图像。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

根据索引返回图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。 |

**返回:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

向演示文稿添加图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 要添加的图像。 |

--------------------

该方法在将 WMF/EMF 元文件插入演示文稿之前，将其转换为栅格 PNG 图像。

**返回:**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

从流向演示文稿添加图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于添加图像的流。 |

--------------------

该方法可以在不将 WMF/EMF 元文件转换为栅格 PNG 图像的情况下，将其添加到演示文稿中。

**返回:**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

从流创建并添加图像到演示文稿。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 用于添加图像文件的流。 |
| loadingStreamBehavior | int | 将应用于流的行为。 |

**返回:**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加 [IPPImage](../../com.aspose.slides/ippimage)。

### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

从指定缓冲区向演示文稿添加图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 缓冲区。 |

**返回:**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

从另一个演示文稿添加图像的副本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | 源图像。 |

**返回:**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

从 SVG 对象向演示文稿添加图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG 图像对象 [ISvgImage](../../com.aspose.slides/isvgimage) |

**返回:**
[IPPImage](../../com.aspose.slides/ippimage) - 已添加的图像。