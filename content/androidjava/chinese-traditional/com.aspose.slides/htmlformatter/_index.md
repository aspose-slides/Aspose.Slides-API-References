---
title: HtmlFormatter
second_title: Aspose.Slides 用於 Android 的 Java API 參考
description: 代表 HTML 檔案模板。
type: docs
url: /zh-hant/com.aspose.slides/htmlformatter/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)  
```
public final class HtmlFormatter implements IHtmlFormatter
```

代表 HTML 檔案模板。

## 方法

| 方法 | 說明 |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | 建立並傳回簡單文件檢視的 HTML 格式化程式，該檢視由一系列上下排列的投影片組成。 |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | 建立並傳回簡易投影片放映的 HTML 格式化程式，該放映會依序顯示投影片。 |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | 建立並傳回用於自訂回呼驅動的 HTML 產生之格式化程式。 |

### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

建立並傳回簡單文件檢視的 HTML 格式化程式，該檢視由一系列上下排列的投影片組成。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| css | java.lang.String | 指定此檔案的 CSS。 |
| showSlideTitle | boolean | 若投影片圖像上方有標題，則加入投影片標題。 |

**傳回值:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - 此 [HtmlFormatter](../../com.aspose.slides/htmlformatter) 物件。

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

建立並傳回簡易投影片放映的 HTML 格式化程式，該放映會依序顯示投影片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| css | java.lang.String | 指定所使用的 CCS 檔案 URL。 |
| showSlideTitle | boolean | 若投影片圖像上方有標題，則加入投影片標題。 |

**傳回值:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - 此 [HtmlFormatter](../../com.aspose.slides/htmlformatter) 物件。

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

建立並傳回用於自訂回呼驅動的 HTML 產生之格式化程式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | 控制 HTML 檔案產生的回呼介面。 |

**傳回值:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - 此 [HtmlFormatter](../../com.aspose.slides/htmlformatter) 物件。