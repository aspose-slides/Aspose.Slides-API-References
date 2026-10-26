---
title: SVGOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili opsi SVG.
type: docs
url: /id/com.aspose.slides/svgoptions/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Mewakili opsi SVG.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Menginisialisasi instansi baru dari kelas SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Menginisialisasi instansi baru dari kelas SVGOptions dengan menentukan objek kontroler penanaman tautan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. |
| [getUseFrameSize()](#getUseFrameSize--) | Menentukan apakah bingkai teks akan disertakan dalam area rendering atau tidak. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Menentukan apakah bingkai teks akan disertakan dalam area rendering atau tidak. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat rendering atau tidak. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat rendering atau tidak. |
| [getVectorizeText()](#getVectorizeText--) | Menentukan apakah teks pada slide akan disimpan sebagai grafik. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Menentukan apakah teks pada slide akan disimpan sebagai grafik. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Mengembalikan atau mengatur batas resolusi rendah untuk rasterisasi metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Mengembalikan atau mengatur batas resolusi rendah untuk rasterisasi metafile. |
| [getDisable3DText()](#getDisable3DText--) | Menentukan apakah teks 3D dinonaktifkan dalam SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Menentukan apakah teks 3D dinonaktifkan dalam SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. |
| [getDefault()](#getDefault--) | Mengembalikan pengaturan default. |
| [getSimple()](#getSimple--) | Mengembalikan pengaturan untuk generasi file SVG paling sederhana dan terkecil. |
| [getWYSIWYG()](#getWYSIWYG--) | Mengembalikan pengaturan untuk generasi file SVG paling akurat. |
| [getJpegQuality()](#getJpegQuality--) | Menentukan kualitas enkoding JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Menentukan kualitas enkoding JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Mengembalikan dan mengatur antarmuka callback yang memungkinkan pengguna mengontrol konversi bentuk. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Mengembalikan dan mengatur antarmuka callback yang memungkinkan pengguna mengontrol konversi bentuk. |
| [getPicturesCompression()](#getPicturesCompression--) | Mewakili tingkat kompresi gambar |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Mewakili tingkat kompresi gambar |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Menentukan cara menangani font yang dimuat secara eksternal. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Menentukan cara menangani font yang dimuat secara eksternal. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Menginisialisasi instansi baru dari kelas SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Menginisialisasi instansi baru dari kelas SVGOptions dengan menentukan objek kontroler penanaman tautan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Referensi kontroler penanaman tautan. |

--------------------

Kontroler penanaman tautan adalah objek delegasi yang bertanggung jawab untuk membuat keputusan apakah sumber daya (seperti gambar) perlu ditanamkan atau direferensikan sebagai sumber daya eksternal. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Baca-saja [IInkOptions](../../com.aspose.slides/iinkoptions)

**Mengembalikan:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Menentukan apakah bingkai teks akan disertakan dalam area rendering atau tidak. Baca/tulis boolean. Nilai default adalah false.

**Mengembalikan:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Menentukan apakah bingkai teks akan disertakan dalam area rendering atau tidak. Baca/tulis boolean. Nilai default adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat rendering atau tidak. Baca/tulis boolean. Nilai default adalah true.

**Mengembalikan:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat rendering atau tidak. Baca/tulis boolean. Nilai default adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Menentukan apakah teks pada slide akan disimpan sebagai grafik. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Menentukan apakah teks pada slide akan disimpan sebagai grafik. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Mengembalikan atau mengatur batas resolusi rendah untuk rasterisasi metafile. Baca/tulis int.

**Mengembalikan:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Mengembalikan atau mengatur batas resolusi rendah untuk rasterisasi metafile. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Menentukan apakah teks 3D dinonaktifkan dalam SVG. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Menentukan apakah teks 3D dinonaktifkan dalam SVG. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. Mesin penulisan SVG Aspose.Slides memiliki solusi sementara: memotong ujung garis dengan panah sehingga garis tidak tumpang tindih dengan penanda. Opsi ini menonaktifkan perilaku tersebut. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. Mesin penulisan SVG Aspose.Slides memiliki solusi sementara: memotong ujung garis dengan panah sehingga garis tidak tumpang tindih dengan penanda. Opsi ini menonaktifkan perilaku tersebut. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Mengembalikan pengaturan default. Baca-saja [SVGOptions](../../com.aspose.slides/svgoptions).

**Mengembalikan:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Mengembalikan pengaturan untuk generasi file SVG paling sederhana dan terkecil. Baca-saja [SVGOptions](../../com.aspose.slides/svgoptions).

**Mengembalikan:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Mengembalikan pengaturan untuk generasi file SVG paling akurat. Baca-saja [SVGOptions](../../com.aspose.slides/svgoptions).

**Mengembalikan:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Menentukan kualitas enkoding JPEG. Baca/tulis int.

**Mengembalikan:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Menentukan kualitas enkoding JPEG. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Mengembalikan dan mengatur antarmuka callback yang memungkinkan pengguna mengontrol konversi bentuk. Baca/tulis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Mengembalikan:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Mengembalikan dan mengatur antarmuka callback yang memungkinkan pengguna mengontrol konversi bentuk. Baca/tulis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true bagian yang dipotong akan dihapus, jika false mereka akan diserialisasi dalam dokumen (yang dapat menyebabkan file lebih besar)

**Mengembalikan:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true bagian yang dipotong akan dihapus, jika false mereka akan diserialisasi dalam dokumen (yang dapat menyebabkan file lebih besar)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Menentukan cara menangani font yang dimuat secara eksternal. Baca/tulis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Mengembalikan:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Menentukan cara menangani font yang dimuat secara eksternal. Baca/tulis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika diset ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diset ke false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
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

Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika diset ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diset ke false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |