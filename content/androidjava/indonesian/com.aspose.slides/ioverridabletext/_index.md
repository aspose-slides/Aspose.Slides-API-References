---
title: IOverridableText
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili teks yang dapat ditimpa untuk diagram.
type: docs
url: /id/com.aspose.slides/ioverridabletext/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Mewakili teks yang dapat ditimpa untuk diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Dapat berisi teks berformat kaya. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inisialisasi TextFrameForOverriding dengan teks pada parameter "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Dapat berisi teks berformat kaya. Jika properti ini tidak null maka nilai teks berformat ini menggantikan teks yang dihasilkan secara otomatis. Teks yang dihasilkan secara otomatis merupakan properti implisit dari label data, label satuan tampilan pada sumbu nilai, judul sumbu, judul diagram, label garis tren. Teks yang dihasilkan secara otomatis diformat dengan properti IFormattedTextContainer.TextFormat. Baca-saja [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

Inisialisasi TextFrameForOverriding dengan teks pada parameter "text". Jika TextFrameForOverriding sudah diinisialisasi maka cukup mengubah teksnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks untuk TextFrameForOverriding baru. |

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe) - Bingkai teks [ITextFrame](../../com.aspose.slides/itextframe)