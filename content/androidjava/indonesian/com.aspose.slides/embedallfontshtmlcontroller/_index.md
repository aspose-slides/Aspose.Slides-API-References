---
title: EmbedAllFontsHtmlController
second_title: Referensi API Java Aspose.Slides untuk Android
description: Kelas pengontrol format yang digunakan untuk menyematkan semua font presentasi dalam format WOFF.
type: docs
url: /id/com.aspose.slides/embedallfontshtmlcontroller/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Kelas pengontrol format untuk digunakan dalam menyematkan semua font presentasi dalam format WOFF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Membuat instance baru |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Membuat instance baru |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Dipanggil untuk menulis header dokumen html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Dipanggil untuk menulis footer dokumen html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Dipanggil untuk menulis header slide html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Dipanggil untuk menulis footer slide html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Dipanggil sebelum proses rendering shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Dipanggil sebelum proses rendering shape. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Menulis semua font yang terkandung dalam [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Menulis data sebagai base64 ke dalam dokumen HTML itu sendiri |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

Membuat instance baru

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

Membuat instance baru

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Font yang akan dikecualikan dari penyematan |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Dipanggil untuk menulis header dokumen html. Dipanggil sekali per konversi presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang sedang dirender. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Dipanggil untuk menulis footer dokumen html. Dipanggil sekali per konversi presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang sedang dirender. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Dipanggil untuk menulis header slide html. Dipanggil sekali per setiap slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek output. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide yang sedang dirender. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Dipanggil untuk menulis footer slide html. Dipanggil sekali per setiap slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek output. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide yang sedang dirender. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Dipanggil sebelum proses rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan dan gambar baru akan dimulai di atas yang sebelumnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek output. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan dirender. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Dipanggil sebelum proses rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan dan gambar baru akan dimulai di atas yang sebelumnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek output. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape yang dirender terakhir. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Menulis semua font yang terkandung dalam [Presentation](../../com.aspose.slides/presentation).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang sedang dirender. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Menulis data sebagai base64 ke dalam dokumen HTML itu sendiri

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Generator HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Font yang akan diserialisasi |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Font yang digantikan (jika substitusi font terjadi), null bila tidak |
| fontStyle | java.lang.String | Gaya font |
| fontWeight | java.lang.String | Berat font |
| fontData | byte[] | Data font |