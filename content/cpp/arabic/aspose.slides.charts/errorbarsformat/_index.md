---
title: ErrorBarsFormat
second_title: Aspose.Slides لـ C++ مرجع API
description: "يمثل أشرطة الخطأ لسلسلة المخطط. قيم ErrorBars المخصصة موجودة في IChartDataPointCollection (في خاصية IChartDataPoint::get_ErrorBarsCustomValues())."
type: docs
weight: 482
url: /ar/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat فئة

يمثل أشرطة الخطأ لسلسلة المخطط. قيم ErrorBars المخصصة موجودة في [IChartDataPointCollection](../ichartdatapointcollection/) (في خاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/)).

```cpp
class ErrorBarsFormat : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartSeries>>,
                        public Aspose::Slides::Charts::IErrorBarsFormat
```

## الطرق

| طريقة | وصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة بنقطة عائمة على نمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة بنقطة عائمة على نمط C# حيث يُعتبر NaNانان متساويين على الرغم من أن IEC 60559:1989 يحدد أن NaN ليس مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يرجع المخطط الأصلي. للقرة فقط [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | يمثل تنسيق أشرطة الخطأ. [IFormat](../iformat/) للقراءة. |
| **bool** [get_HasEndCap](./get_hasendcap/)() override | يحدد أنه لا يتم رسم غطاء نهائي على أشرطة الخطأ. قراءة **bool**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | يحصل على قابلية رؤية أشرطة الخطأ. قراءة **bool**. |
| [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() override | يحصل على نوع أشرطة الخطأ. [ErrorBarType](../errorbartype/) للقراءة. |
| **float** [get_Value](./get_value/)() override | يحصل على القيمة المستخدمة مع Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. في أي حالة أخرى سيعيد NaN. قراءة **float**. |
| [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() override | يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. في حالة نوع القيمة المخصص لتحديد القيمة استخدم خاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) للنقطة البيانية المحددة في مجموعة DataPoints للسلسلة. في حالة Fixed أو Percentage أو StandardDeviation استخدم خاصية Value لتحديد القيمة. 

قراءة [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تماثل طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تماثل استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تماثل معامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تماثل طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | يُنشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيء فعليًا، بل يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن بالمرجعية كائن النوع القيمي مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | يمثل تنسيق أشرطة الخطأ. اكتب [IFormat](../iformat/). |
| void [set_HasEndCap](./set_hasendcap/)(**bool**) override | يحدد أنه لا يتم رسم غطاء نهائي على أشرطة الخطأ. اكتب **bool**. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | يضبط قابلية رؤية أشرطة الخطأ. اكتب **bool**. |
| void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) override | يضبط نوع أشرطة الخطأ. اكتب [ErrorBarType](../errorbartype/). |
| void [set_Value](./set_value/)(**float**) override | يضبط القيمة المستخدمة مع Fixed و Percentage و StandardDeviation لتحديد طول أشرطة الخطأ. في أي حالة أخرى سيعيد NaN. اكتب **float**. |
| void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) override | يمثل الطرق الممكنة لتحديد طول أشرطة الخطأ. في حالة نوع القيمة المخصص لتحديد القيمة استخدم خاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) للنقطة البيانية المحددة في مجموعة DataPoints للسلسلة. في حالة Fixed أو Percentage أو StandardDeviation استخدم خاصية Value لتحديد القيمة. 

اكتب [ErrorBarValueType](../errorbarvaluetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط الوسيط القالب الـ n'th كمؤشر ضعيف (بدلاً من المشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضعية الضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تماثل طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم بدلاً من ذلك المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [DomObject](../../aspose.slides/domobject/)
* الفئة [IErrorBarsFormat](../ierrorbarsformat/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)