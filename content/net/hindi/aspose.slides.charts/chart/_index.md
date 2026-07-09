---
title: Chart
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: एक स्लाइड पर ग्राफिक चार्ट का प्रतिनिधित्व करता है।
type: docs
weight: 1260
url: /hi/aspose.slides.charts/chart/
---
## Chart क्लास

Represents an graphic chart on a slide.

```csharp
public class Chart : GraphicalObject, IChart
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से संबद्ध वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से संबद्ध वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | बेस IFormattedTextContainer इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | बेस IThemeable इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | चार्ट एक्सिस तक पहुंच प्रदान करता है। केवल-पढ़ने योग्य [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | 3D चार्ट की बैक वॉल के फॉर्मैट को बदलने की अनुमति देने वाला वस्तु लौटाता है। केवल-पढ़ने योग्य [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्दिष्ट करता है कि एक आकार काले-और-सफेद प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | एक चार्ट से संबद्ध लिंक्ड या एम्बेडेड डेटा के बारे में जानकारी लौटाता है। केवल-पढ़ने योग्य [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | एक चार्ट की डेटा तालिका लौटाता है। केवल-पढ़ने योग्य [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | एक चार्ट का शीर्षक लौटाता है या सेट करता है। केवल-पढ़ने योग्य [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | एक चार्ट पर खाली कोशिकाओं को प्लॉट करने का तरीका लौटाता है या सेट करता है। पढ़ें/लिखें [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | आकार पर लागू पिक्सेल प्रभावों को शामिल करने वाला EffectFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जो प्रभाव गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | आकार के लिए भराव फ़ॉर्मेटिंग गुणों को शामिल करने वाला FillFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जो भराव गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | 3D चार्ट के फ़्लोर के फॉर्मैट को बदलने की अनुमति देने वाला वस्तु लौटाता है। केवल-पढ़ने योग्य [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुण लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | निर्धारित करता है कि चार्ट में डेटा तालिका है या नहीं। पढ़ें/लिखें Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | निर्धारित करता है कि चार्ट में लेजेंड है या नहीं। पढ़ें/लिखें Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | निर्देशित करता है कि चार्ट क्षेत्र में गोल कोने हों। पढ़ें/लिखें Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | निर्धारित करता है कि चार्ट में एक दृश्यमान शीर्षक है या नहीं। पढ़ें/लिखें Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई, पॉइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | एक चार्ट के लिए लेजेंड को प्राप्त या सेट करता है। केवल-पढ़ने योग्य [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | आकार के लिए रेखा फ़ॉर्मेटिंग गुणों को शामिल करने वाला LineFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जिनमें रेखा गुण नहीं होते, यह null लौट सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार की आयु तक स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार का विश्वसनीय रूप से संदर्भ देने की अनुमति देता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पिता GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | एक चार्ट के प्लॉट क्षेत्र का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | निर्धारित करता है कि केवल दृश्यमान कोशिकाएँ ही प्लॉट की जाएँ। दोनों दृश्यमान और छिपी कोशिकाओं को प्लॉट करने के लिए False सेट करें। पढ़ें/लिखें Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पिता प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम के गुणों को प्राप्त या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को प्राप्त या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विरोधी दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | एक चार्ट का 3D घुमाव लौटाता है। केवल-पढ़ने योग्य [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। (2 गुण) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | निर्देशित करता है कि चार्ट के अधिकतम पर डेटा लेबल दिखाए जाएँ। पढ़ें/लिखें Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | 3D चार्ट की साइड वॉल के फॉर्मैट को बदलने की अनुमति देने वाला वस्तु लौटाता है। केवल-पढ़ने योग्य [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पिता स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | चार्ट शैली को प्राप्त या सेट करता है। पढ़ें/लिखें [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। यह गुण निम्न प्रकारों पर लागू नहीं होता: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker। केवल-पढ़ने योग्य [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | थीम प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | आकार के लिए 3D प्रभाव गुणों को शामिल करने वाला ThreeDFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जिनमें 3D गुण नहीं होते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | चार्ट प्रकार को प्राप्त या सेट करता है। पढ़ें/लिखें [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामmatically द्वारा पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | चार्ट के ऊपर बनाए गए आकारों को निर्दिष्ट करता है। केवल-पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई, पॉइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] सामने वाला आकार लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुण सेट करता है। |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | इस चार्ट के लिए प्रभावी थीम लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग होता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की दृश्य सीमा प्राप्त करता है जो उसके रेंडर की गई सामग्री से गणना की जाती है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | चार्ट तत्वों के वास्तविक मानों की गणना करता है। वास्तविक मानों में उन तत्वों की स्थिति शामिल है जो IActualLayout इंटरफ़ेस (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) को लागू करते हैं और वास्तविक एक्सिस मान (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) शामिल हैं। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [IChart](../ichart)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->