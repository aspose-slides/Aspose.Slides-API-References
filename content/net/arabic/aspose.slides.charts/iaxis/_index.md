---
title: IAxis
second_title: مرجع API Aspose.Sildes لـ .NET
description: يغلف الكائن الذي يمثل محور المخطط.
type: docs
weight: 1710
url: /ar/aspose.slides.charts/iaxis/
---
## IAxis واجهة

يغلف الكائن الذي يمثل محور المخطط.

```csharp
public interface IAxis : IFormattedTextContainer
```

## الخصائص

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | يحدد القيمة العظمى الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | يحدد الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | يحدد مقياس الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | يحدد القيمة الصغرى الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | يمثل نوع التجميع لمحور الفئة (التجميع). يُطبق على الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | يسمح بالحصول على واجهة IFormattedTextContainer الأساسية. قراءة فقط [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | يمثل ما إذا كان محور القيمة يتقاطع مع محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قراءة/كتابة منطقية. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | يحدد عرض الحاوية عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | يحدد نوع محور الفئة. قراءة/كتابة [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | يمثل النقطة على المحور التي يتقاطع معها المحور العمودي. قراءة/كتابة من النوع Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | يمثل CrossType على المحور المحدد حيث يتقاطع المحور الآخر. قراءة/كتابة [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | يحدد قيمة التحجيم لوحدات العرض لمحور القيمة. قراءة/كتابة [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | يمثل تنسيق المحور. قراءة فقط [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | يحدد ما إذا كان للمحور عنوان واضح. قراءة/كتابة منطقية. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعين تلقائيًا. قراءة/كتابة منطقية. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | يشير إلى ما إذا كانت القيمة العظمى تُعين تلقائيًا. قراءة/كتابة منطقية. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | يشير إلى ما إذا كانت الوحدة الصغرى للمحور تُعين تلقائيًا. قراءة/كتابة منطقية. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | يشير إلى ما إذا كانت القيمة الصغرى تُعين تلقائيًا. قراءة/كتابة منطقية. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | يحدد قيمة حاوية الفائض التلقائية. إذا كانت false: استخدم خاصية OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | يحدد قيمة تباعد تسميات العلامات التلقائي. إذا كانت false: استخدم خاصية TickLabelSpacing. قراءة/كتابة منطقية. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | يحدد قيمة تباعد علامات العلامات التلقائي. إذا كانت false: استخدم خاصية TickMarksSpacing. قراءة/كتابة منطقية. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | يحدد قيمة حاوية الانخفاض التلقائية. إذا كانت false: استخدم خاصية UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | يمثل ما إذا كان نوع مقياس محور القيمة لوغاريتميًا أم لا. قراءة/كتابة منطقية. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قراءة/كتابة منطقية. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | يحدد ما إذا تم تطبيق حاوية الفائض. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة حاوية الفائض. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قراءة/كتابة منطقية. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | يحدد ما إذا تم تطبيق حاوية الانخفاض. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة حاوية الانخفاض. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | يمثل ما إذا كان المحور مرئيًا. قراءة/كتابة منطقية. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | يحدد مسافة التسميات عن المحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%. قراءة/كتابة من النوع UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | يمثل الأساس اللوغاريتمي. القيمة الافتراضية هي 10. قراءة/كتابة من النوع Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | يمثل تنسيق خطوط الشبكة الرئيسية على محور المخطط. قراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | يمثل نوع علامة العلامة الرئيسية للمحور المحدد. قراءة/كتابة [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. قراءة/كتابة من النوع Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | يمثل القيمة العظمى على محور القيمة. قراءة/كتابة من النوع Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | يمثل تنسيق خطوط الشبكة الصغرى على محور المخطط. قراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | يمثل نوع علامة العلامة الصغرى للمحور المحدد. قراءة/كتابة [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | يمثل الوحدات الصغرى لمحور التاريخ أو القيمة. قراءة/كتابة من النوع Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قراءة/كتابة [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | يمثل القيمة الصغرى على محور القيمة. قراءة/كتابة من النوع Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | يمثل سلسلة التنسيق لتسميات المحور. قراءة/كتابة من النوع String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | يحدد عدد الحاويات عندما تكون قيمة خاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | يحدد قيمة مخصصة لحاوية الفائض. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة على false وتكون خاصية IsOverflowBin مساوية لـ true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | يمثل موضع المحور. قراءة/كتابة [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | يمثل ما إذا كانت خطوط الشبكة الرئيسية معروضة. قراءة فقط منطقية. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | يمثل ما إذا كانت خطوط الشبكة الصغرى معروضة. قراءة فقط منطقية. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | يمثل موضع تسميات العلامات على المحور المحدد. قراءة/كتابة [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | يمثل زاوية دوران تسميات العلامات. قراءة/كتابة من النوع Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | يحدد عدد تسميات العلامات التي يجب تخطيها بين التسميات المرسومة. قراءة/كتابة من النوع UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | يحدد عدد علامات العلامات التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. قراءة/كتابة من النوع UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | يحصل على عنوان المحور. قراءة فقط [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | يحدد قيمة مخصصة لحاوية الانخفاض. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة على false وتكون خاصية IsUnderflowBin مساوية لـ true. |

## الأساليب

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور. |

### انظر أيضًا

* الواجهة [IFormattedTextContainer](../iformattedtextcontainer)
* النطاق [Aspose.Slides.Charts](../../aspose.slides.charts)
* المجموعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->