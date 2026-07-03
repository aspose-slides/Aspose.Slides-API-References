---
title: ChartSeries
second_title: مرجع API لـ Aspose.Sildes for .NET
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
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | يحدد شكل سلسلة من مخطط شريطي ثلاثي الأبعاد. قد يؤدي تغيير قيمة هذه الخاصية إلى تغيير نوع السلسلة تلقائيًا. قراءة/كتابة [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.BubbleSizeRepresentation قراءة/كتابة لتغيير القيمة. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.BubbleSizeScale قراءة/كتابة لتغيير القيمة. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | إرجاع المخطط الأصل. قراءة فقط [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | إرجاع مجموعة نقاط البيانات لهذه السلسلة. قراءة فقط [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و 90 بالمائة من حجم مساحة الرسم). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.DoughnutHoleSize قراءة/كتابة لتغيير القيمة. قراءة فقط Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | يمثل ErrorBars للسلسلة ذات الاتجاه X. تتوفر ErrorBars باتجاه X للسلاسل من نوع area, bar, scatter و bubble. لأي أنواع أخرى من المخططات تُرجع هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). قراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | يمثل ErrorBars للسلسلة ذات الاتجاه Y. تتوفر ErrorBars باتجاه Y للسلاسل من نوع area, bar, line, scatter و bubble. لأي أنواع أخرى من المخططات تُرجع هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). قراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | المسافة التي يبتعد فيها شريحة الفطيرة المفتوحة عن مركز مخطط الفطيرة تُعبّر كنسبة مئوية من قطر الفطيرة. قراءة/كتابة Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | يحدد زاوية أول شريحة في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.FirstSliceAngle قراءة/كتابة لتغيير القيمة. قراءة فقط UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | إرجاع تنسيق السلسلة. قراءة فقط [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | إرجاع أو تعيين المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.GapDepth قراءة/كتابة لتغيير القيمة. قراءة فقط Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة، كنسبة مئوية من عرض العمود أو الشريط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.GapWidth قراءة/كتابة لتغيير القيمة. قراءة فقط Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | يحدد ما إذا كانت هناك خطوط سلسلة لهذه السلسلة والسلاسل المرتبطة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.HasSeriesLines قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلسلة. قراءة فقط Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | يحدد ما إذا كان مخطط الخط أو المخطط الشمعداني يحتوي على أشرطة صعود/هبوط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.UpDownBars.HasUpDownBars قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.UpDownBars لتنسيق أشرطة الصعود/الهبوط. قراءة فقط Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | يحدد لون صلب معكوس للسلسلة. لتطبيق ضبط اللون اضبط FillType لتنسيق السلسلة إلى FillType.Solid. قراءة/كتابة [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | يحدد ما إذا كان يجب عكس ألوان السلسلة الشريطية أو العمودية أو الفقاعية إذا كانت القيمة سالبة. قراءة/كتابة Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | يحدد أن لكل علامة بيانات في السلسلة لونًا مختلفًا. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.IsColorVaried قراءة/كتابة لتغيير القيمة. قراءة فقط Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | إرجاع Labels للسلسلة. قراءة فقط [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Marker. قراءة فقط [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | إرجاع اسم السلسلة. قراءة فقط [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. قراءة/كتابة String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. قراءة/كتابة String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. قراءة/كتابة String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. قراءة/كتابة String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | إرجاع ترتيب السلسلة. قراءة/كتابة Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية. إنها تمثيل الخاصية المناسبة في مجموعة السلاسل الأصلية، وبالتالي هذه الخاصية للقراءة فقط. لتغيير القيمة، استخدم الخاصية !:ParentSeriesGroup.Overlap قراءة/كتابة. قراءة فقط SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | يمثل تخطيط تسميات الفئة الأصلية. يُطبق فقط على مخططات Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. قراءة فقط [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.PieSplitBy قراءة/كتابة لتغيير القيمة. قراءة فقط [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | معلومات الانقسام المخصص لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. قراءة فقط [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع خاصية PieSplitBy. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.PieSplitPosition قراءة/كتابة لتغيير القيمة. قراءة فقط Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | يحدد ما إذا كانت هذه السلسلة مرسومة على المحور الثانوي. قراءة/كتابة Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | يمثل طريقة الربعيات. يُطبق فقط على مخططات BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | يمثل مدخل الأسطورة المتعلق بهذه السلسلة. قراءة فقط [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 بالمائة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع السلاسل في مجموعة السلاسل الأصلية - هذه تمثيل خاصية المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم خاصية ParentSeriesGroup.SecondPieSize قراءة/كتابة لتغيير القيمة. قراءة فقط UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | يمثل خطوط الاتصال. يُطبق فقط على مخططات Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | يمثل النقاط الداخلية. True إذا تم عرض النقاط الداخلية في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | يمثل خط المتوسط. True إذا تم عرض خط المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | يمثل علامات المتوسط. True إذا تم عرض علامات المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | يمثل نقاط القيم المتطرفة. True إذا تم عرض نقاط القيم المتطرفة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | يمثل تنعيم المنحنى. True إذا تم تشغيل تنعيم المنحنى لمخطط الخط أو مخطط النقاط المتصلة. يُطبق فقط على مخططات الخط والنقاط المتصلة. قراءة/كتابة Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | مجموعة خطوط الاتجاه للسلسلة. قراءة فقط [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | إرجاع نوع هذه السلسلة. قراءة/كتابة [`ChartType`](../charttype). |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | إرجاع لون تلقائي للسلسلة بناءً على مؤشر السلسلة ونمط المخطط. يُستخدم هذا اللون افتراضياً إذا كان FillType يساوي NotDefined. |

### انظر أيضًا

* واجهة [IChartSeries](../ichartseries)
* نطاق [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->