---
title: IAxis
second_title: مرجع واجهة برمجة التطبيقات لـ Aspose.Sildes للـ .NET
description: يُغلف الكائن الذي يمثل محور المخطط.
type: docs
weight: 1710
url: /ar/aspose.slides.charts/iaxis/
---
## IAxis واجهة

يُغلف الكائن الذي يمثل محور المخطط.

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
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | يمثل نوع التجميع لمحور الفئة (التقسيم إلى مجموعات). يُطبق على الفئات. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | يسمح بالحصول على الواجهة الأساسية IFormattedTextContainer. للقراءة فقط [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئات، ولا تنطبق على المخططات ثلاثية الأبعاد. قراءة/كتابة Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | يحدد أصغر وحدة زمنية يتم تمثيلها على محور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | يحدد نوع محور الفئة. قراءة/كتابة [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | يمثل النقطة على المحور حيث يعبر المحور العمودي عليه. قراءة/كتابة Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | يمثل نوع CrossType على المحور المحدد حيث يعبر المحور الآخر. قراءة/كتابة [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | يحدد قيمة التحجيم لوحدات العرض لمحور القيم. قراءة/كتابة [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | يمثل تنسيق المحور. للقراءة فقط [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | يحدد ما إذا كان للمحور عنوان مرئي. قراءة/كتابة Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُحدد تلقائيًا. قراءة/كتابة Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | يشير إلى ما إذا كانت القيمة القصوى تُحدد تلقائيًا. قراءة/كتابة Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | يشير إلى ما إذا كانت الوحدة الفرعية للمحور تُحدد تلقائيًا. قراءة/كتابة Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | يشير إلى ما إذا كانت القيمة الدنيا تُحدد تلقائيًا. قراءة/كتابة Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | يحدد قيمة حاوية الفائض التلقائية. إذا كان false: استخدم خاصية OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | يحدد قيمة تباعد تسميات العلامات التلقائية. إذا كان false: استخدم خاصية TickLabelSpacing. قراءة/كتابة Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | يحدد قيمة تباعد علامات العلامات التلقائية. إذا كان false: استخدم خاصية TickMarksSpacing. قراءة/كتابة Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | يحدد قيمة حاوية النقص التلقائية. إذا كان false: استخدم خاصية UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قراءة/كتابة Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قراءة/كتابة Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | يحدد ما إذا تم تطبيق حاوية الفائض. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة حاوية الفائض. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قراءة/كتابة Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | يحدد ما إذا تم تطبيق حاوية النقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة حاوية النقص. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | يمثل ما إذا كان المحور مرئيًا. قراءة/كتابة Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | يحدد مسافة التسميات من المحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%. قراءة/كتابة UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | يمثل الأساس اللوغاريتمي. القيمة الافتراضية هي 10. قراءة/كتابة Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | يمثل تنسيق خطوط الشبكة الرئيسية على محور المخطط. للقراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | يمثل نوع علامة التجزئة الرئيسية للمحور المحدد. قراءة/كتابة [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. قراءة/كتابة Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | يمثل القيمة القصوى على محور القيم. قراءة/كتابة Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | يمثل تنسيق خطوط الشبكة الفرعية على محور المخطط. للقراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | يمثل نوع علامة التجزئة الفرعية للمحور المحدد. قراءة/كتابة [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | يمثل الوحدات الفرعية لمحور التاريخ أو القيمة. قراءة/كتابة Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | يمثل القيمة الدنيا على محور القيم. قراءة/كتابة Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | يمثل سلسلة التنسيق لتسميات المحور. قراءة/كتابة String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | يحدد قيمة مخصصة لحاوية الفائض. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin تساوي true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | يمثل موضع المحور. قراءة/كتابة [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | يمثل ما إذا كانت خطوط الشبكة الرئيسية معروضة. للقراءة فقط Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | يمثل ما إذا كانت خطوط الشبكة الفرعية معروضة. للقراءة فقط Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | يمثل موضع تسميات علامات التجزئة على المحور المحدد. قراءة/كتابة [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | يمثل زاوية دوران تسميات العلامات. قراءة/كتابة Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | يحدد عدد تسميات العلامات التي ينبغي تخطيها بين العلامة المرسومة. قراءة/كتابة UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | يحدد عدد علامات التجزئة التي ينبغي تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. قراءة/كتابة UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | يحصل على عنوان المحور. للقراءة فقط [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | يحدد قيمة مخصصة لحاوية النقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin تساوي true. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | يضبط خاصية IAxis.CategoryAxisType بقيمة تُحدد تلقائيًا استنادًا إلى بيانات المحور. |

### انظر أيضًا

* واجهة [IFormattedTextContainer](../iformattedtextcontainer)
* مساحة الأسماء [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->