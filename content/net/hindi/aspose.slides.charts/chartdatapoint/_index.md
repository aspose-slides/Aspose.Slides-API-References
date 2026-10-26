---
title: ChartDataPoint
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
weight: 1330
url: /hi/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint क्लास

सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Properties

| Name | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | चार्ट तत्व का वास्तविक x स्थान (बाएँ) चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | चार्ट तत्व का वास्तविक शीर्ष चार्ट के बाएँ शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize। केवल-पढ़ने-योग्य [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | चार्ट डेटा पॉइंट का रंग मान लौटाता है। Map चार्ट्स के साथ उपयोग किया जाता है। केवल-पढ़ने-योग्य [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | डेटा पॉइंट स्तरों का कंटेनर लौटाता है। TreeMap और Sunburst श्रृंखलाओं के लिए लागू। डेटा पॉइंट स्तरों की इंडेक्सिंग शून्य-आधारित है। |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | कस्टम वैल्यू प्रकार के मामले में सीरीज़ एरर बार मान दर्शाता है। केवल-पढ़ने-योग्य [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | डेटा पॉइंट को पाई के केंद्र से हटाने की मात्रा निर्दिष्ट करता है। पढ़ें/लिखें Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | फ़ॉर्मेटिंग प्रॉपर्टीज़ दर्शाता है। पढ़ें/लिखें [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | यदि मान नकारात्मक हो तो डेटा पॉइंट अपने रंग उलट देगा। पढ़ें/लिखें Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | निर्दिष्ट करता है कि बबल्स पर 3-D इफ़ेक्ट लागू हो। पढ़ें/लिखें Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | लेबल। केवल-पढ़ने-योग्य [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | डेटा मार्कर निर्दिष्ट करता है। केवल-पढ़ने-योग्य [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | सूची में से चार्ट प्रकार के लिए संबंधित लेजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। केवल-पढ़ने-योग्य [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू। |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | चार्ट डेटा पॉइंट का आकार मान लौटाता है। Treemap और Sunburst चार्ट्स के साथ उपयोग किया जाता है। केवल-पढ़ने-योग्य [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | मान। केवल-पढ़ने-योग्य [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue। केवल-पढ़ने-योग्य [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue। केवल-पढ़ने-योग्य [`IDoubleChartValue`](../idoublechartvalue). |

## Methods

| Name | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | डेटा पॉइंट का एक स्वचालित रंग लौटाता है जो series index, data point index, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट शैली पर आधारित है। यदि FillType NotDefined के बराबर है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | चार्ट सीरीज़ से DataPoint को हटाता है। |

### देखे भी

* इंटरफ़ेस [IChartDataPoint](../ichartdatapoint)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->