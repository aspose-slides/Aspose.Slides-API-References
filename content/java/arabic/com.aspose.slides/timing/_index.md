---
title: Timing
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة Java
description: يمثل توقيت الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/timing/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ITiming](../../com.aspose.slides/itiming), com.aspose.slides.IDOMObject
```
public class Timing implements ITiming, IDOMObject
```

يمثل توقيت الرسوم المتحركة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAccelerate()](#getAccelerate--) | يصف النسبة المئوية لتأثير سلوك التسريع للمدة. |
| [setAccelerate(float value)](#setAccelerate-float-) | يصف النسبة المئوية لتأثير سلوك التسريع للمدة. |
| [getDecelerate()](#getDecelerate--) | يصف النسبة المئوية لتأثير سلوك التباطؤ للمدة. |
| [setDecelerate(float value)](#setDecelerate-float-) | يصف النسبة المئوية لتأثير سلوك التباطؤ للمدة. |
| [getAutoReverse()](#getAutoReverse--) | يصف ما إذا كان يجب تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. |
| [setAutoReverse(boolean value)](#setAutoReverse-boolean-) | يصف ما إذا كان يجب تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. |
| [getDuration()](#getDuration--) | يصف مدة تأثير الرسوم المتحركة. |
| [setDuration(float value)](#setDuration-float-) | يصف مدة تأثير الرسوم المتحركة. |
| [getRepeatCount()](#getRepeatCount--) | يصف عدد مرات تكرار التأثير. |
| [setRepeatCount(float value)](#setRepeatCount-float-) | يصف عدد مرات تكرار التأثير. |
| [getRepeatUntilEndSlide()](#getRepeatUntilEndSlide--) | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. |
| [setRepeatUntilEndSlide(boolean value)](#setRepeatUntilEndSlide-boolean-) | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. |
| [getRepeatUntilNextClick()](#getRepeatUntilNextClick--) | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. |
| [setRepeatUntilNextClick(boolean value)](#setRepeatUntilNextClick-boolean-) | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. |
| [getRepeatDuration()](#getRepeatDuration--) | يصف عدد مرات تكرار التأثير. |
| [setRepeatDuration(float value)](#setRepeatDuration-float-) | يصف عدد مرات تكرار التأثير. |
| [getRestart()](#getRestart--) | يحدد ما إذا كان يجب إعادة تشغيل التأثير بعد الانتهاء. |
| [setRestart(int value)](#setRestart-int-) | يحدد ما إذا كان يجب إعادة تشغيل التأثير بعد الانتهاء. |
| [getRewind()](#getRewind--) | هذه الخاصية تحدد ما إذا كان سيتم إرجاع التأثير عند الانتهاء من تشغيله. |
| [setRewind(boolean value)](#setRewind-boolean-) | هذه الخاصية تحدد ما إذا كان سيتم إرجاع التأثير عند الانتهاء من تشغيله. |
| [getSpeed()](#getSpeed--) | يحدد النسبة المئوية التي يتم تسريع (أو إبطاء) التوقيت بها. |
| [setSpeed(float value)](#setSpeed-float-) | يحدد النسبة المئوية التي يتم تسريع (أو إبطاء) التوقيت بها. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | يصف زمن التأخير بعد المشغل. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | يصف زمن التأخير بعد المشغل. |
| [getTriggerType()](#getTriggerType--) | يصف نوع المشغل. |
| [setTriggerType(int value)](#setTriggerType-int-) | يصف نوع المشغل. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getAccelerate() {#getAccelerate--}
```
public final float getAccelerate()
```

يصف النسبة المئوية لتأثير سلوك التسريع للمدة. قراءة/كتابة float.

**الإرجاع:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public final void setAccelerate(float value)
```

يصف النسبة المئوية لتأثير سلوك التسريع للمدة. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public final float getDecelerate()
```

يصف النسبة المئوية لتأثير سلوك التباطؤ للمدة. قراءة/كتابة float.

**الإرجاع:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public final void setDecelerate(float value)
```

يصف النسبة المئوية لتأثير سلوك التباطؤ للمدة. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public final boolean getAutoReverse()
```

يصف ما إذا كان يجب تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public final void setAutoReverse(boolean value)
```

يصف ما إذا كان يجب تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public final float getDuration()
```

يصف مدة تأثير الرسوم المتحركة. قراءة/كتابة float.

**الإرجاع:**
float
### setDuration(float value) {#setDuration-float-}
```
public final void setDuration(float value)
```

يصف مدة تأثير الرسوم المتحركة. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public final float getRepeatCount()
```

يصف عدد مرات تكرار التأثير. قراءة/كتابة float.

**الإرجاع:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public final void setRepeatCount(float value)
```

يصف عدد مرات تكرار التأثير. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public final boolean getRepeatUntilEndSlide()
```

هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
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
public final void setRepeatUntilEndSlide(boolean value)
```

هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "حتى نهاية الشريحة"
>      effect.getTiming().setRepeatUntilEndSlide(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRepeatUntilNextClick() {#getRepeatUntilNextClick--}
```
public final boolean getRepeatUntilNextClick()
```

هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
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
public final void setRepeatUntilNextClick(boolean value)
```

هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "حتى النقر التالي"
>      effect.getTiming().setRepeatUntilNextClick(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRepeatDuration() {#getRepeatDuration--}
```
public final float getRepeatDuration()
```

يصف عدد مرات تكرار التأثير. قراءة/كتابة float.

**الإرجاع:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public final void setRepeatDuration(float value)
```

يصف عدد مرات تكرار التأثير. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public final int getRestart()
```

يحدد ما إذا كان يجب إعادة تشغيل التأثير بعد الانتهاء. قراءة/كتابة [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**الإرجاع:**
int
### setRestart(int value) {#setRestart-int-}
```
public final void setRestart(int value)
```

يحدد ما إذا كان يجب إعادة تشغيل التأثير بعد الانتهاء. قراءة/كتابة [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public final boolean getRewind()
```

هذه الخاصية تحدد ما إذا كان سيتم إرجاع التأثير عند الانتهاء من تشغيله. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // قم بتفعيل توقيت/إرجاع التأثير.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
boolean
### setRewind(boolean value) {#setRewind-boolean-}
```
public final void setRewind(boolean value)
```

هذه الخاصية تحدد ما إذا كان سيتم إرجاع التأثير عند الانتهاء من تشغيله. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشريحة الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // قم بتفعيل توقيت/إرجاع التأثير.
>      effect.getTiming().setRewind(true);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSpeed() {#getSpeed--}
```
public final float getSpeed()
```

يحدد النسبة المئوية التي يتم تسريع (أو إبطاء) التوقيت بها. قراءة/كتابة float.

**الإرجاع:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public final void setSpeed(float value)
```

يحدد النسبة المئوية التي يتم تسريع (أو إبطاء) التوقيت بها. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public final float getTriggerDelayTime()
```

يصف زمن التأخير بعد المشغل. قراءة/كتابة float.

**الإرجاع:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public final void setTriggerDelayTime(float value)
```

يصف زمن التأخير بعد المشغل. قراءة/كتابة float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public final int getTriggerType()
```

يصف نوع المشغل. قراءة/كتابة [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**الإرجاع:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public final void setTriggerType(int value)
```

يصف نوع المشغل. قراءة/كتابة [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يُرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject