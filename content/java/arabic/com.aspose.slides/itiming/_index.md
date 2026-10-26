---
title: ITiming
second_title: Aspose.Slides for Java مرجع API
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
| [getAccelerate()](#getAccelerate--) | يصف النسبة المئوية لتأثير سلوك التسارع خلال المدة. |
| [setAccelerate(float value)](#setAccelerate-float-) | يصف النسبة المئوية لتأثير سلوك التسارع خلال المدة. |
| [getDecelerate()](#getDecelerate--) | يصف النسبة المئوية لتأثير سلوك التباطؤ خلال المدة. |
| [setDecelerate(float value)](#setDecelerate-float-) | يصف النسبة المئوية لتأثير سلوك التباطؤ خلال المدة. |
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
| [getRestart()](#getRestart--) | يحدد ما إذا كان التأثير سيُعاد تشغيله بعد الاكتمال. |
| [setRestart(int value)](#setRestart-int-) | يحدد ما إذا كان التأثير سيُعاد تشغيله بعد الاكتمال. |
| [getSpeed()](#getSpeed--) | يحدد النسبة المئوية التي يتم بموجبها تسريع (أو إبطاء) التوقيت. |
| [setSpeed(float value)](#setSpeed-float-) | يحدد النسبة المئوية التي يتم بموجبها تسريع (أو إبطاء) التوقيت. |
| [getTriggerDelayTime()](#getTriggerDelayTime--) | يصف زمن التأخير بعد المُشغل. |
| [setTriggerDelayTime(float value)](#setTriggerDelayTime-float-) | يصف زمن التأخير بعد المُشغل. |
| [getTriggerType()](#getTriggerType--) | يصف نوع المُشغل. |
| [setTriggerType(int value)](#setTriggerType-int-) | يصف نوع المُشغل. |
| [getRewind()](#getRewind--) | هذه الخاصية تحدد ما إذا كان التأثير سيُعيد إلى البداية عند الانتهاء من التشغيل. |
| [setRewind(boolean value)](#setRewind-boolean-) | هذه الخاصية تحدد ما إذا كان التأثير سيُعيد إلى البداية عند الانتهاء من التشغيل. |

### getAccelerate() {#getAccelerate--}
```
public abstract float getAccelerate()
```

يصف النسبة المئوية لتأثير سلوك التسارع خلال المدة. قراءة/كتابة float.

**الإرجاع:**
float
### setAccelerate(float value) {#setAccelerate-float-}
```
public abstract void setAccelerate(float value)
```

يصف النسبة المئوية لتأثير سلوك التسارع خلال المدة. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDecelerate() {#getDecelerate--}
```
public abstract float getDecelerate()
```

يصف النسبة المئوية لتأثير سلوك التباطؤ خلال المدة. قراءة/كتابة float.

**الإرجاع:**
float
### setDecelerate(float value) {#setDecelerate-float-}
```
public abstract void setDecelerate(float value)
```

يصف النسبة المئوية لتأثير سلوك التباطؤ خلال المدة. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getAutoReverse() {#getAutoReverse--}
```
public abstract boolean getAutoReverse()
```

يصف ما إذا كان يجب تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setAutoReverse(boolean value) {#setAutoReverse-boolean-}
```
public abstract void setAutoReverse(boolean value)
```

يصف ما إذا كان يجب تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDuration() {#getDuration--}
```
public abstract float getDuration()
```

يصف مدة تأثير الرسوم المتحركة. قراءة/كتابة float.

**الإرجاع:**
float
### setDuration(float value) {#setDuration-float-}
```
public abstract void setDuration(float value)
```

يصف مدة تأثير الرسوم المتحركة. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRepeatCount() {#getRepeatCount--}
```
public abstract float getRepeatCount()
```

يصف عدد مرات تكرار التأثير. قراءة/كتابة float.

**الإرجاع:**
float
### setRepeatCount(float value) {#setRepeatCount-float-}
```
public abstract void setRepeatCount(float value)
```

يصف عدد مرات تكرار التأثير. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRepeatUntilEndSlide() {#getRepeatUntilEndSlide--}
```
public abstract boolean getRepeatUntilEndSlide()
```

هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشرائح الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "Until End of Slide"
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

هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشرائح الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "Until End of Slide"
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

هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشرائح الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "Until Next Click"
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

هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشرائح الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
>      IEffect effect = effectsSequence.get_Item(0);
>      // غيّر توقيت/تكرار التأثير إلى "Until Next Click"
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

يصف عدد مرات تكرار التأثير. قراءة/كتابة float.

**الإرجاع:**
float
### setRepeatDuration(float value) {#setRepeatDuration-float-}
```
public abstract void setRepeatDuration(float value)
```

يصف عدد مرات تكرار التأثير. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getRestart() {#getRestart--}
```
public abstract int getRestart()
```

يحدد ما إذا كان التأثير سيُعاد تشغيله بعد الاكتمال. قراءة/كتابة [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**الإرجاع:**
int
### setRestart(int value) {#setRestart-int-}
```
public abstract void setRestart(int value)
```

يحدد ما إذا كان التأثير سيُعاد تشغيله بعد الاكتمال. قراءة/كتابة [EffectRestartType](../../com.aspose.slides/effectrestarttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSpeed() {#getSpeed--}
```
public abstract float getSpeed()
```

يحدد النسبة المئوية التي يتم بموجبها تسريع (أو إبطاء) التوقيت. قراءة/كتابة float.

**الإرجاع:**
float
### setSpeed(float value) {#setSpeed-float-}
```
public abstract void setSpeed(float value)
```

يحدد النسبة المئوية التي يتم بموجبها تسريع (أو إبطاء) التوقيت. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTriggerDelayTime() {#getTriggerDelayTime--}
```
public abstract float getTriggerDelayTime()
```

يصف زمن التأخير بعد المُشغل. قراءة/كتابة float.

**الإرجاع:**
float
### setTriggerDelayTime(float value) {#setTriggerDelayTime-float-}
```
public abstract void setTriggerDelayTime(float value)
```

يصف زمن التأخير بعد المُشغل. قراءة/كتابة float.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getTriggerType() {#getTriggerType--}
```
public abstract int getTriggerType()
```

يصف نوع المُشغل. قراءة/كتابة [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**الإرجاع:**
int
### setTriggerType(int value) {#setTriggerType-int-}
```
public abstract void setTriggerType(int value)
```

يصف نوع المُشغل. قراءة/كتابة [EffectTriggerType](../../com.aspose.slides/effecttriggertype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRewind() {#getRewind--}
```
public abstract boolean getRewind()
```

هذه الخاصية تحدد ما إذا كان التأثير سيُعيد إلى البداية عند الانتهاء من التشغيل. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشرائح الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
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

هذه الخاصية تحدد ما إذا كان التأثير سيُعيد إلى البداية عند الانتهاء من التشغيل. قراءة/كتابة boolean.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // احصل على تسلسل التأثيرات للشرائح الأولى
>      ISequence effectsSequence = presentation.getSlides().get_Item(0).getTimeline().getMainSequence();
>      // احصل على أول تأثير في التسلسل الرئيسي.
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