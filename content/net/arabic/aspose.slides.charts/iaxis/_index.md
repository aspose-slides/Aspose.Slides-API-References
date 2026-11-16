---
title: IAxis
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يغلف الكائن الذي يمثل محور المخطط.
type: docs
weight: 1720
url: /ar/aspose.slides.charts/iaxis/
---
## IAxis الواجهة

يغلف الكائن الذي يمثل محور المخطط.

```csharp
public interface IAxis : IFormattedTextContainer
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | يحدد القيمة القصوى الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | يحدد الوحدة الفرعية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | يحدد مقياس الوحدة الفرعية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | يحدد القيمة الدنيا الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | يمثل نوع التجميع لمحور الفئة (التجميع). يُطبق على الفئة. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | يتيح الحصول على واجهة IFormattedTextContainer الأساسية. للقراءة فقط [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | يحدد ما إذا كان محور القيمة يتقاطع مع محور الفئة بين الفئات. هذا الخصائص تنطبق فقط على محاور الفئات، ولا تنطبق على المخططات الثلاثية الأبعاد. منطقي قراءة/كتابة. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | يحدد أصغر وحدة زمنية تُعرض على محور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | يحدد عرض الصندوق عندما تكون قيمة الخاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | يحدد نوع محور الفئة. قراءة/كتابة [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | يمثل النقطة على المحور حيث يتقاطع المحور العمودي معه. قراءة/كتابة Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | يمثل CrossType على المحور المحدد حيث يتقاطع المحور الآخر. قراءة/كتابة [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | يحدد قيمة مقياس وحدات العرض للمحور القيمي. قراءة/كتابة [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | يمثل تنسيق المحور. للقراءة فقط [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | يحدد ما إذا كان للمحور عنوان مرئي. قراءة/كتابة منطقي. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُassign تلقائيًا. قراءة/كتابة منطقي. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | يشير إلى ما إذا كانت القيمة القصوى تُassign تلقائيًا. قراءة/كتابة منطقي. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُassign تلقائيًا. قراءة/كتابة منطقي. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | يشير إلى ما إذا كانت القيمة الدنيا تُassign تلقائيًا. قراءة/كتابة منطقي. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | يحدد قيمة الصندوق الزائد التلقائي. إذا كان false: استخدم الخاصية OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | يحدد قيمة تباعد تسميات العلامات التلقائية. إذا كان false: استخدم الخاصية TickLabelSpacing. قراءة/كتابة منطقي. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | يحدد قيمة تباعد العلامات التلقائية. إذا كان false: استخدم الخاصية TickMarksSpacing. قراءة/كتابة منطقي. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | يحدد قيمة الصندوق الناقص التلقائي. إذا كان false: استخدم الخاصية UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | يمثل ما إذا كان نوع مقياس محور القيمة لوغاريتميًا أم لا. قراءة/كتابة منطقي. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قراءة/كتابة منطقي. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | يحدد ما إذا كان الصندوق الزائد مُطبقًا. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة الصندوق الزائد. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | يمثل ما إذا كان PowerPoint يرسم نقاط البيانات من الأخيرة إلى الأولى. قراءة/كتابة منطقي. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | يحدد ما إذا كان الصندوق الناقص مُطبقًا. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة الصندوق الناقص. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | يمثل ما إذا كان المحور مرئيًا. قراءة/كتابة منطقي. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | يحدد مسافة التسميات من المحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%. قراءة/كتابة UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | يمثل الأساس اللوغاريتمي. القيمة الافتراضية هي 10. قراءة/كتابة Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | يمثل تنسيق الخطوط الشبكية الرئيسية على محور المخطط. للقراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | يمثل نوع العلامة الرئيسية للمحور المحدد. قراءة/كتابة [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. قراءة/كتابة Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | يمثل القيمة القصوى على محور القيمة. قراءة/كتابة Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | يمثل تنسيق الخطوط الشبكية الفرعية على محور المخطط. للقراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | يمثل نوع العلامة الفرعية للمحور المحدد. قراءة/كتابة [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | يمثل الوحدات الفرعية لمحور التاريخ أو القيمة. قراءة/كتابة Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | يمثل القيمة الدنيا على محور القيمة. قراءة/كتابة Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | يمثل سلسلة التنسيق لتسميات المحور. قراءة/كتابة String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | يحدد عدد الصناديق عندما تكون قيمة الخاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يُستخدم مع سلاسل Histogram أو HistogramPareto فقط. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | يحدد قيمة مخصصة للصندوق الزائد. يُطبق عندما تكون الخاصية IsAutomaticOverflowBin مضبوطة على false وتكون الخاصية IsOverflowBin تساوي true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | يمثل موقع المحور. قراءة/كتابة [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | يمثل ما إذا كانت الخطوط الشبكية الرئيسية معروضة. للقراءة فقط منطقي. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | يمثل ما إذا كانت الخطوط الشبكية الفرعية معروضة. للقراءة فقط منطقي. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | يمثل موقع تسميات العلامات على المحور المحدد. قراءة/كتابة [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | يمثل زاوية دوران تسميات العلامات. قراءة/كتابة Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | يحدد عدد تسميات العلامات التي تُهمل بين كل تسمية مرسومة. قراءة/كتابة UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | يحدد عدد العلامات التي تُهمل قبل رسم العلامة التالية. يُطبق على محاور الفئة أو السلسلة. قراءة/كتابة UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | يحصل على عنوان المحور. للقراءة فقط [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | يحدد قيمة مخصصة للصندوق الناقص. يُطبق عندما تكون الخاصية IsAutomaticUnderflowBin مضبوطة على false وتكون الخاصية IsUnderflowBin تساوي true. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | يضبط خاصية IAxis.CategoryAxisType بقيمة تُحدد تلقائيًا بناءً على بيانات المحور. |

### انظر أيضا

* الواجهة [IFormattedTextContainer](../iformattedtextcontainer)
* النطاق [Aspose.Slides.Charts](../../aspose.slides.charts)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->