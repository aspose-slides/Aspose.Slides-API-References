---
title: Timing
second_title: وثائق API لـ Aspose.Slides للـ C++
description: يمثل توقيت الرسوم المتحركة.
type: docs
weight: 625
url: /ar/aspose.slides.animation/timing/
---
## فئة Timing

يمثل توقيت الرسوم المتحركة.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يتم اعتبار NaNين متساويين على الرغم من أن وفقًا لـ IEC 60559:1989 NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| **float** [get_Accelerate](./get_accelerate/)() override | يصف النسبة المئوية لتأثير سلوك التسريع خلال المدة. قراءة **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | يصف ما إذا كان سيتم تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. قراءة **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | يصف النسبة المئوية لتأثير سلوك التباطؤ خلال المدة. قراءة **float**. |
| **float** [get_Duration](./get_duration/)() override | يصف مدة تأثير الرسوم المتحركة. قراءة **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | يصف عدد مرات تكرار التأثير. قراءة **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | يصف عدد مرات تكرار التأثير. قراءة **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. قراءة **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. قراءة **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | يحدد ما إذا كان التأثير سيُعاد بدء تشغيله بعد الانتهاء. قراءة [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | هذه الخاصية تحدد ما إذا كان التأثير سيعود إلى البداية عند انتهاء التشغيل. قراءة **bool**. |
| **float** [get_Speed](./get_speed/)() override | يحدد النسبة المئوية لتسريع (أو إبطاء) التوقيت. قراءة **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | يصف وقت التأخير بعد الزناد. قراءة **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | يصف نوع الزناد. قراءة [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عداد المرجعية المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | تنفذ عملية القفل في تعليمة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويتيح إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالات السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجعية المشترك بالقيمة المحددة. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | يصف النسبة المئوية لتأثير سلوك التسريع خلال المدة. كتابة **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | يصف ما إذا كان سيتم تشغيل الرسوم المتحركة تلقائيًا بالعكس بعد تشغيلها في الاتجاه الأمامي. كتابة **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | يصف النسبة المئوية لتأثير سلوك التباطؤ خلال المدة. كتابة **float**. |
| void [set_Duration](./set_duration/)(**float**) override | يصف مدة تأثير الرسوم المتحركة. كتابة **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | يصف عدد مرات تكرار التأثير. كتابة **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | يصف عدد مرات تكرار التأثير. كتابة **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. كتابة **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. كتابة **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | يحدد ما إذا كان يجب إعادة تشغيل التأثير بعد الانتهاء. كتابة [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | هذه الخاصية تحدد ما إذا كان التأثير سيعود إلى البداية عند انتهاء التشغيل. كتابة **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | يحدد النسبة المئوية لتسريع (أو إبطاء) التوقيت. كتابة **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | يصف وقت التأخير بعد الزناد. كتابة **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | يصف نوع الزناد. كتابة [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n ليكون مؤشرًا ضعيفًا (بدلاً من مشترك). يسمح بتغيير المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجعية المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجعية المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجعية المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | تنفذ عملية إلغاء القفل في تعليمة C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجعية الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [ITiming](../itiming/)
* فئة [IDOMObject](../../aspose.slides/idomobject/)
* نطاق [Aspose::Slides::Animation](../)
* مكتبة [Aspose.Slides](../../)