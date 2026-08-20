---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides 的 Java API 參考
description: 用於以 WOFF 格式嵌入所有簡報字型的格式化控制器類別。
type: docs
url: /zh-hant/com.aspose.slides/embedallfontshtmlcontroller/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

用於以 WOFF 格式嵌入所有簡報字型的格式化控制器類別。

## 建構子

| 建構子 | 說明 |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | 建立新執行個體 |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | 建立新執行個體 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 用於寫入 HTML 文件標頭。 |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 用於寫入 HTML 文件頁腳。 |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 用於寫入 HTML 投影片標頭。 |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | 用於寫入 HTML 投影片頁腳。 |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 於形狀渲染之前呼叫。 |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | 於形狀渲染之前呼叫。 |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | 寫入 [Presentation](../../com.aspose.slides/presentation) 中包含的所有字型。 |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | 將資料以 Base64 編碼寫入 HTML 文件本身 |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

建立新執行個體

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

建立新執行個體

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | 要從嵌入中排除的字型 |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

用於寫入 HTML 文件標頭。於每次簡報轉換時呼叫一次。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在渲染的簡報。 |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

用於寫入 HTML 文件頁腳。於每次簡報轉換時呼叫一次。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在渲染的簡報。 |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

用於寫入 HTML 投影片標頭。於每張投影片呼叫一次。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 目前正在渲染的投影片。 |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

用於寫入 HTML 投影片頁腳。於每張投影片呼叫一次。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 目前正在渲染的投影片。 |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

於形狀渲染之前呼叫。於每個形狀呼叫一次。若此函式向 generator 寫入任何內容，當前投影片影像生成將結束，加入的 HTML 片段將被插入，並在先前的影像之上開始新影像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 即將渲染的形狀。 |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

於形狀渲染之前呼叫。於每個形狀呼叫一次。若此函式向 generator 寫入任何內容，當前投影片影像生成將結束，加入的 HTML 片段將被插入，並在先前的影像之上開始新影像。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 最後渲染的形狀。 |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

寫入 [Presentation](../../com.aspose.slides/presentation) 中包含的所有字型。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | 輸出物件。 |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 目前正在渲染的簡報。 |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

將資料以 Base64 編碼寫入 HTML 文件本身

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML 產生器 |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | 要序列化的字型 |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | 替代字型（若發生字型替代），否則為 null |
| fontStyle | java.lang.String | 字型樣式 |
| fontWeight | java.lang.String | 字型粗細 |
| fontData | byte[] | 字型資料 |