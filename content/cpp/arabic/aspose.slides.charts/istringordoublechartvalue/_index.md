---
title: IStringOrDoubleChartValue
second_title: مرجع API Aspose.Slides للغة C++
description: "يمثل قيمة نصية أو عددية مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا دفتر العمل المرتبط بالمخطط؛ 2) كقيمة حرفية."
type: docs
weight: 1210
url: /ar/aspose.slides.charts/istringordoublechartvalue/
---
## IStringOrDoubleChartValue الفئة

يمثل قيمة نصية أو عددية مزدوجة يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا دفتر العمل المرتبط بالمخطط؛ 2) كقيمة حرفية.

```cpp
class IStringOrDoubleChartValue : public Aspose::Slides::Charts::ISingleCellChartValue
```

## الطرق

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام C# [Object.Equals](../../system/object/equals/) الدلالات. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطية عائمة بنمط C# حيث تُعتبر NaNّان متساويتين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطية عائمة بنمط C# حيث تُعتبر NaNّان متساويتين على الرغم من أنه وفقًا لـ IEC 60559:1989 لا يكون NaN مساويًا لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](../isinglecellchartvalue/get_ascell/)() | يعيد خلية بيانات المخطط. قراءة [IChartDataCell](../ichartdatacell/). |
| virtual **double** [get_AsLiteralDouble](./get_asliteraldouble/)() | يعيد القيمة العشرية الحرفية إذا كانت خاصية DataSourceType هي [DataSourceType::DoubleLiterals](../datasourcetype/). قراءة **double**. |
| virtual [System::String](../../system/string/) [get_AsLiteralString](./get_asliteralstring/)() | يعيد السلسلة الحرفية إذا كانت خاصية DataSourceType هي [DataSourceType::StringLiterals](../datasourcetype/). قراءة [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Data](../ibasechartvalue/get_data/)() |  |
| virtual [Aspose::Slides::Charts::DataSourceType](../datasourcetype/) [get_DataSourceType](../ibasechartvalue/get_datasourcetype/)() | يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. بعبارة أخرى يحدد نوع قيمة خاصية Data. هذه الخاصية للقراءة فقط. لتغيير قيمة هذه الخاصية يمكنك استخدام واحدة من خصائص ChartDataPointCollection.DataSourceTypeFor<...>. قراءة [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية بيانات عدّاد الإشارة المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل مثيلاً للنوع الموصوف بواسطة targetType. نظير مشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيء جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويُمكّن إنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | مشغل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيء كائنًا جديدًا ويُمكّن إنشاء نسخ فرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجعية مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد الإشارة المشترك بالقيمة المحددة. |
| virtual void [set_AsCell](../isinglecellchartvalue/set_ascell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | يضبط خلية بيانات المخطط. كتابة [IChartDataCell](../ichartdatacell/). |
| virtual void [set_AsLiteralDouble](./set_asliteraldouble/)(**double**) | يضبط القيمة العشرية الحرفية إذا كانت خاصية DataSourceType هي [DataSourceType::DoubleLiterals](../datasourcetype/). كتابة **double**. |
| virtual void [set_AsLiteralString](./set_asliteralstring/)([System::String](../../system/string/)) | يضبط السلسلة الحرفية إذا كانت خاصية DataSourceType هي [DataSourceType::StringLiterals](../datasourcetype/). كتابة [System::String](../../system/string/). |
| virtual void [set_Data](../ibasechartvalue/set_data/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) |  |
| virtual void [set_DataSourceType](../ibasechartvalue/set_datasourcetype/)([Aspose::Slides::Charts::DataSourceType](../datasourcetype/)) | يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية. بعبارة أخرى يحدد نوع قيمة خاصية Data. هذه الخاصية للقراءة فقط. لتغيير قيمة هذه الخاصية يمكنك استخدام واحدة من خصائص ChartDataPointCollection.DataSourceTypeFor<...>. كتابة [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضعية ضعيفة. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعدّاد الإشارة المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد الإشارة المشترك. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual **double** [ToDouble](./todouble/)() | يحوّل القيمة إلى double. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يمكّن تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ فك قفل بيان C# lock(). استدعه مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بدلاً من ذلك، استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [ISingleCellChartValue](../isinglecellchartvalue/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)