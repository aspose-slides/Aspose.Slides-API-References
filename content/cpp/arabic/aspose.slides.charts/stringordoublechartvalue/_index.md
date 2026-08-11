---
title: StringOrDoubleChartValue
second_title: Aspose.Slides لـ C++ مرجع API
description: "يمثل قيمة سلسلة أو مزدوج يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من مصنف مرتبط بالمخطط; 2) كقيمة حرفية."
type: docs
weight: 1353
url: /ar/aspose.slides.charts/stringordoublechartvalue/
---
## StringOrDoubleChartValue فئة

يمثل قيمة سلسلة أو عدد مزدوج يمكن تخزينها في مستند عرض تقديمي pptx بطريقتين: 1) في خلية/خلايا من مصنف مرتبط بالمخطط؛ 2) كقيمة حرفية.

```cpp
class StringOrDoubleChartValue : public Aspose::Slides::Charts::BaseChartValue,
                                 public Aspose::Slides::Charts::IStringOrDoubleChartValue
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُنظر إلى NaNين على أنهما متساويان على الرغم من أنه وفقًا للمعيار IEC 60559:1989 NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُنظر إلى NaNين على أنهما متساويان على الرغم من أنه وفقًا للمعيار IEC 60559:1989 NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](./get_ascell/)() override | يرجع خلية بيانات المخطط. اقرأ [IChartDataCell](../ichartdatacell/). |
| **double** [get_AsLiteralDouble](./get_asliteraldouble/)() override | يرجع القيمة كعدد مزدوج حرفي. اقرأ **double**. |
| [System::String](../../system/string/) [get_AsLiteralString](./get_asliteralstring/)() override | يرجع القيمة كسلسلة حرفية. اقرأ [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Data](./get_data/)() override | يرجع كائن Data. اقرأ [System::Object](../../system/object/). |
| [Aspose::Slides::Charts::DataSourceType](../datasourcetype/) [get_DataSourceType](../basechartvalue/get_datasourcetype/)() override | يحدد ما إذا كانت خاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble هي الفعلية في الفروع. بمعنى آخر يحدد نوع قيمة خاصية Data. اقرأ [Charts::DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية البيانات الخاصة بعداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. تمثيل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل بيان C# lock(). استدعِ مباشرة أو استخدم [LockContext](../../system/lockcontext/) كائن الحراسة. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء، في الواقع، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء، في الواقع، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بناء الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن المرجع لكائن من نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AsCell](./set_ascell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | يضبط خلية بيانات المخطط. اكتب [IChartDataCell](../ichartdatacell/). |
| void [set_AsLiteralDouble](./set_asliteraldouble/)(**double**) override | يضبط القيمة كعدد مزدوج حرفي. اكتب **double**. |
| void [set_AsLiteralString](./set_asliteralstring/)([System::String](../../system/string/)) override | يضبط القيمة كسلسلة حرفية. اكتب [System::String](../../system/string/). |
| void [set_Data](./set_data/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يضبط كائن Data. اكتب [System::Object](../../system/object/). |
| void [set_DataSourceType](../basechartvalue/set_datasourcetype/)([Aspose::Slides::Charts::DataSourceType](../datasourcetype/)) override | يحدد ما إذا كانت خاصية AsCell أو AsCells أو AsLiteralString أو AsLiteralDouble هي الفعلية في الفروع. بمعنى آخر يحدد نوع قيمة خاصية Data. اكتب [Charts::DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب رقم n'th كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| **double** [ToDouble](./todouble/)() override | يحول إلى double. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل بيان C# lock(). استدعِ مباشرة أو استخدم [LockContext](../../system/lockcontext/) كائن الحراسة. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد الإشارة الضعيفة. لا ينبغي استدعاؤه مباشرة؛ بل استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* فئة [BaseChartValue](../basechartvalue/)
* فئة [IStringOrDoubleChartValue](../istringordoublechartvalue/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)