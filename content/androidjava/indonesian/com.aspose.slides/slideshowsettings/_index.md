---
title: SlideShowSettings
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili pengaturan tayangan slide untuk presentasi.
type: docs
url: /id/com.aspose.slides/slideshowsettings/
---
**Pewarisan:**
java.lang.Object
```
public class SlideShowSettings
```

Mewakili pengaturan tayangan slide untuk presentasi.
## Metode

| Method | Description |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Mendapatkan atau mengatur tipe tayangan slide. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Mendapatkan atau mengatur tipe tayangan slide. |
| [getLoop()](#getLoop--) | Tayangan Slide Berulang |
| [setLoop(boolean value)](#setLoop-boolean-) | Tayangan Slide Berulang |
| [getShowNarration()](#getShowNarration--) | Tampilkan Narasi dalam Tayangan Slide |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Tampilkan Narasi dalam Tayangan Slide |
| [getShowAnimation()](#getShowAnimation--) | Tampilkan Animasi dalam Tayangan Slide |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Tampilkan Animasi dalam Tayangan Slide |
| [getPenColor()](#getPenColor--) | Warna Pena untuk Tayangan Slide |
| [getSlides()](#getSlides--) | Rentang Slide |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Rentang Slide |
| [getUseTimings()](#getUseTimings--) | Gunakan Timing dalam Tayangan Slide |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Gunakan Timing dalam Tayangan Slide |
| [getShowMediaControls()](#getShowMediaControls--) | Tampilkan Kontrol Media |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Tampilkan Kontrol Media |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Mendapatkan atau mengatur tipe tayangan slide. Diwakili oleh SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) induk: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) dan [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // untuk mengatur tipe "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // untuk mengatur tipe "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // untuk mengatur tipe "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Mendapatkan atau mengatur tipe tayangan slide. Diwakili oleh SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) induk: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) dan [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // untuk mengatur tipe "Browsed at a kiosk (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // untuk mengatur tipe "Browsed by individual (window)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // untuk mengatur tipe "Presented by a speaker (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |
### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Tayangan Slide Berulang

**Mengembalikan:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Tayangan Slide Berulang

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Tampilkan Narasi dalam Tayangan Slide

**Mengembalikan:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Tampilkan Narasi dalam Tayangan Slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Tampilkan Animasi dalam Tayangan Slide

**Mengembalikan:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Tampilkan Animasi dalam Tayangan Slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Warna Pena untuk Tayangan Slide

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Rentang Slide

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Rentang Slide

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |
### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Gunakan Timing dalam Tayangan Slide

**Mengembalikan:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Gunakan Timing dalam Tayangan Slide

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Tampilkan Kontrol Media

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Tampilkan Kontrol Media

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |