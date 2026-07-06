---
title: GroupShape
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक स्लाइड पर आकारों के समूह का प्रतिनिधित्व करता है।
type: docs
weight: 5090
url: /hi/aspose.slides/groupshape/
---
## GroupShape वर्ग

एक स्लाइड पर आकारों के समूह का प्रतिनिधित्व करता है।

```csharp
public class GroupShape : Shape, IGroupShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | शेप से जुड़े वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | शेप से जुड़े वैकल्पिक पाठ के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | बेस IShape इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्धारित करती है कि एक शेप काली-श्याम डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइट्स की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें शेप पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। ध्यान दें: कुछ प्रकार के शेप्स के लिए जो इफ़ेक्ट गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें शेप के भरने के फ़ॉर्मेटिंग गुण होते हैं। ध्यान दें: कुछ प्रकार के शेप्स के लिए जो भरने के गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | शेप की लॉकिंग स्थितियों को लौटाता है। केवल पढ़ने योग्य [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेप की ऊँचाई, जिसे पॉइंट में मापा जाता है, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शेप छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शेप समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें शेप के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं। ध्यान दें: GroupShape ऑब्जेक्ट्स के लिए null लौटाता है क्योंकि उनके पास लाइन गुण नहीं होते। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | शेप का नाम प्राप्त करता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-सीमित अनूठा पहचानकर्ता लौटाता है जो शेप के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी शेप को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल पढ़ने योग्य UInt32। संबंधित देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | शेप के लिए प्लेसहोल्डर लौटाता है। यदि शेप में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्ची शेप फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शेप के z-अक्ष के चारों ओर घुमाए गये डिग्री की संख्या को प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान उल्टी दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | शेप की लॉकिंग स्थितियों को लौटाता है। केवल पढ़ने योग्य [`IGroupShapeLock`](../igroupshapelock). (2 प्रॉपर्टीज़) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | समूह के भीतर के शेपों का संग्रह लौटाता है। केवल पढ़ने योग्य [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | शेप की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें शेप के 3D इफ़ेक्ट गुण होते हैं। ध्यान दें: कुछ प्रकार के शेप्स के लिए जिनके पास 3D गुण नहीं होते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-सीमित पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अनूठी कुंजी माना नहीं जाना चाहिए। केवल पढ़ने योग्य UInt32। संबंधित देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | शेप की चौड़ाई, जिसे पॉइंट में मापा जाता है, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | शेप के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, जिसे पॉइंट में मापा जाता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेप के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, जिसे पॉइंट में मापा जाता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | शेप की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे का शेप लौटाता है, और Shapes[Shapes.Count - 1] z-ऑर्डर के आगे का शेप लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर शेप लौटाता है (लेआउट और/या मास्टर स्लाइड से वह शेप जिससे वर्तमान शेप विरासत में मिला है)। यदि वर्तमान शेप विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | शेप थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape शेप थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेप थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | शेप की दृश्य सीमा को उसके रेंडर किए गए कंटेंट से गणना करके प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें भी

* वर्ग [Shape](../shape)
* इंटरफ़ेस [IGroupShape](../igroupshape)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->