---
title: Connector
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक कनेक्टर का प्रतिनिधित्व करता है।
type: docs
weight: 2690
url: /hi/aspose.slides/connector/
---
## Connector वर्ग

एक कनेक्टर का प्रतिनिधित्व करता है।

```csharp
public class Connector : GeometryShape, IConnector
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकार के समायोजन मानों का संग्रह लौटाता है। केवल पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection)। |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्दिष्ट करती है कि एक आकार काले-सफ़ेद प्रदर्शन मोड में कैसे प्रस्तुत होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32। |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | कनेक्टर के लॉक लौटाता है। केवल पढ़ने योग्य [`IConnectorLock`](../iconnectorlock)। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार के आकार जिनमें प्रभाव गुण नहीं होते, के लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | कनेक्टर के अंत को संलग्न करने के लिए आकार लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShape`](../ishape)। |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | अंत आकार के लिए कनेक्शन साइट के सूचकांक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य UInt32। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के भराव स्वरूपण गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें भराव गुण नहीं होते, के लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुणों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को बिंदुओं में मापते हुए लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहबद्ध है या नहीं। केवल पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लाइन स्वरूपण गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें लाइन गुण नहीं होते, के लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकार का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ने/लिखने योग्य String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-सीमित अद्वितीय पहचानकर्ता लौटाता है जो आकार के आयु तक स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार का विश्वसनीय संदर्भ देने देता है। केवल पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहबद्ध है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम के गुणों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या लौटाता है या सेट करता है। धनात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; ऋणात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [`IConnectorLock`](../iconnectorlock)। (2 गुण) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार के शैली ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [`IShapeStyle`](../ishapestyle)। |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | AutoShape प्रकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`ShapeType`](../shapetype)। |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकार की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide)। |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | कनेक्टर की शुरुआत को संलग्न करने के लिए आकार को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShape`](../ishape)। |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | शुरू आकार के लिए कनेक्शन साइट के सूचकांक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य UInt32। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें 3D गुण नहीं होते, के लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन या अन्य कोड द्वारा उपयोग के लिये एक आंतरिक, प्रस्तुति-सीमित पहचानकर्ता लौटाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को बिंदुओं में मापते हुए प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को बिंदुओं में मापते हुए प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को बिंदुओं में मापते हुए प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | एक आकार की z-क्रम में स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे वाले आकार को लौटाता है, और Shapes[Shapes.Count - 1] आगे वाले आकार को लौटाता है। केवल पढ़ने योग्य Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणों को सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों का एरे बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में लिया गया है)। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटाया जाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति आकार के पाथ की प्रतिलिपि लौटाता है। निर्देशांक आकार के बाएँ ऊपर कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए हुए कंटेंट से गणना किए गए आकार की दृश्य सीमाओं को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [Reroute](../../aspose.slides/connector/reroute)() | कनेक्टर को पुनः मार्गित करता है ताकि वह जुड़े हुए आकारों के बीच सबसे छोटा संभव पथ ले। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से आकार की ज्यामिति को अद्यतन करता है। निर्देशांक आकार के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) एरे से आकार की ज्यामिति को अद्यतन करता है। निर्देशांक आकार के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* वर्ग [GeometryShape](../geometryshape)
* इंटरफ़ेस [IConnector](../iconnector)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->