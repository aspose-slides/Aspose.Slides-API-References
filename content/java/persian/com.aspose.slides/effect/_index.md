---
title: Effect
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر اثر انیمیشن.
type: docs
url: /fa/com.aspose.slides/effect/
---
**به‌ارث‌بردگی:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject  
```
public class Effect implements IEffect, IDOMObject
```

نمایش اثر انیمیشن.

## متدها

| متد | توضیح |
| --- | --- |
| [getSequence()](#getSequence--) | دنباله‌ای برای یک اثر برمی‌گرداند. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation فقط‌خواندنی [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | کلاس اثر را تعریف می‌کند. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | کلاس اثر را تعریف می‌کند. |
| [getType()](#getType--) | نوع اثر را تعریف می‌کند. |
| [setType(int value)](#setType-int-) | نوع اثر را تعریف می‌کند. |
| [getSubtype()](#getSubtype--) | زیرنوع اثر را تعریف می‌کند. |
| [setSubtype(int value)](#setSubtype-int-) | زیرنوع اثر را تعریف می‌کند. |
| [getBehaviors()](#getBehaviors--) | مجموعه‌ای از رفتارهای اثر را برمی‌گرداند. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | مجموعه‌ای از رفتارهای اثر را برمی‌گرداند. |
| [getTiming()](#getTiming--) | مقدار زمان‌بندی اثر را تعریف می‌کند. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | مقدار زمان‌بندی اثر را تعریف می‌کند. |
| [getTargetShape()](#getTargetShape--) | شکل هدف اثر را برمی‌گرداند. |
| [getSound()](#getSound--) | صدای توکار برای اثر تعریف شده است. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | صدای توکار برای اثر تعریف شده است. |
| [getStopPreviousSound()](#getStopPreviousSound--) | این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدا قبلی را متوقف می‌کند یا خیر. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدا قبلی را متوقف می‌کند یا خیر. |
| [getAfterAnimationType()](#getAfterAnimationType--) | نوع پس-انیمیشن برای اثر را تعریف می‌کند. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | نوع پس-انیمیشن برای اثر را تعریف می‌کند. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | رنگ پس-انیمیشن برای اثر را تعریف می‌کند. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | رنگ پس-انیمیشن برای اثر را تعریف می‌کند. |
| [getAnimateTextType()](#getAnimateTextType--) | نوع متنی که انیمیت می‌شود برای اثر را تعریف می‌کند. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | نوع متنی که انیمیت می‌شود برای اثر را تعریف می‌کند. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | تاخیر بین بخش‌های متنی انیمیت‌شده (کلمات یا حروف) را تعریف می‌کند. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | تاخیر بین بخش‌های متنی انیمیت‌شده (کلمات یا حروف) را تعریف می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

دنباله‌ای برای یک اثر برمی‌گرداند. فقط‌خواندنی [ISequence](../../com.aspose.slides/isequence).

**بازگشت:**  
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation فقط‌خواندنی [ITextAnimation](../../com.aspose.slides/itextanimation).

**بازگشت:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

کلاس اثر را تعریف می‌کند. قابل‌نوشتن [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**بازگشت:**  
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

کلاس اثر را تعریف می‌کند. قابل‌نوشتن [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

نوع اثر را تعریف می‌کند. قابل‌نوشتن [EffectType](../../com.aspose.slides/effecttype).

**بازگشت:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

نوع اثر را تعریف می‌کند. قابل‌نوشتن [EffectType](../../com.aspose.slides/effecttype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

زیرنوع اثر را تعریف می‌کند. قابل‌نوشتن [EffectSubtype](../../com.aspose.slides/effectsubtype).

**بازگشت:**  
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

زیرنوع اثر را تعریف می‌کند. قابل‌نوشتن [EffectSubtype](../../com.aspose.slides/effectsubtype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

مجموعه‌ای از رفتارهای اثر را برمی‌گرداند. قابل‌نوشتن [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**بازگشت:**  
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

مجموعه‌ای از رفتارهای اثر را برمی‌گرداند. قابل‌نوشتن [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

مقدار زمان‌بندی اثر را تعریف می‌کند. قابل‌نوشتن [ITiming](../../com.aspose.slides/itiming).

**بازگشت:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

مقدار زمان‌بندی اثر را تعریف می‌کند. قابل‌نوشتن [ITiming](../../com.aspose.slides/itiming).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

شکل هدف اثر را برمی‌گرداند. فقط‌خواندنی [IShape](../../com.aspose.slides/ishape).

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

صدای توکار برای اثر تعریف شده است. قابل‌نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // دنباله اثرها را برای اسلاید دریافت می‌کند
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // صدای اثر را به صورت آرایه بایت استخراج می‌کند
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازگشت:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

صدای توکار برای اثر تعریف شده است. قابل‌نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // دنباله اثرها را برای اسلاید دریافت می‌کند
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // صدای اثر را به صورت آرایه بایت استخراج می‌کند
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدا قبلی را متوقف می‌کند یا خیر. قابل‌نوشتن boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // دریافت اولین اثر اسلاید دوم.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // تغییر بهبود/صدا اثر دوم به "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازگشت:**  
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدا قبلی را متوقف می‌کند یا خیر. قابل‌نوشتن boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // دریافت اولین اثر اسلاید دوم.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // تغییر صدا/بهبودهای اثر دوم به "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

نوع پس-انیمیشن برای اثر را تعریف می‌کند. قابل‌نوشتن [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر پس-انیمیشن اثر به "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازگشت:**  
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

نوع پس-انیمیشن برای اثر را تعریف می‌کند. قابل‌نوشتن [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect After animation to "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

رنگ پس-انیمیشن برای اثر را تعریف می‌کند. قابل‌نوشتن [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع پس-انیمیشن اثر به "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // تنظیم رنگ پس-انیمیشن اثر.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

رنگ پس-انیمیشن برای اثر را تعریف می‌کند. قابل‌نوشتن [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع پس-انیمیشن اثر به "Color"
> 
>      // تنظیم رنگ پس-انیمیشن اثر.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

نوع متنی که انیمیت می‌شود برای اثر را تعریف می‌کند. متن شکل می‌تواند به صورت حرف، کلمه یا به‌صورت کلی انیمیت شود. قابل‌نوشتن AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع متن انیمیشن اثر به "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازگشت:**  
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

نوع متنی که انیمیت می‌شود برای اثر را تعریف می‌کند. متن شکل می‌تواند به صورت حرف، کلمه یا به‌صورت کلی انیمیت شود. قابل‌نوشتن AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect Animate text type to "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

تاخیر بین بخش‌های متنی انیمیت‌شده (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت اثر را مشخص می‌کند. مقدار منفی تاخیر را بر حسب ثانیه تعیین می‌کند. قابل‌نوشتن float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع متن انیمیشن اثر به "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // تنظیم تاخیر بین بخش‌های متنی انیمیت‌شده به 20٪ از مدت اثر.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازگشت:**  
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

تاخیر بین بخش‌های متنی انیمیت‌شده (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت اثر را مشخص می‌کند. مقدار منفی تاخیر را بر حسب ثانیه تعیین می‌کند. قابل‌نوشتن float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع متن انیمیشن اثر به "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // تنظیم تاخیر بین بخش‌های متنی انیمیت‌شده به 20٪ از مدت اثر.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط‌خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject