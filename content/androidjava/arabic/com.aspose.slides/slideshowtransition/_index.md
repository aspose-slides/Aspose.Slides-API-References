---
title: SlideShowTransition
second_title: مرجع Aspose.Slides لنظام Android عبر Java API
description: يمثل انتقال عرض الشرائح.
type: docs
url: /ar/com.aspose.slides/slideshowtransition/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)  
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

يمثل انتقال عرض الشرائح.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSound()](#getSound--) | إرجاع أو تعيين بيانات الصوت المضمنة. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | إرجاع أو تعيين بيانات الصوت المضمنة. |
| [getSoundMode()](#getSoundMode--) | تعيين أو إرجاع وضع الصوت لانتقال الشريحة. |
| [setSoundMode(int value)](#setSoundMode-int-) | تعيين أو إرجاع وضع الصوت لانتقال الشريحة. |
| [getSoundLoop()](#getSoundLoop--) | هذه الخاصية تحدد ما إذا كان الصوت سيتكرر حتى حدوث حدث صوتي التالي في عرض الشرائح. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | هذه الخاصية تحدد ما إذا كان الصوت سيتكرر حتى حدوث حدث صوتي التالي في عرض الشرائح. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | تحدد ما إذا كان النقر بالفأرة سيتقدم بالشريحة أم لا. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | تحدد ما إذا كان النقر بالفأرة سيتقدم بالشريحة أم لا. |
| [getAdvanceAfter()](#getAdvanceAfter--) | هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد مدة زمنية معينة. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد مدة زمنية معينة. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | تحدد الوقت بالميليثانية التي يبدأ بعدها الانتقال. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | تحدد الوقت بالميليثانية التي يبدأ بعدها الانتقال. |
| [getSpeed()](#getSpeed--) | تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. |
| [setSpeed(int value)](#setSpeed-int-) | تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. |
| [getValue()](#getValue--) | قيمة انتقال عرض الشرائح. |
| [getType()](#getType--) | نوع الانتقال. |
| [setType(int value)](#setType-int-) | نوع الانتقال. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | تحدد ما إذا كان هذا الصوت مدمجًا أم لا. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | تحدد ما إذا كان هذا الصوت مدمجًا أم لا. |
| [getSoundName()](#getSoundName--) | تحدد اسمًا قابلًا للقراءة البشرية لصوت الانتقال. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | تحدد اسمًا قابلًا للقراءة البشرية لصوت الانتقال. |
| [getDuration()](#getDuration--) | إرجاع أو تعيين مدة تأثير انتقال الشريحة بالميليثانية. |
| [setDuration(int value)](#setDuration-int-) | إرجاع أو تعيين مدة تأثير انتقال الشريحة بالميليثانية. |
| [equals(Object obj)](#equals-java.lang.Object-) | تحدد ما إذا كانت كائني SlideShowTransition متساويين. |
| [hashCode()](#hashCode--) | تعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

إرجاع أو تعيين بيانات الصوت المضمنة. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**الإرجاع:**  
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

إرجاع أو تعيين بيانات الصوت المضمنة. قراءة/كتابة [IAudio](../../com.aspose.slides/iaudio).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

تعيين أو إرجاع وضع الصوت لانتقال الشريحة. قراءة/كتابة [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**الإرجاع:**  
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

تعيين أو إرجاع وضع الصوت لانتقال الشريحة. قراءة/كتابة [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

هذه الخاصية تحدد ما إذا كان الصوت سيتكرر حتى حدوث حدث صوتي التالي في عرض الشرائح. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

هذه الخاصية تحدد ما إذا كان الصوت سيتكرر حتى حدوث حدث صوتي التالي في عرض الشرائح. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

تحدد ما إذا كان النقر بالفأرة سيتقدم بالشريحة أم لا. إذا لم يتم تحديد هذه الخاصية فسيُفترض القيمة true. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

تحدد ما إذا كان النقر بالفأرة سيتقدم بالشريحة أم لا. إذا لم يتم تحديد هذه الخاصية فسيُفترض القيمة true. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد مدة زمنية معينة. قراءة/كتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // الحصول على أول انتقال للشرائح
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // التحقق مما إذا تم تعيين علامة التقدم بعد الشريحة
>      if (slideTransition.getAdvanceAfter())
>      {
>          // الحصول على قيمة وقت التقدم بعد الشريحة
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
public final void setAdvanceAfter(boolean value)
```

هذه الخاصية تحدد ما إذا كان عرض الشرائح سينتقل إلى الشريحة التالية بعد مدة زمنية معينة. قراءة/كتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // الحصول على أول انتقال للشرائح
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // التحقق مما إذا تم تعيين علامة التقدم بعد الشريحة
>      if (slideTransition.getAdvanceAfter())
>      {
>          // الحصول على قيمة وقت التقدم بعد الشريحة
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
public final long getAdvanceAfterTime()
```

تحدد الوقت بالميليثانية التي يبدأ بعدها الانتقال. قد يُستخدم هذا الإعداد مع خاصية advClick. إذا لم يتم تحديد هذه الخاصية فسيُفترض عدم وجود تقدم تلقائي. قراءة/كتابة long.

**الإرجاع:**  
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

تحدد الوقت بالميليثانية التي يبدأ بعدها الانتقال. قد يُستخدم هذا الإعداد مع خاصية advClick. إذا لم يتم تحديد هذه الخاصية فسيُفترض عدم وجود تقدم تلقائي. قراءة/كتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. قراءة/كتابة [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**الإرجاع:**  
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

تحدد سرعة الانتقال التي ستُستخدم عند الانتقال من الشريحة الحالية إلى التالية. قراءة/كتابة [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

قيمة انتقال عرض الشرائح. للقراءة فقط [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**الإرجاع:**  
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

نوع الانتقال. قراءة/كتابة [TransitionType](../../com.aspose.slides/transitiontype).

**الإرجاع:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

نوع الانتقال. قراءة/كتابة [TransitionType](../../com.aspose.slides/transitiontype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

تحدد ما إذا كان هذا الصوت مدمجًا أم لا. إذا تم تعيين هذه الخاصية إلى true فسيتم إعلام التطبيق المولد للتحقق من سمة الاسم المحدد لهذا الصوت في قائمة الأصوات المدمجة ويمكنه بعد ذلك عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

تحدد ما إذا كان هذا الصوت مدمجًا أم لا. إذا تم تعيين هذه الخاصية إلى true فسيتم إعلام التطبيق المولد للتحقق من سمة الاسم المحدد لهذا الصوت في قائمة الأصوات المدمجة ويمكنه بعد ذلك عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

تحدد اسمًا قابلًا للقراءة البشرية لصوت الانتقال. يجب تعيين الخاصية Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) للحصول على اسم الصوت أو تعيينه. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

تحدد اسمًا قابلًا للقراءة البشرية لصوت الانتقال. يجب تعيين الخاصية Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) للحصول على اسم الصوت أو تعيينه. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

إرجاع أو تعيين مدة تأثير انتقال الشريحة بالميليثانية. قراءة/كتابة int.

--------------------

يتوافق مع الخاصية p14:dur في عنصر p:transition في مخطط PresentationML. إذا لم يتم تعيينه، تُحدد المدة تلقائيًا بناءً على الخاصية \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) ونوع الانتقال.

**الإرجاع:**  
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

إرجاع أو تعيين مدة تأثير انتقال الشريحة بالميليثانية. قراءة/كتابة int.

--------------------

يتوافق مع الخاصية p14:dur في عنصر p:transition في مخطط PresentationML. إذا لم يتم تعيينه، تُحدد المدة تلقائيًا بناءً على الخاصية \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) ونوع الانتقال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تحدد ما إذا كان كائني SlideShowTransition متساويين. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ SlideShowTransition للمقارنة مع الـ SlideShowTransition الحالي. |

**الإرجاع:**  
boolean - **true** إذا كان الـ SlideShowTransition المحدد متساويًا مع الـ SlideShowTransition الحالي؛ وإلا **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

تعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

**الإرجاع:**  
int - 23454

--------------------

تم تجاوزها لجعل المترجم سعيدًا. دائمًا تُعيد قيمة ثابتة لأن الكائن قابل للتغيير.