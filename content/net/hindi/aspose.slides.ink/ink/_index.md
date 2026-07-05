---
title: Ink
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 7550
url: /hi/aspose.slides.ink/ink/
---
## Ink वर्ग

एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class Ink : GraphicalObject, IInk
```

## गुण

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से संबंधित वैकल्पिक टेक्स्ट को प्राप्त करता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से संबंधित वैकल्पिक टेक्स्ट का शीर्षक प्राप्त करता है या सेट करता है। Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि आकार काली-श्वेत डिस्प्ले मोड में कैसे दिखेगा। Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइट्स की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार के आकार जिनमें प्रभाव गुण नहीं होते, उनके लिए null लौट सकता है। Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए भराव स्वरूपण गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें भराव गुण नहीं होते, उनके लिए null लौट सकता है। Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टी को प्राप्त करता है या सेट करता है। Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊंचाई, पॉइंट्स में मापी गई, प्राप्त करता है या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘मार्क एज़ डेकोरेटिव’ विकल्प को प्राप्त करता है या सेट करता है। Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए रेखा स्वरूपण गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें रेखा गुण नहीं होते, उनके लिए null लौट सकता है। Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकार का नाम प्राप्त करता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का प्रयोग करें। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-सीमित अनूठा पहचानकर्ता लौटाता है जो आकार के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार का विश्वसनीय रूप से संदर्भ देने में सक्षम बनाता है। Read-only UInt32. See also [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ आकार फ्रेम की प्रॉपर्टी को प्राप्त करता है या सेट करता है। Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने के डिग्री प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान विपरीत दिशा में घूर्णन दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकार की पैरेंट स्लाइड को लौटाता है। Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें 3D गुण नहीं होते, उनके लिए null लौट सकता है। Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | IInk तत्व [`IInkTrace`](../iinktrace) में सभी ट्रेस प्राप्त करता है। Read-only. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-सीमित पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अनूठी कुंजी के रूप में नहीं माना जाना चाहिए। Read-only UInt32. See also [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई, पॉइंट्स में मापी गई, प्राप्त करता है या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के बायें-ऊपरी कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के बायें-ऊपरी कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है। Read-only Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | इंक ब्रश के दृश्य प्रभावों का अनुकरण करने के लिए उपयोग की जाने वाली कस्टम इमेज संग्रह को प्राप्त करता है। ये इमेज विशेष [`InkEffectType`](../inkeffecttype) मानों (जैसे Galaxy, Rainbow आदि) के साथ इंक रेंडर करने पर उपयोग होती हैं। अपनी खुद की इमेज प्रदान करके आप प्रत्येक इंक प्रभाव की उपस्थिति को नियंत्रित कर सकते हैं। |

## विधियाँ

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर की प्रॉपर्टी को निर्दिष्ट एक पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य बाउंड्स प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* वर्ग [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [IInk](../iink)
* नेमस्पेस [Aspose.Slides.Ink](../../aspose.slides.ink)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->