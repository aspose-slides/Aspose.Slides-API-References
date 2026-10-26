---
title: Connector
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक कनेक्टर का प्रतिनिधित्व करता है।
type: docs
weight: 2670
url: /hi/aspose.slides/connector/
---
## Connector क्लास

एक कनेक्टर को दर्शाता है।

```csharp
public class Connector : GeometryShape, IConnector
```

## गुण

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | शेप के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक शेप से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक शेप से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि एक शेप काली-और-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगी.. पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइट्स की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | कनेक्टर के लॉक लौटाता है। केवल-पढ़ने योग्य [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | शेप पर लागू पिक्सेल इफ़ेक्ट्स वाला EffectFormat ऑब्जेक्ट लौटाता है। नोट: उन शेप के प्रकारों के लिए जो इफ़ेक्ट प्रॉपर्टीज नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | कनेक्टर के अंत को संलग्न करने के लिए शेप को लौटाता है या सेट करता है। पढ़ें/लिखें [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | अंत वाले शेप के कनेक्शन साइट का अनुक्रमांक लौटाता है या सेट करता है। पढ़ें/लिखें UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | शेप के लिए भराव फॉर्मेटिंग प्रॉपर्टीज वाला FillFormat ऑब्जेक्ट लौटाता है। नोट: उन शेप के प्रकारों के लिए जो भराव प्रॉपर्टीज नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम की प्रॉपर्टीज लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेप की ऊँचाई को पॉइंट्स में प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शेप छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए निर्धारित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए निर्धारित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शेप समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | शेप के लाइन फॉर्मेटिंग प्रॉपर्टीज वाला LineFormat ऑब्जेक्ट लौटाता है। नोट: उन शेप के प्रकारों के लिए जिनमें लाइन प्रॉपर्टीज नहीं हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक शेप का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक हो तो खाली स्ट्रिंग मान का प्रयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | शेप के जीवनकाल के दौरान स्थायी रहने वाला स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी शेप को भरोसेमंद रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32. देखें भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | शेप के लिए प्लेसहोल्डर लौटाता है। यदि शेप के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे शेप फ्रेम की प्रॉपर्टीज लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शेप द्वारा z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिगणात्मक घूर्णन दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | शेप के लॉक लौटाता है। केवल-पढ़ने योग्य [`IConnectorLock`](../iconnectorlock). (2 प्रॉपर्टीज) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | शेप के स्टाइल ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | AutoShape प्रकार को लौटाता है या सेट करता है। पढ़ें/लिखें [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक शेप की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | कनेक्टर की शुरुआत को संलग्न करने के लिए शेप को लौटाता है या सेट करता है। पढ़ें/लिखें [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | आरंभिक शेप के कनेक्शन साइट का अनुक्रमांक लौटाता है या सेट करता है। पढ़ें/लिखें UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | शेप के 3D इफ़ेक्ट प्रॉपर्टीज वाला ThreeDFormat ऑब्जेक्ट लौटाता है। नोट: उन शेप के प्रकारों के लिए जिनमें 3D प्रॉपर्टीज नहीं हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन्स या अन्य कोड द्वारा उपयोग हेतु एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। क्योंकि यह मान उपयोगकर्ता द्वारा या प्रोग्रामेटिक रूप से पुनः असाइन किया जा सकता है, इसे स्थायी अद्वैत कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32. देखें भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | शेप की चौड़ाई को पॉइंट्स में प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | शेप के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेप के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | शेप की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] पीछे की ओर वाला शेप लौटाता है, और Shapes[Shapes.Count - 1] आगे की ओर वाला शेप लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियाँ

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर की प्रॉपर्टीज़ को निर्दिष्ट एक पर सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | शेप के तत्वों का एरे बनाता है और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर शेप लौटाता है (लेआउट और/या मास्टर स्लाइड से वह शेप जिससे वर्तमान शेप विरासत में मिला है)। यदि वर्तमान शेप विरासत में नहीं मिला है तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति शेप के पथ की प्रतिलिपि लौटाता है। निर्देशांक शेप के बाएँ ऊपर कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | शेप थंबनेल लौटाता है। डिफ़ॉल्ट रूप में ShapeThumbnailBounds.Shape शेप थंबनेल बाउंड्स प्रकार का उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेप थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए कंटेंट से गणना किए गए शेप की दृश्य सीमा प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| [Reroute](../../aspose.slides/connector/reroute)() | कनेक्टर को फिर से रूट करता है ताकि वह जुड़े हुए शेप के बीच संभावित सबसे छोटा मार्ग ले। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | शेप ज्योमेट्री को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक शेप के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | शेप ज्योमेट्री को [`IGeometryPath`](../igeometrypath) की एरे से अपडेट करता है। निर्देशांक शेप के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें भी

* क्लास [GeometryShape](../geometryshape)
* इंटरफ़ेस [IConnector](../iconnector)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->