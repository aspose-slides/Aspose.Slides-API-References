---
title: ISlide
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sebuah slide dalam presentasi.
type: docs
url: /id/com.aspose.slides/islide/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Mewakili sebuah slide dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter dari slide. |
| [getSlideNumber()](#getSlideNumber--) | Mengembalikan nomor slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Mengembalikan nomor slide. |
| [getHidden()](#getHidden--) | Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. |
| [setHidden(boolean value)](#setHidden-boolean-) | Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Mengembalikan objek gambar dengan skala khusus. |
| [getImage()](#getImage--) | Mengembalikan objek Gambar Thumbnail (20% dari ukuran sebenarnya). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Mengembalikan objek gambar dengan ukuran yang ditentukan. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Mengembalikan objek bitmap tiff Thumbnail dengan parameter yang ditentukan. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Mengembalikan objek Bitmap Thumbnail. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Mengembalikan objek Bitmap Thumbnail dengan skala khusus. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Mengembalikan objek Bitmap Thumbnail dengan ukuran yang ditentukan. |
| [getLayoutSlide()](#getLayoutSlide--) | Mengembalikan atau mengatur layout slide untuk slide saat ini. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Mengembalikan atau mengatur layout slide untuk slide saat ini. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Memungkinkan mengakses slide catatan, menambah dan menghapusnya. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Menyimpan konten slide sebagai file SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Menyimpan konten slide sebagai file SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Menyimpan konten slide sebagai file EMF. |
| [remove()](#remove--) | Menghapus slide dari presentasi. |
| [reset()](#reset--) | Mengatur ulang posisi, ukuran, dan pemformatan setiap shape yang memiliki prototipe pada LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Mengembalikan manajer HeaderFooter dari slide. Hanya-baca [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Mengembalikan:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Mengembalikan nomor slide. Indeks slide dalam koleksi [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) selalu sama dengan SlideNumber - 1. Baca/tulis int.

**Mengembalikan:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Mengembalikan nomor slide. Indeks slide dalam koleksi [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) selalu sama dengan SlideNumber - 1. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Mengembalikan objek gambar dengan skala khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | float | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | float | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Mengembalikan objek Gambar Thumbnail (20% dari ukuran sebenarnya).

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Mengembalikan objek gambar dengan ukuran yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Ukuran gambar yang akan dibuat. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Mengembalikan objek bitmap tiff Thumbnail dengan parameter yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opsi tiff. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Mengembalikan objek Bitmap Thumbnail.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Mengembalikan objek Bitmap Thumbnail dengan skala khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |
| scaleX | float | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | float | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Mengembalikan objek Bitmap Thumbnail dengan ukuran yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |
| imageSize | java.awt.Dimension | Ukuran gambar yang akan dibuat. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Mengembalikan atau mengatur layout slide untuk slide saat ini. Baca/tulis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Mengembalikan atau mengatur layout slide untuk slide saat ini. Baca/tulis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Memungkinkan mengakses slide catatan, menambah dan menghapusnya. Hanya-baca [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Mengembalikan:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Penulis komentar yang ingin ditemukan atau null untuk mengembalikan semua komentar. |

**Mengembalikan:**
com.aspose.slides.IComment[] - Array dari [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Menyimpan konten slide sebagai file SVG.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Menyimpan konten slide sebagai file SVG.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opsi pembuatan SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Menyimpan konten slide sebagai file EMF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |
### remove() {#remove--}
```
public abstract void remove()
```

Menghapus slide dari presentasi.
### reset() {#reset--}
```
public abstract void reset()
```

Mengatur ulang posisi, ukuran, dan pemformatan setiap shape yang memiliki prototipe pada LayoutSlide.