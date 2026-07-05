---
title: GeometryShape
second_title: Aspose.Sildes for .NET API संदर्भ
description: सभी ज्यामितीय आकारों के लिए पैरेंट क्लास का प्रतिनिधित्व करता है।
type: docs
weight: 4970
url: /hi/aspose.slides/geometryshape/
---
## GeometryShape वर्ग

सभी ज्यामितीय आकारों के लिए पैरेंट वर्ग का प्रतिनिधित्व करता है।

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकार के समायोजन मानों का संग्रह लौटाता है। केवल पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection)। |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से जुड़े वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से जुड़े वैकल्पिक पाठ के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | गुण निर्दिष्ट करता है कि आकार काला-से-बैज रंग के प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | आकार पर लागू पिक्सेल प्रभावों को शामिल करने वाला EffectFormat ऑब्जेक्ट लौटाता है। नोट: उन प्रकार के आकारों के लिए जो प्रभाव गुण नहीं रखते, यह null लौट सकती है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | आकार के लिए भराव फॉर्मेटिंग गुणों को शामिल करने वाला FillFormat ऑब्जेक्ट लौटाता है। नोट: उन प्रकार के आकारों के लिए जो भराव गुण नहीं रखते, यह null लौट सकती है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुणों को लौटाता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई, पॉइंट में मापी गई, को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | आकार के लिए रेखा फॉर्मेटिंग गुणों को शामिल करने वाला LineFormat ऑब्जेक्ट लौटाता है। नोट: उन प्रकार के आकारों के लिए जो रेखा गुण नहीं रखते, यह null लौट सकती है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम प्राप्त करता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ने/लिखने योग्य String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकार के आयु के दौरान स्थिर रहने वाला स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है, जिससे PowerPoint या इंटरऑप कोड दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित कर सकता है। केवल पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटा है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम के गुणों को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [`IBaseShapeLock`](../ibaseshapelock)। |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार की शैली ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [`IShapeStyle`](../ishapestyle)। |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | ज्यामिति प्रीसेट प्रकार को प्राप्त करता है या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ने/लिखने योग्य [`ShapeType`](../shapetype)। |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | आकार के 3D प्रभाव गुणों को शामिल करने वाला ThreeDFormat ऑब्जेक्ट लौटाता है। नोट: उन प्रकार के आकारों के लिए जो 3D गुण नहीं रखते, यह null लौट सकती है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन या अन्य कोड द्वारा उपयोग के लिए इंटर्नल, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई, पॉइंट में मापी गई, को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-क्रम में आकार की स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे वाली आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाली आकार लौटाता है। केवल पढ़ने योग्य Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट एक के लिए प्लेसहोल्डर गुण सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों का सरणी बनाता है और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (वर्तमान आकार जिस लेआउट और/या मुख्य स्लाइड से विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति आकार के पथ की प्रति लौटाता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार के थंबनेल को लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार के थंबनेल को लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमाओं को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | आकार ज्यामिति को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](./shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | आकार ज्यामिति को [`IGeometryPath`](../igeometrypath) की सरणी से अपडेट करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](./shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* वर्ग [Shape](../shape)
* इंटरफ़ेस [IGeometryShape](../igeometryshape)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* एसेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->