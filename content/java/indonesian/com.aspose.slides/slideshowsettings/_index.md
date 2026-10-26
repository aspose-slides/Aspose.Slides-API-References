---
title: SlideShowSettings
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili pengaturan pertunjukan slide untuk presentasi.
type: docs
url: /id/com.aspose.slides/slideshowsettings/
---
**Warisan:**
java.lang.Object
```
public class SlideShowSettings
```

Mewakili pengaturan pertunjukan slide untuk presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Mendapatkan atau mengatur jenis pertunjukan slide. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Mendapatkan atau mengatur jenis pertunjukan slide. |
| [getLoop()](#getLoop--) | Putar Ulang Slide Show |
| [setLoop(boolean value)](#setLoop-boolean-) | Putar Ulang Slide Show |
| [getShowNarration()](#getShowNarration--) | Tampilkan Narasi dalam Slide Show |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Tampilkan Narasi dalam Slide Show |
| [getShowAnimation()](#getShowAnimation--) | Tampilkan Animasi dalam Slide Show |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Tampilkan Animasi dalam Slide Show |
| [getPenColor()](#getPenColor--) | Warna Pena untuk Slide Show |
| [getSlides()](#getSlides--) | Rentang slide |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Rentang slide |
| [getUseTimings()](#getUseTimings--) | Gunakan Timing dalam Slide Show |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Gunakan Timing dalam Slide Show |
| [getShowMediaControls()](#getShowMediaControls--) | Tampilkan Kontrol Media |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Tampilkan Kontrol Media |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```


Mendapatkan atau mengatur jenis pertunjukan slide. Diwakili oleh SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) dan [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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


Mendapatkan atau mengatur jenis pertunjukan slide. Diwakili oleh SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) dan [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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


Putar Ulang Slide Show

**Mengembalikan:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```


Putar Ulang Slide Show

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```


Tampilkan Narasi dalam Slide Show

**Mengembalikan:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```


Tampilkan Narasi dalam Slide Show

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```


Tampilkan Animasi dalam Slide Show

**Mengembalikan:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```


Tampilkan Animasi dalam Slide Show

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```


Warna Pena untuk Slide Show

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```


Rentang slide

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


Rentang slide

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


Gunakan Timing dalam Slide Show

**Mengembalikan:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```


Gunakan Timing dalam Slide Show

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
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |