---
title: Shape
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: स्लाइड पर एक आकार का प्रतिनिधित्व करता है।
type: docs
weight: 9830
url: /hi/aspose.slides/shape/
---
## Shape क्लास

एक स्लाइड पर एक आकार का प्रतिनिधित्व करता है।

```csharp
public class Shape : IShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | शेप से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | शेप से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | गुण निर्धारित करता है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइट्स की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | शेप पर लागू पिक्सेल इफ़ेक्ट्स वाली EffectFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के आकार जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होतीं, उनके लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक आकार के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ वाली FillFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के आकार जिनमें भराव प्रॉपर्टीज़ नहीं होतीं, उनके लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेप की ऊँचाई, पॉइंट्स में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधनकर्ता को लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | डेकोरेटिव चिह्नित करने का विकल्प प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ वाली LineFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के आकार जिनमें लाइन प्रॉपर्टीज़ नहीं होतीं, उनके लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकार का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग का प्रयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड यूनिक आइडेंटिफायर को लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ने योग्य UInt32. देखें भी [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट को लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर को लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पैरेंट प्रस्तुति को लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे shape फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्धारित शाेप को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन को दर्शाता है; नकारात्मक मान उल्टी दिशा में घूर्णन को दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | shape के लॉक को लौटाता है। केवल पढ़ने योग्य [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकार की पैरेंट स्लाइड को लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक आकार के लिए 3D इफ़ेक्ट प्रॉपर्टीज़ वाली ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के आकार जिनमें 3D प्रॉपर्टीज़ नहीं होतीं, उनके लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता को लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामेटिकली पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32. देखें भी [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई, पॉइंट्स में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में एक आकार की स्थिति को लौटाता है। Shapes[0] z-ऑर्डर के पीछे का आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे का आकार लौटाता है। केवल पढ़ने योग्य Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट के लिए प्लेसहोल्डर प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जिसे वर्तमान आकार विरासत में प्राप्त करता है)। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य बाउंड्स प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Shape की कंटेंट को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Shape की कंटेंट को SVG फ़ाइल के रूप में सहेजता है। |

### देखें भी

* इंटरफ़ेस [IShape](../ishape)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->