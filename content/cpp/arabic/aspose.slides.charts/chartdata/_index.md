---
title: ChartData
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل البيانات المستخدمة في رسم المخطط.
type: docs
weight: 118
url: /ar/aspose.slides.charts/chartdata/
---
## ChartData فئة


يمثل البيانات المستخدمة في رسم المخطط.

```cpp
class ChartData : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                  public Aspose::Slides::Charts::IChartData
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام دلالات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساوٍ لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يقوم بمحاكاة مقارنة النقطة العائمة على نمط C# حيث يتم اعتبار NaNين متساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN ليس مساوٍ لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() override | يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا تم تعيين [ChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) إلى false). قراءة فقط [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) override | إرجاع الفئة الأساسية عند الفهرس المحدد. إذا كان [get_UseSecondaryCategories](./get_usesecondarycategories/) false، احصل على الفئة من جميع الفئات. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() override | يحصل على مصنع الخلايا لإنشاء الخلايا المستخدمة في سلاسل المخطط أو الفئات. قراءة فقط [IChartDataWorkbook](../ichartdataworkbook/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | إرجاع السلسلة عند الفهرس المحدد. |
| [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() override | يمثل مسار دفتر العمل الخارجي إذا كان مصدر البيانات خارجيًا، وإلا يكون null. |
| [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() override | يحصل على نوع دفتر العمل المدمج. إرجاع [WorkbookType::NotDefined](../workbooktype/) إذا كان [ChartData::get_DataSourceType](./get_datasourcetype/) [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). قراءة فقط [WorkbookType](../workbooktype/). |
| [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() override | يمثل مصدر بيانات المخطط |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() override | يحصل على الفئات الثانوية إذا كان [ChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) true. قراءة فقط [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) override | إرجاع الفئة الثانوية عند الفهرس المحدد. إذا كان [get_UseSecondaryCategories](./get_usesecondarycategories/) false، فإن [ChartData::get_SecondaryCategories](./get_secondarycategories/) يكون null. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() override | يحصل على السلاسل. قراءة فقط [IChartSeriesCollection](../ichartseriescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) override | إرجاع مجموعة السلاسل عند الفهرس المحدد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() override | يحصل على مجموعات السلاسل. قراءة فقط [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() override | إذا تم تعيينه إلى false فإن [ChartData::get_SecondaryCategories](./get_secondarycategories/) يُرجع null وتُستخدم البيانات في [ChartData::get_Categories](./get_categories/) لكل من السلاسل الأساسية والثانوية. إذا تم تعيينه إلى true تُستخدم البيانات في [ChartData::get_SecondaryCategories](./get_secondarycategories/) للسلاسل الثانوية وتُستخدم البيانات في [ChartData::get_Categories](./get_categories/) للسلاسل الأساسية. قراءة **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| [System::String](../../system/string/) [GetRange](./getrange/)() override | يحصل على نطاق بيانات المخطط. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | تحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. نظير عامل 'is' في C#. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل تعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ شيئًا، بل يقوم فقط بتهيئة كائن جديد ويسمح بإنشاء نسخ فرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا، بل يقوم فقط بتهيئة كائن جديد ويسمح بإنشاء نسخ فرعية. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() override | يكتب دفتر العمل [Excel](../../aspose.slides.excel/) المضمن داخليًا إلى تدفق في الذاكرة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) override | إذا تم تعيينه إلى false فإن [ChartData::get_SecondaryCategories](./get_secondarycategories/) يُرجع null وتُستخدم البيانات في [ChartData::get_Categories](./get_categories/) لكل من السلاسل الأساسية والثانوية. إذا تم تعيينه إلى true تُستخدم البيانات في [ChartData::get_SecondaryCategories](./get_secondarycategories/) للسلاسل الثانوية وتُستخدم البيانات في [ChartData::get_Categories](./get_categories/) للسلاسل الأساسية. كتابة **bool**. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) override | يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات [Chart](../chart/) من دفتر العمل الهدف. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) override | يضبط دفتر العمل الخارجي كمصدر بيانات للمخطط. |
| void [SetRange](./setrange/)([System::String](../../system/string/)) override | يضبط نطاق بيانات المخطط. سيتم تحديث السلاسل والفئات بناءً على النطاق الجديد. إذا كان عدد السلاسل في نطاق البيانات أكبر من عدد السلاسل في بيانات المخطط، فستُضاف سلاسل إضافية من نفس نوع السلسلة الأخيرة في المجموعة الحالية إلى نهاية المجموعة. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط الوسيط النمطي رقم n كإشارة ضعيفة (بدلاً من المشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقوم بتقليل وإرجاع عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [SwitchRowColumn](./switchrowcolumn/)() override | تبديل البيانات عبر المحور. البيانات المرسومة على محور X ستنتقل إلى محور Y والعكس بالعكس. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء القفل لتعبير C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقوم بتقليل عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector بدلاً من ذلك. |
| void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) override | يهيئ دفتر العمل [Excel](../../aspose.slides.excel/) المضمن داخليًا بالقيمة المحددة من قبل المستخدم. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* الفئة [DomObject](../../aspose.slides/domobject/)
* الفئة [IChartData](../ichartdata/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)