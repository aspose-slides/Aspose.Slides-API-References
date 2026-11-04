---
title: LegacyDiagram
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक लेगेसी डायाग्राम वस्तु का प्रतिनिधित्व करता है।
type: docs
weight: 7690
url: /hi/aspose.slides/legacydiagram/
---
## LegacyDiagram वर्ग

एक लेगेसी डायाग्राम वस्तु को दर्शाता है।

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़ी वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | बेस IGraphicalObject इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्दिष्ट करती है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइट्स की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: उन आकार प्रकारों के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टी नहीं है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन आकार प्रकारों के लिए null लौटाया जा सकता है जिनमें भराव प्रॉपर्टी नहीं है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | डेकोरेटिव के रूप में चिह्नित करने का विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन आकार प्रकारों के लिए null लौटाया जा सकता है जिनमें लाइन प्रॉपर्टी नहीं है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकार का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अनन्य पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घूर्णन दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टीज़) |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D प्रभाव प्रॉपर्टीज़ होते हैं। नोट: उन आकार प्रकारों के लिए null लौटाया जा सकता है जिनमें 3D प्रॉपर्टी नहीं है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन या अन्य कोड द्वारा उपयोग के लिए है। चूंकि इस मान को उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी अनन्य कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बायें कोने का x-निर्देशांक प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बायें कोने का y-निर्देशांक प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में एक आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे का आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे का आकार लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियां

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट एक में सेट करता है। |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | लेगेसी डायाग्राम को संपादन योग्य ग्रुप शॉपी में परिवर्तित करता है। निर्मित GroupShape ऑब्जेक्ट समान स्थिति पर पैरेंट ग्रुप शॉपी में जोड़ता है। |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | लेगेसी डायाग्राम को संपादन योग्य SmartArt ऑब्जेक्ट में परिवर्तित करता है। निर्मित SmartArt ऑब्जेक्ट समान स्थिति पर पैरेंट ग्रुप शॉपी में जोड़ता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर शॉपी लौटाता है (लेआउट और/या मास्टर स्लाइड से शॉपी जिससे वर्तमान शॉपी विरासत में मिली है)। यदि वर्तमान शॉपी विरासत में नहीं है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | शॉपी थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape शॉपी थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शॉपी थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेण्डर की गई सामग्री से गणना किए गए शॉपी के विज़ुअल बाउंड्स प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शॉपी प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शॉपी की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शॉपी की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [ILegacyDiagram](../ilegacydiagram)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेम्बली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->