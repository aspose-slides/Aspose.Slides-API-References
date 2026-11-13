---
title: ChartSeries
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل سلسلة مخطط.
type: docs
weight: 1450
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
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. يمكن أن يؤدي تغيير قيمة هذه الخاصية إلى تغيير نوع السلسلة تلقائيًا. قراءة/كتابة [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | يحدد كيف يتم تمثيل قيم حجم الفقاعات في مخطط الفقاعات. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.BubbleSizeRepresentation قراءة/كتابة لتغيير القيمة. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمئة من الحجم الافتراضي). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.BubbleSizeScale قراءة/كتابة لتغيير القيمة. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | يعيد المخطط الأصلي. للقراءة فقط [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | يعيد مجموعة نقاط البيانات لهذه السلسلة. للقراءة فقط [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | يحدد حجم الثقب في مخطط الدونات (يمكن أن يكون بين 10 و 90 بالمئة من حجم مساحة الرسم). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.DoughnutHoleSize قراءة/كتابة لتغيير القيمة. للقراءة فقط Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | يمثل ErrorBars للسلسلة ذات الاتجاه X. تتوفر ErrorBars بالاتجاه X للسلاسل من النوع area أو bar أو scatter أو bubble. بالنسبة لأي أنواع أخرى من المخططات تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (باستخدام الخاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). للقراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | يمثل ErrorBars للسلسلة ذات الاتجاه Y. تتوفر ErrorBars بالاتجاه Y للسلاسل من النوع area أو bar أو line أو scatter أو bubble. بالنسبة لأي أنواع أخرى من المخططات تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (باستخدام الخاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). للقراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | المسافة بين شريحة الفطيرة المفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. قراءة/كتابة Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.FirstSliceAngle قراءة/كتابة لتغيير القيمة. للقراءة فقط UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | يعيد تنسيق السلسلة. للقراءة فقط [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | يعيد أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.GapDepth قراءة/كتابة لتغيير القيمة. للقراءة فقط Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | يحدد المسافة بين مجموعات الأعمدة أو القضبان، كنسبة مئوية من عرض العمود أو الشريط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.GapWidth قراءة/كتابة لتغيير القيمة. للقراءة فقط Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | يحدد ما إذا كانت هناك خطوط سلسلة لهذه السلسلة والسلاسل المرتبطة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.HasSeriesLines قراءة/كتابة لتغيير القيمة. استخدم الخاصية ParentSeriesGroup.SeriesLinesFormat للتنسيق. للقراءة فقط Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | يحدد ما إذا كان مخطط الخط أو المخطط الشريطي يحتوي على أشرطة صعود/هبوط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.UpDownBars.HasUpDownBars قراءة/كتابة لتغيير القيمة. استخدم الخاصية ParentSeriesGroup.UpDownBars للتنسيق. للقراءة فقط Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | يحدد عكس اللون الصلب للسلسلة. لتطبيق إعداد اللون ضع تنسيق السلسلة FillType إلى FillType.Solid. قراءة/كتابة [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | يحدد ما إذا كانت سلسلة الشريط أو العمود أو الفقاعة تعكس ألوانها إذا كانت القيمة سالبة. قراءة/كتابة Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.IsColorVaried قراءة/كتابة لتغيير القيمة. للقراءة فقط Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | يعيد التسميات لسلسلة. للقراءة فقط [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | العلامة. للقراءة فقط [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | يعيد اسم السلسلة. للقراءة فقط [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. قراءة/كتابة String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. قراءة/كتابة String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. قراءة/كتابة String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. قراءة/كتابة String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | يعيد ترتيب السلسلة. قراءة/كتابة Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية. هي إظهار للخاصية المناسبة في مجموعة السلسلة الأصلية، وبالتالي هذه الخاصية للقراءة فقط. لتغيير القيمة، استخدم الخاصية !:ParentSeriesGroup.Overlap قراءة/كتابة. للقراءة فقط SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | يمثل تخطيط تسميات الفئة الأصلية. ينطبق فقط على مخططات Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. للقراءة فقط [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.PieSplitBy قراءة/كتابة لتغيير القيمة. للقراءة فقط [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | المعلومات المخصصة للانقسام لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يحتوي على نقاط البيانات التي ستُرسم في الفطيرة أو الشريط الثاني. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. للقراءة فقط [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع الخاصية PieSplitBy. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.PieSplitPosition قراءة/كتابة لتغيير القيمة. للقراءة فقط Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | يشير إذا كانت هذه السلسلة مرسومة على المحور الثانوي. قراءة/كتابة Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | يمثل طريقة الربع. ينطبق فقط على مخططات BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | يمثل مدخل الأسطورة المتعلق بهذه السلسلة. للقراءة فقط [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمئة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إظهار للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.SecondPieSize قراءة/كتابة لتغيير القيمة. للقراءة فقط UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | يمثل خطوط الوصل. ينطبق فقط على مخططات Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | يمثل النقاط الداخلية. صحيح إذا كانت النقاط الداخلية معروضة في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | يمثل خط المتوسط. صحيح إذا كان خط المتوسط معروضًا في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | يمثل علامات المتوسط. صحيح إذا كانت علامات المتوسط معروضة في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | يمثل نقاط الشذوذ. صحيح إذا كانت نقاط الشذوذ معروضة في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | يمثل تنعيم المنحنى. صحيح إذا تم تفعيل تنعيم المنحنى لمخطط الخط أو مخطط التبعثر المتصل بخطوط. ينطبق فقط على مخططات الخط والتبعثر المتصل بخطوط. قراءة/كتابة Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | مجموعة خطوط اتجاه السلسلة. للقراءة فقط [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | يعيد نوع هذه السلسلة. قراءة/كتابة [`ChartType`](../charttype). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | يعيد لونًا تلقائيًا للسلسلة بناءً على فهرس السلسلة ونمط المخطط. يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined. |

### انظر أيضًا

* الواجهة [IChartSeries](../ichartseries)
* النطاق [Aspose.Slides.Charts](../../aspose.slides.charts)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->