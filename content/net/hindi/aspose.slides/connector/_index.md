---
title: Connector
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक कनेक्टर का प्रतिनिधित्व करता है।
type: docs
weight: 2670
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
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से संबंधित वैकल्पिक पाठ को लौटाता या निर्धारित करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से संबंधित वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्धारित करती है कि आकार काली-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | कनेक्टर के लॉक लौटाता है। केवल-पढ़ने योग्य [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | आकार पर लागू पिक्सल प्रभावों को शामिल करने वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: उन आकारों के प्रकारों के लिए जो प्रभाव गुण नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | कनेक्टर के अंत को संलग्न करने के लिए आकार को लौटाता या सेट करता है। पढ़ें/लिखें [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | अंतिम आकार के लिए कनेक्शन साइट का सूचकांक लौटाता या सेट करता है। पढ़ें/लिखें UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | आकार के लिए भरने के फ़ॉर्मेटिंग गुणों को शामिल करने वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: उन आकारों के प्रकारों के लिए जो भराव गुण नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुण लौटाता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई, पॉइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त करता या सेट करता है। Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | आकार के लिए रेखा फ़ॉर्मेटिंग गुणों को शामिल करने वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: उन आकारों के प्रकारों के लिए जिनमें रेखा गुण नहीं हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता या सेट करता है। null नहीं होना चाहिए। आवश्यकता पड़े तो खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकार के जीवनकाल के दौरान स्थिर रहने वाला स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल-पढ़ने योग्य UInt32। देखें भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम के गुण लौटाता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाए जाने के डिग्री की संख्या लौटाता या सेट करता है। धनात्मक मान घड़ी की दिशा में घुमाव को दर्शाता है; ऋणात्मक मान घड़ी की विपरीत दिशा में घुमाव को दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IConnectorLock`](../iconnectorlock)। (2 गुण) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार की शैली ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | AutoShape प्रकार को लौटाता या सेट करता है। पढ़ें/लिखें [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | कनेक्टर की शुरुआत को संलग्न करने के लिए आकार को लौटाता या सेट करता है। पढ़ें/लिखें [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | प्रारंभिक आकार के लिए कनेक्शन साइट का सूचकांक लौटाता या सेट करता है। पढ़ें/लिखें UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक आकार के लिए 3D प्रभाव गुणों को रखने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: उन आकारों के प्रकारों के लिए जिनमें 3D गुण नहीं हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन या अन्य कोड द्वारा उपयोग के लिए निर्धारित एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई, पॉइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | एक आकार की z-क्रम में स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] सामने वाला आकार लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियां

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुण निर्धारित करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों का सरणी बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (आकार लेआउट और/या मास्टर स्लाइड से जो वर्तमान आकार से विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामितीय आकार के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार की थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार प्रयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार की थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमा प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [Reroute](../../aspose.slides/connector/reroute)() | कनेक्टर को पुनः मार्गित करता है ताकि वह जुड़े हुए आकारों के बीच सबसे छोटा संभव पथ ले। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से आकार की ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) की सरणी से आकार की ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। आकार का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* वर्ग [GeometryShape](../geometryshape)
* इंटरफ़ेस [IConnector](../iconnector)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->