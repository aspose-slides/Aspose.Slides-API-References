---
title: Axis
second_title: مرجع API لـ Aspose.Sildes for .NET
description: يُغلف الكائن الذي يمثل محور المخطط.
type: docs
weight: 1180
url: /ar/aspose.slides.charts/axis/
---
## Axis فئة

يُغلف الكائن الذي يمثل محور المخطط.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | يحدد القيمة العظمى الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | يحدد الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | يحدد مقياس الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | يحدد القيمة الدنيا الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | يمثل نوع التجميع لمحور الفئة (التقسيم إلى صناديق). يُطبق على الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | يمثل ما إذا كان محور القيم يعبر محور الفئة بين الفئات. هذه الخاصية تنطبق فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قابل للقراءة/الكتابة Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. قابل للقراءة/الكتابة [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | يحدد عرض الصندوق عندما تكون قيمة الخاصية AggregationType مضبوطة على AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | يحدد نوع محور الفئة. قابل للقراءة/الكتابة [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | يرجع المخطط الأصل. للقراءة فقط [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | يمثل النقطة على المحور حيث يعبر المحور العمودي ذلك. قابل للقراءة/الكتابة Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | يمثل نوع التقاطع (CrossType) على المحور المحدد حيث يعبر المحور الآخر. قابل للقراءة/الكتابة [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | يحدد قيمة التحجيم لوحدات العرض لمحور القيم. قابل للقراءة/الكتابة [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | يمثل تنسيق المحور. للقراءة فقط [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | يحدد ما إذا كان للمحور عنوان مرئي. قابل للقراءة/الكتابة Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | يشير إلى ما إذا كانت الوحدة الرئيسية للمحور تُعين تلقائيًا. قابل للقراءة/الكتابة Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | يشير إلى ما إذا كانت القيمة العظمى تُعين تلقائيًا. قابل للقراءة/الكتابة Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | يشير إلى ما إذا كانت الوحدة الصغرى للمحور تُعين تلقائيًا. قابل للقراءة/الكتابة Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | يشير إلى ما إذا كانت القيمة الدنيا تُعين تلقائيًا. قابل للقراءة/الكتابة Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | يحدد قيمة الصندوق الزائد التلقائي. إذا كان false: استخدم الخاصية OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | يحدد قيمة التباعد التلقائي لتسميات العلامات. إذا كان false: استخدم الخاصية TickLabelSpacing. قابل للقراءة/الكتابة Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | يحدد قيمة التباعد التلقائي لعلامات الفواصل. إذا كان false: استخدم الخاصية TickMarksSpacing. قابل للقراءة/الكتابة Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | يحدد قيمة الصندوق الناقص التلقائي. إذا كان false: استخدم الخاصية UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | يمثل ما إذا كان نوع مقياس محور القيم لوغاريتميًا أم لا. قابل للقراءة/الكتابة Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | يشير إلى ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قابل للقراءة/الكتابة Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | يحدد ما إذا تم تطبيق الصندوق الزائد. استخدم IsAutomaticOverflowBin وOverflowBin لضبط قيمة الصندوق الزائد. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قابل للقراءة/الكتابة Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | يحدد ما إذا تم تطبيق الصندوق الناقص. استخدم IsAutomaticUnderflowBin وUnderflowBin لضبط قيمة الصندوق الناقص. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | يمثل ما إذا كان المحور مرئيًا. قابل للقراءة/الكتابة Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | يحدد مسافة التسميات من المحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و1000%. قابل للقراءة/الكتابة UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قابل للقراءة/الكتابة Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | يمثل تنسيق الخطوط الرئيسية للشبكة على محور المخطط. للقراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | يمثل نوع العلامة الفاصلة الرئيسية للمحور المحدد. قابل للقراءة/الكتابة [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. قابل للقراءة/الكتابة Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة/الكتابة [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | يمثل القيمة القصوى على محور القيمة. قابل للقراءة/الكتابة Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | يمثل تنسيق الخطوط الصغرى للشبكة على محور المخطط. للقراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | يمثل نوع العلامة الفاصلة الصغرى للمحور المحدد. قابل للقراءة/الكتابة [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | يمثل الوحدات الصغرى لمحور التاريخ أو القيمة. قابل للقراءة/الكتابة Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة/الكتابة [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | يمثل القيمة الدنيا على محور القيمة. قابل للقراءة/الكتابة Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | يمثل سلسلة التنسيق لتسميات المحور. قابل للقراءة/الكتابة String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | يحدد عدد الصناديق عندما تكون قيمة الخاصية AggregationType مضبوطة على AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | يحدد قيمة مخصصة للصندوق الزائد. يُطبق عندما تكون الخاصية IsAutomaticOverflowBin مضبوطة على false وتكون الخاصية IsOverflowBin true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | يمثل موضع المحور. قابل للقراءة/الكتابة [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | لإخفاء الخط الرئيسي للشبكة اضبط MajorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. للقراءة فقط Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | لإخفاء الخط الصغير للشبكة اضبط MinorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. للقراءة فقط Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | يمثل تنسيق النص. للقراءة فقط [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | يمثل موضع تسميات العلامات على المحور المحدد. قابل للقراءة/الكتابة [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | يمثل زاوية دوران تسميات العلامات. قابل للقراءة/الكتابة Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | يحدد عدد تسميات العلامات التي يتم تخطيها بين كل تسمية يتم رسمها. يُطبق على محور الفئة أو السلسلة. قابل للقراءة/الكتابة UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | يحدد عدد علامات الفواصل التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. قابل للقراءة/الكتابة UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | يحصل على عنوان المحور. للقراءة فقط [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | يحدد قيمة مخصصة للصندوق الناقص. يُطبق عندما تكون الخاصية IsAutomaticUnderflowBin مضبوطة على false وتكون الخاصية IsUnderflowBin true. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور. |

### انظر أيضًا

* فئة [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* فئة [AxesManager](../axesmanager)
* واجهة [IAxis](../iaxis)
* مساحة أسماء [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->