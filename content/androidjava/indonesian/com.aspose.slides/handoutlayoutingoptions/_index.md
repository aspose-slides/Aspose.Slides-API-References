---
title: HandoutLayoutingOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili mode tata letak presentasi handout untuk ekspor.
type: docs
url: /id/com.aspose.slides/handoutlayoutingoptions/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

Mewakili mode tata letak presentasi handout untuk ekspor.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | Menginisialisasi nilai default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHandout()](#getHandout--) | Menentukan berapa banyak slide dan dalam urutan apa yang akan ditempatkan pada halaman [HandoutType](../../com.aspose.slides/handouttype). |
| [setHandout(int value)](#setHandout-int-) | Menentukan berapa banyak slide dan dalam urutan apa yang akan ditempatkan pada halaman [HandoutType](../../com.aspose.slides/handouttype). |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | Menentukan apakah nomor slide yang ditampilkan akan dicetak atau tidak. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | Menentukan apakah nomor slide yang ditampilkan akan dicetak atau tidak. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | Menentukan apakah akan menggambar bingkai di sekitar slide yang ditampilkan atau tidak. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | Menentukan apakah akan menggambar bingkai di sekitar slide yang ditampilkan atau tidak. |
| [getPrintComments()](#getPrintComments--) | Menentukan apakah komentar pada slide akan ditampilkan atau tidak |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | Menentukan apakah komentar pada slide akan ditampilkan atau tidak |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```


Menginisialisasi nilai default.

### getHandout() {#getHandout--}
```
public final int getHandout()
```


Menentukan berapa banyak slide dan dalam urutan apa yang akan ditempatkan pada halaman [HandoutType](../../com.aspose.slides/handouttype).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Nilai default adalah  **HandoutType.Handouts6Horizontal** .

**Mengembalikan:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```


Menentukan berapa banyak slide dan dalam urutan apa yang akan ditempatkan pada halaman [HandoutType](../../com.aspose.slides/handouttype).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah  **HandoutType.Handouts6Horizontal** .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```


Menentukan apakah nomor slide yang ditampilkan akan dicetak atau tidak.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah  **true** .

**Mengembalikan:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```


Menentukan apakah nomor slide yang ditampilkan akan dicetak atau tidak.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah  **true** .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```


Menentukan apakah akan menggambar bingkai di sekitar slide yang ditampilkan atau tidak.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah  **true** .

**Mengembalikan:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```


Menentukan apakah akan menggambar bingkai di sekitar slide yang ditampilkan atau tidak.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah  **true** .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```


Menentukan apakah komentar pada slide akan ditampilkan atau tidak

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah  **false** .

**Mengembalikan:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```


Menentukan apakah komentar pada slide akan ditampilkan atau tidak

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai default adalah  **false** .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |