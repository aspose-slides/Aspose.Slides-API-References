---
title: IChartSeriesGroup
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل مجموعة من السلاسل.
type: docs
weight: 1970
url: /ar/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup واجهة

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | يتيح الحصول على واجهة IChartComponent الأساسية. للقراءة فقط [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. للقراءة والكتابة [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). للقراءة والكتابة Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 بالمائة من حجم مساحة الرسم). للقراءة والكتابة Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | يحصل على أو يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). للقراءة والكتابة UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | يحصل على أو يحدد المسافة بين سلاسل البيانات في مخطط ثلاثي الأبعاد، كنسبة مئوية من عرض العلامة. يجب أن تكون القيمة بين 0 و 500. للقراءة والكتابة UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | يحصل على أو يحدد المسافة بين مجموعات الأعمدة أو الأشرطة، كنسبة مئوية من عرض العمود أو الشريط. يجب أن تكون القيمة بين 0 و 500. للقراءة والكتابة UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | صحيح إذا كان المخطط يحتوي على خطوط السلسلة. يُطبق على مخططات الشريط المكدس و OfPie. للقراءة والكتابة Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | يحدد تنسيق HiLowLines. تُطبق HiLowLines مع أنواع المخططات HiLowClose و OpenHiLowClose و VolumeHiLowClose و VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. للقراءة والكتابة Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | يحصل على العنصر عند الفهرس المحدد. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). - -100%: أقصى مسافة (الأشرطة منفصلة تمامًا). - 0%: توضع الأشرطة جنبًا إلى جنب دون تداخل أو مسافة. - 100%: أقصى تداخل (الأشرطة تتداخل تمامًا مع بعضها). هذه الخاصية للقراءة والكتابة SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | يحدد طريقة تحديد نقاط البيانات الموجودة في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. للقراءة والكتابة [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | معلومات الانقسام المخصص لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. للقراءة فقط [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | يحدد قيمة تُستخدم لتحديد نقاط البيانات الموجودة في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع خاصية PieSplitBy. للقراءة والكتابة Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | يشير إذا ما كانت سلاسل هذه المجموعة مرسومة على المحور الثانوي. للقراءة فقط Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمائة). للقراءة والكتابة UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | تُعيد مجموعة قراءة فقط لسلاسل المخطط. للقراءة فقط [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | تُعيد نوع مجموعة السلاسل هذه. للقراءة فقط [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | يوفر الوصول إلى أشرطة الصعود/الهبوط في مخطط الخط أو مخطط الأسهم. للقراءة فقط [`IUpDownBarsManager`](../iupdownbarsmanager). |

### ملاحظات

1) راجع الملخص والملاحظات لصف `ChartSeriesGroupCollection` و تعداد `CombinableSeriesTypesGroup`. 2) مجموعة السلاسل تحتوي على بعض خصائص السلسلة التي مشتركة لكل سلسلة في المجموعة "series group properties". "Series group properties" في صف `ChartSeriesGroup` يمكن قراءتها وكتابتها. كل من "series group properties" يمكن أن يكون له تمثيل للقراءة فقط في صف `ChartSeries`.

### انظر أيضاً

* واجهة [IChartComponent](../ichartcomponent)
* مساحة الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->