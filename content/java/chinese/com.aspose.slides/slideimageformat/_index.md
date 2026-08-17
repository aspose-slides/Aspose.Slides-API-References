---
title: SlideImageFormat
second_title: Aspose.Slides for Java API 参考
description: 确定在导出为 HTML 演示文稿时保存幻灯片图像的格式。
type: docs
url: /zh/com.aspose.slides/slideimageformat/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)  
```
public class SlideImageFormat implements ISlideImageFormat
```

确定在导出为 HTML 演示文稿时保存幻灯片图像的格式。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | 幻灯片应转换为 SVG 格式。 |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | 幻灯片应转换为光栅图像。 |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

幻灯片应转换为 SVG 格式。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG 导出的选项。 |

**返回值:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - 该 [SlideImageFormat](../../com.aspose.slides/slideimageformat) 对象。

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

幻灯片应转换为光栅图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scale | float | 用于缩放输出图像的比例因子。 |
| imageFormat | int | 生成图像的格式（例如 PNG、JPEG）。 |

**返回值:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -  