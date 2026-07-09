---
title: IShape
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक स्लाइड पर आकार का प्रतिनिधित्व करता है।
type: docs
weight: 6950
url: /hi/aspose.slides/ishape/
---
## IShape इंटरफ़ेस

एक स्लाइड पर एक आकार का प्रतिनिधित्व करता है।

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | एक आकार से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | एक आकार से जुड़ा वैकल्पिक टेक्स्ट शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | बेस IHyperlinkContainer इंटरफ़ेस प्राप्त करने की अनुमति देता है। पढ़ें-केवल [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | बेस ISlideComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। पढ़ें-केवल [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्दिष्ट करती है कि एक आकार काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। पढ़ें-केवल Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। पढ़ें-केवल [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। पढ़ें-केवल [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए भराव फ़ॉर्मेटिंग गुण होते हैं। पढ़ें-केवल [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | आकार की ऊँचाई प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। पढ़ें-केवल Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder है या नहीं। पढ़ें-केवल Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं। पढ़ें-केवल [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | आकार का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | आकार के जीवनकाल के दौरान स्थिर रहने वाला स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी भाग से आकार को विश्वसनीय रूप से संदर्भित करने देता है। पढ़ें-केवल UInt32। देखें [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। पढ़ें-केवल [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। पढ़ें-केवल [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | रॉ आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | निर्दिष्ट आकार को Z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | आकार के लॉक लौटाता है। पढ़ें-केवल [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं। पढ़ें-केवल [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन्स या अन्य कोड द्वारा किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामेटिकली पुनः नियोजित किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। पढ़ें-केवल UInt32। देखें [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | आकार की चौड़ाई प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | एक आकार की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] z-ऑर्डर के सामने वाला आकार लौटाता है। पढ़ें-केवल Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट वाले के लिए प्लेसहोल्डर गुण सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* इंटरफ़ेस [IHyperlinkContainer](../ihyperlinkcontainer)
* इंटरफ़ेस [ISlideComponent](../islidecomponent)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->