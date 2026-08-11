---
title: ITiming
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل توقيت الرسوم المتحركة.
type: docs
weight: 443
url: /ar/aspose.slides.animation/itiming/
---
## ITiming فئة


Represents animation timing.

```cpp
class ITiming : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالة C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | محاكاة مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | محاكاة مقارنة النقطة العائمة بنمط C# حيث يتم اعتبار NaNين متساويين على الرغم من أنه وفقًا لـ IEC 60559:1989 فإن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | يصف النسبة المئوية لتأثير تسريع السلوك للمدة. اقرأ **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | يصف ما إذا كان يجب تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. اقرأ **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | يصف النسبة المئوية لتأثير إبطاء السلوك للمدة. اقرأ **float**. |
| virtual **float** [get_Duration](./get_duration/)() | يصف مدة تأثير الرسوم المتحركة. اقرأ **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | يصف عدد مرات تكرار التأثير. اقرأ **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | يصف عدد مرات تكرار التأثير. اقرأ **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. اقرأ **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. اقرأ **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | يحدد ما إذا كان يجب إعادة تشغيل التأثير بعد الاكتمال. اقرأ [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | هذه الخاصية تحدد ما إذا كان التأثير سيعود إلى البداية عند انتهاء التشغيل. اقرأ **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | يحدد النسبة المئوية لتسريع (أو إبطاء) التوقيت. اقرأ **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | يصف وقت التأخير بعد المشغّل. اقرأ **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | يصف نوع المشغّل. اقرأ [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تناظر عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيّئ جميع الهياكل الداخلية للبيانات. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح بناء النسخ للفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يهيئ كائنًا جديدًا ويتيح بناء النسخ للفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجع كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | يصف النسبة المئوية لتأثير تسريع السلوك للمدة. اكتب **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | يصف ما إذا كان يجب تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. اكتب **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | يصف النسبة المئوية لتأثير إبطاء السلوك للمدة. اكتب **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | يصف مدة تأثير الرسوم المتحركة. اكتب **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | يصف عدد مرات تكرار التأثير. اكتب **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | يصف عدد مرات تكرار التأثير. اكتب **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. اكتب **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. اكتب **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | يحدد ما إذا كان يجب إعادة تشغيل التأثير بعد الاكتمال. اكتب [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | هذه الخاصية تحدد ما إذا كان التأثير سيعود إلى البداية عند انتهاء التشغيل. اكتب **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | يحدد النسبة المئوية لتسريع (أو إبطاء) التوقيت. اكتب **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | يصف وقت التأخير بعد المشغّل. اكتب **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | يصف نوع المشغّل. اكتب [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | عيّن الوسيط النمطي رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يتيح تبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [Object](../../system/object/)
* نطاق [Aspose::Slides::Animation](../)
* مكتبة [Aspose.Slides](../../)