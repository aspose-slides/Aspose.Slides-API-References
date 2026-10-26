---
title: SlideShowSettings
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر تنظیمات اسلاید شو برای ارائه.
type: docs
url: /fa/com.aspose.slides/slideshowsettings/
---
**ارث‌بری:**
java.lang.Object
```
public class SlideShowSettings
```

نمایش تنظیمات اسلاید شو برای ارائه.

## متدها

| Method | Description |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | دریافت یا تنظیم نوع اسلاید شو. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | دریافت یا تنظیم نوع اسلاید شو. |
| [getLoop()](#getLoop--) | حلقه اسلاید شو |
| [setLoop(boolean value)](#setLoop-boolean-) | حلقه اسلاید شو |
| [getShowNarration()](#getShowNarration--) | نمایش گفتار در اسلاید شو |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | نمایش گفتار در اسلاید شو |
| [getShowAnimation()](#getShowAnimation--) | نمایش انیمیشن در اسلاید شو |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | نمایش انیمیشن در اسلاید شو |
| [getPenColor()](#getPenColor--) | رنگ قلم برای اسلاید شو |
| [getSlides()](#getSlides--) | محدوده اسلایدها |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | محدوده اسلایدها |
| [getUseTimings()](#getUseTimings--) | استفاده از زمان‌بندی در اسلاید شو |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | استفاده از زمان‌بندی در اسلاید شو |
| [getShowMediaControls()](#getShowMediaControls--) | نمایش کنترل‌های رسانه‌ای |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | نمایش کنترل‌های رسانه‌ای |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

دریافت یا تنظیم نوع اسلاید شو. نمایش داده شده توسط SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) اجداد: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) و [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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

**بازگشت:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

دریافت یا تنظیم نوع اسلاید شو. نمایش داده شده توسط SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) اجداد: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) و [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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


**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

حلقه اسلاید شو

**بازگشت:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

حلقه اسلاید شو

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

نمایش گفتار در اسلاید شو

**بازگشت:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

نمایش گفتار در اسلاید شو

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

نمایش انیمیشن در اسلاید شو

**بازگشت:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

نمایش انیمیشن در اسلاید شو

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

رنگ قلم برای اسلاید شو

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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

استفاده از زمان‌بندی در اسلاید شو

**بازگشت:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

استفاده از زمان‌بندی در اسلاید شو

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

نمایش کنترل‌های رسانه‌ای

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

نمایش کنترل‌های رسانه‌ای

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |