---
title: Effect
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل تأثير الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/effect/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المطبقة:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

يمثل تأثيرًا متحركًا.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSequence()](#getSequence--) | يعيد تسلسلًا لتأثير. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation للقراءة فقط [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | يعرف فئة التأثير. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | يعرف فئة التأثير. |
| [getType()](#getType--) | يعرف نوع التأثير. |
| [setType(int value)](#setType-int-) | يعرف نوع التأثير. |
| [getSubtype()](#getSubtype--) | يعرف نوعًا فرعيًا للتأثير. |
| [setSubtype(int value)](#setSubtype-int-) | يعرف نوعًا فرعيًا للتأثير. |
| [getBehaviors()](#getBehaviors--) | يعيد مجموعة من السلوكيات للتأثير. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | يعيد مجموعة من السلوكيات للتأثير. |
| [getTiming()](#getTiming--) | يعرف قيمة التوقيت للتأثير. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | يعرف قيمة التوقيت للتأثير. |
| [getTargetShape()](#getTargetShape--) | يعيد الشكل الهدف للتأثير. |
| [getSound()](#getSound--) | يحدد الصوت المضمن للتأثير. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | يحدد الصوت المضمن للتأثير. |
| [getStopPreviousSound()](#getStopPreviousSound--) | هذه الخاصية تحدد ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | هذه الخاصية تحدد ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. |
| [getAfterAnimationType()](#getAfterAnimationType--) | يعرف نوعًا بعد التحريك للتأثير. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | يعرف نوعًا بعد التحريك للتأثير. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | يعرف لونًا بعد التحريك للتأثير. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | يعرف لونًا بعد التحريك للتأثير. |
| [getAnimateTextType()](#getAnimateTextType--) | يعرف نوع تحريك النص للتأثير. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | يعرف نوع تحريك النص للتأثير. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

يعيد تسلسلًا لتأثير. للقراءة فقط [ISequence](../../com.aspose.slides/isequence).

**الإرجاع:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation للقراءة فقط [ITextAnimation](../../com.aspose.slides/itextanimation).

**الإرجاع:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

يعرف فئة التأثير. قراءة/كتابة [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**الإرجاع:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

يعرف فئة التأثير. قراءة/كتابة [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public final int getType()
```

يعرف نوع التأثير. قراءة/كتابة [EffectType](../../com.aspose.slides/effecttype).

**الإرجاع:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

يعرف نوع التأثير. قراءة/كتابة [EffectType](../../com.aspose.slides/effecttype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

يعرف نوعًا فرعيًا للتأثير. قراءة/كتابة [EffectSubtype](../../com.aspose.slides/effectsubtype).

**الإرجاع:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

يعرف نوعًا فرعيًا للتأثير. قراءة/كتابة [EffectSubtype](../../com.aspose.slides/effectsubtype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

يعيد مجموعة من السلوكيات للتأثير. قراءة/كتابة [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**الإرجاع:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

يعيد مجموعة من السلوكيات للتأثير. قراءة/كتابة [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

يعرف قيمة التوقيت للتأثير. قراءة/كتابة [ITiming](../../com.aspose.slides/itiming).

**الإرجاع:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

يعرف قيمة التوقيت للتأثير. قراءة/كتابة [ITiming](../../com.aspose.slides/itiming).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

يعيد الشكل الهدف للتأثير. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```

يحدد الصوت المضمن للتأثير. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

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

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

يحدد الصوت المضمن للتأثير. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

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
public final boolean getStopPreviousSound()
```

هذه الخاصية تحدد ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // احصل على التأثير الأول للشريحة الثانية.
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

**الإرجاع:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public final void setStopPreviousSound(boolean value)
```

هذه الخاصية تحدد ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. قراءة/كتابة  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // احصل على التأثير الأول للشريحة الثانية.
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
public final int getAfterAnimationType()
```

يعرف نوعًا بعد التحريك للتأثير. قراءة/كتابة [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر تأثير After animation إلى "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**الإرجاع:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

يعرف نوعًا بعد التحريك للتأثير. قراءة/كتابة [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر تأثير After animation إلى "Hide on Next Mouse Click"
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
public final IColorFormat getAfterAnimationColor()
```

يعرف لونًا بعد التحريك للتأثير. قراءة/كتابة [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع After animation للتأثير إلى "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // عيّن لون after animation.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

يعرف لونًا بعد التحريك للتأثير. قراءة/كتابة [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع After animation للتأثير إلى "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // عيّن لون after animation.
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
public final int getAnimateTextType()
```

يعرف نوع تحريك النص للتأثير. يمكن تحريك نص الشكل حرفًا، أو كلمة، أو كله مرة واحدة. قراءة/كتابة  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع Animate text للتأثير إلى "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**الإرجاع:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public final void setAnimateTextType(int value)
```

يعرف نوع تحريك النص للتأثير. يمكن تحريك نص الشكل حرفًا، أو كلمة، أو كله مرة واحدة. قراءة/كتابة  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع Animate text للتأثير إلى "By letter"
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
public final float getDelayBetweenTextParts()
```

يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السالبة تحدد التأخير بالثواني. قراءة/كتابة  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع Animate text للتأثير إلى "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // عيّن التأخير بين أجزاء النص المتحركة إلى 20% من مدة التأثير.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السالبة تحدد التأخير بالثواني. قراءة/كتابة  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع Animate text للتأثير إلى "By word"
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
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject