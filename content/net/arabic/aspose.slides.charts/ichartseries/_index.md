---
title: IChartSeries
second_title: مرجع API لـ Aspose.Sildes لـ .NET
description: يمثل سلسلة مخطط.
type: docs
weight: 1930
url: /ar/aspose.slides.charts/ichartseries/
---
## IChartSeries واجهة

يمثل سلسلة مخطط.

```csharp
public interface IChartSeries : IChartComponent
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | يسمح بالحصول على واجهة IChartComponent الأساسية. قراءة فقط [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. قد يؤدي تغيير قيمة هذه الخاصية إلى تغيير نوع السلسلة تلقائيًا. قراءة/كتابة [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاع. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.BubbleSizeRepresentation قراءة/كتابة لتغيير القيمة. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 بالمائة من الحجم الافتراضي). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.BubbleSizeScale قراءة/كتابة لتغيير القيمة. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | يُرجع مجموعة نقاط البيانات لهذه السلسلة. قراءة فقط [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | يحدد حجم الثقب في مخطط الدونات (يمكن أن يكون بين 10 و 90 بالمائة من حجم مساحة الرسم). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.DoughnutHoleSize قراءة/كتابة لتغيير القيمة. قراءة فقط Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | يمثل خطوط الأخطاء (ErrorBars) للسلسلة باتجاه X. خطوط الأخطاء باتجاه X متاحة للسلاسل من النوع area, bar, scatter و bubble. لأي نوع مخطط آخر تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). قراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | يمثل خطوط الأخطاء (ErrorBars) للسلسلة باتجاه Y. خطوط الأخطاء باتجاه Y متاحة للسلاسل من النوع area, bar, line, scatter و bubble. لأي نوع مخطط آخر تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). قراءة فقط [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | المسافة التي يبعدها شريحة البيت المفتوح عن مركز مخطط الدائرة، معبرة كنسبة مئوية من قطر الدائرة. قراءة/كتابة Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | يحدد زاوية الشريحة الأولى في مخطط الدونات أو الفطيرة، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.FirstSliceAngle قراءة/كتابة لتغيير القيمة. قراءة فقط UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | يُرجع تنسيق السلسلة. قراءة فقط [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | يُعيد أو يحدد المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.GapDepth قراءة/كتابة لتغيير القيمة. قراءة فقط Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | يحدد المسافة بين مجموعات الأعمدة أو الشرائط، كنسبة مئوية من عرض العمود أو الشريط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.GapWidth قراءة/كتابة لتغيير القيمة. قراءة فقط Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | يحدد ما إذا كانت هناك خطوط سلسلة لهذه السلسلة والسلاسل المماثلة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.HasSeriesLines قراءة/كتابة لتغيير القيمة. استخدم الخاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلسلة. قراءة فقط Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | يحدد ما إذا كان مخطط الخط أو المخطط العمودي يحتوي على أشرطة صعود/هبوط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.UpDownBars.HasUpDownBars قراءة/كتابة لتغيير القيمة. استخدم الخاصية ParentSeriesGroup.UpDownBars لتنسيق أشرطة الصعود/الهبوط. قراءة فقط Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | يحدد لون صلب مقلوب للسلسلة. لتطبيق إعداد اللون ضع تنسيق السلسلة FillType إلى FillType.Solid. قراءة/كتابة [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | يحدد ما إذا كان يجب عكس ألوان الشريط أو العمود أو سلسلة الفقاع عندما تكون القيمة سالبة. قراءة/كتابة Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.IsColorVaried قراءة/كتابة لتغيير القيمة. قراءة فقط Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | يُرجع تسميات السلسلة. قراءة فقط [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | يُرجع علامة السلسلة. قراءة فقط [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | يُرجع اسم السلسلة. قراءة فقط [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | يُعيد أو يحدد تنسيق الأرقام لأحجام فقاعات السلسلة. قراءة/كتابة String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | يُعيد أو يحدد تنسيق الأرقام لقيم السلسلة. قراءة/كتابة String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | يُعيد أو يحدد تنسيق الأرقام لقيم X للسلسلة. قراءة/كتابة String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | يُعيد أو يحدد تنسيق الأرقام لقيم Y للسلسلة. قراءة/كتابة String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | يُعيد ترتيب السلسلة. قراءة/كتابة Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | يحدد مقدار تداخل الأعمدة والشرائط في المخططات الثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. لتغيير القيمة، استخدم الخاصية ParentSeriesGroup.Overlap قراءة/كتابة. قراءة فقط SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | يمثل تخطيط تسميات الفئات الأصلية. يُطبق فقط على مخططات Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | يُرجع مجموعة السلاسل الأصلية. قراءة فقط [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | يحدد كيفية تحديد نقاط البيانات التي تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.PieSplitBy قراءة/كتابة لتغيير القيمة. قراءة فقط [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | معلومات التقسيم المخصص لمخطط pie-of-pie أو bar-of-pie مع تقسيم مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. قراءة فقط [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | يحدد قيمة تُستخدم لتحديد نقاط البيانات التي تكون في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. تُستخدم مع الخاصية PieSplitBy. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.PieSplitPosition قراءة/كتابة لتغيير القيمة. قراءة فقط Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | يشير ما إذا كانت هذه السلسلة مرسومة على المحور القيمي الثاني. قراءة/كتابة Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | يمثل طريقة الربيع (quartile). يُطبق فقط على مخططات BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | يمثل مدخل أسطوري متعلق بهذه السلسلة. قراءة فقط [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و 200 بالمائة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.SecondPieSize قراءة/كتابة لتغيير القيمة. قراءة فقط UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | يمثل خطوط الاتصال. يُطبق فقط على مخططات Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | يمثل النقاط الداخلية. true إذا تم إظهار النقاط الداخلية في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | يمثل علامات المتوسط. true إذا تم إظهار خط المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | يمثل علامات المتوسط. true إذا تم إظهار علامات المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | يمثل نقاط القيم المتطرفة. true إذا تم إظهار نقاط القيم المتطرفة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | يمثل تنعيم المنحنى. true إذا تم تشغيل تنعيم المنحنى للمخططات الخطية أو مخططات التبعثر المتصلة بخطوط. يُطبق فقط على مخططات الخط والتبعثر المتصلة بخطوط. قراءة/كتابة Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | مجموعة خطوط اتجاه السلسلة. قراءة فقط [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | يُعيد أو يحدد نوع هذه السلسلة. قراءة/كتابة [`ChartType`](../charttype). |

## الأساليب

| الاسم | الوصف |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | يُعيد لونًا تلقائيًا للسلسلة استنادًا إلى فهرس السلسلة ونمط المخطط. يُستخدم هذا اللون كافتراضي إذا كان FillType يساوي NotDefined. |

### انظر أيضا

* واجهة [IChartComponent](../ichartcomponent)
* مساحة الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->