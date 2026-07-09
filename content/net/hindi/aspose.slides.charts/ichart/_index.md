---
title: IChart
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।
type: docs
weight: 1740
url: /hi/aspose.slides.charts/ichart/
---
## IChart इंटरफ़ेस

एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | आधार IFormattedTextContainer इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | आधार IGraphicalObject इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | IOverrideThemeable इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | चार्ट एक्सिस तक पहुँच प्रदान करता है। केवल-पढ़ने योग्य [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट की बैक वॉल के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल-पढ़ने योग्य [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | चार्ट से जुड़े लिंक्ड या एम्बेडेड डेटा की जानकारी लौटाता है। केवल-पढ़ने योग्य [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | एक चार्ट की डेटा टेबल लौटाता है। केवल-पढ़ने योग्य [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | एक चार्ट शीर्षक लौटाता या सेट करता है। केवल-पढ़ने योग्य [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | एक चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट के फ़्लोर के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल-पढ़ने योग्य [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | निर्धारित करता है कि क्या चार्ट में डेटा टेबल है। पढ़ने/लिखने योग्य Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | निर्धारित करता है कि क्या चार्ट में लेजेंड है। पढ़ने/लिखने योग्य Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | निर्धारित करता है कि चार्ट क्षेत्र में गोल किनारे हों। पढ़ने/लिखने योग्य Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | निर्धारित करता है कि क्या चार्ट में दिखाई देने वाला शीर्षक है। पढ़ने/लिखने योग्य Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | एक चार्ट के लिए लेजेंड लौटाता या सेट करता है। केवल-पढ़ने योग्य [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | चार्ट के प्लॉट एरिया का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | निर्धारित करता है कि केवल दृश्यमान कोशिकाएँ ही प्लॉट की जाएँ। दोनों दृश्यमान और छिपी कोशिकाओं को प्लॉट करने के लिए false सेट करें। पढ़ने/लिखने योग्य Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | एक चार्ट का 3D घूर्णन लौटाता है। केवल-पढ़ने योग्य [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | निर्धारित करता है कि चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ। पढ़ने/लिखने योग्य Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट की साइट वॉल के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल-पढ़ने योग्य [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | चार्ट शैली लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | चार्ट प्रकार लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | चार्ट के ऊपर खींची गई आकृतियों को निर्दिष्ट करता है। केवल-पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | चार्ट तत्वों के वास्तविक मानों की गणना करता है। वास्तविक मान उन तत्वों की स्थिति शामिल करते हैं जो IActualLayout इंटरफ़ेस को लागू करते हैं (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) और वास्तविक एक्सिस मान (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### देखें भी

* इंटरफ़ेस [IFormattedTextContainer](../iformattedtextcontainer)
* इंटरफ़ेस [IGraphicalObject](../../aspose.slides/igraphicalobject)
* इंटरफ़ेस [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->