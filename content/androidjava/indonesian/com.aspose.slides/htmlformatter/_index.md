---
title: HtmlFormatter
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili templat file HTML.
type: docs
url: /id/com.aspose.slides/htmlformatter/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Mewakili templat file HTML.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple document view which consists of sequences of slides one below another. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple slide show html which shows slides one after another. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Creates and returns HTML formatter for custom callback-driven html generation. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Membuat dan mengembalikan format HTML untuk tampilan dokumen sederhana yang terdiri dari urutan slide satu di bawah yang lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| css | java.lang.String | Specifies CSS for this file. |
| showSlideTitle | boolean | Add slide title if there is one above slide image. |

**Returns:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objek [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Membuat dan mengembalikan format HTML untuk slide show sederhana yang menampilkan slide satu demi satu.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| css | java.lang.String | Specifies URL of CCS file used. |
| showSlideTitle | boolean | Add slide title if there is one above slide image. |

**Returns:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objek [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Membuat dan mengembalikan format HTML untuk generasi HTML berbasis callback khusus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Callback interface which controls html file generation. |

**Returns:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objek [HtmlFormatter](../../com.aspose.slides/htmlformatter).