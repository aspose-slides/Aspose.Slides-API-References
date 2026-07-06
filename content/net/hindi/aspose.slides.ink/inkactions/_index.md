---
title: InkActions
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: इंक एक्शन्स के मूल का प्रतिनिधित्व करता है।
type: docs
weight: 7560
url: /hi/aspose.slides.ink/inkactions/
---
## InkActions क्लास

इंक एक्शन्स की मूल प्रतिनिधित्व करता है।

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्धारित करता है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को लौटाता है। Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | आकार पर लागू पिक्सल इफ़ेक्ट्स को सम्मिलित करने वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जो इफ़ेक्ट प्रॉपर्टीज़ नहीं रखते, null लौटाया जा सकता है। Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | आकार के भराव फ़ॉर्मेट प्रॉपर्टीज़ को सम्मिलित करने वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जिनमें भराव प्रॉपर्टीज़ नहीं होते, null लौटाया जा सकता है। Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को पॉइंट्स में मापे हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छुपा हुआ है या नहीं। Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | आकार के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ को सम्मिलित करने वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जिनमें लाइन प्रॉपर्टीज़ नहीं होते, null लौटाया जा सकता है। Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकार का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग मान का उपयोग करें। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल भर स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित करने देता है। Read-only UInt32. देखें [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार का प्लेसहोल्डर नहीं है तो null लौटाता है। Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिघड़ी दिशा में घूर्णन दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकार की पैरेंट स्लाइड लौटाता है। Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | आकार के लिए 3D इफ़ेक्ट प्रॉपर्टीज़ वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जिनमें 3D प्रॉपर्टीज़ नहीं होते, null लौटाया जा सकता है। Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक अंतर्निहित, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन्स या अन्य कोड द्वारा किया जाता है। चूँकि यह मान उपयोगकर्ता या प्रोग्रामेटिकली पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। Read-only UInt32. देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को पॉइंट्स में मापे हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के उपर-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापे हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के उपर-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापे हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है। Read-only Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की रेंडर की गई सामग्री से गणना किए गए विज़ुअल बाउंड्स प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [IInkActions](../iinkactions)
* नेमस्पेस [Aspose.Slides.Ink](../../aspose.slides.ink)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->