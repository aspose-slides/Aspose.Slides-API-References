---
title: IChartSeries
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل سلسلة مخطط.
type: docs
weight: 1950
url: /ar/aspose.slides.charts/ichartseries/
---
## واجهة IChartSeries

يمثل سلسلة مخطط.

```csharp
public interface IChartSeries : IChartComponent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | السماح بالحصول على واجهة IChartComponent الأساسية. قراءة فقط [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | يحدد شكل سلسلة في مخطط أعمدة ثلاثي الأبعاد. قد يؤدي تغيير قيمة هذه الخاصية إلى تغيير نوع السلسلة تلقائيًا. قراءة/كتابة [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | يحدد كيفية تمثيل قيم حجم الفقاعات على مخطط الفقاعات. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.BubbleSizeRepresentation قراءة/كتابة لتغيير القيمة. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.BubbleSizeScale قراءة/كتابة لتغيير القيمة. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | يعيد مجموعة نقاط البيانات لهذه السلسلة. قراءة فقط [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | يحدد حجم الفتق في مخطط الحلقة (يمكن أن يكون بين 10 و 90 بالمائة من حجم منطقة الرسم). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.DoughnutHoleSize قراءة/كتابة لتغيير القيمة. قراءة فقط Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | يمثل ErrorBars للسلسلة باتجاه X. تتوفر ErrorBars باتجاه X للسلاسل من النوع area و bar و scatter و bubble. بالنسبة لأي أنواع أخرى من المخططات، تعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (باستخدام خاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). قراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | يمثل ErrorBars للسلسلة باتجاه Y. تتوفر ErrorBars باتجاه Y للسلاسل من النوع area و bar و line و scatter و bubble. بالنسبة لأي أنواع أخرى من المخططات، تعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (باستخدام خاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). قراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | المسافة بين شريحة فطيرة مفتوحة ومركز مخطط الفطيرة تُعبر عنها كنسبة مئوية من قطر الفطيرة. قراءة/كتابة Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو الحلقة، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.FirstSliceAngle قراءة/كتابة لتغيير القيمة. قراءة فقط UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | يعيد تنسيق السلسلة. قراءة فقط [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | يعيد أو يحدد المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.GapDepth قراءة/كتابة لتغيير القيمة. قراءة فقط Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | يحدد الفاصل بين مجموعات الأعمدة أو الأشرطة، كنسبة مئوية من عرض العمود أو الشريط. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.GapWidth قراءة/كتابة لتغيير القيمة. قراءة فقط Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | يحدد ما إذا كانت هناك خطوط سلسلة لهذه السلسلة والسلاسل المرتبطة. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.HasSeriesLines قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلسلة. قراءة فقط Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | يحدد ما إذا كان مخطط الخط أو المخطط العمودي يحتوي على أشرطة صعود/هبوط. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصل إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.UpDownBars.HasUpDownBars قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.UpDownBars لتنسيق أشرطة الصعود/الهبوط. قراءة فقط Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | يحدد عكس اللون الصلب للسلسلة. لتطبيق إعداد اللون اضبط FillType لتنسيق السلسلة إلى FillType.Solid. قراءة/كتابة [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | يحدد أن سلسلة الأعمدة أو الأعمدة أو الفقاعات ستعكس ألوانها إذا كانت القيمة سلبية. قراءة/كتابة Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.IsColorVaried قراءة/كتابة لتغيير القيمة. قراءة فقط Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | يعيد العلامات لسلسلة. قراءة فقط [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | يعيد علامة السلسلة. قراءة فقط [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | يعيد اسم السلسلة. قراءة فقط [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | يعيد أو يحدد تنسيق الأرقام لأحجام فقاعات السلسلة. قراءة/كتابة String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | يعيد أو يحدد تنسيق الأرقام لقيم السلسلة. قراءة/كتابة String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | يعيد أو يحدد تنسيق الأرقام لقيم x في السلسلة. قراءة/كتابة String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | يعيد أو يحدد تنسيق الأرقام لقيم y في السلسلة. قراءة/كتابة String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | يعيد ترتيب السلسلة. قراءة/كتابة Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | يحدد مدى تراكب الأعمدة والأشرطة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم. إنها إسقاط للخاصية المناسبة في المجموعة، وبالتالي هذه الخاصية قراءة فقط. لتغيير القيمة، استخدم خاصية ParentSeriesGroup.Overlap قراءة/كتابة. قراءة فقط SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | يمثل تخطيط تسميات الفئات الأم. ينطبق فقط على مخططات Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | يعيد مجموعة السلسلة الأم. قراءة فقط [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | يحدد طريقة تحديد نقاط البيانات الموجودة في الشريحة الثانية أو العمود الثاني في مخطط pie-of-pie أو bar-of-pie. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.PieSplitBy قراءة/كتابة لتغيير القيمة. قراءة فقط [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | معلومات الانقسام المخصَّص لمخطط pie-of-pie أو bar-of-pie مع انقسام مخصَّص. يحتوي على نقاط البيانات التي يجب رسمها في الشريحة أو العمود الثاني. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. قراءة فقط [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | يحدد قيمة تُستخدم لتحديد نقاط البيانات الموجودة في الشريحة أو العمود الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع خاصية PieSplitBy. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.PieSplitPosition قراءة/كتابة لتغيير القيمة. قراءة فقط Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | يشير إلى ما إذا كانت هذه السلسلة مرسومة على محور القيمة الثاني. قراءة/كتابة Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | يمثل طريقة الربعيات. ينطبق فقط على مخططات BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | يمثل مدخل الأسطورة المتعلق بهذه السلسلة. قراءة فقط [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | يحدد حجم الشريحة أو العمود الثاني في مخطط pie-of-pie أو bar-of-pie كنسبة مئوية من حجم الشريحة الأولى (يمكن أن تكون بين 5 و 200 بالمائة). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع السلاسل في مجموعة السلسلة الأم - إنها إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأم. استخدم خاصية ParentSeriesGroup.SecondPieSize قراءة/كتابة لتغيير القيمة. قراءة فقط UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | يمثل خطوط الوصل. ينطبق فقط على مخططات Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | يمثل النقاط الداخلية. true إذا تم إظهار النقاط الداخلية على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | يمثل علامات المتوسط. true إذا تم إظهار خط المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | يمثل علامات المتوسط. true إذا تم إظهار علامات المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | يمثل نقاط الخارج. true إذا تم إظهار نقاط الخارج على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | يمثل تنعيم المنحنى. true إذا كان تنعيم المنحنى مفعلاً لمخطط الخط أو مخطط التبعثر. ينطبق فقط على مخططات الخط والتبعثر المتصلة بخطوط. قراءة/كتابة Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | مجموعة خطوط الاتجاه للسلسلة. قراءة فقط [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | يعيد نوع هذه السلسلة. قراءة/كتابة [`ChartType`](../charttype). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | يعيد لونًا تلقائيًا للسلسلة بناءً على فهرس السلسلة ونمط المخطط. يُستخدم هذا اللون كقيمة افتراضية إذا كان FillType يساوي NotDefined. |

### انظر أيضًا

* واجهة [IChartComponent](../ichartcomponent)
* مساحة الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* التجميعة [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->