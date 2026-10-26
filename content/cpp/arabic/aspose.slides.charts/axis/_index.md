---
title: Axis
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يُغلف الكائن الذي يمثل محور المخطط.
type: docs
weight: 14
url: /ar/aspose.slides.charts/axis/
---
## Axis فئة

Encapsulates the object that represents a chart's axis.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع المرجع بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن الكائنات من نوع القيمة بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة نقطة عائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يوضح أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة نقطة عائمة بأسلوب C# حيث يُعتبر NaNانان متساويين بالرغم من أن معيار IEC 60559:1989 يوضح أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | يحدد القيمة العظمى الفعلية على المحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | يحدد الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | يحدد مقياس الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | يحدد القيمة الصغرى الفعلية على المحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | يمثل نوع التجميع لمحور الفئة (التجميع). يُطبق على الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. هذه الخاصية تنطبق فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قراءة **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. قراءة [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على [AxisAggregationType::ByBinWidth](../axisaggregationtype/). يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | يحدد نوع محور الفئة. قراءة [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | يُرجع المخطط الأصلي. قراءة فقط [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | يمثل النقطة على المحور حيث يعبر المحور العمودي عليه. قراءة **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | يمثل نوع التقاطع على المحور المحدد حيث يعبر المحور الآخر. قراءة [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | يحدد قيمة المقياس لوحدات العرض لمحور القيم. قراءة [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | يمثل تنسيق المحور. قراءة فقط [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | يحدد ما إذا كان للمحور عنوان مرئي. قراءة **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. قراءة **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | يشير إلى ما إذا كانت القيمة العظمى تُعيّن تلقائيًا. قراءة **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | يشير إلى ما إذا كانت الوحدة الصغرى للمحور تُعيّن تلقائيًا. قراءة **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | يشير إلى ما إذا كانت القيمة الصغرى تُعيّن تلقائيًا. قراءة **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | يحدد قيمة الحاوية الزائدة التلقائية. إذا كان false: استخدم خاصية OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | يحدد قيمة تباعد علامات الفواصل التلقائية. إذا كان false: استخدم خاصية TickLabelSpacing. قراءة **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | يحدد قيمة تباعد علامات الفواصل التلقائية. إذا كان false: استخدم خاصية TickMarksSpacing. قراءة **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | يحدد قيمة الحاوية الناقصة التلقائية. إذا كان false: استخدم خاصية UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | يمثل ما إذا كان نوع مقياس محور القيم لوجاريتميًا أم لا. قراءة **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قراءة **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | يحدد ما إذا تم تطبيق حاوية الزائدة. استخدم IsAutomaticOverflowBin و OverflowBin لتعديل قيمة الحاوية الزائدة. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | يمثل ما إذا كانت PowerPoint ترسم نقاط البيانات من الأخير إلى الأول. قراءة **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | يحدد ما إذا تم تطبيق حاوية النقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لتعديل قيمة الحاوية الناقصة. |
| **bool** [get_IsVisible](./get_isvisible/)() override | يمثل ما إذا كان المحور مرئيًا. قراءة **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | يحدد المسافة بين التسميات والمحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%. قراءة **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | يمثل الأساس اللوغاريتمي. القيمة الافتراضية هي 10. قراءة **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | يمثل تنسيق خطوط الشبكة الرئيسية على محور المخطط. قراءة فقط [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | يمثل نوع علامة الفاصل الرئيسية للمحور المحدد. قراءة [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | يمثل الوحدات الرئيسية للمحور الزمني أو محور القيم. قراءة **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | يمثل مقياس الوحدة الرئيسية للمحور الزمني. قراءة [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | يمثل القيمة العظمى على محور القيم. قراءة **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | يمثل تنسيق خطوط الشبكة الصغرى على محور المخطط. قراءة فقط [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | يمثل نوع علامة الفاصل الصغرى للمحور المحدد. قراءة [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | يمثل الوحدات الصغرى للمحور الزمني أو محور القيم. قراءة **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | يمثل مقياس الوحدة الرئيسية للمحور الزمني. قراءة [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | يمثل القيمة الصغرى على محور القيم. قراءة **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | يمثل سلسلة التنسيق لتسميات [Axis](./). قراءة [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | يحدد قيمة مخصصة للحاوية الزائدة. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin تساوي true. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | يمثل موضع المحور. قراءة [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | لإخفاء خط الشبكة الرئيسي اضبط [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() إلى [FillType::NoFill](../../aspose.slides/filltype/). قراءة فقط **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | لإخفاء خط الشبكة الصغرى اضبط [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() إلى [FillType::NoFill](../../aspose.slides/filltype/). قراءة فقط **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | يمثل تنسيق النص. قراءة فقط [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | يمثل موضع تسميات علامات الفاصل على المحور المحدد. قراءة [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | يمثل زاوية دوران تسميات الفواصل. قراءة **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | يحدد عدد تسميات الفواصل التي يتم تخطيها بين التسميات المرسومة. يُطبق على محور الفئة أو السلسلة. قراءة **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | يحدد عدد علامات الفواصل التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. قراءة **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | يحصل على عنوان المحور. قراءة فقط [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | يحدد قيمة مخصصة للحاوية الناقصة. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin تساوي true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبطة بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | تناظر لطريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. تناظر لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. تناظر لمعامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفذ قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | تناظر لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخ. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجعية. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن مرجعيًا كائن نوع القيمة مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ينقص عداد المرجع المشترك بالقيمة المحددة. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | يمثل نوع التجميع لمحور الفئة (التجميع). يُطبق على الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. هذه الخاصية تنطبق فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. اكتب **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. اكتب [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على [AxisAggregationType::ByBinWidth](../axisaggregationtype/). يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | يحدد نوع محور الفئة. اكتب [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | يمثل النقطة على المحور حيث يعبر المحور العمودي عليه. اكتب **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | يمثل نوع التقاطع على المحور المحدد حيث يعبر المحور الآخر. اكتب [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | يحدد قيمة المقياس لوحدات العرض للمحور القيمي. اكتب [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | يحدد ما إذا كان للمحور عنوان مرئي. اكتب **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. اكتب **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | يشير إلى ما إذا كانت القيمة العظمى تُعيّن تلقائيًا. اكتب **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | يشير إلى ما إذا كانت الوحدة الصغرى للمحور تُعيّن تلقائيًا. اكتب **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | يشير إلى ما إذا كانت القيمة الصغرى تُعيّن تلقائيًا. اكتب **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | يحدد قيمة الحاوية الزائدة التلقائية. إذا كان false: استخدم خاصية OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | يحدد قيمة تباعد علامات الفواصل التلقائية. إذا كان false: استخدم خاصية TickLabelSpacing. اكتب **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | يحدد قيمة تباعد علامات الفواصل التلقائية. إذا كان false: استخدم خاصية TickMarksSpacing. اكتب **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | يحدد قيمة الحاوية الناقصة التلقائية. إذا كان false: استخدم خاصية UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | يمثل ما إذا كان نوع مقياس محور القيم لوجاريتميًا أم لا. اكتب **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. اكتب **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | يحدد ما إذا تم تطبيق حاوية الزائدة. استخدم IsAutomaticOverflowBin و OverflowBin لتعديل قيمة الحاوية الزائدة. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | يمثل ما إذا كانت PowerPoint ترسم نقاط البيانات من الأخير إلى الأول. اكتب **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | يحدد ما إذا تم تطبيق حاوية النقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لتعديل قيمة الحاوية الناقصة. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | يمثل ما إذا كان المحور مرئيًا. اكتب **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | يحدد المسافة بين التسميات والمحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%. اكتب **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | يمثل الأساس اللوغاريتمي. القيمة الافتراضية هي 10. اكتب **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | يمثل نوع علامة الفاصل الرئيسية للمحور المحدد. اكتب [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | يمثل الوحدات الرئيسية للمحور الزمني أو القيمي. اكتب **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | يمثل مقياس الوحدة الرئيسية للمحور الزمني. اكتب [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | يمثل القيمة العظمى على محور القيم. اكتب **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | يمثل نوع علامة الفاصل الصغرى للمحور المحدد. اكتب [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | يمثل الوحدات الصغرى للمحور الزمني أو القيمي. اكتب **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | يمثل مقياس الوحدة الرئيسية للمحور الزمني. اكتب [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | يمثل القيمة الصغرى على محور القيم. اكتب **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | يمثل سلسلة التنسيق لتسميات [Axis](./). اكتب [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | يحدد قيمة مخصصة للحاوية الزائدة. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin تساوي true. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | يمثل موضع المحور. اكتب [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | يمثل موضع تسميات علامات الفاصل على المحور المحدد. اكتب [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | يمثل زاوية دوران تسميات الفواصل. اكتب **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | يحدد عدد تسميات الفواصل التي يتم تخطيها بين التسميات المرسومة. يُطبق على محور الفئة أو السلسلة. اكتب **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | يحدد عدد علامات الفواصل التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. اكتب **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | يحدد قيمة مخصصة للحاوية الناقصة. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin تساوي true. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | يضبط خاصية IAxis::get(set)_CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | يضبط الوسيط النموذجي n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ينقص ويعيد عداد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | تناظر لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة نصية. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفذ إلغاء قفل عبارة C# lock(). استدعِ مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ينقص عداد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم مؤشرات ذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع بنى البيانات الداخلية. |

## انظر أيضًا

* الفئة [DomObject](../../aspose.slides/domobject/)
* الفئة [IAxis](../iaxis/)
* النطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)