---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: يمثل انتقال عرض الشرائح.
type: docs
url: /ar/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

يمثل انتقال عرض الشرائح.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getSound()](#getSound--) | إرجاع أو ضبط بيانات الصوت المدمجة. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | إرجاع أو ضبط بيانات الصوت المدمجة. |
| [getSoundMode()](#getSoundMode--) | ضبط أو إرجاع وضع الصوت للانتقال بين الشرائح. |
| [setSoundMode(int value)](#setSoundMode-int-) | ضبط أو إرجاع وضع الصوت للانتقال بين الشرائح. |
| [getSoundLoop()](#getSoundLoop--) | هذه الخاصية تحدد ما إذا كان الصوت سيتكرر حتى حدوث حدث صوتي التالي في عرض الشرائح. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | هذه الخاصية تحدد ما إذا كان الصوت سيتكرر حتى حدوث حدث صوتي التالي في عرض الشرائح. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | تحدد ما إذا كانت نقرة الفأرة ستحرك الشريحة إلى الأمام أم لا. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | تحدد ما إذا كانت نقرة الفأرة ستحرك الشريحة إلى الأمام أم لا. |
| [getAdvanceAfter()](#getAdvanceAfter--) | هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد وقت معين. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد وقت معين. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | تحدد الوقت، بالميلي ثانية، بعده يجب أن يبدأ الانتقال. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | تحدد الوقت، بالميلي ثانية، بعده يجب أن يبدأ الانتقال. |
| [getSpeed()](#getSpeed--) | تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. |
| [setSpeed(int value)](#setSpeed-int-) | تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. |
| [getValue()](#getValue--) | قيمة انتقال عرض الشرائح. |
| [getType()](#getType--) | نوع الانتقال. |
| [setType(int value)](#setType-int-) | نوع الانتقال. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | تحدد ما إذا كان هذا الصوت من الأصوات المدمجة أم لا. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | تحدد ما إذا كان هذا الصوت من الأصوات المدمجة أم لا. |
| [getSoundName()](#getSoundName--) | تحدد اسماً قابلاً للقراءة للإنسان لصوت الانتقال. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | تحدد اسماً قابلاً للقراءة للإنسان لصوت الانتقال. |
| [getDuration()](#getDuration--) | إرجاع أو ضبط مدة تأثير انتقال الشريحة بالميلي ثانية. |
| [setDuration(int value)](#setDuration-int-) | إرجاع أو ضبط مدة تأثير انتقال الشريحة بالميلي ثانية. |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

إرجاع أو ضبط بيانات الصوت المدمجة. قابل للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

إرجاع أو ضبط بيانات الصوت المدمجة. قابل للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

ضبط أو إرجاع وضع الصوت للانتقال بين الشرائح. قابل للقراءة والكتابة [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**الإرجاع:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

ضبط أو إرجاع وضع الصوت للانتقال بين الشرائح. قابل للقراءة والكتابة [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

هذه الخاصية تحدد ما إذا كان الصوت سيتكرر حتى حدوث حدث صوتي التالي في عرض الشرائح. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

هذه الخاصية تحدد ما إذا كان الصوت سيتكرر حتى حدوث حدث صوتي التالي في عرض الشرائح. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

تحدد ما إذا كانت نقرة الفأرة ستحرك الشريحة إلى الأمام أم لا. إذا لم يتم تحديد هذه الخاصية، يُفترض القيمة true. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

تحدد ما إذا كانت نقرة الفأرة ستحرك الشريحة إلى الأمام أم لا. إذا لم يتم تحديد هذه الخاصية، يُفترض القيمة true. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد وقت معين. قابل للقراءة والكتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // احصل على الانتقال الأول للشرائح
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // تحقق مما إذا كان العلم Advance Slide After مفعلًا
>      if (slideTransition.getAdvanceAfter())
>      {
>          // احصل على قيمة وقت التقدم بعد الشريحة
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد وقت معين. قابل للقراءة والكتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // احصل على الانتقال الأول للشرائح
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // تحقق مما إذا كان العلم Advance Slide After مفعلًا
>      if (slideTransition.getAdvanceAfter())
>      {
>          // احصل على قيمة وقت التقدم بعد الشريحة
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

تحدد الوقت، بالميلي ثانية، بعده يجب أن يبدأ الانتقال. قد تُستخدم هذه الإعدادات بالتزامن مع الخاصية advClick. إذا لم يتم تحديد هذه الخاصية، يُفترض عدم حدوث تقدم تلقائي. قابل للقراءة والكتابة long.

**الإرجاع:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

تحدد الوقت، بالميلي ثانية، بعده يجب أن يبدأ الانتقال. قد تُستخدم هذه الإعدادات بالتزامن مع الخاصية advClick. إذا لم يتم تحديد هذه الخاصية، يُفترض عدم حدوث تقدم تلقائي. قابل للقراءة والكتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. قابل للقراءة والكتابة [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**الإرجاع:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. قابل للقراءة والكتابة [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

قيمة انتقال عرض الشرائح. للقراءة فقط [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**الإرجاع:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

نوع الانتقال. قابل للقراءة والكتابة [TransitionType](../../com.aspose.slides/transitiontype).

**الإرجاع:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

نوع الانتقال. قابل للقراءة والكتابة [TransitionType](../../com.aspose.slides/transitiontype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

تحدد ما إذا كان هذا الصوت من الأصوات المدمجة أم لا. إذا تم تعيين هذه الخاصية إلى true، فإن التطبيق المولد يُنبه للتحقق من الخاصية name المحددة لهذا الصوت في قائمة الأصوات المدمجة، ويمكنه إظهار اسم مخصص أو واجهة مستخدم حسب الحاجة. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

تحدد ما إذا كان هذا الصوت من الأصوات المدمجة أم لا. إذا تم تعيين هذه الخاصية إلى true، فإن التطبيق المولد يُنبه للتحقق من الخاصية name المحددة لهذا الصوت في قائمة الأصوات المدمجة، ويمكنه إظهار اسم مخصص أو واجهة مستخدم حسب الحاجة. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

تحدد اسماً قابلاً للقراءة للإنسان لصوت الانتقال. يجب تعيين الخاصية (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) للحصول على اسم الصوت أو ضبطه. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

تحدد اسماً قابلاً للقراءة للإنسان لصوت الانتقال. يجب تعيين الخاصية \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) للحصول على اسم الصوت أو ضبطه. قابل للقراءة والكتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

إرجاع أو ضبط مدة تأثير انتقال الشريحة بالميلي ثانية. قابل للقراءة والكتابة int.

--------------------

يتوافق مع السمة p14:dur لعنصر p:transition في مخطط PresentationML. إذا لم يتم تعيينها، يتم تحديد المدة تلقائيًا بناءً على الخاصية \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) ونوع الانتقال.

**الإرجاع:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

إرجاع أو ضبط مدة تأثير انتقال الشريحة بالميلي ثانية. قابل للقراءة والكتابة int.

--------------------

يتوافق مع السمة p14:dur لعنصر p:transition في مخطط PresentationML. إذا لم يتم تعيينها، يتم تحديد المدة تلقائيًا بناءً على الخاصية \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) ونوع الانتقال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |