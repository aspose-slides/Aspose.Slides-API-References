---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: 控制 HTML 文件的生成。
type: docs
url: /zh/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

控制 HTML 文件的生成。

## 方法

| 方法 | 描述 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 用于写入 HTML 文档头部。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 用于写入 HTML 文档页脚。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 用于写入 HTML 幻灯片头部。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 用于写入 HTML 幻灯片页脚。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 在形状渲染之前调用。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 在形状渲染之前调用。 |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

用于写入 HTML 文档头部。每次演示文稿转换调用一次。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 当前正在渲染的演示文稿。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

用于写入 HTML 文档页脚。每次演示文稿转换调用一次。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 当前正在渲染的演示文稿。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

用于写入 HTML 幻灯片头部。每张幻灯片调用一次。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 当前正在渲染的幻灯片。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

用于写入 HTML 幻灯片页脚。每张幻灯片调用一次。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 当前正在渲染的幻灯片。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

在形状渲染之前调用。每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片的图像生成将结束，插入添加的 HTML 片段并在前一个图像之上开始生成新图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 即将渲染的形状。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

在形状渲染之前调用。每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片的图像生成将结束，插入添加的 HTML 片段并在前一个图像之上开始生成新图像。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最后渲染的形状。 |