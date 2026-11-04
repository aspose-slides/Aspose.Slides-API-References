---
title: Chart
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।
type: docs
weight: 1270
url: /hi/aspose.slides.charts/chart/
---
## Chart क्लास

एक स्लाइड पर ग्राफ़िक चार्ट का प्रतिनिधित्व करता है।

```csharp
public class Chart : GraphicalObject, IChart
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से संबंधित वैकल्पिक टेक्स्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से संबंधित वैकल्पिक टेक्स्ट के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String। |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | बेस IFormattedTextContainer इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IFormattedTextContainer`](../iformattedtextcontainer)। |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | बेस IThemeable इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IThemeable`](../../aspose.slides.theme/ithemeable)। |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | चार्ट एक्सिस तक पहुँच प्रदान करता है। केवल पढ़ने योग्य [`IAxesManager`](../iaxesmanager)। |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट की बैक वाल के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [`IChartWall`](../ichartwall)। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्दिष्ट करती है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)। |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | एक चार्ट से जुड़े लिंक्ड या एंबेडेड डेटा के बारे में जानकारी लौटाता है। केवल पढ़ने योग्य [`IChartData`](../ichartdata)। |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | एक चार्ट की डेटा टेबल लौटाता है। केवल पढ़ने योग्य [`IDataTable`](../idatatable)। |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | एक चार्ट का शीर्षक प्राप्त करता है या सेट करता है। केवल पढ़ने योग्य [`IChartTitle`](../icharttitle)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइट्स की संख्या लौटाता है। केवल पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../../aspose.slides/icustomdata)। |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | एक चार्ट पर खाली सेल्स को प्लॉट करने का तरीका प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`DisplayBlanksAsType`](../displayblanksastype)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: कुछ प्रकार के आकार जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होतीं, उनके लिए null लौट सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनमें फ़िल प्रॉपर्टीज़ नहीं होतीं, उनके लिए null लौट सकता है। केवल पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat)। |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट के फ़्लोर के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [`IChartWall`](../ichartwall)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe)। |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | निर्धारित करता है कि क्या एक चार्ट में डेटा टेबल है। पढ़ें/लिखें Boolean। |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | निर्धारित करता है कि क्या एक चार्ट में लेजेंड है। पढ़ें/लिखें Boolean। |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | निर्दिष्ट करता है कि चार्ट क्षेत्र के कोने गोल हों। पढ़ें/लिखें Boolean। |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | निर्धारित करता है कि क्या एक चार्ट में दृश्यमान शीर्षक है। पढ़ें/लिखें Boolean। |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई प्राप्त करता है या सेट करता है, जो पॉइंट्स में मापी जाती है। पढ़ें/लिखें Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि क्या आकार छिपा हुआ है। पढ़ें/लिखें Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink)। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि क्या आकार ग्रुपेड है। केवल पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि क्या आकार TextHolder_PPT है। केवल पढ़ने योग्य Boolean। |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | एक चार्ट के लिए लेजेंड को प्राप्त करता है या सेट करता है। केवल पढ़ने योग्य [`ILegend`](../ilegend)। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनमें लाइन प्रॉपर्टीज़ नहीं होतीं, उनके लिए null लौट सकता है। केवल पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकार का नाम प्राप्त करता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है जो आकार के जीवनकाल के लिए स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ने योग्य UInt32। देखें [`UniqueId`](../../aspose.slides/shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार ग्रुपेड है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../../aspose.slides/iplaceholder)। |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | एक चार्ट के प्लॉट एरिया का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [`IChartPlotArea`](../ichartplotarea)। |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | निर्धारित करता है कि केवल दृश्यमान सेल्स प्लॉट किए जाएँ। दोनों दृश्यमान और छिपे सेल्स प्लॉट करने के लिए false सेट करें। पढ़ें/लिखें Boolean। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../../aspose.slides/ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ आकार फ्रेम की प्रॉपर्टीज़ प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe)। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार के Z-अक्ष के चारों ओर घुमने के डिग्री की संख्या प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single। |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | एक चार्ट की 3D रोटेशन लौटाता है। केवल पढ़ने योग्य [`IRotation3D`](../irotation3d)। |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। (2 प्रॉपर्टीज़) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | निर्धारित करता है कि चार्ट के अधिकतम पर डेटा लेबल दिखाए जाने चाहिए। पढ़ें/लिखें Boolean। |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | एक ऑब्जेक्ट लौटाता है जो 3D चार्ट की साइड वॉल के फ़ॉर्मेट को बदलने की अनुमति देता है। केवल पढ़ने योग्य [`IChartWall`](../ichartwall)। |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकार की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../../aspose.slides/ibaseslide)। |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | चार्ट स्टाइल प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`StyleType`](../styletype)। |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। यह प्रॉपर्टी नीचे दिए गए प्रकारों के लिए लागू नहीं है: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker। केवल पढ़ने योग्य [`IChartTextFormat`](../icharttextformat)। |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | थीम मैनेजर लौटाता है। केवल पढ़ने योग्य [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए 3D इफ़ेक्ट प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनमें 3D प्रॉपर्टीज़ नहीं होते, उनके लिए null लौट सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../../aspose.slides/ithreedformat)। |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | चार्ट प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`ChartType`](../charttype)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक इंटर्नल, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन्स या अन्य कोड द्वारा किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे एक स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)। |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | चार्ट के ऊपर खींचे गए आकारों को निर्दिष्ट करता है। केवल पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई प्राप्त करता है या सेट करता है, जो पॉइंट्स में मापी जाती है। पढ़ें/लिखें Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को प्राप्त करता है या सेट करता है, जो पॉइंट्स में मापी जाती है। पढ़ें/लिखें Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को प्राप्त करता है या सेट करता है, जो पॉइंट्स में मापी जाती है। पढ़ें/लिखें Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | एक आकार की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है। केवल पढ़ने योग्य Int32। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | इस चार्ट के लिए प्रभावी थीम लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार इनहेरिटेड है)। यदि वर्तमान आकार इनहेरिटेड नहीं है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग होता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की दृश्य सीमाएँ प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | चार्ट तत्वों के वास्तविक मानों की गणना करता है। वास्तविक मानों में उन तत्वों की स्थिति शामिल है जो IActualLayout इंटरफ़ेस को इम्प्लीमेंट करते हैं (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) तथा वास्तविक एक्सिस मान (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [IChart](../ichart)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->