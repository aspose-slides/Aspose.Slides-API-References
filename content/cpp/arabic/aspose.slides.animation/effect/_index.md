---
title: Effect
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تأثير الرسوم المتحركة.
type: docs
weight: 118
url: /ar/aspose.slides.animation/effect/
---
## Effect فئة

يمثل تأثير الرسوم المتحركة.

```cpp
class Effect : public Aspose::Slides::Animation::IEffect,
               public Aspose::Slides::IDOMObject
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوك C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيم NaN اثنان متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر القيم NaN اثنان متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() override | يحدد لون ما بعد الرسوم المتحركة للتأثير. اقرأ [IColorFormat](../../aspose.slides/icolorformat/). |
| [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() override | يحدد نوع ما بعد الرسوم المتحركة للتأثير. اقرأ [AfterAnimationType](../afteranimationtype/). |
| [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() override | يحدد نوع نص الرسوم المتحركة للتأثير. يمكن تحريك نص الشكل بالحرف، أو بالكلمة، أو بالكامل مرة واحدة. اقرأ [AnimateTextType](../animatetexttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) override | يعيد سلوك الرسوم المتحركة عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() override | يعيد مجموعة من السلوكيات للتأثير. اقرأ [IBehaviorCollection](../ibehaviorcollection/). |
| **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() override | يحدد تأخيرًا بين أجزاء النص المتحركة (الكلمات أو الأحرف). قيمة موجبة تحدد النسبة المئوية لمدة التأثير. قيمة سالبة تحدد التأخير بالثواني. اقرأ **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [get_Effect](./get_effect/)(**int32_t**) override | يعيد تأثير تسلسل عند الفهرس المحدد. |
| [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() override | يحدد فئة التأثير. اقرأ [EffectPresetClassType](../effectpresetclasstype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() override | يعيد تسلسلاً لتأثير. للقراءة فقط [ISequence](../isequence/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | يعرف صوتًا مضمّنًا للتأثير. اقرأ [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_StopPreviousSound](./get_stopprevioussound/)() override | تحدد هذه السمة ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. اقرأ **bool**. |
| [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() override | يحدد النوع الفرعي للتأثير. اقرأ [EffectSubtype](../effectsubtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() override | يعيد الشكل المستهدف للتأثير. للقراءة فقط [IShape](../../aspose.slides/ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() override | [TextAnimation](../textanimation/) للقراءة فقط [ITextAnimation](../itextanimation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() override | يحدد قيمة التوقيت للتأثير. اقرأ [ITiming](../itiming/). |
| [EffectType](../effecttype/) [get_Type](./get_type/)() override | يحدد نوع التأثير. اقرأ [EffectType](../effecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل مثالًا للنوع الموضّح بواسطة targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل تعبير C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات عن طريق الإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات عن طريق الإشارة. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالإشارة إلى nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد الإشارة المشترك بالقيمة المحددة. |
| void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | يحدد لون ما بعد الرسوم المتحركة للتأثير. اكتب [IColorFormat](../../aspose.slides/icolorformat/). |
| void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) override | يحدد نوع ما بعد الرسوم المتحركة للتأثير. اكتب [AfterAnimationType](../afteranimationtype/). |
| void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) override | يحدد نوع نص الرسوم المتحركة للتأثير. يمكن تحريك نص الشكل بالحرف، أو بالكلمة، أو بالكامل مرة واحدة. اكتب [AnimateTextType](../animatetexttype/). |
| void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) override | يضبط سلوك الرسوم المتحركة عند الفهرس المحدد. |
| void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) override | يعيد مجموعة من السلوكيات للتأثير. اكتب [IBehaviorCollection](../ibehaviorcollection/). |
| void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) override | يحدد تأخيرًا بين أجزاء النص المتحركة (الكلمات أو الأحرف). قيمة موجبة تحدد النسبة المئوية لمدة التأثير. قيمة سالبة تحدد التأخير بالثواني. اكتب **float**. |
| void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) override | يحدد فئة التأثير. اكتب [EffectPresetClassType](../effectpresetclasstype/). |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | يعرف صوتًا مضمّنًا للتأثير. اكتب [IAudio](../../aspose.slides/iaudio/). |
| void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) override | تحدد هذه السمة ما إذا كان تأثير الرسوم المتحركة يوقف الصوت السابق. اكتب **bool**. |
| void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) override | يحدد النوع الفرعي للتأثير. اكتب [EffectSubtype](../effectsubtype/). |
| void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | يحدد قيمة التوقيت للتأثير. اكتب [ITiming](../itiming/). |
| void [set_Type](./set_type/)([EffectType](../effecttype/)) override | يحدد نوع التأثير. اكتب [EffectType](../effecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي الـ n't إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء قفل تعبير C# lock(). يُستدعى مباشرة أو يستخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يُدمّر الكائن. يحرّر جميع هياكل البيانات الداخلية. |

## راجع أيضًا

* فئة [IEffect](../ieffect/)
* فئة [IDOMObject](../../aspose.slides/idomobject/)
* نطاق [Aspose::Slides::Animation](../)
* مكتبة [Aspose.Slides](../../)