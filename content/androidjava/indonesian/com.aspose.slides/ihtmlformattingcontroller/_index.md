---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Mengontrol pembuatan file html.
type: docs
url: /id/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Mengontrol pembuatan file html.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Dipanggil untuk menulis header dokumen html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Dipanggil untuk menulis footer dokumen html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Dipanggil untuk menulis header slide html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Dipanggil untuk menulis footer slide html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Dipanggil sebelum rendering shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Dipanggil sebelum rendering shape. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Dipanggil untuk menulis header dokumen html. Dipanggil sekali per konversi presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek keluaran. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang sedang dirender. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Dipanggil untuk menulis footer dokumen html. Dipanggil sekali per konversi presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek keluaran. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang sedang dirender. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Dipanggil untuk menulis header slide html. Dipanggil sekali per setiap slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek keluaran. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide yang sedang dirender. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Dipanggil untuk menulis footer slide html. Dipanggil sekali per setiap slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek keluaran. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide yang sedang dirender. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Dipanggil sebelum rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan dan gambar baru akan dimulai di atas yang sebelumnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek keluaran. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape yang akan dirender. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Dipanggil sebelum rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan dan gambar baru akan dimulai di atas yang sebelumnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objek keluaran. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape yang dirender terakhir. |