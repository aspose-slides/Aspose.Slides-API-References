---
title: SlideShowSettings
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر تنظیمات نمایش اسلاید برای ارائه.
type: docs
url: /fa/com.aspose.slides/slideshowsettings/
---
**ارث‌بری:**  
java.lang.Object  
```
public class SlideShowSettings
```

نمایانگر تنظیمات نمایش اسلاید برای ارائه است.
## متدها

| متد | توضیح |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | دریافت یا تنظیم نوع نمایش اسلاید. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | دریافت یا تنظیم نوع نمایش اسلاید. |
| [getLoop()](#getLoop--) | پخش اسلاید به صورت حلقه‌ای |
| [setLoop(boolean value)](#setLoop-boolean-) | پخش اسلاید به صورت حلقه‌ای |
| [getShowNarration()](#getShowNarration--) | نمایش گفتار در نمایش اسلاید |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | نمایش گفتار در نمایش اسلاید |
| [getShowAnimation()](#getShowAnimation--) | نمایش انیمیشن در نمایش اسلاید |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | نمایش انیمیشن در نمایش اسلاید |
| [getPenColor()](#getPenColor--) | رنگ قلم برای نمایش اسلاید |
| [getSlides()](#getSlides--) | محدوده اسلایدها |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | محدوده اسلایدها |
| [getUseTimings()](#getUseTimings--) | استفاده از زمان‌بندی‌ها در اسلایدشو |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | استفاده از زمان‌بندی‌ها در اسلایدشو |
| [getShowMediaControls()](#getShowMediaControls--) | نمایش کنترل‌های مدیا |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | نمایش کنترل‌های مدیا |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```


دریافت یا تنظیم نوع نمایش اسلاید. نمایش داده شده توسط SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) پدران: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // برای تنظیم نوع "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // برای تنظیم نوع "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // برای تنظیم نوع "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```


دریافت یا تنظیم نوع نمایش اسلاید. نمایش داده شده توسط SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) پدران: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // برای تنظیم نوع "Browsed at a kiosk (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // برای تنظیم نوع "Browsed by individual (window)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // برای تنظیم نوع "Presented by a speaker (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```


پخش اسلاید به صورت حلقه‌ای

**بازگشت:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```


پخش اسلاید به صورت حلقه‌ای

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```


نمایش گفتار در نمایش اسلاید

**بازگشت:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```


نمایش گفتار در نمایش اسلاید

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```


نمایش انیمیشن در نمایش اسلاید

**بازگشت:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```


نمایش انیمیشن در نمایش اسلاید

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```


رنگ قلم برای نمایش اسلاید

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```


محدوده اسلایدها

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

**بازگشت:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```


محدوده اسلایدها

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

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```


استفاده از زمان‌بندی‌ها در اسلایدشو

**بازگشت:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```


استفاده از زمان‌بندی‌ها در اسلایدشو

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```


نمایش کنترل‌های مدیا

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```


نمایش کنترل‌های مدیا

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |