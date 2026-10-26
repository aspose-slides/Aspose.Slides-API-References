---
title: SlideShowSettings
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل إعدادات عرض الشرائح للعرض التقديمي.
type: docs
url: /ar/com.aspose.slides/slideshowsettings/
---
**الوراثة:**
java.lang.Object
```
public class SlideShowSettings
```

يمثل إعدادات عرض الشرائح للعرض التقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | يحصل أو يعيّن نوع عرض الشرائح. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | يحصل أو يعيّن نوع عرض الشرائح. |
| [getLoop()](#getLoop--) | تشغيل عرض الشرائح بشكل دوري |
| [setLoop(boolean value)](#setLoop-boolean-) | تشغيل عرض الشرائح بشكل دوري |
| [getShowNarration()](#getShowNarration--) | عرض الشرح الصوتي في عرض الشرائح |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | عرض الشرح الصوتي في عرض الشرائح |
| [getShowAnimation()](#getShowAnimation--) | عرض الرسوم المتحركة في عرض الشرائح |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | عرض الرسوم المتحركة في عرض الشرائح |
| [getPenColor()](#getPenColor--) | لون القلم لعرض الشرائح |
| [getSlides()](#getSlides--) | نطاق الشرائح |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | نطاق الشرائح |
| [getUseTimings()](#getUseTimings--) | استخدام التوقيتات في عرض الشرائح |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | استخدام التوقيتات في عرض الشرائح |
| [getShowMediaControls()](#getShowMediaControls--) | عرض عناصر التحكم في الوسائط |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | عرض عناصر التحكم في الوسائط |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

يحصل أو يعيّن نوع عرض الشرائح. مُمَثَّل بـ SlideShowType التالي (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) السلف: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) و [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // لتعيين النوع "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // لتعيين النوع "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // لتعيين النوع "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

يحصل أو يعيّن نوع عرض الشرائح. مُمَثَّل بـ SlideShowType التالي (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) السلف: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) و [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // لتعيين النوع "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // لتعيين النوع "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // لتعيين النوع "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

تشغيل عرض الشرائح بشكل دوري

**القيمة المرجعة:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

تشغيل عرض الشرائح بشكل دوري

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

عرض الشرح الصوتي في عرض الشرائح

**القيمة المرجعة:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

عرض الشرح الصوتي في عرض الشرائح

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

عرض الرسوم المتحركة في عرض الشرائح

**القيمة المرجعة:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

عرض الرسوم المتحركة في عرض الشرائح

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

لون القلم لعرض الشرائح

**القيمة المرجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

نطاق الشرائح

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

**القيمة المرجعة:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

نطاق الشرائح

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

استخدام التوقيتات في عرض الشرائح

**القيمة المرجعة:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

استخدام التوقيتات في عرض الشرائح

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

عرض عناصر التحكم في الوسائط

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

عرض عناصر التحكم في الوسائط

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |