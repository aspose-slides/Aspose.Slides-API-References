---
title: ChartSeriesGroup
second_title: مرجع Aspose.Sildes لـ .NET API
description: يمثل مجموعة من السلاسل.
type: docs
weight: 1470
url: /ar/aspose.slides.charts/chartseriesgroup/
---
## فئة ChartSeriesGroup

يمثل مجموعة من السلاسل.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## الخصائص

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قابل للقراءة والكتابة [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المئة من الحجم الافتراضي). قابل للقراءة والكتابة Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | يرجع المخطط الأب. للقراءة فقط [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 0 و 90 في المئة من حجم مساحة الرسم). قابل للقراءة والكتابة Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | يحصل أو يضبط زاوية القطعة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قابل للقراءة والكتابة UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | يحصل أو يضبط المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد، كنسبة مئوية من عرض العلامة. يجب أن تكون القيمة بين 0 و 500. قابل للقراءة والكتابة UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | يحصل أو يضبط المسافة بين مجموعات الأعمدة أو الأعمدة، كنسبة مئوية من عرض العمود أو الشريط. يجب أن تكون القيمة بين 0 و 500. قابل للقراءة والكتابة UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True إذا كان المخطط يحتوي على خطوط السلاسل. يُطبق على مخططات الشريط المكدس ومخططات OfPie. قابل للقراءة والكتابة Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | يحدد تنسيق HiLowLines. يتم تطبيق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قابل للقراءة والكتابة Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | يحصل على العنصر عند الفهرس المحدد. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات الثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). - -100%: الحد الأقصى للمسافات (الأشرطة منفصلة تمامًا). - 0%: تُوضع الأشرطة جنبًا إلى جنب بدون تداخل أو مسافة. - 100%: الحد الأقصى للتداخل (الأشرطة تتداخل تمامًا). هذه الخاصية قابلة للقراءة والكتابة SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | يحدد الطريقة لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. قابل للقراءة والكتابة [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | معلومات الانقسام المخصصة لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. للقراءة فقط [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع خاصية PieSplitBy. قابل للقراءة والكتابة Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | يشير ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. للقراءة فقط Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 في المئة). قابل للقراءة والكتابة UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | يرجع مجموعة من السلاسل. للقراءة فقط [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | يرجع نوع هذه المجموعة من السلاسل. للقراءة فقط [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | يوفر الوصول إلى أشرطة الارتفاع/الانخفاض في مخطط الخط أو مخطط السهم. للقراءة فقط [`IUpDownBarsManager`](../iupdownbarsmanager). |

### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection والعدد CombinableSeriesTypesGroup. 2) تحتوي مجموعة السلاسل على بعض خصائص السلسلة المشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلاسل"). "خصائص مجموعة السلاسل" في فئة ChartSeriesGroup قابلة للقراءة والكتابة. كل واحدة من "خصائص مجموعة السلاسل" يمكن أن يكون لها إسقاط للقراءة فقط في فئة ChartSeries.

### انظر أيضًا

* واجهة [IChartSeriesGroup](../ichartseriesgroup)
* نطاق الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->