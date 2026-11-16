---
title: ChartDataPoint
second_title: Aspose.Sildes لـ .NET مرجع API
description: يمثل نقطة بيانات السلسلة.
type: docs
weight: 1340
url: /ar/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint فئة

يمثل نقطة بيانات السلسلة.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. للقراءة Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. للقراءة Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | يحدد الموقع الفعلي x (اليسار) لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. للقراءة Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | يحدد الجزء العلوي الفعلي لعنصر المخطط بالنسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. للقراءة Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. للقراءة فقط [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | يحصل على حجم الفقاعات المخزن مؤقتًا لنقطة بيانات المخطط. للقراءة فقط [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | يحصل على القيمة المخزنة مؤقتًا لنقطة بيانات المخطط. للقراءة فقط [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | يحصل على القيمة X المخزنة مؤقتًا لنقطة بيانات المخطط. للقراءة فقط [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | يحصل على القيمة Y المخزنة مؤقتًا لنقطة بيانات المخطط. للقراءة فقط [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | يعطي قيمة اللون لنقطة بيانات المخطط. يُستخدم مع مخططات الخريطة. للقراءة فقط [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | يعطي الحاوية لمستويات نقطة البيانات. يُطبق على سلسلة Treeamp و Sunburst. فهرسة مستويات نقطة البيانات تبدأ من الصفر. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | يمثل قيم أشرطة الأخطاء للسلسلة في حالة نوع القيمة المخصص. للقراءة فقط [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. للقراءة والكتابة Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | يمثل خصائص التنسيق. للقراءة والكتابة [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | يحدد أن نقطة البيانات ستعكس ألوانها إذا كانت القيمة سلبية. للقراءة والكتابة Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مُطبق عليها. للقراءة والكتابة Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. للقراءة فقط [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | يحدد علامة بيانات. للقراءة فقط [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | خصائص عنصر الأسطورة الموافق في حالة نوع المخطط من القائمة التالية: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. للقراءة فقط [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | يضبط نقطة البيانات كإجمالي. يُطبق فقط على نوع سلسلة Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | يعطي قيمة الحجم لنقطة بيانات المخطط. يُستخدم مع مخططات Treemap و Sunburst. للقراءة فقط [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. للقراءة فقط [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. للقراءة فقط [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. للقراءة فقط [`IDoubleChartValue`](../idoublechartvalue). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | يعطي لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried وطراز المخطط. يُستخدم هذا اللون كإفتراضي إذا كانت FillType تساوي NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | يزيل DataPoint من سلسلة المخطط. |

### انظر أيضًا

* واجهة [IChartDataPoint](../ichartdatapoint)
* مساحة الأسماء [Aspose.Slides.Charts](../../aspose.slides.charts)
* تجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->