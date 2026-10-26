---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: 控制 HTML 檔案的產生。
type: docs
url: /zh-hant/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

控制 HTML 檔案的產生。
## 方法

| 方法 | 說明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 呼叫以寫入 HTML 文件標頭。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 呼叫以寫入 HTML 文件頁尾。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 呼叫以寫入 HTML 投影片標頭。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 呼叫以寫入 HTML 投影片頁尾。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 在形狀渲染之前呼叫。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 在形狀渲染之前呼叫。 |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

呼叫以寫入 HTML 文件標頭。每次簡報轉換僅呼叫一次。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在渲染的簡報。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

呼叫以寫入 HTML 文件頁尾。每次簡報轉換僅呼叫一次。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在渲染的簡報。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

呼叫以寫入 HTML 投影片標頭。每張投影片僅呼叫一次。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 目前正在渲染的投影片。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

呼叫以寫入 HTML 投影片頁尾。每張投影片僅呼叫一次。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 目前正在渲染的投影片。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

在形狀渲染之前呼叫。每個形狀僅呼叫一次。如果此函式寫入任何內容到 generator，則目前投影片的影像產生將結束，插入已添加的 HTML 片段，並在先前的影像之上開始新的影像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 即將渲染的形狀。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

在形狀渲染之前呼叫。每個形狀僅呼叫一次。如果此函式寫入任何內容到 generator，則目前投影片的影像產生將結束，插入已添加的 HTML 片段，並在先前的影像之上開始新的影像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最後渲染的形狀。 |