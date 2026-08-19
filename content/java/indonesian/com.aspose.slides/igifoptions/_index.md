---
title: IGifOptions
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili opsi pengeksporan GIF.
type: docs
url: /id/com.aspose.slides/igifoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Mewakili opsi pengeksporan GIF.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Mendapatkan atau mengatur ukuran frame. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Mendapatkan atau mengatur ukuran frame. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Menentukan apakah slide tersembunyi akan diekspor. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Menentukan apakah slide tersembunyi akan diekspor. |
| [getTransitionFps()](#getTransitionFps--) | Mendapatkan atau mengatur FPS transisi [frame/dtk] Nilai default adalah 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Mendapatkan atau mengatur FPS transisi [frame/dtk] Nilai default adalah 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Mendapatkan atau mengatur waktu tunda default [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Mendapatkan atau mengatur waktu tunda default [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```

Mendapatkan atau mengatur ukuran frame.

--------------------

Jika ukuran kosong maka nilai akan diambil dari [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Mengembalikan:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```

Mendapatkan atau mengatur ukuran frame.

--------------------

Jika ukuran kosong maka nilai akan diambil dari [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Dimension |  |
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

Mendapatkan atau mengatur FPS transisi [frame/dtk] Nilai default adalah 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

Mendapatkan atau mengatur FPS transisi [frame/dtk] Nilai default adalah 25.

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

Mendapatkan atau mengatur waktu tunda default [ms]. Nilai ini akan digunakan jika [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) tidak disetel. Nilai default adalah 1000.

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

Mendapatkan atau mengatur waktu tunda default [ms]. Nilai ini akan digunakan jika [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) tidak disetel. Nilai default adalah 1000.

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