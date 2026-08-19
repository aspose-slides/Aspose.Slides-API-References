---
title: IEffect
second_title: Aspose.Slides for Java API Reference
description: نمایانگر اثر انیمیشن
type: docs
url: /fa/com.aspose.slides/ieffect/
---```
public interface IEffect
```

نمایانگر اثر انیمیشن.
## متدها

| متد | توضیح |
| --- | --- |
| [getSequence()](#getSequence--) | یک توالی برای یک اثر برمی‌گرداند. |
| [getTextAnimation()](#getTextAnimation--) | انیمیشن متن را برمی‌گرداند. |
| [getPresetClassType()](#getPresetClassType--) | کلاس اثر را تعریف می‌کند. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | کلاس اثر را تعریف می‌کند. |
| [getType()](#getType--) | نوع اثر را تعریف می‌کند. |
| [setType(int value)](#setType-int-) | نوع اثر را تعریف می‌کند. |
| [getSubtype()](#getSubtype--) | زیرنوع اثر را تعریف می‌کند. |
| [setSubtype(int value)](#setSubtype-int-) | زیرنوع اثر را تعریف می‌کند. |
| [getBehaviors()](#getBehaviors--) | مجموعه‌ای از رفتارهای اثر را برمی‌گرداند. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | مجموعه‌ای از رفتارهای اثر را برمی‌گرداند. |
| [getTiming()](#getTiming--) | مقدار زمان‌بندی برای اثر را تعریف می‌کند. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | مقدار زمان‌بندی برای اثر را تعریف می‌کند. |
| [getTargetShape()](#getTargetShape--) | شکل هدف برای اثر را برمی‌گرداند. |
| [getSound()](#getSound--) | صداهای جاسازی‌شده برای اثر تعریف شده‌اند. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | صداهای جاسازی‌شده برای اثر تعریف شده‌اند. |
| [getStopPreviousSound()](#getStopPreviousSound--) | این ویژگی مشخص می‌کند آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا خیر. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | این ویژگی مشخص می‌کند آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا خیر. |
| [getAfterAnimationType()](#getAfterAnimationType--) | نوع پس از انیمیشن برای اثر تعریف شده است. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | نوع پس از انیمیشن برای اثر تعریف شده است. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | رنگ پس از انیمیشن برای اثر تعریف شده است. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | رنگ پس از انیمیشن برای اثر تعریف شده است. |
| [getAnimateTextType()](#getAnimateTextType--) | یک نوع انیمیشن متن برای اثر را تعریف می‌کند. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | یک نوع انیمیشن متن برای اثر را تعریف می‌کند. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | تاخیر بین بخش‌های متنی انیمیشنی (کلمات یا حروف) را تعریف می‌کند. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | تاخیر بین بخش‌های متنی انیمیشنی (کلمات یا حروف) را تعریف می‌کند. |

### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

یک توالی برای یک اثر برمی‌گرداند. فقط‌خواندنی [ISequence](../../com.aspose.slides/isequence).

**باز می‌گردد:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

انیمیشن متن را برمی‌گرداند. فقط‌خواندنی [ITextAnimation](../../com.aspose.slides/itextanimation).

**باز می‌گردد:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

کلاس اثر را تعریف می‌کند. قابل‌خواندن‌و‌نوشتن [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**باز می‌گردد:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

کلاس اثر را تعریف می‌کند. قابل‌خواندن‌و‌نوشتن [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

نوع اثر را تعریف می‌کند. قابل‌خواندن‌و‌نوشتن [EffectType](../../com.aspose.slides/effecttype).

**باز می‌گردد:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

نوع اثر را تعریف می‌کند. قابل‌خواندن‌و‌نوشتن [EffectType](../../com.aspose.slides/effecttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

زیرنوع اثر را تعریف می‌کند. قابل‌خواندن‌و‌نوشتن [EffectSubtype](../../com.aspose.slides/effectsubtype).

**باز می‌گردد:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

زیرنوع اثر را تعریف می‌کند. قابل‌خواندن‌و‌نوشتن [EffectSubtype](../../com.aspose.slides/effectsubtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

مجموعه‌ای از رفتارهای اثر را برمی‌گرداند. قابل‌خواندن‌و‌نوشتن [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**باز می‌گردد:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

مجموعه‌ای از رفتارهای اثر را برمی‌گرداند. قابل‌خواندن‌و‌نوشتن [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

مقدار زمان‌بندی برای اثر را تعریف می‌کند. قابل‌خواندن‌و‌نوشتن [ITiming](../../com.aspose.slides/itiming).

**باز می‌گردد:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

مقدار زمان‌بندی برای اثر را تعریف می‌کند. قابل‌خواندن‌و‌نوشتن [ITiming](../../com.aspose.slides/itiming).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

شکل هدف برای اثر را برمی‌گرداند. فقط‌خواندنی [IShape](../../com.aspose.slides/ishape).

**باز می‌گردد:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

صداهای جاسازی‌شده برای اثر تعریف شده‌اند. قابل‌خواندن‌و‌نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // دریافت توالی اثرها برای اسلاید
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // استخراج صدای اثر در آرایه بایت
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**باز می‌گردد:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

صداهای جاسازی‌شده برای اثر تعریف شده‌اند. قابل‌خواندن‌و‌نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // دریافت توالی اثرها برای اسلاید
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // استخراج صدای اثر در آرایه بایت
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
public abstract boolean getStopPreviousSound()
```

این ویژگی مشخص می‌کند آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا خیر. قابل‌خواندن‌و‌نوشتن  boolean .

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
>          // تغییر بهبودهای/صدای اثر دوم به "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**باز می‌گردد:**
boolean

### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

این ویژگی مشخص می‌کند آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا خیر. قابل‌خواندن‌و‌نوشتن  boolean .

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
>          // تغییر بهبودهای/صدای اثر دوم به "Stop Previous Sound"
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
public abstract int getAfterAnimationType()
```

نوع پس از انیمیشن برای اثر تعریف شده است. قابل‌خواندن‌و‌نوشتن  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر اثر After animation به "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**باز می‌گردد:**
int

### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

نوع پس از انیمیشن برای اثر تعریف شده است. قابل‌خواندن‌و‌نوشتن  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر After animation اثر به "Hide on Next Mouse Click"
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
public abstract IColorFormat getAfterAnimationColor()
```

رنگ پس از انیمیشن برای اثر تعریف شده است. قابل‌خواندن‌و‌نوشتن [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع After animation اثر به "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // تنظیم رنگ After animation اثر.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**باز می‌گردد:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

رنگ پس از انیمیشن برای اثر تعریف شده است. قابل‌خواندن‌و‌نوشتن [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر After animation اثر به "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // تنظیم رنگ After animation اثر.
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
public abstract int getAnimateTextType()
```

یک نوع انیمیشن متن برای اثر را تعریف می‌کند. متن شکل می‌تواند به‌صورت حرف، کلمه یا به‌صورت کلی انیمیت شود. قابل‌خواندن‌و‌نوشتن  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع Animate text اثر به "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**باز می‌گردد:**
int

### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

یک نوع انیمیشن متن برای اثر را تعریف می‌کند. متن شکل می‌تواند به‌صورت حرف، کلمه یا به‌صورت کلی انیمیت شود. قابل‌خواندن‌و‌نوشتن  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع Animate text اثر به "By letter"
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
public abstract float getDelayBetweenTextParts()
```

تاخیر بین بخش‌های متنی انیمیشنی (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت اثر را مشخص می‌کند. مقدار منفی تاخیر را بر حسب ثانیه تعیین می‌کند. قابل‌خواندن‌و‌نوشتن  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع Animate text اثر به "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // تنظیم تاخیر بین بخش‌های متنی انیمیشنی به 20% از مدت اثر.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**باز می‌گردد:**
float

### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

تاخیر بین بخش‌های متنی انیمیشنی (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت اثر را مشخص می‌کند. مقدار منفی تاخیر را بر حسب ثانیه تعیین می‌کند. قابل‌خواندن‌و‌نوشتن  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع Animate text اثر به "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // تنظیم تاخیر بین بخش‌های متنی انیمیشنی به 20% از مدت اثر.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |