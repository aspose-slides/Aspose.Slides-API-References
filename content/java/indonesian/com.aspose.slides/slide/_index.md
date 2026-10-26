---
title: Slide
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili slide dalam presentasi.
type: docs
url: /id/com.aspose.slides/slide/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Mewakili slide dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan pengelola HeaderFooter dari slide. |
| [getThemeManager()](#getThemeManager--) | Mengembalikan pengelola tema yang menimpa. |
| [getSlideNumber()](#getSlideNumber--) | Mengembalikan nomor slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Mengembalikan nomor slide. |
| [getHidden()](#getHidden--) | Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. |
| [setHidden(boolean value)](#setHidden-boolean-) | Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Mengembalikan objek Thumbnail Image dengan skala khusus. |
| [getImage()](#getImage--) | Mengembalikan objek Thumbnail Image (20% dari ukuran asli). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Mengembalikan objek Thumbnail Image dengan ukuran tertentu. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Mengembalikan objek gambar tiff Thumbnail dengan parameter tertentu. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Mengembalikan objek Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Mengembalikan objek Thumbnail Image dengan skala khusus. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Mengembalikan objek Thumbnail Image dengan ukuran tertentu. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Menyimpan konten slide sebagai berkas SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Menyimpan konten slide sebagai berkas SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Menyimpan konten slide sebagai berkas EMF. |
| [remove()](#remove--) | Menghapus slide dari presentasi. |
| [getLayoutSlide()](#getLayoutSlide--) | Mengembalikan atau mengatur layout slide untuk slide saat ini. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Mengembalikan atau mengatur layout slide untuk slide saat ini. |
| [reset()](#reset--) | Mengatur ulang posisi, ukuran, dan pemformatan setiap shape yang memiliki prototipe pada LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Memungkinkan mengakses notes slide, menambah dan menghapusnya. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan pemformatan yang sama di semua paragraf dalam semua shape yang dapat diterima. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Mengembalikan pengelola HeaderFooter dari slide. Hanya-baca [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Mengembalikan:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Mengembalikan pengelola tema yang menimpa. Hanya-baca [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Mengembalikan:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Mengembalikan nomor slide. Indeks slide dalam koleksi [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) selalu sama dengan SlideNumber - Presentation.FirstSlideNumber. Baca/tulis int.

**Mengembalikan:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Mengembalikan nomor slide. Indeks slide dalam koleksi [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) selalu sama dengan SlideNumber - Presentation.FirstSlideNumber. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Mengembalikan objek Thumbnail Image dengan skala khusus.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Membuat gambar skala penuh
>      IImage bmp = sld.getImage(1f, 1f);
>      // Menyimpan gambar ke disk dalam format JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Mengonversi slide pertama dalam presentasi menjadi objek Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Menyimpan gambar dalam format PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // Membuat gambar skala penuh
>          IImage bmp = sld.getImage(1f, 1f);
>          // Menyimpan gambar ke disk dalam format JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // Menentukan dimensi
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Mendapatkan nilai skala X dan Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Membuat gambar skala penuh
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Menyimpan gambar ke disk dalam format JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | float | Nilai yang digunakan untuk mengubah skala Thumbnail ini pada arah sumbu x. |
| scaleY | float | Nilai yang digunakan untuk mengubah skala Thumbnail ini pada arah sumbu y. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - objek IImage.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Mengembalikan objek Thumbnail Image (20% dari ukuran asli).

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Mengembalikan objek Thumbnail Image dengan ukuran tertentu.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Mengonversi slide pertama dalam presentasi menjadi Bitmap dengan ukuran yang ditentukan
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Menyimpan gambar dalam format JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Ukuran gambar yang akan dibuat. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - objek Image.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Mengembalikan objek gambar tiff Thumbnail dengan parameter tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | opsi Tiff. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - objek Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Mengembalikan objek Thumbnail Image.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | opsi rendering. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - objek Image.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Mengembalikan objek Thumbnail Image dengan skala khusus.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Membuat opsi rendering
>      IRenderingOptions options = new RenderingOptions();
>      // Membuat opsi tata letak catatan dan komentar
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Menetapkan posisi catatan pada halaman
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Menetapkan posisi komentar pada halaman
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Menetapkan lebar area keluaran komentar
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Menetapkan warna untuk area komentar
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Menetapkan opsi tata letak untuk rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Mengonversi slide pertama dari presentasi menjadi objek BufferedImage
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Menyimpan gambar dalam format GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | opsi rendering. |
| scaleX | float | Nilai yang digunakan untuk mengubah skala Thumbnail ini pada arah sumbu x. |
| scaleY | float | Nilai yang digunakan untuk mengubah skala Thumbnail ini pada arah sumbu y. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - objek Bitmap.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Mengembalikan objek Thumbnail Image dengan ukuran tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | opsi rendering. |
| imageSize | java.awt.Dimension | Ukuran gambar yang akan dibuat. |

**Mengembalikan:**
[IImage](../../com.aspose.slides/iimage) - objek Image.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Menyimpan konten slide sebagai berkas SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Menyimpan slide pertama sebagai berkas SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Menyimpan konten slide sebagai berkas SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Menyimpan slide pertama sebagai berkas SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | opsi pembuatan SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Menyimpan konten slide sebagai berkas EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Menyimpan slide pertama sebagai metafile
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |
### remove() {#remove--}
```
public final void remove()
```

Menghapus slide dari presentasi.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Mengembalikan atau mengatur layout slide untuk slide saat ini. Baca/tulis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Mengembalikan:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Mengembalikan atau mengatur layout slide untuk slide saat ini. Baca/tulis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

Mengatur ulang posisi, ukuran, dan pemformatan setiap shape yang memiliki prototipe pada LayoutSlide.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Memungkinkan mengakses notes slide, menambah dan menghapusnya. Hanya-baca [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Mengembalikan:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Penulis komentar yang dicari atau null untuk mengembalikan semua komentar. |

**Mengembalikan:**
com.aspose.slides.IComment[] - Array dari [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Menggabungkan run dengan pemformatan yang sama di semua paragraf dalam semua shape yang dapat diterima.