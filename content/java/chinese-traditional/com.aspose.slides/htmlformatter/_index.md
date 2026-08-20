---
title: HtmlFormatter
second_title: Aspose.Slides for Java API 參考
description: 代表 HTML 檔案範本。
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

代表 HTML 檔案範本。
## 方法

| 方法 | 說明 |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | 建立並傳回 HTML 格式化器，用於以簡單文件視圖顯示由一系列上下排列的投影片組成的內容。 |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | 建立並傳回 HTML 格式化器，用於簡單的投影片播放 HTML，依序顯示投影片。 |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | 建立並傳回 HTML 格式化器，用於自訂的回呼驅動 HTML 產生。 |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


建立並傳回 HTML 格式化器，用於以簡單文件視圖顯示由一系列上下排列的投影片組成的內容。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| css | java.lang.String | 指定此檔案的 CSS。 |
| showSlideTitle | boolean | 如果投影片影像上方有標題，則加入投影片標題。 |

**回傳值:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) 物件。
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


建立並傳回 HTML 格式化器，用於簡單的投影片播放 HTML，依序顯示投影片。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| css | java.lang.String | 指定所使用的 CCS 檔案的 URL。 |
| showSlideTitle | boolean | 如果投影片影像上方有標題，則加入投影片標題。 |

**回傳值:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) 物件。
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


建立並傳回 HTML 格式化器，用於自訂的回呼驅動 HTML 產生。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | 回呼介面，用於控制 HTML 檔案的產生。 |

**回傳值:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) 物件。