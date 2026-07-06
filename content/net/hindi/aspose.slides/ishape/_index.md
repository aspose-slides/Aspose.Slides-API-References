---
title: IShape
second_title: Aspose.Sildes for .NET API संदर्भ
description: स्लाइड पर एक आकार को दर्शाता है।
type: docs
weight: 6950
url: /hi/aspose.slides/ishape/
---
## IShape interface

स्लाइड पर एक आकार को दर्शाता है।

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | एक आकार से जुड़े वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | एक आकार से जुड़े वैकल्पिक पाठ के शीर्षक को प्राप्त करता है या सेट करता है। Read/write String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | बेस IHyperlinkContainer इंटरफ़ेस को प्राप्त करने की अनुमति देता है। Read-only [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | बेस ISlideComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। Read-only [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | यह निर्धारित करता है कि आकार काले-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगा। Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या को प्राप्त करता है। Read-only Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | आकार के कस्टम डेटा को प्राप्त करता है। Read-only [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | वह EffectFormat वस्तु को प्राप्त करता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। Read-only [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | वह FillFormat वस्तु को प्राप्त करता है जिसमें आकार के लिए भराव स्वरूप गुण होते हैं। Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टी को प्राप्त करता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | आकार की ऊँचाई को पॉइंट में प्राप्त करता है या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। Read/write Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। Read/write Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder है या नहीं। Read-only Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | वह LineFormat वस्तु को प्राप्त करता है जिसमें आकार के लिए रेखा स्वरूप गुण होते हैं। Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | आकार का नाम प्राप्त करता है या सेट करता है। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | स्लाइड-स्कोप्ड अनूठा पहचानकर्ता प्राप्त करता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। Read-only UInt32. अन्य देखें [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape वस्तु को प्राप्त करता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | आकार के प्लेसहोल्डर को प्राप्त करता है। Read-only [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | कच्चे आकार फ्रेम की प्रॉपर्टी को प्राप्त करता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने के डिग्रीज़ को प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिदिश घुमाव दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | आकार के लॉक को प्राप्त करता है। Read-only [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | वह ThreeDFormat वस्तु को प्राप्त करता है जिसमें आकार के लिए रेखा स्वरूप गुण होते हैं। Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता को प्राप्त करता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जा सकता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा बदला जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। Read-only UInt32. अन्य देखें [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | आकार की चौड़ाई को पॉइंट में प्राप्त करता है या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में प्राप्त करता है या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में प्राप्त करता है या सेट करता है। Read/write Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | z-क्रम में आकार की स्थिति को प्राप्त करता है। Shapes[0] पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है। Read-only Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टी सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | मूल प्लेसहोल्डर आकार (लेआउट या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में प्राप्त हुआ है) को लौटाता है। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटाता है। |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | आकार थंबनेल को प्राप्त करता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | आकार थंबनेल को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | यह निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->