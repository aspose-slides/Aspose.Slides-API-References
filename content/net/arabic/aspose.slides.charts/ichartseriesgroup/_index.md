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
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. قراءة/كتابة [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). قراءة/كتابة Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | يحدد حجم الفتحة في مخطط الدونات (يمكن أن تكون بين 10 و 90 بالمائة من حجم مساحة المخطط). قراءة/كتابة Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | يحصل أو يضبط زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). قراءة/كتابة UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | يرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. قراءة/كتابة UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | يحدد الفاصل بين مجموعات الأعمدة أو الأشرطة، كنسبة مئوية من عرض العمود أو الشريط. قراءة/كتابة UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على المخططات المكدسة والـ OfPie. قراءة/كتابة Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | يحدد تنسيق HiLowLines. يتم تطبيق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. قراءة/كتابة Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | يحصل على العنصر في الفهرس المحدد. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | يحدد مدى تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). - -100%: أقصى مسافة (الأشرطة مفصولة تمامًا). - 0%: تُوضع الأشرطة جنبًا إلى جنب دون تداخل أو مسافة. - 100%: أقصى تداخل (الأشرطة تتداخل تمامًا مع بعضها). هذه الخاصية قراءة/كتابة SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | يحدد طريقة تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة. قراءة/كتابة [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | معلومات الانقسام المخصص لمخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة. قراءة فقط [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة. تُستخدم مع خاصية PieSplitBy. قراءة/كتابة Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | يشير ما إذا كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. قراءة فقط Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و 200 بالمائة). قراءة/كتابة UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | يرجع مجموعة قراءة فقط لسلاسل المخطط. قراءة فقط [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | يرجع نوع مجموعة السلاسل هذه. قراءة فقط [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | يوفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو المخطط السهمي. قراءة فقط [`IUpDownBarsManager`](../iupdownbarsmanager). |

### ملاحظات

1) راجع الملخص والملاحظات لفئة ChartSeriesGroupCollection وتعداد CombinableSeriesTypesGroup. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة المشتركة لكل سلسلة في المجموعة ("خصائص مجموعة السلسلة"). "خصائص مجموعة السلسلة" في فئة ChartSeriesGroup هي قراءة/كتابة. يمكن أن يكون لكل من "خصائص مجموعة السلسلة" تجسيد قراءة فقط في فئة ChartSeries.

### انظر أيضًا

* واجهة [IChartComponent](../ichartcomponent)
* نطاق الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->