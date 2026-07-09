---
title: ChartSeriesGroup
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل مجموعة من السلاسل.
type: docs
weight: 1460
url: /ar/aspose.slides.charts/chartseriesgroup/
---
## فئة ChartSeriesGroup

يمثل مجموعة من السلاسل.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | تحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قراءة/كتابة [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | تحدد معامل التحجيم لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمئة من الحجم الافتراضي). قراءة/كتابة Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | يرجع المخطط الأب. قراءة فقط [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | تحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 0 و 90 بالمئة من حجم مساحة الرسم). قراءة/كتابة Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | تحصل أو تعين زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | يرجع أو يعين المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | تحدد المسافة بين مجموعات الأعمدة أو الشرائح، كنسبة مئوية من عرض العمود أو الشريط. قراءة/كتابة UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | صواب إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الأعمدة المتكدسة ومخططات OfPie. قراءة/كتابة Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | تحدد تنسيق HiLowLines. يتم تطبيق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | تحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | تحصل على العنصر عند الفهرس المحدد. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | تحدد مقدار تداخل الأعمدة والشرائح في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). - -100٪: أقصى مسافة (الأعمدة منفصلة تمامًا). - 0٪: توضع الأعمدة بجانب بعضها دون تداخل أو مسافة. - 100٪: أقصى تداخل (الأعمدة تتداخل تمامًا). هذه الخاصية قراءة/كتابة SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | تحدد كيفية تحديد نقاط البيانات التي تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. قراءة/كتابة [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | معلومات الانقسام المخصصة لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. قراءة فقط [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | تحدد قيمة تُستخدم لتحديد نقاط البيانات الموجودة في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع الخاصية PieSplitBy. قراءة/كتابة Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | تشير إلى ما إذا كانت سلاسل هذه المجموعة تُرسم على المحور الثانوي. قراءة فقط Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | تحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و 200 بالمئة). قراءة/كتابة UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | يرجع مجموعة من السلاسل. قراءة فقط [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | يرجع نوع هذه المجموعة من السلاسل. قراءة فقط [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | توفر وصولًا إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي. قراءة فقط [`IUpDownBarsManager`](../iupdownbarsmanager). |

### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection والعدد CombinableSeriesTypesGroup. 2) تحتوي مجموعة السلاسل على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). خصائص مجموعة السلسلة في فئة ChartSeriesGroup هي قراءة/كتابة. يمكن لكل من "خصائص مجموعة السلسلة" أن يكون لها تمثيل قراءة فقط في فئة ChartSeries.

### راجع أيضًا

* واجهة [IChartSeriesGroup](../ichartseriesgroup)
* نطاق [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->