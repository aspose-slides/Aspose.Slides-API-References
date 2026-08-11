---
title: IPropertyEffect
second_title: مرجع API ل Aspose.Slides للغة C++
description: يمثل سلوك تأثير الخاصية.
type: docs
weight: 339
url: /ar/aspose.slides.animation/ipropertyeffect/
---
## الفئة IPropertyEffect

يمثل سلوك تأثير الخاصية.

```cpp
class IPropertyEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد [Object.Equals](../../system/object/equals/) في C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتي NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتي NaN متساويتين على الرغم من أن معيار IEC 60559:1989 يحدد أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | يمثل ما إذا كان سلوكيات الرسوم المتحركة متراكمة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسوم متحركة أخرى قيد التشغيل. اقرأ [BehaviorAdditiveType](../behavioradditivetype/). |
| virtual [System::String](../../system/string/) [get_By](./get_by/)() | يحدد قيمة إزاحة نسبية للرسوم المتحركة بالنسبة إلى موقعها قبل بدء الرسوم المتحركة. اقرأ [System::String](../../system/string/). |
| virtual [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() | يحدد وضع الاستيفاء للرسوم المتحركة. اقرأ [PropertyCalcModeType](../propertycalcmodetype/). |
| virtual [System::String](../../system/string/) [get_From](./get_from/)() | يحدد القيمة الابتدائية للرسوم المتحركة. اقرأ [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) | يعيد نقطة من الرسوم المتحركة عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() | يحدد نقاط الرسوم المتحركة. اقرأ [IPointCollection](../ipointcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | يمثل خصائص السلوك. قراءة فقط [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | يمثل خصائص التوقيت لسلوك التأثير. اقرأ [ITiming](../itiming/). |
| virtual [System::String](../../system/string/) [get_To](./get_to/)() | يحدد القيمة النهائية للرسوم المتحركة. اقرأ [System::String](../../system/string/). |
| virtual [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() | يحدد نوع قيمة الخاصية. اقرأ [PropertyValueType](../propertyvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، بل يقوم فقط بتهيئة كائن جديد ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، بل يقوم فقط بتهيئة كائن جديد ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | يمثل ما إذا كان سلوكيات الرسوم المتحركة متراكمة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسوم متحركة أخرى قيد التشغيل. اكتب [BehaviorAdditiveType](../behavioradditivetype/). |
| virtual void [set_By](./set_by/)([System::String](../../system/string/)) | يحدد قيمة إزاحة نسبية للرسوم المتحركة بالنسبة إلى موقعها قبل بدء الرسوم المتحركة. اكتب [System::String](../../system/string/). |
| virtual void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) | يحدد وضع الاستيفاء للرسوم المتحركة. اكتب [PropertyCalcModeType](../propertycalcmodetype/). |
| virtual void [set_From](./set_from/)([System::String](../../system/string/)) | يحدد القيمة الابتدائية للرسوم المتحركة. اكتب [System::String](../../system/string/). |
| virtual void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) | يحدد نقاط الرسوم المتحركة. اكتب [IPointCollection](../ipointcollection/). |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | يمثل خصائص التوقيت لسلوك التأثير. اكتب [ITiming](../itiming/). |
| virtual void [set_To](./set_to/)([System::String](../../system/string/)) | يحدد القيمة النهائية للرسوم المتحركة. اكتب [System::String](../../system/string/). |
| virtual void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) | يحدد نوع قيمة الخاصية. اكتب [PropertyValueType](../propertyvaluetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتبديل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ فك قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [IBehavior](../ibehavior/)
* النطاق [Aspose::Slides::Animation](../)
* المكتبة [Aspose.Slides](../../)