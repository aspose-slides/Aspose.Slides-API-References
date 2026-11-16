---
title: ChartDataPoint
second_title: Aspose.Sildes for .NET API संदर्भ
description: सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
weight: 1340
url: /hi/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint वर्ग

सीरीज डेटा पॉइंट का प्रतिनिधित्व करता है।

```csharp
public class ChartDataPoint : IChartDataPoint
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। Read Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। Read Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | चार्ट तत्व का वास्तविक x स्थान (बायाँ) चार्ट के बाएँ ऊपरी कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। Read Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | चार्ट तत्व का वास्तविक शीर्ष, चार्ट के बाएँ ऊपरी कोने के सापेक्ष, निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() विधि को कॉल करें। Read Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | एक चार्ट डेटा पॉइंट के कैश किए गये बबल आकार को प्राप्त करता है। केवल-पढ़ने योग्य [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | एक चार्ट डेटा पॉइंट के कैश किए गये मान को प्राप्त करता है। केवल-पढ़ने योग्य [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | एक चार्ट डेटा पॉइंट के कैश किए गये X मान को प्राप्त करता है। केवल-पढ़ने योग्य [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | एक चार्ट डेटा पॉइंट के कैश किए गये Y मान को प्राप्त करता है। केवल-पढ़ने योग्य [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | चार्ट डेटा पॉइंट का रंग मान लौटाता है। मैप चार्ट्स के साथ उपयोग किया जाता है। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | डेटा पॉइंट स्तरों का कंटेनर लौटाता है। Treeamp और Sunburst सीरीज़ के लिए लागू। डेटा पॉइंट स्तरों का इंडेक्स शून्य-आधारित है। |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | कस्टम वैल्यू टाइप की स्थिति में सीरीज़ एरर बार मानों का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | डेटा पॉइंट को पाई के केंद्र से स्थानांतरित किए जाने की मात्रा निर्दिष्ट करता है। Read/write Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। Read/write [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंगों को उल्टा करेगा, यह निर्दिष्ट करता है। Read/write Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | बबल्स पर 3-D प्रभाव लागू किया गया है, यह निर्दिष्ट करता है। Read/write Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | लेबल। केवल-पढ़ने योग्य [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | डेटा मार्कर निर्दिष्ट करता है। केवल-पढ़ने योग्य [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | इस सूची में से चार्ट प्रकार के लिए संबंधित लेजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। केवल-पढ़ने योग्य [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू। |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | चार्ट डेटा पॉइंट का आकार मान लौटाता है। Treemap और Sunburst चार्ट्स के साथ उपयोग किया जाता है। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | मान। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue। केवल-पढ़ने योग्य [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue). |

## विधियां

| नाम | विवरण |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट स्टाइल के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। यदि FillType NotDefined के बराबर है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | चार्ट सीरीज़ से DataPoint को हटाता है। |

### देखें

* इंटरफ़ेस [IChartDataPoint](../ichartdatapoint)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->