---
title: TiffOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format TIFF.
type: docs
url: /id/com.aspose.slides/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Membuat objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Menyimpan presentasi ke dokumen TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Membuat objek Presentation yang mewakili file Presentation
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Membuat objek TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Menetapkan tipe kompresi
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Tipe Kompresi
>      // Default - Menentukan skema kompresi default (LZW).
>      // None - Menentukan tidak ada kompresi.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Kedalaman tergantung pada tipe kompresi dan tidak dapat diatur secara manual.
>      // Unit resolusi selalu sama dengan 2 (dots per inch)
>      // Menetapkan DPI gambar
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Menetapkan Ukuran Gambar
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Simpan presentasi ke TIFF dengan ukuran gambar yang ditentukan
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Membuat objek Presentation yang mewakili file Presentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat berisi nilai-nilai berikut (seperti dapat dilihat pada dokumentasi):
>      //Format1bppIndexed; // 1 bit per piksel, diindeks.
>      //Format4bppIndexed; // 4 bit per piksel, diindeks.
>      //Format8bppIndexed; // 8 bit per piksel, diindeks.
>      //Format24bppRgb; // 24 bit per piksel, RGB.
>      //Format32bppArgb; // 32 bit per piksel, ARGB.
> 
>      // Simpan presentasi ke TIFF dengan ukuran gambar yang ditentukan
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Konstruktor default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getImageSize()](#getImageSize--) | Menentukan ukuran gambar TIFF yang dihasilkan. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Menentukan ukuran gambar TIFF yang dihasilkan. |
| [getDpiX()](#getDpiX--) | Menentukan resolusi horizontal dalam titik per inci. |
| [setDpiX(long value)](#setDpiX-long-) | Menentukan resolusi horizontal dalam titik per inci. |
| [getDpiY()](#getDpiY--) | Menentukan resolusi vertikal dalam titik per inci. |
| [setDpiY(long value)](#setDpiY-long-) | Menentukan resolusi vertikal dalam titik per inci. |
| [getCompressionType()](#getCompressionType--) | Menentukan tipe kompresi. |
| [setCompressionType(int value)](#setCompressionType-int-) | Menentukan tipe kompresi. |
| [getPixelFormat()](#getPixelFormat--) | Menentukan format piksel untuk gambar yang dihasilkan. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Menentukan format piksel untuk gambar yang dihasilkan. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Mendapatkan atau menetapkan mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Mendapatkan atau menetapkan mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Konstruktor default.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Hanya-baca [IInkOptions](../../com.aspose.slides/iinkoptions)

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

Menentukan ukuran gambar TIFF yang dihasilkan. Nilai default adalah 0x0, yang berarti bahwa ukuran gambar yang dihasilkan akan dihitung berdasarkan nilai ukuran slide presentasi. Baca/tulis [Size](../../com.aspose.slides.android/size).

**Mengembalikan:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

Menentukan ukuran gambar TIFF yang dihasilkan. Nilai default adalah 0x0, yang berarti bahwa ukuran gambar yang dihasilkan akan dihitung berdasarkan nilai ukuran slide presentasi. Baca/tulis [Size](../../com.aspose.slides.android/size).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Menentukan resolusi horizontal dalam titik per inci. Baca/tulis long.

**Mengembalikan:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Menentukan resolusi horizontal dalam titik per inci. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Menentukan resolusi vertikal dalam titik per inci. Baca/tulis long.

**Mengembalikan:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Menentukan resolusi vertikal dalam titik per inci. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Menentukan tipe kompresi. Baca/tulis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Mengembalikan:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Menentukan tipe kompresi. Baca/tulis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Menentukan format piksel untuk gambar yang dihasilkan. Baca/tulis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Mengembalikan:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Menentukan format piksel untuk gambar yang dihasilkan. Baca/tulis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Mendapatkan atau menetapkan mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
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

Mendapatkan atau menetapkan mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih. Opsi ini hanya diterapkan jika CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) diatur ke [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) atau [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Baca/tulis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default adalah [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

Menentukan algoritma untuk mengubah gambar berwarna menjadi gambar hitam putih. Opsi ini hanya diterapkan jika CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) diatur ke [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) atau [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Baca/tulis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default adalah [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |