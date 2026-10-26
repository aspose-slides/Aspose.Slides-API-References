---
title: ITiffOptions
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format TIFF.
type: docs
url: /id/com.aspose.slides/itiffoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format TIFF.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getImageSize()](#getImageSize--) | Menentukan ukuran gambar TIFF yang dihasilkan. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Menentukan ukuran gambar TIFF yang dihasilkan. |
| [getDpiX()](#getDpiX--) | Menentukan resolusi horizontal dalam titik per inci. |
| [setDpiX(long value)](#setDpiX-long-) | Menentukan resolusi horizontal dalam titik per inci. |
| [getDpiY()](#getDpiY--) | Menentukan resolusi vertikal dalam titik per inci. |
| [setDpiY(long value)](#setDpiY-long-) | Menentukan resolusi vertikal dalam titik per inci. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getCompressionType()](#getCompressionType--) | Menentukan jenis kompresi. |
| [setCompressionType(int value)](#setCompressionType-int-) | Menentukan jenis kompresi. |
| [getPixelFormat()](#getPixelFormat--) | Menentukan format piksel untuk gambar yang dihasilkan. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Menentukan format piksel untuk gambar yang dihasilkan. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. |
| [getInkOptions()](#getInkOptions--) | Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Menentukan ukuran gambar TIFF yang dihasilkan. Nilai default adalah 0x0, yang berarti bahwa ukuran gambar yang dihasilkan akan dihitung berdasarkan nilai ukuran slide presentasi. Baca/tulis [Size](../../com.aspose.slides.android/size).

**Mengembalikan:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Menentukan ukuran gambar TIFF yang dihasilkan. Nilai default adalah 0x0, yang berarti bahwa ukuran gambar yang dihasilkan akan dihitung berdasarkan nilai ukuran slide presentasi. Baca/tulis [Size](../../com.aspose.slides.android/size).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Menentukan resolusi horizontal dalam titik per inci. Baca/tulis long.

**Mengembalikan:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Menentukan resolusi horizontal dalam titik per inci. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Menentukan resolusi vertikal dalam titik per inci. Baca/tulis long.

**Mengembalikan:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Menentukan resolusi vertikal dalam titik per inci. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah false.

**Mengembalikan:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah false.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Menentukan jenis kompresi. Baca/tulis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Mengembalikan:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Menentukan jenis kompresi. Baca/tulis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Menentukan format piksel untuk gambar yang dihasilkan. Baca/tulis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Mengembalikan:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Menentukan format piksel untuk gambar yang dihasilkan. Baca/tulis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Mendapatkan atau mengatur mode penempatan slide pada halaman saat mengekspor presentasi [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract int getBwConversionMode()
```

Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) diatur ke [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) atau [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Baca/tulis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default adalah [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public abstract void setBwConversionMode(int value)
```

Menentukan algoritma untuk mengonversi gambar berwarna menjadi gambar hitam putih. Opsi ini hanya akan diterapkan jika CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) diatur ke [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) atau [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Baca/tulis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default adalah [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Menyediakan opsi yang mengontrol tampilan objek Ink dalam dokumen yang diekspor. Hanya-baca [IInkOptions](../../com.aspose.slides/iinkoptions)

**Mengembalikan:**
[IInkOptions](../../com.aspose.slides/iinkoptions)