---
title: IChartData
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل البيانات المستخدمة في رسم المخطط.
type: docs
weight: 651
url: /ar/aspose.slides.charts/ichartdata/
---
## IChartData الفئة

يمثل البيانات المستخدمة في رسم المخطط.

```cpp
class IChartData : public virtual System::Object
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بنمط C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يُحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانين متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يُحاكي مقارنة النقطة العائمة على نمط C# حيث يُعتبر NaNانين متساويين على الرغم من أن IEC 60559:1989 تنص على أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للاستخدام الداخلي فقط. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | يُحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا كان [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) مضبوطًا على false). قراءة فقط [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | يعيد الفئة الأساسية عند الفهرس المحدد. إذا كان [get_UseSecondaryCategories](./get_usesecondarycategories/) false، احصل على أي من جميع الفئات. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | يُحصل على مصنع الخلايا لإنشاء خلايا تُستَخدم في سلاسل المخطط أو الفئات. قراءة فقط [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | يعيد السلسلة عند الفهرس المحدد. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | يمثل مصدر بيانات المخطط. |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | يُحصل على نوع دفتر العمل المدمج. يُعيد [WorkbookType::NotDefined](../workbooktype/) إذا كان [IChartData::get_DataSourceType](./get_datasourcetype/) هو [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). قراءة فقط [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | يمثل مسار دفتر العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا يكون null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | يُحصل على الفئات الثانوية إذا كان [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) true. قراءة فقط [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | يعيد الفئة الثانوية عند الفهرس المحدد. إذا كان [get_UseSecondaryCategories](./get_usesecondarycategories/) false، فإن [IChartData::get_SecondaryCategories](./get_secondarycategories/) يكون null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | يُحصل على السلاسل. قراءة فقط [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | يعيد مجموعة السلاسل عند الفهرس المحدد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | يُحصل على مجموعات السلاسل. قراءة فقط [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | إذا تم ضبطه على false فإن [IChartData::get_SecondaryCategories](./get_secondarycategories/) يُعيد null وتُستَخدم البيانات في [IChartData::get_Categories](./get_categories/) لكلا السلسلتين الأساسية والثانوية. إذا تم ضبطه على true تُستَخدم البيانات في [IChartData::get_SecondaryCategories](./get_secondarycategories/) للسلسلة الثانوية والبيانات في [IChartData::get_Categories](./get_categories/) للسلسلة الأساسية. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يُحصل على بنية عداد المراجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تمثيل لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | يُحصل على نطاق بيانات المخطط. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يُحصل على النوع الفعلي للكائن. تمثيل لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تمثيل لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تمثيل لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بنية الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بنسخ بنية الفئات الفرعية. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | يكتب دفتر العمل [Excel](../../aspose.slides.excel/) المتضمن داخليًا إلى تدفق في الذاكرة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات حسب المرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | إذا تم ضبطه على false فإن [IChartData::get_SecondaryCategories](./get_secondarycategories/) يُعيد null وتُستَخدم البيانات في [IChartData::get_Categories](./get_categories/) لكلا السلسلتين الأساسية والثانوية. إذا تم ضبطه على true تُستَخدم البيانات في [IChartData::get_SecondaryCategories](./get_secondarycategories/) للسلسلة الثانوية والبيانات في [IChartData::get_Categories](./get_categories/) للسلسلة الأساسية. كتابة **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. سيُحدّث بيانات [Chart](../chart/) من دفتر العمل الهدف. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | يضبط نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على النطاق الجديد. إذا كان عدد السلاسل في النطاق أكبر من عدد السلاسل في بيانات المخطط، فستُضاف سلاسل إضافية من نفس نوع السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالبي الـ n كمرجع ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يُحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يُخفض ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | تبديل البيانات على المحور. البيانات المرسومة على المحور X ستنتقل إلى المحور Y والعكس بالعكس. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تمثيل لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ إلغاء قفل عبارة C# lock(). استدعِ مباشرةً أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يُخفض عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | يُهيئ دفتر العمل [Excel](../../aspose.slides.excel/) المتضمن داخليًا بالقيمة المحددة من قبل المستخدم. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [Object](../../system/object/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)