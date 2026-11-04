---
title: IChartDataPoint
second_title: Aspose.Sildes for .NET API संदर्भ
description: सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
weight: 1840
url: /hi/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint इंटरफ़ेस

Represents series data point.

```csharp
public interface IChartDataPoint : IActualLayout
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | IActualLayout इंटरफ़ेस लौटाता है। |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | चार्ट डेटा बिंदु का बबल आकार प्राप्त करता है। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue)। |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | चार्ट डेटा बिंदु के कैश किए गए बबल आकार को प्राप्त करता है। केवल-पढ़ने योग्य [`ICachedChartValue`](../icachedchartvalue)। |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | चार्ट डेटा बिंदु के कैश किए गए मान को प्राप्त करता है। केवल-पढ़ने योग्य [`ICachedChartValue`](../icachedchartvalue)। |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | चार्ट डेटा बिंदु के कैश किए गए X मान को प्राप्त करता है। केवल-पढ़ने योग्य [`ICachedChartValue`](../icachedchartvalue)। |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | चार्ट डेटा बिंदु के कैश किए गए Y मान को प्राप्त करता है। केवल-पढ़ने योग्य [`ICachedChartValue`](../icachedchartvalue)। |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | चार्ट डेटा बिंदु का रंग मान प्राप्त करता है। मानचित्र चार्ट्स के साथ उपयोग किया जाता है। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue)। |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | डेटा बिंदु स्तरों का कंटेनर लौटाता है। Treeamp और Sunburst श्रृंखलाओं के लिए लागू है। डेटा बिंदु स्तरों की अनुक्रमणिका शून्य-आधारित है। |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | कस्टम मान प्रकार के मामले में श्रृंखला त्रुटि बार मानों का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [`IErrorBarsCustomValues`](../ierrorbarscustomvalues)। |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | डेटा बिंदु को पाई के केंद्र से कितनी दूरी पर ले जाना है, यह निर्दिष्ट करता है। पढ़ें/लिखें Int32। |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | स्वरूपण गुणों का प्रतिनिधित्व करता है। पढ़ें/लिखें [`IFormat`](../iformat)। |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | निर्धारित करता है कि इस डेटा बिंदु को पैरेंट की बाल संग्रह में किस पर लागू किया जाता है। पढ़ें UInt32। |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | यदि मान नकारात्मक है तो डेटा बिंदु के रंग उलटने को निर्दिष्ट करता है। पढ़ें/लिखें Boolean। |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | बबल्स पर 3-डी प्रभाव लागू होने को निर्दिष्ट करता है। पढ़ें/लिखें Boolean। |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | चार्ट डेटा बिंदु का लेबल दर्शाता है। केवल-पढ़ने योग्य [`IDataLabel`](../idatalabel)। |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | डेटा मार्कर निर्दिष्ट करता है। केवल-पढ़ने योग्य [`IMarker`](../imarker)। |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | इस सूची में चार्ट प्रकार के मामले में संबंधित लेजेंड प्रविष्टि के गुण: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। केवल-पढ़ने योग्य [`ILegendEntryProperties`](../ilegendentryproperties)। |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | डेटा बिंदु को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू। |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | चार्ट डेटा बिंदु का आकार मान प्राप्त करता है। Treemap और Sunburst चार्ट्स के साथ उपयोग किया जाता है। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue)। |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | चार्ट डेटा बिंदु का मान प्राप्त करता है। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue)। |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | चार्ट डेटा बिंदु का x मान प्राप्त करता है। केवल-पढ़ने योग्य [`IStringOrDoubleChartValue`](../istringordoublechartvalue)। |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | चार्ट डेटा बिंदु का y मान प्राप्त करता है। केवल-पढ़ने योग्य [`IDoubleChartValue`](../idoublechartvalue)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | श्रृंखला इंडेक्स, डेटा बिंदु इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट शैली के आधार पर डेटा बिंदु का स्वतः रंग लौटाता है। यदि FillType NotDefined के बराबर है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | चार्ट श्रृंखला से DataPoint हटाता है। |

### संबंधित देखें

* इंटरफ़ेस [IActualLayout](../iactuallayout)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->