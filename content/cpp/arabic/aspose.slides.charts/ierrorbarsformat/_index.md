---
title: IErrorBarsFormat
second_title: Aspose.Slides لـ C++ مرجع API
description: "يمثل أشرطة الخطأ لسلسلة الرسم البياني. قيم ErrorBars المخصصة موجودة في IChartDataPointCollection (في خاصية IChartDataPoint::get_ErrorBarsCustomValues())."
type: docs
weight: 1028
url: /ar/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat فئة


يمثل أعمدة الخطأ لسلسلة الرسم البياني. قيم ErrorBars المخصصة موجودة في [IChartDataPointCollection](../ichartdatapointcollection/) (في خاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/)).

```cpp
class IErrorBarsFormat : public Aspose::Slides::Charts::IChartComponent
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if\<![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أن IEC 60559:1989 تشير إلى أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث تُعتبر قيمتا NaN متساويتين رغم أن IEC 60559:1989 تشير إلى أن NaN ليست مساوية لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يعيد المخطط. قراءة فقط [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | يمثل تنسيق أعمدة الخطأ. قراءة [IFormat](../iformat/). |
| virtual **bool** [get_HasEndCap](./get_hasendcap/)() | يحدد عدم رسم غطاء نهائي على أعمدة الخطأ. قراءة **bool**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | يحصل على رؤية Error Bars. قراءة **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يعيد العرض التقديمي. قراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يعيد الشريحة الأساسية. قراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() | يحصل على نوع أعمدة الخطأ. قراءة [ErrorBarType](../errorbartype/). |
| virtual **float** [get_Value](./get_value/)() | يحصل على القيمة التي تُستخدم مع الأنواع Fixed و Percentage و StandardDeviation لتحديد طول أعمدة الخطأ. قراءة **float**. |
| virtual [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() | يمثل الطرق الممكنة لتحديد طول أعمدة الخطأ. في حالة نوع قيمة مخصص لتحديد القيمة، استخدم خاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) للنقطة البيانية المحددة في مجموعة DataPoints للسلسلة. 

 قراءة [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلًا للنوع الموصوف بـ targetType. تمثيل لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | يمثل تنسيق أعمدة الخطأ. كتابة [IFormat](../iformat/). |
| virtual void [set_HasEndCap](./set_hasendcap/)(**bool**) | يحدد عدم رسم غطاء نهائي على أعمدة الخطأ. كتابة **bool**. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | يضبط رؤية Error Bars. كتابة **bool**. |
| virtual void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) | يضبط نوع أعمدة الخطأ. كتابة [ErrorBarType](../errorbartype/). |
| virtual void [set_Value](./set_value/)(**float**) | يضبط القيمة التي تُستخدم مع الأنواع Fixed و Percentage و StandardDeviation لتحديد طول أعمدة الخطأ. كتابة **float**. |
| virtual void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) | يمثل الطرق الممكنة لتحديد طول أعمدة الخطأ. في حالة نوع قيمة مخصص لتحديد القيمة، استخدم خاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) للنقطة البيانية المحددة في مجموعة DataPoints للسلسلة. 

 كتابة [ErrorBarValueType](../errorbarvaluetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط النمطي رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## انظر أيضًا

* الفئة [IChartComponent](../ichartcomponent/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)