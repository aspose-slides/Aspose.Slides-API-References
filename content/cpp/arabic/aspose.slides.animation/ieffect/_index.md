---
title: IEffect
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تأثير الرسوم المتحركة.
type: docs
weight: 248
url: /ar/aspose.slides.animation/ieffect/
---
## IEffect فئة

يمثل تأثير الرسوم المتحركة.

```cpp
class IEffect : public virtual System::Object
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة على نمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة على نمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() | حدد لونًا بعد الرسوم المتحركة للتأثير. اقرأ [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() | حدد نوعًا بعد الرسوم المتحركة للتأثير. اقرأ [AfterAnimationType](../afteranimationtype/). |
| virtual [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() | يعرف نوعًا لتحريك النص للتأثير. يمكن تحريك نص الشكل بالحرف أو بالكلمة أو كله مرة واحدة. اقرأ [AnimateTextType](../animatetexttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) | يرجع سلوك الرسوم المتحركة في الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() | يرجع مجموعة السلوكيات للتأثير. اقرأ [IBehaviorCollection](../ibehaviorcollection/). |
| virtual **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() | يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السالبة تحدد التأخير بالثواني. اقرأ **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffect](./)\> [get_Effect](./get_effect/)(**int32_t**) | يرجع تأثيرًا لتسلسل في الفهرس المحدد. |
| virtual [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() | يعرف فئة التأثير. اقرأ [EffectPresetClassType](../effectpresetclasstype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() | قراءة فقط [ISequence](../isequence/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() | حدد صوتًا مدمجًا للتأثير. اقرأ [IAudio](../../aspose.slides/iaudio/). |
| virtual **bool** [get_StopPreviousSound](./get_stopprevioussound/)() | تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. اقرأ **bool**. |
| virtual [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() | يعرف نوعًا فرعيًا للتأثير. اقرأ [EffectSubtype](../effectsubtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() | يرجع الشكل المستهدف للتأثير. للقراءة فقط [IShape](../../aspose.slides/ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() | يرجع تحريك النص. للقراءة فقط [ITextAnimation](../itextanimation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() | يعرف قيمة التوقيت للتأثير. اقرأ [ITiming](../itiming/). |
| virtual [EffectType](../effecttype/) [get_Type](./get_type/)() | يعرف نوع التأثير. اقرأ [EffectType](../effecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة مشابهة لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة مشابهة لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نسخة مشابهة للمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة مشابهة لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخة من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخة من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بـ nullptr بالمرجع. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) | حدد لونًا بعد الرسوم المتحركة للتأثير. اكتب [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) | حدد نوعًا بعد الرسوم المتحركة للتأثير. اكتب [AfterAnimationType](../afteranimationtype/). |
| virtual void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) | يعرف نوعًا لتحريك النص للتأثير. يمكن تحريك نص الشكل بالحرف أو بالكلمة أو كله مرة واحدة. اكتب [AnimateTextType](../animatetexttype/). |
| virtual void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) | عيّن سلوك الرسوم المتحركة في الفهرس المحدد. |
| virtual void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) | يرجع مجموعة السلوكيات للتأثير. اكتب [IBehaviorCollection](../ibehaviorcollection/). |
| virtual void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) | يعرف تأخيرًا بين أجزاء النص المتحركة (كلمات أو أحرف). القيمة الموجبة تحدد نسبة مدة التأثير. القيمة السالبة تحدد التأخير بالثواني. اكتب **float**. |
| virtual void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) | يعرف فئة التأثير. اكتب [EffectPresetClassType](../effectpresetclasstype/). |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) | حدد صوتًا مدمجًا للتأثير. اكتب [IAudio](../../aspose.slides/iaudio/). |
| virtual void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) | تحدد هذه الخاصية ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. اكتب **bool**. |
| virtual void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) | يعرف نوعًا فرعيًا للتأثير. اكتب [EffectSubtype](../effectsubtype/). |
| virtual void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | يعرف قيمة التوقيت للتأثير. اكتب [ITiming](../itiming/). |
| virtual void [set_Type](./set_type/)([EffectType](../effecttype/)) | يعرف نوع التأثير. اكتب [EffectType](../effecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كمرجع ضعيف (بدلاً من المشترك). يتيح تحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة مشابهة لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرةً؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## أنظر أيضًا

* فئة [Object](../../system/object/)
* مساحة اسم [Aspose::Slides::Animation](../)
* مكتبة [Aspose.Slides](../../)