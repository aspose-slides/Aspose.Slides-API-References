---
title: Effect
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل تأثير الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/effect/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

يمثل تأثير الرسوم المتحركة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSequence()](#getSequence--) | يرجع تسلسلاً لتأثير. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation للقراءة فقط [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | يحدد فئة التأثير. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | يحدد فئة التأثير. |
| [getType()](#getType--) | يحدد نوع التأثير. |
| [setType(int value)](#setType-int-) | يحدد نوع التأثير. |
| [getSubtype()](#getSubtype--) | يحدد نوعًا فرعيًا للتأثير. |
| [setSubtype(int value)](#setSubtype-int-) | يحدد نوعًا فرعيًا للتأثير. |
| [getBehaviors()](#getBehaviors--) | يرجع مجموعة من السلوكيات للتأثير. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | يرجع مجموعة من السلوكيات للتأثير. |
| [getTiming()](#getTiming--) | يحدد قيمة التوقيت للتأثير. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | يحدد قيمة التوقيت للتأثير. |
| [getTargetShape()](#getTargetShape--) | يرجع الشكل الهدف للتأثير. |
| [getSound()](#getSound--) | تم تعريف الصوت المدمج للتأثير. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | تم تعريف الصوت المدمج للتأثير. |
| [getStopPreviousSound()](#getStopPreviousSound--) | تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. |
| [getAfterAnimationType()](#getAfterAnimationType--) | يحدد نوع ما بعد الرسوم المتحركة للتأثير. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | يحدد نوع ما بعد الرسوم المتحركة للتأثير. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | يحدد لون ما بعد الرسوم المتحركة للتأثير. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | يحدد لون ما بعد الرسوم المتحركة للتأثير. |
| [getAnimateTextType()](#getAnimateTextType--) | يحدد نوع تحريك النص للتأثير. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | يحدد نوع تحريك النص للتأثير. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

يرجع تسلسلاً لتأثير. للقراءة فقط [ISequence](../../com.aspose.slides/isequence).

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

يحدد فئة التأثير. للقراءة والكتابة [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**الإرجاع:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

يحدد فئة التأثير. للقراءة والكتابة [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

يحدد نوع التأثير. للقراءة والكتابة [EffectType](../../com.aspose.slides/effecttype).

**الإرجاع:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

يحدد نوع التأثير. للقراءة والكتابة [EffectType](../../com.aspose.slides/effecttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

يحدد نوعًا فرعيًا للتأثير. للقراءة والكتابة [EffectSubtype](../../com.aspose.slides/effectsubtype).

**الإرجاع:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

يحدد نوعًا فرعيًا للتأثير. للقراءة والكتابة [EffectSubtype](../../com.aspose.slides/effectsubtype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

يرجع مجموعة من السلوكيات للتأثير. للقراءة والكتابة [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**الإرجاع:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

يرجع مجموعة من السلوكيات للتأثير. للقراءة والكتابة [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

يحدد قيمة التوقيت للتأثير. للقراءة والكتابة [ITiming](../../com.aspose.slides/itiming).

**الإرجاع:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

يحدد قيمة التوقيت للتأثير. للقراءة والكتابة [ITiming](../../com.aspose.slides/itiming).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

يرجع الشكل الهدف للتأثير. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public final IAudio getSound()
```

تم تعريف الصوت المدمج للتأثير. للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

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

تم تعريف الصوت المدمج للتأثير. للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getStopPreviousSound() {#getStopPreviousSound--}
```
public final boolean getStopPreviousSound()
```

هذه الخاصية تحدد ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. للقراءة والكتابة boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشرائح الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // احصل على التأثير الأول للشرائح الثانية.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // غير تحسينات/صوت التأثير الثاني إلى "Stop Previous Sound"
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

هذه الخاصية تحدد ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. للقراءة والكتابة boolean .

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAfterAnimationType() {#getAfterAnimationType--}
```
public final int getAfterAnimationType()
```

يحدد نوع ما بعد الرسوم المتحركة للتأثير. للقراءة والكتابة [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر After animation للتأثير إلى "Hide on Next Mouse Click"
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

يحدد نوع ما بعد الرسوم المتحركة للتأثير. للقراءة والكتابة [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر After animation للتأثير إلى "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public final IColorFormat getAfterAnimationColor()
```

يحدد لون ما بعد الرسوم المتحركة للتأثير. للقراءة والكتابة [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      // عيّن لون After animation للتأثير.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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

يحدد لون ما بعد الرسوم المتحركة للتأثير. للقراءة والكتابة [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر After animation للتأثير إلى "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // عيّن لون After animation للتأثير.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getAnimateTextType() {#getAnimateTextType--}
```
public final int getAnimateTextType()
```

يحدد نوع تحريك النص للتأثير. يمكن تحريك نص الشكل بالحرف أو بالكلمة أو مرة واحدة. للقراءة والكتابة AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع تحريك النص للتأثير إلى "By letter"
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

يحدد نوع تحريك النص للتأثير. يمكن تحريك نص الشكل بالحرف أو بالكلمة أو مرة واحدة. للقراءة والكتابة AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع تحريك النص للتأثير إلى "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public final float getDelayBetweenTextParts()
```

يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). قيمة موجبة تحدد نسبة مدة التأثير. قيمة سالبة تحدد التأخير بالثواني. للقراءة والكتابة float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع تحريك النص للتأثير إلى "By word"
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

يحدد تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). قيمة موجبة تحدد نسبة مدة التأثير. قيمة سالبة تحدد التأخير بالثواني. للقراءة والكتابة float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // احصل على التأثير الأول للشريحة الأولى.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // غيّر نوع تحريك النص للتأثير إلى "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // عيّن التأخير بين أجزاء النص المتحركة إلى 20% من مدة التأثير.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. للقراءة فقط IDDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject