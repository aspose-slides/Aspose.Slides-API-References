---
title: SlideShowTransition
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل انتقال عرض الشرائح.
type: docs
url: /ar/com.aspose.slides/slideshowtransition/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

يمثل انتقال عرض الشرائح.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getSound()](#getSound--) | إرجاع أو تعيين بيانات الصوت المضمّنة. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | إرجاع أو تعيين بيانات الصوت المضمّنة. |
| [getSoundMode()](#getSoundMode--) | تعيين أو إرجاع وضع الصوت لانتقال الشريحة. |
| [setSoundMode(int value)](#setSoundMode-int-) | تعيين أو إرجاع وضع الصوت لانتقال الشريحة. |
| [getSoundLoop()](#getSoundLoop--) | تحدد هذه السمة ما إذا كان الصوت سيعيد التشغيل إلى أن يحدث حدث صوتي التالي في عرض الشرائح. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | تحدد هذه السمة ما إذا كان الصوت سيعيد التشغيل إلى أن يحدث حدث صوتي التالي في عرض الشرائح. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | تحدد ما إذا كان النقر بالفأرة سيتقدم بالشريحة أم لا. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | تحدد ما إذا كان النقر بالفأرة سيتقدم بالشريحة أم لا. |
| [getAdvanceAfter()](#getAdvanceAfter--) | تحدد هذه السمة ما إذا كان عرض الشرائح سيتنقل إلى الشريحة التالية بعد فترة زمنية معينة. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | تحدد هذه السمة ما إذا كان عرض الشرائح سيتنقل إلى الشريحة التالية بعد فترة زمنية معينة. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | تحدد الوقت بالملي ثانية الذي يجب أن يبدأ منه الانتقال. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | تحدد الوقت بالملي ثانية الذي يجب أن يبدأ منه الانتقال. |
| [getSpeed()](#getSpeed--) | تحدد سرعة الانتقال التي يجب استخدامها عند الانتقال من الشريحة الحالية إلى التالية. |
| [setSpeed(int value)](#setSpeed-int-) | تحدد سرعة الانتقال التي يجب استخدامها عند الانتقال من الشريحة الحالية إلى التالية. |
| [getValue()](#getValue--) | قيمة انتقال عرض الشرائح. |
| [getType()](#getType--) | نوع الانتقال. |
| [setType(int value)](#setType-int-) | نوع الانتقال. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | تحدد ما إذا كان هذا الصوت صوتًا مدمجًا أم لا. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | تحدد ما إذا كان هذا الصوت صوتًا مدمجًا أم لا. |
| [getSoundName()](#getSoundName--) | تحدد اسمًا مقروءًا للإنسان لصوت الانتقال. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | تحدد اسمًا مقروءًا للإنسان لصوت الانتقال. |
| [getDuration()](#getDuration--) | إحضار أو تعيين مدة تأثير انتقال الشريحة بالملي ثانية. |
| [setDuration(int value)](#setDuration-int-) | إحضار أو تعيين مدة تأثير انتقال الشريحة بالملي ثانية. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت مثالي SlideShowTransition متساويتين. |
| [hashCode()](#hashCode--) | تعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

إرجاع أو تعيين بيانات الصوت المضمّنة. قابل للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

**الإرجاع:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

إرجاع أو تعيين بيانات الصوت المضمّنة. قابل للقراءة والكتابة [IAudio](../../com.aspose.slides/iaudio).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

تعيين أو إرجاع وضع الصوت لانتقال الشريحة. قابل للقراءة والكتابة [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**الإرجاع:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

تعيين أو إرجاع وضع الصوت لانتقال الشريحة. قابل للقراءة والكتابة [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

تحدد هذه السمة ما إذا كان الصوت سيعيد التشغيل إلى أن يحدث حدث صوتي التالي في عرض الشرائح. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

تحدد هذه السمة ما إذا كان الصوت سيعيد التشغيل إلى أن يحدث حدث صوتي التالي في عرض الشر Slides. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

تحدد ما إذا كان النقر بالفأرة سيتقدم بالشريحة أم لا. إذا لم يتم تحديد هذه السمة فسيُفترض القيمة true. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

تحدد ما إذا كان النقر بالفأرة سيتقدم بالشريحة أم لا. إذا لم يتم تحديد هذه السمة فسيُفترض القيمة true. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

تحدد هذه السمة ما إذا كان عرض الشرائح سيتنقل إلى الشريحة التالية بعد فترة زمنية معينة. قابل للقراءة والكتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // احصل على انتقال الشريحة الأول
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // تحقق مما إذا كان علم Advance Slide After مفعلاً
>      if (slideTransition.getAdvanceAfter())
>      {
>          // احصل على قيمة Advance Slide After Time
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

تحدد هذه السمة ما إذا كان عرض الشرائح سيتنقل إلى الشريحة التالية بعد فترة زمنية معينة. قابل للقراءة والكتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // احصل على انتقال الشريحة الأول
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // تحقق مما إذا كان علم Advance Slide After مفعلاً
>      if (slideTransition.getAdvanceAfter())
>      {
>          // احصل على قيمة Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

تحدد الوقت بالملي ثانية الذي يجب أن يبدأ منه الانتقال. يمكن استخدام هذا الإعداد مع سمة advClick. إذا لم يتم تحديد هذه السمة فسيُفترض عدم حدوث انتقال تلقائي. قابل للقراءة والكتابة long.

**الإرجاع:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

تحدد الوقت بالملي ثانية الذي يجب أن يبدأ منه الانتقال. يمكن استخدام هذا الإعداد مع سمة advClick. إذا لم يتم تحديد هذه السمة فسيُفترض عدم حدوث انتقال تلقائي. قابل للقراءة والكتابة long.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

تحدد سرعة الانتقال التي يجب استخدامها عند الانتقال من الشريحة الحالية إلى التالية. قابل للقراءة والكتابة [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**الإرجاع:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

تحدد سرعة الانتقال التي يجب استخدامها عند الانتقال من الشريحة الحالية إلى التالية. قابل للقراءة والكتابة [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

قيمة انتقال عرض الشرائح. قراءة فقط [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**الإرجاع:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

نوع الانتقال. قابل للقراءة والكتابة [TransitionType](../../com.aspose.slides/transitiontype).

**الإرجاع:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

نوع الانتقال. قابل للقراءة والكتابة [TransitionType](../../com.aspose.slides/transitiontype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

تحدد ما إذا كان هذا الصوت صوتًا مدمجًا أم لا. إذا تم تعيين هذه السمة إلى true فسيتم إبلاغ التطبيق المولد للتحقق من سمة الاسم المحددة لهذا الصوت في قائمة الأصوات المدمجة ويمكنه حينها عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

تحدد ما إذا كان هذا الصوت صوتًا مدمجًا أم لا. إذا تم تعيين هذه السمة إلى true فسيتم إبلاغ التطبيق المولد للتحقق من سمة الاسم المحددة لهذا الصوت في قائمة الأصوات المدمجة ويمكنه حينها عرض اسم مخصص أو واجهة مستخدم حسب الحاجة. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

تحدد اسمًا مقروءًا للإنسان لصوت الانتقال. يجب تعيين الخاصية Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) للحصول أو تعيين اسم الصوت. قابل للقراءة والكتابة String.

**الإرجاع:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

تحدد اسمًا مقروءًا للإنسان لصوت الانتقال. يجب تعيين الخاصية Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) للحصول أو تعيين اسم الصوت. قابل للقراءة والكتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public final int getDuration()
```

إحضار أو تعيين مدة تأثير انتقال الشريحة بالملي ثانية. قابل للقراءة/الكتابة int.

--------------------

يتCorrespond to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) property and the transition type.

**الإرجاع:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

إحضار أو تعيين مدة تأثير انتقال الشريحة بالملي ثانية. قابل للقراءة/الكتابة int.

--------------------

يتCorrespond to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) property and the transition type.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كانت مثالي SlideShowTransition متساويتين. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ SlideShowTransition للمقارنة مع الـ SlideShowTransition الحالي. |

**الإرجاع:**
boolean - **true** إذا كان الـ SlideShowTransition المحدد مساويًا للـ SlideShowTransition الحالي؛ وإلا **false** .
### hashCode() {#hashCode--}
```
public int hashCode()
```

تعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

**الإرجاع:**
int - 23454

--------------------

تم تجاوزها لجعل المترجم سعيدًا. دائمًا تُعيد قيمة ثابتة لأن الكائن قابل للتغيير.