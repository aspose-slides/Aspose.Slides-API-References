---
title: ChartSeriesGroup
second_title: مرجع API Aspose.Sildes لـ .NET
description: يمثل مجموعة من السلاسل.
type: docs
weight: 1460
url: /ar/aspose.slides.charts/chartseriesgroup/
---
## فئة ChartSeriesGroup

Represents group of series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قراءة/كتابة [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300٪ من الحجم الافتراضي). قراءة/كتابة Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | يرجع المخطط الأب. قراءة فقط [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 0 و 90٪ من حجم مساحة الرسم). قراءة/كتابة Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | يحصل أو يضبط زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | يرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة، كنسبة مئوية من عرض الشريط أو العمود. قراءة/كتابة UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأشرطة المتكدسة ومخططات OfPie. قراءة/كتابة Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | يحدد تنسيق HiLowLines. يتم تطبيق HiLowLines مع أنواع المخططات HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | يحصل على العنصر عند الفهرس المحدد. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). - -100٪: أقصى مسافة بين الأشرطة (الأشرطة منفصلة تمامًا). - 0٪: توضع الأشرطة جنبًا إلى جنب دون تداخل أو مسافة. - 100٪: أقصى تداخل (الأشرطة تتداخل تمامًا). هذه الخاصية قراءة/كتابة SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | يحدد طريقة تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. قراءة/كتابة [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | معلومات الانقسام المخصص لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. قراءة فقط [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع الخاصية PieSplitBy. قراءة/كتابة Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | يشير إلى ما إذا كانت سلسلة هذه المجموعة مرسومة على المحور الثانوي. قراءة فقط Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200٪). قراءة/كتابة UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | يرجع مجموعة من السلاسل. قراءة فقط [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | يرجع نوع هذه المجموعة من السلاسل. قراءة فقط [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | يوفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو مخطط السهم. قراءة فقط [`IUpDownBarsManager`](../iupdownbarsmanager). |

### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection وتعداد CombinableSeriesTypesGroup. 2) يحتوي مجموعة السلاسل على بعض خصائص السلسلة التي هي مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي قراءة/كتابة. يمكن لكل من "خصائص مجموعة السلسلة" أن يكون لها إسقاط قراءة فقط في فئة ChartSeries.

### انظر أيضًا

* واجهة [IChartSeriesGroup](../ichartseriesgroup)
* مساحة الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->