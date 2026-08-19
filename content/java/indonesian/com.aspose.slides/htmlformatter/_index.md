---
title: HtmlFormatter
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili templat file HTML.
type: docs
url: /id/com.aspose.slides/htmlformatter/
---
**Warisan:**
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
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Membuat dan mengembalikan format HTML untuk tampilan dokumen sederhana yang terdiri dari urutan slide satu di bawah yang lain. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Membuat dan mengembalikan format HTML untuk slide show HTML sederhana yang menampilkan slide satu demi satu. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Membuat dan mengembalikan format HTML untuk pembuatan HTML yang dipandu oleh callback khusus. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Membuat dan mengembalikan format HTML untuk tampilan dokumen sederhana yang terdiri dari urutan slide satu di bawah yang lain.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| css | java.lang.String | Menentukan CSS untuk file ini. |
| showSlideTitle | boolean | Tambahkan judul slide jika ada di atas gambar slide. |

**Mengembalikan:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objek [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Membuat dan mengembalikan format HTML untuk slide show HTML sederhana yang menampilkan slide satu demi satu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| css | java.lang.String | Menentukan URL file CSS yang digunakan. |
| showSlideTitle | boolean | Tambahkan judul slide jika ada di atas gambar slide. |

**Mengembalikan:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objek [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Membuat dan mengembalikan format HTML untuk pembuatan HTML yang dipandu oleh callback khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Antarmuka callback yang mengontrol pembuatan file HTML. |

**Mengembalikan:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objek [HtmlFormatter](../../com.aspose.slides/htmlformatter).