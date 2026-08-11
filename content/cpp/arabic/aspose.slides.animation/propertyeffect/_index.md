---
title: PropertyEffect
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثِّل سلوك تأثير الخاصية.
type: docs
weight: 521
url: /ar/aspose.slides.animation/propertyeffect/
---
## PropertyEffect فئة

يمثل سلوك تأثير الخاصية.

```cpp
class PropertyEffect : public Aspose::Slides::Animation::Behavior,
                       public Aspose::Slides::Animation::IPropertyEffect
```

## الطرق

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين رغم أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. اقرأ [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسومات متحركة أخرى قيد التشغيل. اقرأ [BehaviorAdditiveType](../behavioradditivetype/). |
| [System::String](../../system/string/) [get_By](./get_by/)() override | يحدد قيمة إزاحة نسبية للرسوم المتحركة بالنسبة لموقعها قبل بدء الرسوم المتحركة. اقرأ [System::String](../../system/string/). |
| [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() override | يحدد وضع الاستيفاء للرسوم المتحركة. اقرأ [PropertyCalcModeType](../propertycalcmodetype/). |
| [System::String](../../system/string/) [get_From](./get_from/)() override | يحدد القيمة الأولية للرسوم المتحركة. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) override | يرجع نقطة من الرسوم المتحركة عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() override | يحدد نقاط الرسوم المتحركة. اقرأ [IPointCollection](../ipointcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | يمثل خصائص السلوك. للقراءة فقط [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | يمثل خصائص التوقيت لسلوك التأثير. اقرأ [ITiming](../itiming/). |
| [System::String](../../system/string/) [get_To](./get_to/)() override | يحدد القيمة النهائية للرسوم المتحركة. اقرأ [System::String](../../system/string/). |
| [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() override | يحدد نوع قيمة الخاصية. اقرأ [PropertyValueType](../propertyvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تماثل عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ فرعية. |
|  [PropertyEffect](./propertyeffect/)() |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | يمثل ما إذا كانت سلوكيات الرسوم المتحركة متراكمة. اكتب [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | يمثل ما إذا كان سلوك الرسوم المتحركة الحالي مدمجًا مع رسومات متحركة أخرى قيد التشغيل. اكتب [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_By](./set_by/)([System::String](../../system/string/)) override | يحدد قيمة إزاحة نسبية للرسوم المتحركة بالنسبة لموقعها قبل بدء الرسوم المتحركة. اكتب [System::String](../../system/string/). |
| void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) override | يحدد وضع الاستيفاء للرسوم المتحركة. اكتب [PropertyCalcModeType](../propertycalcmodetype/). |
| void [set_From](./set_from/)([System::String](../../system/string/)) override | يحدد القيمة الأولية للرسوم المتحركة. اكتب [System::String](../../system/string/). |
| void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) override | يحدد نقاط الرسوم المتحركة. اكتب [IPointCollection](../ipointcollection/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | يمثل خصائص التوقيت لسلوك التأثير. اكتب [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::String](../../system/string/)) override | يحدد القيمة النهائية للرسوم المتحركة. اكتب [System::String](../../system/string/). |
| void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) override | يحدد نوع قيمة الخاصية. اكتب [PropertyValueType](../propertyvaluetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النون من القالب كضعف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع الضعف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* فئة [Behavior](../behavior/)
* فئة [IPropertyEffect](../ipropertyeffect/)
* مساحة الاسم [Aspose::Slides::Animation](../)
* مكتبة [Aspose.Slides](../../)