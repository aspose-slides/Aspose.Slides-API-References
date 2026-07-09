---
title: ChartSeries
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل سلسلة مخطط.
type: docs
weight: 1440
url: /ar/aspose.slides.charts/chartseries/
---
## ChartSeries فئة

يمثل سلسلة مخطط.

```csharp
public class ChartSeries : IChartSeries
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | يحدد شكل سلسلة في مخطط شريطي ثلاثي الأبعاد. قد يؤدي تغيير قيمة هذه الخاصية إلى تغيير نوع السلسلة تلقائيًا. قراءة/كتابة [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.BubbleSizeRepresentation قراءة/كتابة لتغيير القيمة. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 ٪ من الحجم الافتراضي). هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.BubbleSizeScale قراءة/كتابة لتغيير القيمة. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | يُرجع المخطط الأصل. قراءة فقط [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | يُرجع مجموعة نقاط البيانات لهذه السلسلة. قراءة فقط [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | يحدد حجم الفتحة في المخطط الدائري (يمكن أن يكون بين 10 و90 ٪ من حجم منطقة الرسم). هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.DoughnutHoleSize قراءة/كتابة لتغيير القيمة. قراءة فقط Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | يمثل ErrorBars للسلسلة باتجاه X. تتوفر ErrorBars باتجاه X لسلاسل الأنواع area, bar, scatter و bubble. بالنسبة لأي أنواع مخططات أخرى تُرجع الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حال القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع خاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). قراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | يمثل ErrorBars للسلسلة باتجاه Y. تتوفر ErrorBars باتجاه Y لسلاسل الأنواع area, bar, line, scatter و bubble. بالنسبة لأي أنواع مخططات أخرى تُرجع الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حال القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع خاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). قراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | يُعبّر عن بعد قطعة الفطيرة المفتوحة عن مركز المخطط الدائري كنسبة مئوية من قطر الفطيرة. قراءة/كتابة Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | يحدد زاوية القطعة الأولى في مخطط الفطيرة أو الدونت، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.FirstSliceAngle قراءة/كتابة لتغيير القيمة. قراءة فقط UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | يُرجع تنسيق السلسلة. قراءة فقط [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | يُرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.GapDepth قراءة/كتابة لتغيير القيمة. قراءة فقط Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | يحدد الفاصل بين مجموعات الأعمدة أو الأشرطة كنسبة مئوية من عرض العمود أو الشريط. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.GapWidth قراءة/كتابة لتغيير القيمة. قراءة فقط Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | يحدد ما إذا كانت هناك خطوط سلاسل لهذه السلسلة والسلاسل ذات الصلة. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.HasSeriesLines قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلسلة. قراءة فقط Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | يحدد ما إذا كان مخطط الخط أو المخطط العمودي يحتوي على أعمدة صعود/هبوط. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.UpDownBars.HasUpDownBars قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.UpDownBars لتنسيق أعمدة الصعود/الهبوط. قراءة فقط Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | يحدد لون الصلب المعكوس للسلسلة. لتطبيق إعداد اللون اضبط تنسيق السلسلة FillType إلى FillType.Solid. قراءة/كتابة [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | يحدد ما إذا كان يجب على سلسلة الشريط أو العمود أو الفقاعة عكس ألوانها عندما تكون القيمة سالبة. قراءة/كتابة Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | يحدد أن لكل علامة بيانات في السلسلة لونًا مختلفًا. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.IsColorVaried قراءة/كتابة لتغيير القيمة. قراءة فقط Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | يُرجع العلامات (Labels) الخاصة بالسلسلة. قراءة فقط [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | العلامة (Marker). قراءة فقط [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | يُرجع اسم السلسلة. قراءة فقط [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. قراءة/كتابة String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. قراءة/كتابة String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. قراءة/كتابة String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. قراءة/كتابة String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | يُرجع ترتيب السلسلة. قراءة/كتابة Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | يحدد مقدار تداخل الأعمدة والشرائط في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100 ٪ إلى 100 ٪). هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. لتغيير القيمة استخدم الخاصية ParentSeriesGroup.Overlap قراءة/كتابة. قراءة فقط SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | يمثل تخطيط تسميات الفئات الأصلية. يُطبق فقط على مخططات Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. قراءة فقط [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | يحدد طريقة تحديد نقاط البيانات التي تُرسم في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.PieSplitBy قراءة/كتابة لتغيير القيمة. قراءة فقط [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | معلومات التقسيم المخصصة لمخطط pie-of-pie أو bar-of-pie مع تقسيم مخصص. يحتوي على نقاط البيانات التي تُرسم في الفطيرة أو الشريط الثاني. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. قراءة فقط [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | يحدد قيمة تُستخدم لتحديد نقاط البيانات التي تُرسم في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع خاصية PieSplitBy. هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.PieSplitPosition قراءة/كتابة لتغيير القيمة. قراءة فقط Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | يحدد ما إذا كانت هذه السلسلة مرسومة على المحور الثانوي. قراءة/كتابة Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | يمثل طريقة الربع (quartile). يُطبق فقط على مخططات BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | يمثل مدخل أسطورة (legend) المرتبط بهذه السلسلة. قراءة فقط [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 ٪). هذه الخاصية لا تخص هذه السلسلة فقط بل جميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المقابلة في المجموعة. وبالتالي هي خاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.SecondPieSize قراءة/كتابة لتغيير القيمة. قراءة فقط UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | يمثل خطوط الموصل. يُطبق فقط على مخططات Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | يمثل النقاط الداخلية. True إذا تم إظهار النقاط الداخلية في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | يمثل خط المتوسط. True إذا تم إظهار خط المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | يمثل علامات المتوسط. True إذا تم إظهار علامات المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | يمثل نقاط القيم المتطرفة. True إذا تم إظهار نقاط القيم المتطرفة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | يمثل تنعيم المنحنى. True إذا تم تشغيل تنعيم المنحنى لمخطط الخط أو مخطط التشتت المتصل بخطوط. يُطبق فقط على مخططات الخط والتشتت المتصلة. قراءة/كتابة Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | مجموعة خطوط الاتجاه للسلسلة. قراءة فقط [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | يُرجع نوع هذه السلسلة. قراءة/كتابة [`ChartType`](../charttype). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | يُرجع لونًا تلقائيًا للسلسلة بناءً على فهرس السلسلة ونمط المخطط. يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined. |

### انظر أيضا

* واجهة [IChartSeries](../ichartseries)
* نطاق [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->