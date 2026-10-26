---
title: HtmlOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili opsi pengeksporan HTML.
type: docs
url: /id/com.aspose.slides/htmloptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Mewakili opsi pengeksporan HTML.

## Konstruktor

| Constructor | Deskripsi |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Membuat objek HtmlOptions baru yang menentukan callback. |
| [HtmlOptions()](#HtmlOptions--) | Membuat objek HtmlOptions baru untuk menyimpan ke dalam satu file HTML. |

## Metode

| Method | Deskripsi |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Mengembalikan atau mengatur templat HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Mengembalikan atau mengatur templat HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Mengembalikan atau mengatur opsi format gambar slide. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Mengembalikan atau mengatur opsi format gambar slide. |
| [getJpegQuality()](#getJpegQuality--) | Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Mewakili tingkat kompresi gambar |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Mewakili tingkat kompresi gambar |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True untuk mengecualikan atribut lebar dan tinggi dari kontainer svg - yang akan membuat tata letak responsif. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True untuk mengecualikan atribut lebar dan tinggi dari kontainer svg - yang akan membuat tata letak responsif. |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Membuat objek HtmlOptions baru yang menentukan callback.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Objek callback yang mengontrol penyimpanan proyek. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Membuat objek HtmlOptions baru untuk menyimpan ke dalam satu file HTML.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Baca-saja [IInkOptions](../../com.aspose.slides/iinkoptions)

**Mengembalikan:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah false.

**Mengembalikan:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah false.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Mengembalikan atau mengatur templat HTML. Baca/tulis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Mengembalikan:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Mengembalikan atau mengatur templat HTML. Baca/tulis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Saat diatur ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Saat diatur ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Mengembalikan atau mengatur opsi format gambar slide. Baca/tulis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Mengembalikan:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Mengembalikan atau mengatur opsi format gambar slide. Baca/tulis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Baca/tulis byte.

Berpengaruh hanya ketika dokumen berisi gambar JPEG.

Gunakan properti ini untuk mendapatkan atau mengatur kualitas gambar di dalam dokumen saat menyimpan dalam format PDF. Nilai dapat berkisar dari 0 hingga 100 dimana 0 berarti kualitas terburuk tetapi kompresi maksimum dan 100 berarti kualitas terbaik tetapi kompresi minimum.

Nilai default adalah **95**.

**Mengembalikan:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Mengembalikan atau mengatur nilai yang menentukan kualitas gambar JPEG dalam dokumen PDF. Baca/tulis byte.

Berpengaruh hanya ketika dokumen berisi gambar JPEG.

Gunakan properti ini untuk mendapatkan atau mengatur kualitas gambar di dalam dokumen saat menyimpan dalam format PDF. Nilai dapat berkisar dari 0 hingga 100 dimana 0 berarti kualitas terburuk tetapi kompresi maksimum dan 100 berarti kualitas terbaik tetapi kompresi minimum.

Nilai default adalah **95**.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Mewakili tingkat kompresi gambar

**Mengembalikan:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Mewakili tingkat kompresi gambar

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true, bagian yang dipotong akan dihapus, jika false mereka akan diserialkan dalam dokumen (yang dapat menyebabkan file lebih besar).

**Mengembalikan:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true, bagian yang dipotong akan dihapus, jika false mereka akan diserialkan dalam dokumen (yang dapat menyebabkan file lebih besar).

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True untuk mengecualikan atribut lebar dan tinggi dari kontainer svg - yang akan membuat tata letak responsif. False - sebaliknya. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

True untuk mengecualikan atribut lebar dan tinggi dari kontainer svg - yang akan membuat tata letak responsif. False - sebaliknya. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |