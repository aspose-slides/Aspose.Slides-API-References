---
title: GraphicalObject
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: अमूर्त ग्राफ़िकल ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 5070
url: /hi/aspose.slides/graphicalobject/
---
## GraphicalObject क्लास

एक अमूर्त ग्राफ़िकल ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि एक shape काले-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइट्स की संख्या लौटाता है। केवल-पढ़ें Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape का कस्टम डेटा लौटाता है। केवल-पढ़ें [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल प्रभावों को शामिल करने वाला EffectFormat ऑब्जेक्ट लौटाता है। नोट: कुछ प्रकार के shapes जिनके पास effect प्रॉपर्टीज़ नहीं हैं, उनके लिए null लौटाया जा सकता है। केवल-पढ़ें [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक shape के लिए भराव फॉर्मेटिंग प्रॉपर्टीज़ को शामिल करने वाला FillFormat ऑब्जेक्ट लौटाता है। नोट: कुछ प्रकार के shapes जिनके पास fill प्रॉपर्टीज़ नहीं हैं, उनके लिए null लौटाया जा सकता है। केवल-पढ़ें [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक लौटाता है। केवल-पढ़ें [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई को पॉइंट में लौटाता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छिपी हुई है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। केवल-पढ़ें [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। केवल-पढ़ें Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। केवल-पढ़ें Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक shape के लिए लाइन फॉर्मेटिंग प्रॉपर्टीज़ को शामिल करने वाला LineFormat ऑब्जेक्ट लौटाता है। नोट: कुछ प्रकार के shapes जिनके पास line प्रॉपर्टीज़ नहीं हैं, उनके लिए null लौटाया जा सकता है। केवल-पढ़ें [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape का नाम लौटाता है या सेट करता है। null न होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | slide-स्कोप्ड एक अद्वितीय पहचानकर्ता लौटाता है जो shape के जीवनकाल तक स्थिर रहता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape का विश्वसनीय संदर्भ प्रदान करता है। केवल-पढ़ें UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है, अन्यथा null लौटाता है। केवल-पढ़ें [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape के लिए प्लेसहोल्डर लौटाता है। यदि shape में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ें [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | slide का पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ें [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | raw shape फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान उल्टा दिशा दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक लौटाता है। केवल-पढ़ें [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टीज़) |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट slide लौटाता है। केवल-पढ़ें [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape के 3D प्रभाव प्रॉपर्टीज़ को शामिल करने वाला ThreeDFormat ऑब्जेक्ट लौटाता है। नोट: कुछ प्रकार के shapes जिनके पास 3D प्रॉपर्टीज़ नहीं हैं, उनके लिए null लौटाया जा सकता है। केवल-पढ़ें [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | अंतःस्थ, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन्स या अन्य कोड द्वारा किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ें UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई को पॉइंट में लौटाता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में लौटाता है या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में लौटाता है या सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-क्रम में shape की स्थिति लौटाता है। Shapes[0] पीछे की ओर वाला shape लौटाता है, और Shapes[Shapes.Count - 1] आगे की ओर वाला shape लौटाता है। केवल-पढ़ें Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder मौजूद नहीं है तो नया placeholder जोड़ता है और placeholder की प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी placeholder shape लौटाता है (layout या master slide से वह shape जिससे वर्तमान shape विरासत में मिला है)। यदि वर्तमान shape विरासत में नहीं मिला है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बॉन्ड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए कंटेंट से गणना किए गए shape की विज़ुअल बॉन्ड्स प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | यह परिभाषित करता है कि यह shape placeholder नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* क्लास [Shape](../shape)
* इंटरफ़ेस [IGraphicalObject](../igraphicalobject)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->