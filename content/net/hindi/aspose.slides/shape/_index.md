---
title: Shape
second_title: Aspose.Sildes के लिए .NET API रेफ़रेंस
description: एक स्लाइड पर आकार का प्रतिनिधित्व करता है।
type: docs
weight: 9850
url: /hi/aspose.slides/shape/
---
## Shape क्लास

एक स्लाइड पर आकार का प्रतिनिधित्व करता है।

```csharp
public class Shape : IShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से संबद्ध वैकल्पिक पाठ को वापस करता है या सेट करता है। पढ़ने/लिखने String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से संबद्ध वैकल्पिक पाठ के शीर्षक को वापस करता है या सेट करता है। पढ़ने/लिखने String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | गुण निर्दिष्ट करता है कि एक shape ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या वापस करता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape का कस्टम डेटा वापस करता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल प्रभावों को सम्मिलित करने वाले EffectFormat ऑब्जेक्ट को वापस करता है। नोट: उन कुछ shape प्रकारों के लिए जो प्रभाव गुण नहीं रखते हैं, null वापस कर सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक shape के लिए फ़िल फ़ॉर्मेटिंग गुणों को सम्मिलित करने वाले FillFormat ऑब्जेक्ट को वापस करता है। नोट: उन कुछ shape प्रकारों के लिए जो फ़िल गुण नहीं रखते हैं, null वापस कर सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम के गुणों को वापस करता है या सेट करता है। पढ़ने/लिखने [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई, पॉइंट में मापी गई, को प्राप्त करता है या सेट करता है। पढ़ने/लिखने Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छिपा है या नहीं। पढ़ने/लिखने Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को वापस करता है या सेट करता है। पढ़ने/लिखने [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को वापस करता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को वापस करता है या सेट करता है। पढ़ने/लिखने [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक shape के लिए लाइन फ़ॉर्मेटिंग गुणों को सम्मिलित करने वाले LineFormat ऑब्जेक्ट को वापस करता है। नोट: उन कुछ shape प्रकारों के लिए जो लाइन गुण नहीं रखते हैं, null वापस कर सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक shape का नाम वापस करता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ने/लिखने String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक slide-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो shape के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ने योग्य UInt32। देखें [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक shape के लिए प्लेसहोल्डर लौटाता है। यदि shape के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक slide की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे shape फ्रेम के गुणों को वापस करता है या सेट करता है। पढ़ने/लिखने [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को वापस करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव को दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घुमाव को दर्शाता है। पढ़ने/लिखने Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | shape के लॉक को वापस करता है। केवल पढ़ने योग्य [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक shape की पैरेंट slide लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक shape के लिए 3D प्रभाव गुणों को सम्मिलित करने वाले ThreeDFormat ऑब्जेक्ट को वापस करता है। नोट: उन कुछ shape प्रकारों के लिए जिनके पास 3D गुण नहीं हैं, null वापस कर सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाना है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई, पॉइंट में मापी गई, को प्राप्त करता है या सेट करता है। पढ़ने/लिखने Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ने/लिखने Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ने/लिखने Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-order में एक shape की स्थिति को वापस करता है। Shapes[0] z-order के पीछे वाले shape को लौटाता है, और Shapes[Shapes.Count - 1] आगे वाले shape को लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder नहीं है तो एक नया placeholder जोड़ता है और placeholder गुणों को निर्दिष्ट किए गए एक में सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक placeholder shape लौटाता है (layout और/या master slide से shape जो वर्तमान shape से विरासत में मिला हो)। यदि वर्तमान shape विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप में ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार का उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की दृश्य बाउंड्स को प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape placeholder नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सेव करता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सेव करता है। |

### देखें

* इंटरफ़ेस [IShape](../ishape)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->