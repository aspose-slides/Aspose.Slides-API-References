---
title: IShape
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: स्लाइड पर एक आकार का प्रतिनिधित्व करता है।
type: docs
weight: 6970
url: /hi/aspose.slides/ishape/
---
## IShape इंटरफ़ेस

स्लाइड पर एक आकार का प्रतिनिधित्व करता है।

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | एक आकार से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | एक आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। Read/write String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | बेस IHyperlinkContainer इंटरफ़ेस प्राप्त करने की अनुमति देता है। Read-only [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | बेस ISlideComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। Read-only [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्धारित करती है कि एक आकार काली-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | आकार के कस्टम डेटा को लौटाता है। Read-only [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | एक आकार पर लागू पिक्सल इफ़ेक्ट्स वाले EffectFormat ऑब्जेक्ट को लौटाता है। Read-only [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | एक आकार के लिए भराव फॉर्मेटिंग प्रॉपर्टीज़ वाले FillFormat ऑब्जेक्ट को लौटाता है। Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | आकार की ऊंचाई, पॉइंट में मापी गई, को प्राप्त करता है या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। Read/write Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | निर्धारित करता है कि आकार ग्रुप किया गया है या नहीं। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder है या नहीं। Read-only Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | एक आकार के लिए लाइन फॉर्मेटिंग प्रॉपर्टीज़ वाले LineFormat ऑब्जेक्ट को लौटाता है। Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | एक आकार का नाम लौटाता है या सेट करता है। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरोप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। Read-only UInt32. See also [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | यदि आकार ग्रुप किया गया है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। Read-only [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | कच्चे shape frame की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | निश्चित आकार को z-अक्ष के चारों ओर घुमाए जाने वाले डिग्री की संख्या को लौटाता है या सेट करता है। एक सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; एक नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | shape के लॉक को लौटाता है। Read-only [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | एक आकार के लिए लाइन फॉर्मेटिंग प्रॉपर्टीज़ वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | ऐड-इन या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः नियुक्त किया जा सकता है, इसे एक स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। Read-only UInt32. See also [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | आकार की चौड़ाई, पॉइंट में मापी गई, को प्राप्त करता है या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक, पॉइंट में मापे गए, को प्राप्त करता है या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक, पॉइंट में मापे गए, को प्राप्त करता है या सेट करता है। Read/write Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | z-ऑर्डर में एक आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाले आकार को लौटाता है, और Shapes[Shapes.Count - 1] z-ऑर्डर के आगे वाले आकार को लौटाता है। Read-only Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट वाले में सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | आकार थंबनेल लौटाता है। डिफॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें भी

* इंटरफ़ेस [IHyperlinkContainer](../ihyperlinkcontainer)
* इंटरफ़ेस [ISlideComponent](../islidecomponent)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->