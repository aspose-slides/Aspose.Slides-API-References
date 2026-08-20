---
title: IEffect
second_title: Aspose.Slides لـ Java دليل API
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
| [getSequence()](#getSequence--) | يعيد تسلسلًا لتأثير. |
| [getTextAnimation()](#getTextAnimation--) | يعيد حركة النص. |
| [getPresetClassType()](#getPresetClassType--) | يعرف فئة التأثير. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | يعرف فئة التأثير. |
| [getType()](#getType--) | يعرف نوع التأثير. |
| [setType(int value)](#setType-int-) | يعرف نوع التأثير. |
| [getSubtype()](#getSubtype--) | يعرف النوع الفرعي للتأثير. |
| [setSubtype(int value)](#setSubtype-int-) | يعرف النوع الفرعي للتأثير. |
| [getBehaviors()](#getBehaviors--) | يعيد مجموعة السلوك للتأثير. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | يعيد مجموعة السلوك للتأثير. |
| [getTiming()](#getTiming--) | يعرف قيمة التوقيت للتأثير. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | يعرف قيمة التوقيت للتأثير. |
| [getTargetShape()](#getTargetShape--) | يعيد الشكل المستهدف للتأثير. |
| [getSound()](#getSound--) | يعرف صوتًا مدمجًا للتأثير. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | يعرف صوتًا مدمجًا للتأثير. |
| [getStopPreviousSound()](#getStopPreviousSound--) | تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. |
| [getAfterAnimationType()](#getAfterAnimationType--) | يعرف نوع الرسوم المتحركة بعدية للتأثير. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | يعرف نوع الرسوم المتحركة بعدية للتأثير. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | يعرف لون الرسوم المتحركة بعدية للتأثير. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | يعرف لون الرسوم المتحركة بعدية للتأثير. |
| [getAnimateTextType()](#getAnimateTextType--) | يعرف نوع نص متحرك للتأثير. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | يعرف نوع نص متحرك للتأثير. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو حروف). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو حروف). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

يعيد تسلسلًا لتأثير. للقراءة فقط [ISequence](../../com.aspose.slides/isequence).

**يُرجع:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

يعيد حركة النص. للقراءة فقط [ITextAnimation](../../com.aspose.slides/itextanimation).

**يُرجع:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

يعرف فئة التأثير. قراءة/كتابة [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**يُرجع:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

يعرف فئة التأثير. قراءة/كتابة [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

يعرف نوع التأثير. قراءة/كتابة [EffectType](../../com.aspose.slides/effecttype).

**يُرجع:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

يعرف نوع التأثير. قراءة/كتابة [EffectType](../../com.aspose.slides/effecttype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

يعرف النوع الفرعي للتأثير. قراءة/كتابة [EffectSubtype](../../com.aspose.slides/effectsubtype).

**يُرجع:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

يعرف النوع الفرعي للتأثير. قراءة/كتابة [EffectSubtype](../../com.aspose.slides/effectsubtype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

يعيد مجموعة السلوك للتأثير. قراءة/كتابة [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**يُرجع:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

يعيد مجموعة السلوك للتأثير. قراءة/كتابة [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

يعرف قيمة التوقيت للتأثير. قراءة/كتابة [ITiming](../../com.aspose.slides/itiming).

**يُرجع:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

يعرف قيمة التوقيت للتأثير. قراءة/كتابة [ITiming](../../com.aspose.slides/itiming).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

يعيد الشكل المستهدف للتأثير. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

**يُرجع:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

يعرف صوتًا مدمجًا للتأثير. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // يحصل على تسلسل التأثيرات للشريحة
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

**يُرجع:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

يعرف صوتًا مدمجًا للتأثير. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // يحصل على تسلسل التأثيرات للشريحة
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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // احصل على أول تأثير في الشريحة الثانية.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // غيّر تحسينات/صوت التأثير الثاني إلى "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**يُرجع:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // احصل على أول تأثير في الشريحة الثانية.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // غيّر تحسينات/صوت التأثير الثاني إلى "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

يعرف نوع الرسوم المتحركة بعدية للتأثير. قراءة/كتابة  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر تأثير الرسوم المتحركة بعد إلى "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**يُرجع:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

يعرف نوع الرسوم المتحركة بعدية للتأثير. قراءة/كتابة  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر تأثير الرسوم المتحركة بعد إلى "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

يعرف لون الرسوم المتحركة بعدية للتأثير. قراءة/كتابة [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع تأثير الرسوم المتحركة بعد إلى "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // عيّن لون تأثير الرسوم المتحركة بعد.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**يُرجع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

يعرف لون الرسوم المتحركة بعدية للتأثير. قراءة/كتابة [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع تأثير الرسوم المتحركة بعد إلى "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // عيّن لون تأثير الرسوم المتحركة بعد.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

يعرف نوع نص متحرك للتأثير. يمكن تحريك نص الشكل بالحرف، أو بالكلمة، أو كلها مرة واحدة. قراءة/كتابة  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع نص الحركة للتأثير إلى "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**يُرجع:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

يعرف نوع نص متحرك للتأثير. يمكن تحريك نص الشكل بالحرف، أو بالكلمة، أو كلها مرة واحدة. قراءة/كتابة  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع نص الحركة للتأثير إلى "بحرف"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو حروف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السالبة تحدد التأخير بالثواني. قراءة/كتابة  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع نص الحركة للتأثير إلى "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // عيّن التأخير بين أجزاء النص المتحركة إلى 20% من مدة التأثير.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**يُرجع:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو حروف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السالبة تحدد التأخير بالثواني. قراءة/كتابة  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // احصل على أول تأثير في الشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع نص الحركة للتأثير إلى "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // عيّن التأخير بين أجزاء النص المتحركة إلى 20% من مدة التأثير.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |