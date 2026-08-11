---
title: IAxis
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحتوي على الكائن الذي يمثل محور الرسم البياني.
type: docs
weight: 534
url: /ar/aspose.slides.charts/iaxis/
---
## فئة IAxis

يحتوي على الكائن الذي يمثل محور المخطط.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعتبر NaNين متساويين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة الأعداد العائمة بأسلوب C# حيث يُعتبر NaNين متساويين على الرغم من أن معيار IEC 60559:1989 يوضح أن NaN لا يساوي أي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | للأغراض الداخلية فقط. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | يحدد القيمة القصوى الفعلية على المحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | يحدد الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | يحدد مقياس الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | يحدد القيمة الدنيا الفعلية على المحور. استدعِ الطريقة [IChart::ValidateChartLayout](../ichart/validatechartlayout/) مسبقًا للحصول على القيمة الفعلية. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | يمثل نوع التجميع لمحور الفئة (التجميع). يُطبق على الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على الرسوم البيانية ثلاثية الأبعاد. قراءة **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. قراءة [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | يحدد عرض الفئة عندما تكون قيمة خاصية AggregationType مضبوطة على [AxisAggregationType::ByBinWidth](../axisaggregationtype/). يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | يحدد نوع محور الفئة. قراءة [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | يرجع الرسم البياني. للقراءة فقط [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | يمثل النقطة على المحور حيث يعبر المحور المتعامد عليه. قراءة **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | يمثل CrossType على المحور المحدد حيث يعبر المحور الآخر. قراءة [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | يحدد قيمة التحجيم لوحدات العرض لمحور القيم. قراءة [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | يمثل تنسيق المحور. للقراءة فقط [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | يحدد ما إذا كان للمحور عنوان مرئي. قراءة **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | يشير ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. قراءة **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | يشير ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. قراءة **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | يشير ما إذا كانت الوحدة الصغرى للمحور تُعيّن تلقائيًا. قراءة **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | يشير ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا. قراءة **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | يحدد قيمة الصندوق الزائد التلقائي. إذا كان false: استخدم خاصية OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | يحدد قيمة التباعد التلقائي لتسميات العلامات. إذا كان false: استخدم خاصية TickLabelSpacing. قراءة **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | يحدد قيمة التباعد التلقائي للعلامات. إذا كان false: استخدم خاصية TickMarksSpacing. قراءة **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | يحدد قيمة الصندوق الناقص التلقائي. إذا كان false: استخدم خاصية UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قراءة **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | يشير ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قراءة **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | يحدد ما إذا تم تطبيق الصندوق الزائد. استخدم IsAutomaticOverflowBin وOverflowBin لضبط قيمة الصندوق الزائد. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قراءة **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | يحدد ما إذا تم تطبيق الصندوق الناقص. استخدم IsAutomaticUnderflowBin وUnderflowBin لضبط قيمة الصندوق الناقص. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | يمثل ما إذا كان المحور مرئيًا. قراءة **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | يحدد مسافة التسميات عن المحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و1000%. قراءة **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قراءة **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | يمثل تنسيق خطوط الشبكة الرئيسية على محور الرسم البياني. للقراءة فقط [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | يمثل نوع العلامة الرئيسية للمحور المحدد. قراءة [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | يمثل الوحدات الرئيسية للمحور الزمني أو محور القيم. قراءة **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | يمثل القيمة القصوى على محور القيم. قراءة **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | يمثل تنسيق خطوط الشبكة الصغرى على محور الرسم البياني. للقراءة فقط [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | يمثل نوع العلامة الصغرى للمحور المحدد. قراءة [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | يمثل الوحدات الصغرى للمحور الزمني أو محور القيم. قراءة **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | يمثل القيمة الدنيا على محور القيم. قراءة **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | يمثل سلسلة التنسيق لتسميات [Axis](../axis/). قراءة [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | يحدد قيمة مخصصة للصندوق الزائد. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | يمثل موقع المحور. قراءة [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | يرجع العرض التقديمي. للقراءة فقط [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | يمثل ما إذا كانت خطوط الشبكة الرئيسية معروضة. للقراءة فقط **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | يمثل ما إذا كانت خطوط الشبكة الصغرى معروضة. للقراءة فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | يرجع الشريحة الأساسية. للقراءة فقط [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | يرجع تنسيق نص الرسم البياني. للقراءة فقط [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | يمثل موقع تسميات علامات التحديد على المحور المحدد. قراءة [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | يمثل زاوية دوران تسميات العلامات. قراءة **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | يحدد عدد تسميات العلامات التي يجب تخطيها بين التسميات المرسومة. قراءة **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | يحدد عدد علامات التحديد التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. قراءة **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | يحصل على عنوان المحور. للقراءة فقط [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | يحدد قيمة مخصصة للصندوق الناقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نسخة من طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). تمكّن تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نسخة من استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يفحص ما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نسخة من عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | ينفّذ قفل تعبير C# lock(). استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نسخة من طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). تمكّن استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع بنى البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ النسخ. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويسمح بإنشاء نسخ من الفئات الفرعية. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عدّاد المرجع المشترك بالقيمة المحددة. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | يمثل نوع التجميع لمحور الفئة (التجميع). يُطبق على الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على الرسوم البيانية ثلاثية الأبعاد. كتابة **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. كتابة [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | يحدد عرض الفئة عندما تكون قيمة خاصية AggregationType مضبوطة على [AxisAggregationType::ByBinWidth](../axisaggregationtype/). يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | يحدد نوع محور الفئة. كتابة [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | يمثل النقطة على المحور حيث يعبر المحور المتعامد عليه. كتابة **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | يمثل CrossType على المحور المحدد حيث يعبر المحور الآخر. كتابة [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | يحدد قيمة التحجيم لوحدات العرض لمحور القيم. كتابة [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | يحدد ما إذا كان للمحور عنوان مرئي. كتابة **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | يشير ما إذا كانت الوحدة الرئيسية للمحور تُعيّن تلقائيًا. كتابة **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | يشير ما إذا كانت القيمة القصوى تُعيّن تلقائيًا. كتابة **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | يشير ما إذا كانت الوحدة الصغرى للمحور تُعيّن تلقائيًا. كتابة **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | يشير ما إذا كانت القيمة الدنيا تُعيّن تلقائيًا. كتابة **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | يحدد قيمة الصندوق الزائد التلقائي. إذا كان false: استخدم خاصية OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | يحدد قيمة التباعد التلقائي لتسميات العلامات. إذا كان false: استخدم خاصية TickLabelSpacing. كتابة **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | يحدد قيمة التباعد التلقائي للعلامات. إذا كان false: استخدم خاصية TickMarksSpacing. كتابة **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | يحدد قيمة الصندوق الناقص التلقائي. إذا كان false: استخدم خاصية UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. كتابة **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | يشير ما إذا كان التنسيق مرتبطًا ببيانات المصدر. كتابة **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | يحدد ما إذا تم تطبيق الصندوق الزائد. استخدم IsAutomaticOverflowBin وOverflowBin لضبط قيمة الصندوق الزائد. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. كتابة **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | يحدد ما إذا تم تطبيق الصندوق الناقص. استخدم IsAutomaticUnderflowBin وUnderflowBin لضبط قيمة الصندوق الناقص. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | يمثل ما إذا كان المحور مرئيًا. كتابة **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | يحدد مسافة التسميات عن المحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و1000%. كتابة **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. كتابة **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | يمثل نوع العلامة الرئيسية للمحور المحدد. كتابة [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | يمثل الوحدات الرئيسية للمحور الزمني أو محور القيم. كتابة **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. كتابة [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | يمثل القيمة القصوى على محور القيم. كتابة **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | يمثل نوع العلامة الصغرى للمحور المحدد. كتابة [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | يمثل الوحدات الصغرى للمحور الزمني أو محور القيم. كتابة **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. كتابة [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | يمثل القيمة الدنيا على محور القيم. كتابة **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | يمثل سلسلة التنسيق لتسميات [Axis](../axis/). كتابة [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة على [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | يحدد قيمة مخصصة للصندوق الزائد. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | يمثل موقع المحور. كتابة [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | يمثل موقع تسميات علامات التحديد على المحور المحدد. كتابة [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | يمثل زاوية دوران تسميات العلامات. كتابة **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | يحدد عدد تسميات العلامات التي يجب تخطيها بين التسميات المرسومة. كتابة **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | يحدد عدد علامات التحديد التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. كتابة **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | يحدد قيمة مخصصة للصندوق الناقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | يضبط خاصية IAxis::get(set)_CategoryAxisType بقيمة تُحدد تلقائيًا بناءً على بيانات المحور. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يعيّن الوسيط القالب n كإشارة ضعيفة (بدلاً من مشتركة). يسمح بتبديل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عدّاد المرجع المشترك. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نسخة من طريقة C# [Object.ToString()](../../system/object/tostring/). تمكّن تحويل الكائنات المخصصة إلى نص. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ينفّذ بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ينفّذ قفل تعبير C# lock() لإلغاء القفل. استدعِ مباشرة أو استخدم كائن الحراسة [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عدّاد المرجع الضعيف. لا ينبغي استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يحذف الكائن. يحرّر جميع بنى البيانات الداخلية. |
## أنظر أيضًا

* فئة [IFormattedTextContainer](../iformattedtextcontainer/)
* نطاق [Aspose::Slides::Charts](../)
* مكتبة [Aspose.Slides](../../)