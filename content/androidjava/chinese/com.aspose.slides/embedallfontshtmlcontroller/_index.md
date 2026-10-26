---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for Android via Java API 参考
description: 用于将所有演示文稿字体嵌入为 WOFF 格式的格式化控制器类。
type: docs
url: /zh/com.aspose.slides/embedallfontshtmlcontroller/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)  
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

用于将所有演示文稿字体嵌入为 WOFF 格式的格式化控制器类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | 创建新实例 |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | 创建新实例 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 调用以写入 HTML 文档头部。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 调用以写入 HTML 文档尾部。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 调用以写入 HTML 幻灯片头部。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 调用以写入 HTML 幻灯片尾部。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 在形状渲染之前调用。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 在形状渲染之前调用。 |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 写入包含在 [Presentation](../../com.aspose.slides/presentation) 中的所有字体。 |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | 将数据以 base64 形式写入 HTML 文档本身 |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

创建新实例

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

创建新实例

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | 要从嵌入中排除的字体列表 |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

调用以写入 HTML 文档头部。每次演示文稿转换调用一次。

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 当前正在渲染的演示文稿。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

调用以写入 HTML 文档尾部。每次演示文稿转换调用一次。

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 当前正在渲染的演示文稿。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

调用以写入 HTML 幻灯片头部。每张幻灯片调用一次。

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 当前正在渲染的幻灯片。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

调用以写入 HTML 幻灯片尾部。每张幻灯片调用一次。

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 当前正在渲染的幻灯片。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

在形状渲染之前调用。每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片的图像生成将结束，插入生成的 HTML 片段并在前一图像之上开始生成新图像。

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 即将渲染的形状。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

在形状渲染之前调用。每个形状调用一次。如果此函数向 generator 写入任何内容，当前幻灯片的图像生成将结束，插入生成的 HTML 片段并在前一图像之上开始生成新图像。

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最后渲染的形状。 |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

写入包含在 [Presentation](../../com.aspose.slides/presentation) 中的所有字体。

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 输出对象。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 当前正在渲染的演示文稿。 |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

将数据以 base64 形式写入 HTML 文档本身

**Parameters:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML 生成器 |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | 要序列化的字体 |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | 替代字体（如果发生字体替换），否则为 null |
| fontStyle | java.lang.String | 字体样式 |
| fontWeight | java.lang.String | 字体粗细 |
| fontData | byte[] | 字体数据 |