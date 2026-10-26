---
title: Axis
second_title: Aspose.Sildes لـ .NET مرجع API
description: يُجسد الكائن الذي يمثل محور الرسم البياني.
type: docs
weight: 1180
url: /ar/aspose.slides.charts/axis/
---
## Axis فئة

يُجسد الكائن الذي يمثل محور الرسم البياني.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | يحدد الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | يحدد مقياس الوحدة الرئيسية الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | يحدد القيمة القصوى الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | يحدد الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | يحدد مقياس الوحدة الصغرى الفعلية للمحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | يحدد القيمة الدنيا الفعلية على المحور. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيمة الفعلية. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | يمثل نوع التجميع للمحور الفئوي (التجميع). يُطبق على الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | يمثل ما إذا كان محور القيمة يقطع محور الفئة بين الفئات. تنطبق هذه الخاصية فقط على محاور الفئة، ولا تنطبق على المخططات ثلاثية الأبعاد. قابل للقراءة والكتابة Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | يحدد أصغر وحدة زمنية ممثلة على محور التاريخ. قابل للقراءة والكتابة [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | يحدد عرض الصندوق عندما تكون قيمة خاصية AggregationType مُضبوطة إلى AxisAggregationType.ByBinWidth. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | يحدد نوع محور الفئة. قابل للقراءة والكتابة [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | يرجع المخطط الأب. للقراءة فقط [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | يمثل النقطة على المحور التي يقطعها المحور المتعامد. قابل للقراءة والكتابة Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | يمثل CrossType على المحور المحدد حيث يقطعه المحور الآخر. قابل للقراءة والكتابة [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | يحدد قيمة التحجيم لوحدات العرض لمحور القيمة. قابل للقراءة والكتابة [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | يمثل تنسيق المحور. للقراءة فقط [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | يحدد ما إذا كان للمحور عنوان مرئي. قابل للقراءة والكتابة Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | يظهر ما إذا تم تعيين الوحدة الرئيسية للمحور تلقائيًا. قابل للقراءة والكتابة Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | يظهر ما إذا تم تعيين القيمة القصوى تلقائيًا. قابل للقراءة والكتابة Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | يظهر ما إذا تم تعيين الوحدة الصغرى للمحور تلقائيًا. قابل للقراءة والكتابة Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | يظهر ما إذا تم تعيين القيمة الدنيا تلقائيًا. قابل للقراءة والكتابة Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | يحدد قيمة الصندوق الزائد التلقائي. إذا كان false: استخدم خاصية OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | يحدد قيمة تباعد تسميات العلامات التلقائي. إذا كان false: استخدم خاصية TickLabelSpacing. قابل للقراءة والكتابة Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | يحدد قيمة تباعد علامات التوقيت التلقائي. إذا كان false: استخدم خاصية TickMarksSpacing. قابل للقراءة والكتابة Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | يحدد قيمة الصندوق الناقص التلقائي. إذا كان false: استخدم خاصية UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | يمثل ما إذا كان نوع مقياس محور القيمة لوغاريتميًا أم لا. قابل للقراءة والكتابة Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | يظهر ما إذا كان التنسيق مرتبطًا ببيانات المصدر. قابل للقراءة والكتابة Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | يحدد ما إذا تم تطبيق الصندوق الزائد. استخدم IsAutomaticOverflowBin و OverflowBin لضبط قيمة الصندوق الزائد. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | يمثل ما إذا كان MS PowerPoint يرسم نقاط البيانات من الأخير إلى الأول. قابل للقراءة والكتابة Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | يحدد ما إذا تم تطبيق الصندوق الناقص. استخدم IsAutomaticUnderflowBin و UnderflowBin لضبط قيمة الصندوق الناقص. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | يمثل ما إذا كان المحور مرئيًا. قابل للقراءة والكتابة Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | يحدد مسافة التسميات عن المحور. يُطبق على محور الفئة أو التاريخ. يجب أن تكون القيمة بين 0% و 1000%. قابل للقراءة والكتابة UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | يمثل القاعدة اللوغاريتمية. القيمة الافتراضية هي 10. قابل للقراءة والكتابة Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | يمثل تنسيق الخطوط الرئيسية للشبكة على محور مخطط. للقراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | يمثل نوع علامة التوقيت الرئيسية للمحور المحدد. قابل للقراءة والكتابة [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | يمثل الوحدات الرئيسية لمحور التاريخ أو القيمة. قابل للقراءة والكتابة Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة والكتابة [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | يمثل القيمة القصوى على محور القيمة. قابل للقراءة والكتابة Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | يمثل تنسيق الخطوط الصغرى للشبكة على محور مخطط. للقراءة فقط [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | يمثل نوع علامة التوقيت الصغرى للمحور المحدد. قابل للقراءة والكتابة [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | يمثل الوحدات الصغرى لمحور التاريخ أو القيمة. قابل للقراءة والكتابة Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | يمثل مقياس الوحدة الرئيسية لمحور التاريخ. قابل للقراءة والكتابة [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | يمثل القيمة الدنيا على محور القيمة. قابل للقراءة والكتابة Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | يمثل سلسلة الصيغة لتسميات المحور. قابل للقراءة والكتابة String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | يحدد عدد الصناديق عندما تكون قيمة خاصية AggregationType مضبوطة إلى AxisAggregationType.ByNumberOfBins. يُطبق على محاور الفئة. يُستخدم مع سلسلة Histogram أو HistogramPareto فقط. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | يحدد قيمة مخصصة للصندوق الزائد. يُطبق عندما تكون خاصية IsAutomaticOverflowBin مضبوطة إلى false وتكون خاصية IsOverflowBin مساوية true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | يمثل موضع المحور. قابل للقراءة والكتابة [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | لإخفاء الخط الرئيسي للشبكة اضبط MajorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. للقراءة فقط Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | لإخفاء الخط الصغير للشبكة اضبط MinorGridLinesFormat.Line.FillFormat.FillType إلى FillType.NoFill. للقراءة فقط Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | يمثل تنسيق النص. للقراءة فقط [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | يمثل موضع تسميات علامات التوقيت على المحور المحدد. قابل للقراءة والكتابة [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | يمثل زاوية دوران تسميات العلامات. قابل للقراءة والكتابة Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | يحدد عدد تسميات العلامات التي يجب تخطيها بين كل تسمية مُرسومة. يُطبق على محور الفئة أو السلسلة. قابل للقراءة والكتابة UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | يحدد عدد علامات التوقيت التي يجب تخطيها قبل رسم العلامة التالية. يُطبق على محور الفئة أو السلسلة. قابل للقراءة والكتابة UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | يحصل على عنوان المحور. للقراءة فقط [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | يحدد قيمة مخصصة للصندوق الناقص. يُطبق عندما تكون خاصية IsAutomaticUnderflowBin مضبوطة إلى false وتكون خاصية IsUnderflowBin مساوية true. |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | يضبط خاصية IAxis.CategoryAxisType بقيمة يتم تحديدها تلقائيًا بناءً على بيانات المحور. |

### انظر أيضًا

* فئة [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* فئة [AxesManager](../axesmanager)
* واجهة [IAxis](../iaxis)
* مساحة اسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->