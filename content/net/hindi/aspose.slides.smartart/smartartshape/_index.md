---
title: SmartArtShape
second_title: Aspose.Sildes for .NET API संदर्भ
description: SmartArt आकार का प्रतिनिधित्व करता है
type: docs
weight: 10660
url: /hi/aspose.slides.smartart/smartartshape/
---
## SmartArtShape वर्ग

SmartArt आकार का प्रतिनिधित्व करता है

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से जुड़े वैकल्पिक पाठ को लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | संपत्ति निर्धारित करती है कि आकार काली-श्वेत डिस्प्ले मोड में कैसे प्रदर्शित होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | आकार पर लागू पिक्सेल प्रभावों को शामिल करने वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: उन आकारों के कुछ प्रकारों के लिए जो प्रभाव गुण नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | आकार के भराव स्वरूप गुणों को शामिल करने वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: उन आकारों के कुछ प्रकारों के लिए जो भराव गुण नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को पॉइंट्स में मापकर प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | आकार के लाइन स्वरूप गुणों को शामिल करने वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: उन आकारों के कुछ प्रकारों के लिए जो लाइन गुण नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकार के जीवनकाल के दौरान स्थिर रहने वाला स्लाइड-स्कोप्ड अनूठा पहचानकर्ता लौटाता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमा किए गए डिग्री की संख्या लौटाता या सेट करता है। धनात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; ऋणात्मक मान वामावर्त घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार के शैली ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | ज्यामिति प्रीसेट प्रकार को लौटाता या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों में रीसेट हो जाएंगे। पढ़ने/लिखने योग्य [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | SmartArt आकार का पाठ लौटाता है। केवल-पढ़ने योग्य [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | आकार के लिए 3D प्रभाव गुणों को शामिल करने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: उन आकारों के कुछ प्रकारों के लिए जो 3D गुण नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुन: सौंपा जा सकता है, इसे स्थायी अनन्य कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को पॉइंट्स में मापकर प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापकर प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापकर प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-क्रम में आकार की स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे का आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे का आकार लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणों को सेट करता है. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों का एरे बनाता और लौटाता है. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है). यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाया जाता है. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति आकार के पथ की प्रति लौटाता है. निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होते हैं. |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार की थंबनेल लौटाता है. डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार की थंबनेल लौटाता है. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए सामग्री से गणना किए गए आकार की दृश्य सीमाएँ प्राप्त करता है. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | आकार ज्यामिति को [`IGeometryPath`](../../aspose.slides/igeometrypath) ऑब्जेक्ट से अपडेट करता है. निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होना चाहिए. आकार के प्रकार ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) को कस्टम में बदलता है. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | आकार ज्यामिति को [`IGeometryPath`](../../aspose.slides/igeometrypath) की एरे से अपडेट करता है. निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होना चाहिए. आकार के प्रकार ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) को कस्टम में बदलता है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |

### देखें

* वर्ग [GeometryShape](../../aspose.slides/geometryshape)
* इंटरफ़ेस [ISmartArtShape](../ismartartshape)
* नामस्थान [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->