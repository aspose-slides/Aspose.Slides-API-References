---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل انتقال عرض الشرائح.
type: docs
url: /ar/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

يمثل انتقال عرض الشرائح.
## الأساليب

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | إرجاع أو تعيين بيانات الصوت المضمنة. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | إرجاع أو تعيين بيانات الصوت المضمنة. |
| [getSoundMode()](#getSoundMode--) | تعيين أو إرجاع وضع الصوت لانتقال الشريحة. |
| [setSoundMode(int value)](#setSoundMode-int-) | تعيين أو إرجاع وضع الصوت لانتقال الشريحة. |
| [getSoundLoop()](#getSoundLoop--) | تحدد هذه الخاصية ما إذا كان الصوت سيعيد التكرار حتى يحدث حدث صوتي التالي في عرض الشرائح. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | تحدد هذه الخاصية ما إذا كان الصوت سيعيد التكرار حتى يحدث حدث صوتي التالي في عرض الشرائح. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | تحدد ما إذا كان النقر بالماوس سيقدم الشريحة أم لا. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | تحدد ما إذا كان النقر بالماوس سيقدم الشريحة أم لا. |
| [getAdvanceAfter()](#getAdvanceAfter--) | تحدد هذه الخاصية ما إذا كان عرض الشرائح سيتحرك إلى الشريحة التالية بعد وقت معين. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | تحدد هذه الخاصية ما إذا كان عرض الشرائح سيتحرك إلى الشريحة التالية بعد وقت معين. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | تحدد الوقت، بالمللي ثانية، بعده يجب أن يبدأ الانتقال. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | تحدد الوقت، بالمللي ثانية، بعده يجب أن يبدأ الانتقال. |
| [getSpeed()](#getSpeed--) | تحدد سرعة الانتقال التي ستستخدم عند الانتقال من الشريحة الحالية إلى التالية. |
| [setSpeed(int value)](#setSpeed-int-) | تحدد سرعة الانتقال التي ستستخدم عند الانتقال من الشريحة الحالية إلى التالية. |
| [getValue()](#getValue--) | قيمة انتقال عرض الشرائح. |
| [getType()](#getType--) | نوع الانتقال. |
| [setType(int value)](#setType-int-) | نوع الانتقال. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | تحدد ما إذا كان هذا الصوت مدمجًا أم لا. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | تحدد ما إذا كان هذا الصوت مدمجًا أم لا. |
| [getSoundName()](#getSoundName--) | تحدد اسماً قابلاً للقراءة البشرية لصوت الانتقال. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | تحدد اسماً قابلاً للقراءة البشرية لصوت الانتقال. |
| [getDuration()](#getDuration--) | إرجاع أو تعيين مدة تأثير انتقال الشريحة بالمللي ثانية. |
| [setDuration(int value)](#setDuration-int-) | إرجاع أو تعيين مدة تأثير انتقال الشريحة بالمللي ثانية. |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

إرجاع أو تعيين بيانات الصوت المضمنة. قابل للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

إرجاع أو تعيين بيانات الصوت المضمنة. قابل للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

تعيين أو إرجاع وضع الصوت لانتقال الشريحة. قابل للقراءة والكتابة [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**الإرجاع:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

تعيين أو إرجاع وضع الصوت لانتقال الشريحة. قابل للقراءة والكتابة [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

تحدد هذه الخاصية ما إذا كان الصوت سيعيد التكرار حتى يحدث حدث صوتي التالي في عرض الشرائح. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

تحدد هذه الخاصية ما إذا كان الصوت سيعيد التكرار حتى يحدث حدث صوتي التالي في عرض الشرائح. قراءة/كتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

تحدد ما إذا كان النقر بالماوس سيقدم الشريحة أم لا. إذا لم يتم تحديد هذه الخاصية فإن القيمة true تُفترض. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

تحدد ما إذا كان النقر بالماوس سيقدم الشريحة أم لا. إذا لم يتم تحديد هذه الخاصية فإن القيمة true تُفترض. قراءة/كتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

تحدد هذه الخاصية ما إذا كان عرض الشرائح سيتحرك إلى الشريحة التالية بعد وقت معين. قراءة/كتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // احصل على الانتقال الأول للشرائح
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // تحقق ما إذا كان علم التقدم بعد الشريحة مفعلاً
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

تحدد هذه الخاصية ما إذا كان عرض الشرائح سيتحرك إلى الشريحة التالية بعد وقت معين. قراءة/كتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // احصل على الانتقال الأول للشرائح
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // تحقق ما إذا كان علم التقدم بعد الشريحة مفعلاً
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

تحدد الوقت، بالمللي ثانية، بعده يجب أن يبدأ الانتقال. يمكن استخدام هذا الإعداد بالتزامن مع الخاصية advClick. إذا لم يتم تحديد هذه الخاصية فإن عدم حدوث تقدم تلقائي يُفترض. قراءة/كتابة long.

**الإرجاع:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

تحدد الوقت، بالمللي ثانية، بعده يجب أن يبدأ الانتقال. يمكن استخدام هذا الإعداد بالتزامن مع الخاصية advClick. إذا لم يتم تحديد هذه الخاصية فإن عدم حدوث تقدم تلقائي يُفترض. قراءة/كتابة long.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

تحدد سرعة الانتقال التي ستستخدم عند الانتقال من الشريحة الحالية إلى التالية. قابل للقراءة والكتابة [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**الإرجاع:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

تحدد سرعة الانتقال التي ستستخدم عند الانتقال من الشريحة الحالية إلى التالية. قابل للقراءة والكتابة [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

قيمة انتقال عرض الشرائح. قراءة فقط [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

تحدد ما إذا كان هذا الصوت مدمجًا أم لا. إذا تم ضبط هذه الخاصية إلى true يتم تنبيه التطبيق المولد للتحقق من خاصية الاسم المحددة لهذا الصوت في قائمة الأصوات المدمجة ويمكنه حينها عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

تحدد ما إذا كان هذا الصوت مدمجًا أم لا. إذا تم ضبط هذه الخاصية إلى true يتم تنبيه التطبيق المولد للتحقق من خاصية الاسم المحددة لهذا الصوت في قائمة الأصوات المدمجة ويمكنه حينها عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. قراءة/كتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

تحدد اسماً قابلاً للقراءة البشرية لصوت الانتقال. يجب تعيين الخاصية (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) للحصول على اسم الصوت أو تعيينه. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

تحدد اسماً قابلاً للقراءة البشرية لصوت الانتقال. يجب تعيين الخاصية \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) للحصول على اسم الصوت أو تعيينه. قراءة/كتابة String.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

إرجاع أو تعيين مدة تأثير انتقال الشريحة بالمللي ثانية. قراءة/كتابة int.

--------------------

يتطابق مع خاصية p14:dur لعنصر p:transition في مخطط PresentationML. إذا لم يتم تعيينها، يتم تحديد المدة تلقائيًا بناءً على الخاصية \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) ونوع الانتقال.

**الإرجاع:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

إرجاع أو تعيين مدة تأثير انتقال الشريحة بالمللي ثانية. قراءة/كتابة int.

--------------------

يتطابق مع خاصية p14:dur لعنصر p:transition في مخطط PresentationML. إذا لم يتم تعيينها، يتم تحديد المدة تلقائيًا بناءً على الخاصية \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) ونوع الانتقال.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |