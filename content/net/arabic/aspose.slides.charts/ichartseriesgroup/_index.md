---
title: IChartSeriesGroup
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل مجموعة من السلاسل.
type: docs
weight: 1950
url: /ar/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup واجهة

يمثل مجموعة من السلاسل.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | يسمح بالحصول على واجهة IChartComponent الأساسية. قراءة فقط [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. قراءة/كتابة [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). قراءة/كتابة Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 بالمائة من حجم منطقة الرسم). قراءة/كتابة Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | يحصل على أو يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (عند عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | يعيد أو يحدد المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | يحدد المسافة بين مجموعات الأعمدة أو الأشرطة، كنسبة مئوية من عرض العمود أو الشريط. قراءة/كتابة UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الشريط المكدس و OfPie. قراءة/كتابة Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | يحدد تنسيق HiLowLines. تُطبق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | يحدد أن لكل علامة بيانات في السلسلة لونًا مختلفًا. قراءة/كتابة Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | يحصل على العنصر في الفهرس المحدد. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). - -100%: أقصى مسافة (الأشرطة منفصلة تمامًا). - 0%: توضع الأشرطة جنبًا إلى جنب بدون تداخل أو مسافة. - 100%: أقصى تداخل (الأشرطة تتداخل تمامًا). هذه الخاصية قراءة/كتابة SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | يحدد طريقة تحديد نقاط البيانات التي تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. قراءة/كتابة [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | معلومات الانقسام المخصص لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. قراءة فقط [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | يحدد قيمة تُستخدم لتحديد نقاط البيانات التي تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع خاصية PieSplitBy. قراءة/كتابة Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | يُشير إلى ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. قراءة فقط Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمائة). قراءة/كتابة UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | يعيد مجموعة قراءة فقط لسلسلات المخطط. قراءة فقط [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | يعيد نوع هذه المجموعة من السلاسل. قراءة فقط [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | يوفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط المالي. قراءة فقط [`IUpDownBarsManager`](../iupdownbarsmanager). |

### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection وعدد CombinableSeriesTypesGroup.  
2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي تكون مشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي قراءة/كتابة. كل واحدة من "خصائص مجموعة السلسلة" يمكن أن يكون لها إسقاط قراءة فقط في فئة ChartSeries.

### انظر أيضًا

* واجهة [IChartComponent](../ichartcomponent)
* مساحة الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->