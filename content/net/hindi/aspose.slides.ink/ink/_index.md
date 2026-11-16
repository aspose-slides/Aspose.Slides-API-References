---
title: Ink
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 7570
url: /hi/aspose.slides.ink/ink/
---
## Ink क्लास

एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class Ink : GraphicalObject, IInk
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से संबंधित वैकल्पिक पाठ को लौटाता या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से संबंधित वैकल्पिक पाठ के शीर्षक को लौटाता या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | आकार को काला-सफेद प्रदर्शनी मोड में कैसे रेंडर किया जाएगा, यह निर्धारित करता है। पढ़ें/लिखें [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ें Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल पढ़ें [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार के आकारों के लिए जो प्रभाव गुण नहीं रखते, null लौट सकता है। केवल पढ़ें [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के भराव गुण होते हैं। नोट: कुछ प्रकार के आकारों के लिए जो भराव गुण नहीं रखते, null लौट सकता है। केवल पढ़ें [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार की लॉक जानकारी लौटाता है। केवल पढ़ें [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को पॉइंट में मापता है और सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छुपा हुआ है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। केवल पढ़ें [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल पढ़ें Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल पढ़ें Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के रेखा गुण होते हैं। नोट: कुछ प्रकार के आकारों के लिए जो रेखा गुण नहीं रखते, null लौट सकता है। केवल पढ़ें [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ें UInt32. देखें [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है, अन्यथा null। केवल पढ़ें [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के प्लेसहोल्डर को लौटाता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ें [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड के पैरेंट प्रस्तुति को लौटाता है। केवल पढ़ें [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को Z-अक्ष के चारों ओर घुमाने के डिग्री को सेट या प्राप्त करता है। धनात्मक मान घड़ी की दिशा को दर्शाता है; ऋणात्मक मान विपरीत दिशा को। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार की लॉक जानकारी लौटाता है। केवल पढ़ें [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 गुण) |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड को लौटाता है। केवल पढ़ें [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार के आकारों के लिए जो 3D गुण नहीं रखते, null लौट सकता है। केवल पढ़ें [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | IInk तत्व [`IInkTrace`](../iinktrace) में सभी ट्रेस प्राप्त करता है। केवल पढ़ें. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। चूँकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ें UInt32. देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को पॉइंट में मापता है और सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के X-निर्देशांक को पॉइंट में मापता है और सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के Y-निर्देशांक को पॉइंट में मापता है और सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की Z-क्रम में स्थिति लौटाता है। Shapes[0] पीछे की स्थिति वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे की स्थिति वाला आकार लौटाता है। केवल पढ़ें Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | इंक ब्रशों के लिए दृश्य प्रभाव अनुकरण करने हेतु उपयोग की जाने वाली कस्टम छवियों का संग्रह प्राप्त करता है। इन छवियों का उपयोग विशेष [`InkEffectType`](../inkeffecttype) मानों (जैसे Galaxy, Rainbow आदि) के साथ इंक को रेंडर करने पर होता है। अपनी स्वयं की छवियां प्रदान करके आप प्रत्येक इंक प्रभाव की उपस्थिति को नियंत्रित कर सकते हैं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले में सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक मूलभूत प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकृति जिससे वर्तमान आकृति विरासत में मिली है)। यदि वर्तमान आकृति विरासत में नहीं ली गई है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकृति थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape थंबनेल बाउंड प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकृति थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए सामग्री से गणना किए गए आकृति के दृश्य बाउंड प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [IInk](../iink)
* नामस्थान [Aspose.Slides.Ink](../../aspose.slides.ink)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->