---
title: ISVGOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili opsi SVG.
type: docs
url: /id/com.aspose.slides/isvgoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Mewakili opsi SVG.
## Metode

| Metode | Deskripsi |
| --- | --- |
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
| [getJpegQuality()](#getJpegQuality--) | Menentukan kualitas enkoding JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Menentukan kualitas enkoding JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Mengembalikan dan mengatur antarmuka panggilan balik yang memungkinkan pengguna mengontrol konversi bentuk. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Mengembalikan dan mengatur antarmuka panggilan balik yang memungkinkan pengguna mengontrol konversi bentuk. |
| [getPicturesCompression()](#getPicturesCompression--) | Mewakili tingkat kompresi gambar Baca/tulis \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Mewakili tingkat kompresi gambar Baca/tulis \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. |
| [getUseFrameSize()](#getUseFrameSize--) | Menentukan apakah bingkai teks akan disertakan dalam area render atau tidak. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Menentukan apakah bingkai teks akan disertakan dalam area render atau tidak. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat merender atau tidak. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat merender atau tidak. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Menentukan cara menangani font yang dimuat secara eksternal. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Menentukan cara menangani font yang dimuat secara eksternal. |
| [getInkOptions()](#getInkOptions--) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Menentukan apakah teks pada slide akan disimpan sebagai grafik. Boolean baca/tulis.

**Mengembalikan:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Menentukan apakah teks pada slide akan disimpan sebagai grafik. Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Mengembalikan atau mengatur batas resolusi rendah untuk rasterisasi metafile. Int baca/tulis.

**Mengembalikan:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Mengembalikan atau mengatur batas resolusi rendah untuk rasterisasi metafile. Int baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Menentukan apakah teks 3D dinonaktifkan dalam SVG. Boolean baca/tulis.

**Mengembalikan:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Menentukan apakah teks 3D dinonaktifkan dalam SVG. Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. Boolean baca/tulis.

**Mengembalikan:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Menonaktifkan pemisahan gradien FromCornerX dan FromCenter. Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. Mesin penulisan SVG Aspose.Slides memiliki solusi untuk masalah tersebut: ia memangkas ujung garis dengan panah, sehingga garis tidak tumpang tindih dengan penanda. Opsi ini mematikan perilaku tersebut. Boolean baca/tulis.

**Mengembalikan:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 tidak memiliki kemampuan untuk mendefinisikan inset untuk penanda. Mesin penulisan SVG Aspose.Slides memiliki solusi untuk masalah tersebut: ia memangkas ujung garis dengan panah, sehingga garis tidak tumpang tindih dengan penanda. Opsi ini mematikan perilaku tersebut. Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Menentukan kualitas enkoding JPEG. Int baca/tulis.

**Mengembalikan:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Menentukan kualitas enkoding JPEG. Int baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Mengembalikan dan mengatur antarmuka panggilan balik yang memungkinkan pengguna mengontrol konversi bentuk. Baca/tulis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Mengembalikan:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Mengembalikan dan mengatur antarmuka panggilan balik yang memungkinkan pengguna mengontrol konversi bentuk. Baca/tulis [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Mewakili tingkat kompresi gambar Baca/tulis \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Mengembalikan:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Mewakili tingkat kompresi gambar Baca/tulis \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true bagian yang dipotong akan dihapus, jika false mereka akan diserialkan dalam dokumen (yang dapat menyebabkan file lebih besar) Boolean baca/tulis.

**Mengembalikan:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Bendera boolean menunjukkan apakah bagian yang dipotong tetap menjadi bagian dari dokumen. Jika true bagian yang dipotong akan dihapus, jika false mereka akan diserialkan dalam dokumen (yang dapat menyebabkan file lebih besar) Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Menentukan apakah bingkai teks akan disertakan dalam area render atau tidak. Boolean baca/tulis. Nilai default adalah false.

**Mengembalikan:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Menentukan apakah bingkai teks akan disertakan dalam area render atau tidak. Boolean baca/tulis. Nilai default adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat merender atau tidak. Boolean baca/tulis. Nilai default adalah true.

**Mengembalikan:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Menentukan apakah melakukan rotasi yang ditentukan pada bentuk saat merender atau tidak. Boolean baca/tulis. Nilai default adalah true.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Menentukan cara menangani font yang dimuat secara eksternal. Baca/tulis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Mengembalikan:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Menentukan cara menangani font yang dimuat secara eksternal. Baca/tulis [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Hanya baca [IInkOptions](../../com.aspose.slides/iinkoptions)

**Mengembalikan:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Saat disetel ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke false.

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
public abstract void setDisableFontLigatures(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Saat disetel ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke false.

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
| --- | --- | ---
| value | boolean |  |