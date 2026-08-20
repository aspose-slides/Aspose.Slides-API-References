---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: 控制 html 文件的生成。
type: docs
url: /zh-hant/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

控制 html 文件的生成。
## 方法

| 方法 | 描述 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 呼叫以寫入 html 文件標頭。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 呼叫以寫入 html 文件頁腳。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 呼叫以寫入 html 投影片標頭。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 呼叫以寫入 html 投影片頁腳。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 在形狀渲染之前被呼叫。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 在形狀渲染之前被呼叫。 |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

呼叫以寫入 html 文件標頭。 每次演示轉換時呼叫一次。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在呈現的演示文稿。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

呼叫以寫入 html 文件頁腳。 每次演示轉換時呼叫一次。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在呈現的演示文稿。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

呼叫以寫入 html 投影片標頭。 每張投影片呼叫一次。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 目前正在呈現的投影片。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

呼叫以寫入 html 投影片頁腳。 每張投影片呼叫一次。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 目前正在呈現的投影片。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

在形狀渲染之前被呼叫。 每個形狀呼叫一次。 若此函式向 generator 寫入任何內容，則當前投影片的圖像生成將結束，加入的 html 片段會被插入，並在先前圖像之上開始新的圖像。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 即將渲染的形狀。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

在形狀渲染之前被呼叫。 每個形狀呼叫一次。 若此函式向 generator 寫入任何內容，則當前投影片的圖像生成將結束，加入的 html 片段會被插入，並在先前圖像之上開始新的圖像。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最後渲染的形狀。 |