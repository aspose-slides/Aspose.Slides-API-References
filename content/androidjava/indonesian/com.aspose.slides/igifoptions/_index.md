---
title: IGifOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili opsi ekspor GIF.
type: docs
url: /id/com.aspose.slides/igifoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Mewakili opsi ekspor GIF.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Mendapatkan atau mengatur ukuran bingkai. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Mendapatkan atau mengatur ukuran bingkai. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Menentukan apakah slide tersembunyi akan diekspor. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Menentukan apakah slide tersembunyi akan diekspor. |
| [getTransitionFps()](#getTransitionFps--) | Mendapatkan atau mengatur FPS transisi [frame/detik] Nilai default adalah 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Mendapatkan atau mengatur FPS transisi [frame/detik] Nilai default adalah 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Mendapatkan atau mengatur waktu tunda default [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Mendapatkan atau mengatur waktu tunda default [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


Mendapatkan atau mengatur ukuran bingkai.

--------------------

Jika ukuran kosong maka nilainya akan diambil dari [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Mengembalikan:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```


Mendapatkan atau mengatur ukuran bingkai.

--------------------

Jika ukuran kosong maka nilainya akan diambil dari [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Menentukan apakah slide tersembunyi akan diekspor. Nilai default adalah false.

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
public abstract void setExportHiddenSlides(boolean value)
```


Menentukan apakah slide tersembunyi akan diekspor. Nilai default adalah false.

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
public abstract int getTransitionFps()
```


Mendapatkan atau mengatur FPS transisi [frame/detik] Nilai default adalah 25.

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
public abstract void setTransitionFps(int value)
```


Mendapatkan atau mengatur FPS transisi [frame/detik] Nilai default adalah 25.

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
public abstract int getDefaultDelay()
```


Mendapatkan atau mengatur waktu tunda default [ms]. Nilai ini akan digunakan jika [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) tidak diatur. Nilai default adalah 1000.

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
public abstract void setDefaultDelay(int value)
```


Mendapatkan atau mengatur waktu tunda default [ms]. Nilai ini akan digunakan jika [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) tidak diatur. Nilai default adalah 1000.

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