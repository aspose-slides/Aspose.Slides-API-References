---
title: GeometryShape
second_title: Aspose.Sildes for .NET API संदर्भ
description: सभी ज्यामितीय आकारों के लिए पैरेंट क्लास का प्रतिनिधित्व करता है।
type: docs
weight: 4990
url: /hi/aspose.slides/geometryshape/
---
## GeometryShape क्लास

सभी ज्यामितीय आकारों के लिए पैरेंट क्लास का प्रतिनिधित्व करता है।

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection)। |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से संबंधित वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से संबंधित वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी यह निर्दिष्ट करती है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | आकार पर लागू पिक्सेल इफ़ेक्ट्स वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ आकार प्रकारों के लिए जो इफ़ेक्ट प्रॉपर्टी नहीं रखते, null लौट सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | आकार के भराव फ़ॉर्मेट प्रॉपर्टीज़ वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ आकार प्रकारों के लिए जो भराव प्रॉपर्टी नहीं रखते, null लौट सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई, पॉइंट्स में मापी गई, को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘सजावटी के रूप में चिह्नित’ विकल्प प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | आकार के लाइन फ़ॉर्मेट प्रॉपर्टीज़ वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ आकार प्रकारों के लिए जो लाइन प्रॉपर्टी नहीं रखते, null लौट सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ने/लिखने योग्य String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकार के जीवनकाल तक स्थिर रहने वाला स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है, जिससे PowerPoint या इंटरऑप कोड दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित कर सकता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के प्लेसहोल्डर को लौटाता है। यदि आकार के पास कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति को लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार के Z-अक्ष के चारों ओर घुमाव के डिग्री की संख्या को लौटाता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | आकार के लॉक को लौटाता है। केवल-पढ़ने योग्य [`IBaseShapeLock`](../ibaseshapelock)। |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार की शैली ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../ishapestyle)। |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | ज्यामिति प्रीसेट प्रकार को लौटाता या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान डिफ़ॉल्ट पर रीसेट हो जाएंगे। पढ़ने/लिखने योग्य [`ShapeType`](../shapetype)। |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार के पैरेंट स्लाइड को लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | आकार के 3D इफ़ेक्ट प्रॉपर्टीज़ वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ आकार प्रकारों के लिए जो 3D प्रॉपर्टी नहीं रखते, null लौट सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन या अन्य कोड द्वारा उपयोग के उद्देश्य से एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। चूँकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में न माना जाए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई, पॉइंट्स में मापी गई, को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के X-निर्देशांक को प्राप्त करता या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के Y-निर्देशांक को प्राप्त करता या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z-ऑर्डर में आकार की स्थिति को लौटाता है। Shapes[0] पीछे की स्थिति वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे की स्थिति वाला आकार लौटाता है। केवल-पढ़ने योग्य Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को एक निर्दिष्ट वाले पर सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों का एरे बनाता है और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामितीय आकार के पाथ की कॉपी लौटाता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमा प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | आकार ज्यामिति को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](./shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | आकार ज्यामिति को [`IGeometryPath`](../igeometrypath) के एरे से अपडेट करता है। निर्देशांक आकार के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](./shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* क्लास [Shape](../shape)
* इंटरफ़ेस [IGeometryShape](../igeometryshape)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->