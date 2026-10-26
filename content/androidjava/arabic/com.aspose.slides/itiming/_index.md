---
title: ITiming
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل توقيت الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/itiming/
---```
public interface ITiming
```

يمثل توقيت الرسوم المتحركة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | يصف النسبة المئوية لتسارع سلوك المدة. |
| [setAccelerate(float value)](#setAccelerate-float-) | يصف النسبة المئوية لتسارع سلوك المدة. |
| [getDecelerate()](#getDecelerate--) | يصف النسبة المئوية لتباطؤ سلوك المدة. |
| [setDecelerate(float value)](#setDecelerate-float-) | يصف النسبة المئوية لتباطؤ سلوك المدة. |
| [getAutoReverse()](#getAutoReverse--) | يصف ما إذا كان سيتم تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | يصف ما إذا كان سيتم تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. |
| [getDuration()](#getDuration--) | يصف مدة تأثير الرسوم المتحركة. |
| [setDuration(float value)](#setDuration-float-) | يصف مدة تأثير الرسوم المتحركة. |
| [getRepeatCount()](#getRepeatCount--) | يصف عدد المرات التي يجب أن يتكرر فيها التأثير. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | يصف عدد المرات التي يجب أن يتكرر فيها التأثير. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | تحدد هذه السمة ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | تحدد هذه السمة ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | تحدد هذه السمة ما إذا كان التأثير سيتكرر حتى النقر التالي. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | تحدد هذه السمة ما إذا كان التأثير سيتكرر حتى النقر التالي. |
| [getRepeatDuration()](#getRepeatDuration--) | يصف عدد المرات التي يجب أن يتكرر فيها التأثير. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | يصف عدد المرات التي يجب أن يتكرر فيها التأثير. |
| [getRestart()](#getRestart--) | يحدد ما إذا كان التأثير سيُعاد تشغيله بعد الانتهاء. |
| [setRestart(int value)](#setRestart-int-) | يحدد ما إذا كان التأثير سيُعاد تشغيله بعد الانتهاء. |
| [getSpeed()](#getSpeed--) | يحدد النسبة المئوية لتسريع (أو إبطاء) التوقيت. |
| [setSpeed(float value)](#setSpeed-float-) | يحدد النسبة المئوية لتسريع (أو إبطاء) التوقيت. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | يصف زمن التأخير بعد المشغل. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | يصف زمن التأخير بعد المشغل. |
| [getTriggerType()](#getTriggerType--) | يصف نوع المشغل. |
| [setTriggerType(int value)](#setTriggerType-int-) | يصف نوع المشغل. |
| [getRewind()](#getRewind--) | تحدد هذه السمة ما إذا كان التأثير سيعود إلى البداية عند الانتهاء من تشغيله. |
| [setRewind(boolean value)](#setRewind-boolean-) | تحدد هذه السمة ما إذا كان التأثير سيعود إلى البداية عند الانتهاء من تشغيله. |
### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```


يصف النسبة المئوية لتسارع سلوك المدة. قابل للقراءة/الكتابة float.

**الإرجاع:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```


يصف النسبة المئوية لتسارع سلوك المدة. قابل للقراءة/الكتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```


يصف النسبة المئوية لتباطؤ سلوك المدة. قابل للقراءة/الكتابة float.

**الإرجاع:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```


يصف النسبة المئوية لتباطؤ سلوك المدة. قابل للقراءة/الكتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```


يصف ما إذا كان سيتم تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. قابل للقراءة/الكتابة boolean.

**الإرجاع:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```


يصف ما إذا كان سيتم تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```


يصف مدة تأثير الرسوم المتحركة. قابل للقراءة/الكتابة float.

**الإرجاع:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```


يصف مدة تأثير الرسوم المتحركة. قابل للقراءة/الكتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```


يصف عدد المرات التي يجب أن يتكرر فيها التأثير. قابل للقراءة/الكتابة float.

**الإرجاع:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```


يصف عدد المرات التي يجب أن يتكرر فيها التأثير. قابل للقراءة/الكتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```


تحدد هذه السمة ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. قابل للقراءة/الكتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على التأثير الأول من التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "حتى نهاية الشريحة"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
boolean
### setRepeatUntilEndSlide(boolean value) {#setRepeatUntilEndSlide-boolean-}
```
public abstract void setRepeatUntilEndSlide(boolean value)
```


تحدد هذه السمة ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. قابل للقراءة/الكتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the effects sequence for the first slide
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // Get the first effect of main sequence.
>      IEffect effect = effectsSequence.get_Item(0);
>      // Change the effect Timing/Repeat to "Until End of Slide"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public abstract boolean getRepeatUntilNextClick()
```


تحدد هذه السمة ما إذا كان التأثير سيتكرر حتى النقر التالي. قابل للقراءة/الكتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على التأثير الأول من التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "حتى النقر التالي"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**الإرجاع:**
boolean
### setRepeatUntilNextClick(boolean value) {#setRepeatUntilNextClick-boolean-}
```
public abstract void setRepeatUntilNextClick(boolean value)
```


تحدد هذه السمة ما إذا كان التأثير سيتكرر حتى النقر التالي. قابل للقراءة/الكتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على التأثير الأول من التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "حتى النقر التالي"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public abstract float getRepeatDuration()
```


يصف عدد المرات التي يجب أن يتكرر فيها التأثير. قابل للقراءة/الكتابة float.

**الإرجاع:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```


يصف عدد المرات التي يجب أن يتكرر فيها التأثير. قابل للقراءة/الكتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```


يحدد ما إذا كان التأثير سيُعاد تشغيله بعد الانتهاء. قابل للقراءة/الكتابة [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**الإرجاع:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```


يحدد ما إذا كان التأثير سيُعاد تشغيله بعد الانتهاء. قابل للقراءة/الكتابة [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```


يحدد النسبة المئوية لتسريع (أو إبطاء) التوقيت. قابل للقراءة/الكتابة float.

**الإرجاع:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```


يحدد النسبة المئوية لتسريع (أو إبطاء) التوقيت. قابل للقراءة/الكتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```


يصف زمن التأخير بعد المشغل. قابل للقراءة/الكتابة float.

**الإرجاع:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```


يصف زمن التأخير بعد المشغل. قابل للقراءة/الكتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```


يصف نوع المشغل. قابل للقراءة/الكتابة [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**الإرجاع:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```


يصف نوع المشغل. قابل للقراءة/الكتابة [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```


تحدد هذه السمة ما إذا كان التأثير سيعود إلى البداية عند الانتهاء من تشغيله. قابل للقراءة/الكتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على التأثير الأول من التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // فعّل توقيت/إعادة تشغيل التأثير.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public abstract void setRewind(boolean value)
```


تحدد هذه السمة ما إذا كان التأثير سيعود إلى البداية عند الانتهاء من تشغيله. قابل للقراءة/الكتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على التأثير الأول من التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // فعّل توقيت/إعادة تشغيل التأثير.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |