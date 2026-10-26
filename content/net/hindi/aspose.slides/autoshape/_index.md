---
title: AutoShape
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक AutoShape का प्रतिनिधित्व करता है।
type: docs
weight: 900
url: /hi/aspose.slides/autoshape/
---
## AutoShape वर्ग

एक AutoShape का प्रतिनिधित्व करता है।

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकार के समायोजन मानों का संग्रह लौटाता है। केवल पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से जुड़े वैकल्पिक पाठ को लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | AutoShape के लॉक लौटाता है। केवल पढ़ने योग्य [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | संपत्ति निर्दिष्ट करती है कि आकार काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: उन आकारों के कुछ प्रकारों के लिए जो इफ़ेक्ट प्रॉपर्टी नहीं रखते, यह null लौटा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन आकारों के कुछ प्रकारों के लिए जो भराव प्रॉपर्टी नहीं रखते, यह null लौटा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को बिंदुओं में मापा जाता है, इसे प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि क्या आकार छिपा है। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि क्या आकार समूहित है। केवल पढ़ने योग्य Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | निर्दिष्ट करता है कि आकार एक टेक्स्ट बॉक्स है या नहीं। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन आकारों के कुछ प्रकारों के लिए जो लाइन प्रॉपर्टी नहीं रखते, यह null लौटा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता या सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल के दौरान स्थायी रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार का विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल पढ़ने योग्य UInt32। देखिए [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड का पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम की प्रॉपर्टीज़ को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या को लौटाता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विरुद्ध घड़ी दिशा में घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [`IAutoShapeLock`](../iautoshapelock). (2 गुण) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार की शैली ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | ज्यामिति प्रीसेट प्रकार को लौटाता या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनकी डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ने/लिखने योग्य [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार का पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | AutoShape के लिए TextFrame ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D इफ़ेक्ट प्रॉपर्टीज़ होते हैं। नोट: उन आकारों के कुछ प्रकारों के लिए जो 3D प्रॉपर्टीज़ नहीं रखते, यह null लौटा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः निर्धारित किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में उपयोग नहीं करना चाहिए। केवल पढ़ने योग्य UInt32। देखिए [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | निर्धारित करता है कि यह AutoShape स्लाइड की पृष्ठभूमि भराव से भरा जाना चाहिए या शैली/भराव फ़ॉर्मेट द्वारा निर्दिष्ट। पढ़ने/लिखने योग्य Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को बिंदुओं में प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को बिंदुओं में प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के y-निर्देशांक को बिंदुओं में प्राप्त या सेट करता है। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] पीछे की स्थिति वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे की स्थिति वाला आकार लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | आकार में एक नया TextFrame जोड़ता है। यदि आकार में पहले से TextFrame है तो केवल उसका टेक्स्ट बदल देता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों का एरे बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट या मास्टर स्लाइड से वह आकार जिसे वर्तमान आकार ने विरासत में प्राप्त किया है)। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति आकार के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकार के बाएँ-ऊपर कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमाएँ प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से आकार की ज्यामिति अपडेट करता है। निर्देशांक आकार के बाएँ-ऊपर कोने के सापेक्ष होने चाहिए। आकार का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) के एरे से आकार की ज्यामिति अपडेट करता है। निर्देशांक आकार के बाएँ-ऊपर कोने के सापेक्ष होने चाहिए। आकार का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* वर्ग [GeometryShape](../geometryshape)
* इंटरफ़ेस [IAutoShape](../iautoshape)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->