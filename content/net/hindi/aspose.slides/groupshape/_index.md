---
title: GroupShape
second_title: Aspose.Sildes के लिए .NET API रेफरेंस
description: स्लाइड पर आकृतियों के समूह को दर्शाता है।
type: docs
weight: 5110
url: /hi/aspose.slides/groupshape/
---
## GroupShape क्लास

एक स्लाइड पर आकृतियों के समूह को दर्शाता है।

```csharp
public class GroupShape : Shape, IGroupShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकृति से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकृति से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | बेस IShape इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल पढ़ें [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्दिष्ट करती है कि एक आकृति ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगी। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकृति पर कनेक्शन साइट्स की संख्या लौटाता है। केवल पढ़ें Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकृति का कस्टम डेटा लौटाता है। केवल पढ़ें [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकृति पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: उन खास प्रकार की आकृतियों के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होती हैं। केवल पढ़ें [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकृति के भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: उन खास प्रकार की आकृतियों के लिए null लौटाया जा सकता है जिनमें भराव प्रॉपर्टीज़ नहीं होती हैं। केवल पढ़ें [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | आकृति के लॉक लौटाता है। केवल पढ़ें [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकृति की ऊँचाई (पॉइंट्स में मापी गई) प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकृति छिपी हुई है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल पढ़ें [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकृति समूहित है या नहीं। केवल पढ़ें Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। केवल पढ़ें Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकृति के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: GroupShape ऑब्जेक्ट्स के लिए null लौटाता है क्योंकि उनके पास लाइन प्रॉपर्टीज़ नहीं होती हैं। केवल पढ़ें [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकृति का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकृति के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकृति को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ें UInt32। देखें भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकृति समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ें [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकृति के लिए प्लेसहोल्डर लौटाता है। यदि आकृति के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ें [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ें [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ shape फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकृति के z-धुरी के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव को दर्शाता है; नकारात्मक मान उल्टी दिशा में घुमाव को दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | आकृति के लॉक लौटाता है। केवल पढ़ें [`IGroupShapeLock`](../igroupshapelock)। (2 प्रॉपर्टीज़) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | समूह के अंदर की आकृतियों का संग्रह लौटाता है। केवल पढ़ें [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकृति की पैरेंट स्लाइड लौटाता है। केवल पढ़ें [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकृति के 3D इफ़ेक्ट प्रॉपर्टीज़ होते हैं। नोट: उन खास प्रकार की आकृतियों के लिए null लौटाया जा सकता है जिनमें 3D प्रॉपर्टीज़ नहीं होती हैं। केवल पढ़ें [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाना है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे एक स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ें UInt32। देखें भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकृति की चौड़ाई (पॉइंट्स में मापी गई) प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकृति के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को (पॉइंट्स में मापी गई) प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकृति के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को (पॉइंट्स में मापी गई) प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकृति की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे की आकृति लौटाता है, और Shapes[Shapes.Count - 1] सामने की आकृति लौटाता है। केवल पढ़ें Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट एक पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर आकृति लौटाता है (लेआउट या मास्टर स्लाइड से आकृति जो वर्तमान आकृति से विरासत में मिली हो)। यदि वर्तमान आकृति विरासत में नहीं मिली है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकृति थंबनेल लौटाता है। डिफॉल्ट रूप से ShapeThumbnailBounds.Shape आकृति थंबनेल बॉण्ड्स टाइप उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकृति थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकृति की दृश्य सीमाएं प्राप्त करता है जो उसके रेंडर की गई सामग्री से गणना की गई हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [Shape](../shape)
* इंटरफ़ेस [IGroupShape](../igroupshape)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->