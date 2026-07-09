---
title: GeometryShape
second_title: Aspose.Sildes for .NET API संदर्भ
description: सभी ज्यामितीय आकृतियों के लिए पैरेंट क्लास का प्रतिनिधित्व करता है।
type: docs
weight: 4970
url: /hi/aspose.slides/geometryshape/
---
## GeometryShape क्लास

सभी ज्यामितीय आकृतियों के लिए पैरेंट क्लास का प्रतिनिधित्व करता है।

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकृति के समायोजन मानों का संग्रह लौटाता है। केवल पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकृति से संबद्ध वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकृति से संबद्ध वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि आकृति काली-श्वेत डिस्प्ले मोड में कैसे रेंडर होगी। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकृति के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | आकृति पर लागू पिक्सेल इफेक्ट्स वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो इफ़ेक्ट प्रॉपर्टी नहीं रखतीं, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | आकृति के फ़िल फ़ॉर्मेट प्रॉपर्टी वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो फ़िल प्रॉपर्टी नहीं रखतीं, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकृति की ऊँचाई को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकृति छिपी हुई है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकृति समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | आकृति के लाइन फ़ॉर्मेट प्रॉपर्टी वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो लाइन प्रॉपर्टी नहीं रखतीं, null लौटाया जा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकृति का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकृति के जीवनकाल के दौरान स्थिर रहने वाला स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है, जिससे PowerPoint या इंटरऑप कोड दस्तावेज़ में कहीं से भी आकृति को विश्वसनीय रूप से संदर्भित कर सकता है। केवल पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकृति समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकृति के लिए प्लेसहोल्डर लौटाता है। यदि आकृति के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्ची shape फ्रेम की प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | आकृति के लॉक को लौटाता है। केवल पढ़ने योग्य [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकृति की शैली ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | ज्यामिति प्रीसेट प्रकार को लौटाता है या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ने/लिखने योग्य [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकृति की पैरेंट स्लाइड को लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | आकृति के 3D इफ़ेक्ट प्रॉपर्टी वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो 3D प्रॉपर्टी नहीं रखतीं, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। चूँकि इस मान को उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकृति की चौड़ाई को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में आकृति की स्थिति को लौटाता है। Shapes[0] z-ऑर्डर के पीछे की आकृति लौटाता है, और Shapes[Shapes.Count - 1] आगे की आकृति लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टी सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकृति के तत्वों का एरे बनाता है और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकृति जिससे वर्तमान आकृति विरासत में मिली है)। यदि वर्तमान आकृति विरासत में नहीं मिली है तो null लौटाया जाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामितीय आकृति के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकृति के बाएँ ऊपरी कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए आकार के दृश्य बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | आकार की ज्यामिति को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](./shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | आकार की ज्यामिति को [`IGeometryPath`](../igeometrypath) की एरे से अपडेट करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](./shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### और देखें

* क्लास [Shape](../shape)
* इंटरफ़ेस [IGeometryShape](../igeometryshape)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->