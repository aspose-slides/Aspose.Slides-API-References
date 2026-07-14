---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: نمایانگر اثر انیمیشن.
type: docs
url: /fa/com.aspose.slides/ieffect/
---```
public interface IEffect
```

نمایانگر اثر انیمیشن.
## متدها

| متد | توضیح |
| --- | --- |
| [getSequence()](#getSequence--) | یک توالی برای اثر بازمی‌گرداند. |
| [getTextAnimation()](#getTextAnimation--) | انیمیشن متن را بازمی‌گرداند. |
| [getPresetClassType()](#getPresetClassType--) | کلاس اثر را تعریف می‌کند. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | کلاس اثر را تعریف می‌کند. |
| [getType()](#getType--) | نوع اثر را تعریف می‌کند. |
| [setType(int value)](#setType-int-) | نوع اثر را تعریف می‌کند. |
| [getSubtype()](#getSubtype--) | زیرنوع اثر را تعریف می‌کند. |
| [setSubtype(int value)](#setSubtype-int-) | زیرنوع اثر را تعریف می‌کند. |
| [getBehaviors()](#getBehaviors--) | مجموعهٔ رفتارها برای اثر را بازمی‌گرداند. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | مجموعهٔ رفتارها برای اثر را بازمی‌گرداند. |
| [getTiming()](#getTiming--) | مقدار زمان‌بندی برای اثر را تعریف می‌کند. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | مقدار زمان‌بندی برای اثر را تعریف می‌کند. |
| [getTargetShape()](#getTargetShape--) | شکل هدف برای اثر را بازمی‌گرداند. |
| [getSound()](#getSound--) | صدای جاسازی‌شده برای اثر را تعریف می‌کند. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | صدای جاسازی‌شده برای اثر را تعریف می‌کند. |
| [getStopPreviousSound()](#getStopPreviousSound--) | این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا نه. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا نه. |
| [getAfterAnimationType()](#getAfterAnimationType--) | نوع انیمیشن پس‌از اثر را تعریف می‌کند. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | نوع انیمیشن پس‌از اثر را تعریف می‌کند. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | رنگ پس‌از انیمیشن را برای اثر تعریف می‌کند. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | رنگ پس‌از انیمیشن را برای اثر تعریف می‌کند. |
| [getAnimateTextType()](#getAnimateTextType--) | نوع متن متحرک برای اثر را تعریف می‌کند. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | نوع متن متحرک برای اثر را تعریف می‌کند. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | تاخیر بین بخش‌های متنی متحرک (کلمات یا حروف) را تعریف می‌کند. |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | تاخیر بین بخش‌های متنی متحرک (کلمات یا حروف) را تعریف می‌کند. |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

یک توالی برای اثر بازمی‌گرداند. فقط خواندنی [ISequence](../../com.aspose.slides/isequence).

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

متن انیمیشن را بازمی‌گرداند. فقط خواندنی [ITextAnimation](../../com.aspose.slides/itextanimation).

**بازگشت:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

کلاس اثر را تعریف می‌کند. خواندن/نوشتن [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**بازگشت:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

کلاس اثر را تعریف می‌کند. خواندن/نوشتن [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

نوع اثر را تعریف می‌کند. خواندن/نوشتن [EffectType](../../com.aspose.slides/effecttype).

**بازگشت:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

نوع اثر را تعریف می‌کند. خواندن/نوشتن [EffectType](../../com.aspose.slides/effecttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

زیرنوع اثر را تعریف می‌کند. خواندن/نوشتن [EffectSubtype](../../com.aspose.slides/effectsubtype).

**بازگشت:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

زیرنوع اثر را تعریف می‌کند. خواندن/نوشتن [EffectSubtype](../../com.aspose.slides/effectsubtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

مجموعهٔ رفتارها برای اثر را بازمی‌گرداند. خواندن/نوشتن [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**بازگشت:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

مجموعهٔ رفتارها برای اثر را بازمی‌گرداند. خواندن/نوشتن [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

مقدار زمان‌بندی برای اثر را تعریف می‌کند. خواندن/نوشتن [ITiming](../../com.aspose.slides/itiming).

**بازگشت:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

مقدار زمان‌بندی برای اثر را تعریف می‌کند. خواندن/نوشتن [ITiming](../../com.aspose.slides/itiming).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

شکل هدف برای اثر را بازمی‌گرداند. فقط خواندنی [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

صدای جاسازی‌شده برای اثر را تعریف می‌کند. خواندن/نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // توالی اثرها را برای اسلاید دریافت می‌کند
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
public abstract void setSound(IAudio value)
```

صدای جاسازی‌شده برای اثر را تعریف می‌کند. خواندن/نوشتن [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // توالی اثرها را برای اسلاید دریافت می‌کند
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
public abstract boolean getStopPreviousSound()
```

این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا نه. خواندن/نوشتن boolean .

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
>          // صدای بهبودهای اثر دوم را به "توقف صدای قبلی" تغییر می‌دهد
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
public abstract void setStopPreviousSound(boolean value)
```

این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا نه. خواندن/نوشتن boolean .

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
>          // صدای بهبودهای اثر دوم را به "Stop Previous Sound" تغییر می‌دهد
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

نوع انیمیشن پس‌از اثر را تعریف می‌کند. خواندن/نوشتن AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر انیمیشن پس‌از اثر به "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازگشت:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

نوع انیمیشن پس‌از اثر را تعریف می‌کند. خواندن/نوشتن AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر انیمیشن پس‌از اثر به "Hide on Next Mouse Click"
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

رنگ انیمیشن پس‌از برای اثر را تعریف می‌کند. خواندن/نوشتن [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع انیمیشن پس‌از اثر به "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // تنظیم رنگ انیمیشن پس‌از اثر.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

رنگ انیمیشن پس‌از برای اثر را تعریف می‌کند. خواندن/نوشتن [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع انیمیشن پس‌از اثر به "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // تنظیم رنگ انیمیشن پس‌از اثر.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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

نوع متن متحرک برای اثر را تعریف می‌کند. متن شکل می‌تواند به صورت حرف، کلمه یا به‌صورت کلی متحرک شود. خواندن/نوشتن AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع متن متحرک اثر به "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازگشت:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

نوع متن متحرک برای اثر را تعریف می‌کند. متن شکل می‌تواند به صورت حرف، کلمه یا به‌صورت کلی متحرک شود. خواندن/نوشتن AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع متن متحرک اثر به "By letter"
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

تاخیر بین بخش‌های متنی متحرک (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد طول اثر را تعیین می‌کند، مقدار منفی تاخیر را بر حسب ثانیه مشخص می‌سازد. خواندن/نوشتن float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع متن متحرک اثر به "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // تنظیم تاخیر بین بخش‌های متنی متحرک به 20% از مدت اثر.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازگشت:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

تاخیر بین بخش‌های متنی متحرک (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد طول اثر را تعیین می‌کند، مقدار منفی تاخیر را بر حسب ثانیه مشخص می‌سازد. خواندن/نوشتن float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // دریافت اولین اثر اسلاید اول.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغییر نوع متن متحرک اثر به "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // تنظیم تاخیر بین بخش‌های متنی متحرک به 20% از مدت اثر.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |