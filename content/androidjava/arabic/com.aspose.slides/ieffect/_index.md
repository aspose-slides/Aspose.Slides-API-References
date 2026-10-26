---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل تأثير الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/ieffect/
---```
public interface IEffect
```

يمثل تأثير الرسوم المتحركة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSequence()](#getSequence--) | يرجع تسلسلاً لتأثير. |
| [getTextAnimation()](#getTextAnimation--) | يرجع الرسوم المتحركة للنص. |
| [getPresetClassType()](#getPresetClassType--) | يحدد فئة التأثير. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | يحدد فئة التأثير. |
| [getType()](#getType--) | يحدد نوع التأثير. |
| [setType(int value)](#setType-int-) | يحدد نوع التأثير. |
| [getSubtype()](#getSubtype--) | يحدد النوع الفرعي للتأثير. |
| [setSubtype(int value)](#setSubtype-int-) | يحدد النوع الفرعي للتأثير. |
| [getBehaviors()](#getBehaviors--) | يرجع مجموعة السلوكيات للتأثير. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | يرجع مجموعة السلوكيات للتأثير. |
| [getTiming()](#getTiming--) | يحدد قيمة التوقيت للتأثير. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | يحدد قيمة التوقيت للتأثير. |
| [getTargetShape()](#getTargetShape--) | يرجع الشكل الهدف للتأثير. |
| [getSound()](#getSound--) | تم تعريف الصوت المدمج للتأثير. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | تم تعريف الصوت المدمج للتأثير. |
| [getStopPreviousSound()](#getStopPreviousSound--) | تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. |
| [getAfterAnimationType()](#getAfterAnimationType--) | تم تعريف نوع الرسوم المتحركة اللاحقة للتأثير. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | تم تعريف نوع الرسوم المتحركة اللاحقة للتأثير. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | تم تعريف لون الرسوم المتحركة اللاحقة للتأثير. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | تم تعريف لون الرسوم المتحركة اللاحقة للتأثير. |
| [getAnimateTextType()](#getAnimateTextType--) | يحدد نوع تحريك النص للتأثير. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | يحدد نوع تحريك النص للتأثير. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

يرجع تسلسلاً لتأثير. للقراءة فقط [ISequence](../../com.aspose.slides/isequence).

**الإرجاع:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

يرجع الرسوم المتحركة للنص. للقراءة فقط [ITextAnimation](../../com.aspose.slides/itextanimation).

**الإرجاع:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

يحدد فئة التأثير. قابل للقراءة والكتابة [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**الإرجاع:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

يحدد فئة التأثير. قابل للقراءة والكتابة [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

يحدد نوع التأثير. قابل للقراءة والكتابة [EffectType](../../com.aspose.slides/effecttype).

**الإرجاع:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

يحدد نوع التأثير. قابل للقراءة والكتابة [EffectType](../../com.aspose.slides/effecttype).

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

يحدد النوع الفرعي للتأثير. قابل للقراءة والكتابة [EffectSubtype](../../com.aspose.slides/effectsubtype).

**الإرجاع:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

يحدد النوع الفرعي للتأثير. قابل للقراءة والكتابة [EffectSubtype](../../com.aspose.slides/effectsubtype).

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

يرجع مجموعة السلوكيات للتأثير. قابل للقراءة والكتابة [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**الإرجاع:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

يرجع مجموعة السلوكيات للتأثير. قابل للقراءة والكتابة [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

يحدد قيمة التوقيت للتأثير. قابل للقراءة والكتابة [ITiming](../../com.aspose.slides/itiming).

**الإرجاع:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

يحدد قيمة التوقيت للتأثير. قابل للقراءة والكتابة [ITiming](../../com.aspose.slides/itiming).

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

يرجع الشكل الهدف للتأثير. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

تم تعريف الصوت المدمج للتأثير. قابل للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // يحصل على تسلسل التأثيرات للشرائح
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // يستخرج صوت التأثير في مصفوفة بايت
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

تم تعريف الصوت المدمج للتأثير. قابل للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // يحصل على تسلسل التأثيرات للشرائح
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // يستخرج صوت التأثير في مصفوفة بايت
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قابل للقراءة والكتابة  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // الحصول على أول تأثير في الشريحة الثانية.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // تغيير تحسينات/صوت التأثير الثاني إلى "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قابل للقراءة والكتابة  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // الحصول على أول تأثير في الشريحة الثانية.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // تغيير التحسينات/الصوت للتأثير الثاني إلى "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

تم تعريف نوع الرسوم المتحركة اللاحقة للتأثير. قابل للقراءة والكتابة  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغيير تأثير بعد الرسوم المتحركة إلى "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

تم تعريف نوع الرسوم المتحركة اللاحقة للتأثير. قابل للقراءة والكتابة  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغيير تأثير بعد الرسوم المتحركة إلى "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

تم تعريف لون الرسوم المتحركة اللاحقة للتأثير. قابل للقراءة والكتابة [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغيير نوع تأثير بعد الرسوم المتحركة إلى "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // ضبط لون تأثير بعد الرسوم المتحركة.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

تم تعريف لون الرسوم المتحركة اللاحقة للتأثير. قابل للقراءة والكتابة [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغيير نوع تأثير بعد الرسوم المتحركة إلى "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // ضبط لون تأثير بعد الرسوم المتحركة.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> 
```

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

يحدد نوع تحريك النص للتأثير. يمكن تحريك نص الشكل بحرف، كلمة أو كلها مرة واحدة. قابل للقراءة والكتابة  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغيير نوع تحريك النص للتأثير إلى "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

يحدد نوع تحريك النص للتأثير. يمكن تحريك نص الشكل بحرف، كلمة أو كلها مرة واحدة. قابل للقراءة والكتابة  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغيير نوع تحريك النص للتأثير إلى "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السلبية تحدد التأخير بالثواني. قابل للقراءة والكتابة  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغيير نوع تحريك النص للتأثير إلى "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // ضبط التأخير بين أجزاء النص المتحركة إلى 20% من مدة التأثير.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السلبية تحدد التأخير بالثواني. قابل للقراءة والكتابة  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // الحصول على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // تغيير نوع تحريك النص للتأثير إلى "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // ضبط التأخير بين أجزاء النص المتحركة إلى 20% من مدة التأثير.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |