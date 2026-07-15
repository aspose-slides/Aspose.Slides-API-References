---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 用於以 WOFF 格式嵌入所有簡報字型的格式控制器類別。
type: docs
url: /zh-hant/com.aspose.slides/embedallfontshtmlcontroller/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

用於以 WOFF 格式嵌入所有簡報字型的格式控制器類別。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | 建立新實例 |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | 建立新實例 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 呼叫以寫入 HTML 文件標頭。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 呼叫以寫入 HTML 文件頁尾。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 呼叫以寫入 HTML 投影片標頭。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 呼叫以寫入 HTML 投影片頁尾。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 呼叫於形狀渲染之前。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 呼叫於形狀渲染之前。 |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 寫入 [Presentation](../../com.aspose.slides/presentation) 中包含的所有字型。 |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | 將資料以 base64 形式寫入 HTML 文件本身 |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

建立新實例

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

建立新實例

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | 要從嵌入中排除的字型 |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

呼叫以寫入 HTML 文件標頭。每次簡報轉換時呼叫一次。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在渲染的簡報。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

呼叫以寫入 HTML 文件頁尾。每次簡報轉換時呼叫一次。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在渲染的簡報。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

呼叫以寫入 HTML 投影片標頭。每張投影片呼叫一次。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 目前正在渲染的投影片。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

呼叫以寫入 HTML 投影片頁尾。每張投影片呼叫一次。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 目前正在渲染的投影片。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

呼叫於形狀渲染之前。每個形狀呼叫一次。如果此函式寫入任何內容至 generator，當前投影片的影像產生將會結束，加入的 HTML 片段會被插入，並在先前的影像之上開始產生新的影像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 即將渲染的形狀。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

呼叫於形狀渲染之前。每個形狀呼叫一次。如果此函式寫入任何內容至 generator，當前投影片的影像產生將會結束，加入的 HTML 片段會被插入，並在先前的影像之上開始產生新的影像。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最後渲染的形狀。 |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

寫入 [Presentation](../../com.aspose.slides/presentation) 中包含的所有字型。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在渲染的簡報。 |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

將資料以 base64 形式寫入 HTML 文件本身

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML 產生器 |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | 要序列化的字型 |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | 替代字型（若發生字型取代），否則為 null |
| fontStyle | java.lang.String | 字型樣式 |
| fontWeight | java.lang.String | 字型粗細 |
| fontData | byte[] | 字型資料 |