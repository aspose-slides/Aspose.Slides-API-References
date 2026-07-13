---
title: GifOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili opsi ekspor GIF.
type: docs
url: /id/com.aspose.slides/gifoptions/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Mewakili opsi pengeksporan GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // ukuran GIF yang dihasilkan
>      gifOptions.setDefaultDelay(2000); // berapa lama setiap slide akan ditampilkan sampai diganti ke slide berikutnya
>      gifOptions.setTransitionFps(35); // tingkatkan FPS untuk kualitas animasi transisi yang lebih baik
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GifOptions()](#GifOptions--) | Menginisialisasi instance baru dari kelas GifOptions. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Mendapatkan atau mengatur ukuran frame. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Mendapatkan atau mengatur ukuran frame. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Menentukan apakah slide tersembunyi akan diekspor. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Menentukan apakah slide tersembunyi akan diekspor. |
| [getTransitionFps()](#getTransitionFps--) | Mendapatkan atau mengatur FPS transisi [frame/detik] Nilai defaultnya adalah 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Mendapatkan atau mengatur FPS transisi [frame/detik] Nilai defaultnya adalah 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Mendapatkan atau mengatur waktu tunda default [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Mendapatkan atau mengatur waktu tunda default [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Menginisialisasi instance baru dari kelas GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


Mendapatkan atau mengatur ukuran frame.

--------------------

Jika ukuran kosong maka nilai akan diambil dari [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Mengembalikan:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```


Mendapatkan atau mengatur ukuran frame.

--------------------

Jika ukuran kosong maka nilai akan diambil dari [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Menentukan apakah slide tersembunyi akan diekspor. Nilai defaultnya adalah false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Menentukan apakah slide tersembunyi akan diekspor. Nilai defaultnya adalah false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```


Mendapatkan atau mengatur FPS transisi [frame/detik] Nilai defaultnya adalah 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```


Mendapatkan atau mengatur FPS transisi [frame/detik] Nilai defaultnya adalah 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```


Mendapatkan atau mengatur waktu tunda default [ms]. Nilai ini akan digunakan jika [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) tidak disetel. Nilai defaultnya adalah 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```


Mendapatkan atau mengatur waktu tunda default [ms]. Nilai ini akan digunakan jika [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) tidak disetel. Nilai defaultnya adalah 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |