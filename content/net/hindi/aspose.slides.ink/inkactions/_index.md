---
title: InkActions
second_title: Aspose.Sildes for .NET API संदर्भ
description: इंक एक्शनों की मूल संरचना का प्रतिनिधित्व करता है।
type: docs
weight: 7560
url: /hi/aspose.slides.ink/inkactions/
---
## InkActions क्लास

इंक एक्शन का मूल प्रतिनिधित्व करता है।

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | शेप से जुड़े वैकल्पिक टेक्स्ट को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | शेप से जुड़े वैकल्पिक टेक्स्ट के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्दिष्ट करती है कि शेप ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../../aspose.slides/icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें शेप पर लागू पिक्सेल इफेक्ट्स होते हैं। नोट: कुछ शेप प्रकारों के लिए जहाँ इफ़ेक्ट प्रॉपर्टीज नहीं होते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें शेप के लिए फिल फ़ॉर्मेटिंग प्रॉपर्टीज होते हैं। नोट: कुछ शेप प्रकारों के लिए जहाँ फिल प्रॉपर्टीज नहीं होते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम की प्रॉपर्टीज को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe)। |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | शेप के लॉक को लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेप की ऊँचाई को पॉइंट में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शेप छुपी हुई है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink)। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शेप समूहित है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें शेप के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज होते हैं। नोट: कुछ शेप प्रकारों के लिए जहाँ लाइन प्रॉपर्टीज नहीं होते, यह null लौट सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक शेप का नाम प्राप्त करता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ने/लिखने योग्य String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो शेप के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी शेप को विश्वसनीय रूप से रेफ़र करने की अनुमति देता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../../aspose.slides/shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक शेप के लिए प्लेसेहोल्डर लौटाता है। यदि शेप का कोई प्लेसेहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../../aspose.slides/iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../../aspose.slides/ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे शेप फ्रेम की प्रॉपर्टीज को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe)। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्धारित शेप को z-अक्ष के आसपास घुमाने के डिग्री संख्या को प्राप्त करता है या सेट करता है। सकारात्मक मान clockwise घूर्णन दर्शाता है; नकारात्मक मान counterclockwise घूर्णन दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | शेप के लॉक को लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। (2 प्रॉपर्टी) |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक शेप की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../../aspose.slides/ibaseslide)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें शेप के 3D इफ़ेक्ट प्रॉपर्टीज होते हैं। नोट: कुछ शेप प्रकारों के लिए जहाँ 3D प्रॉपर्टीज नहीं होते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../../aspose.slides/ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक अंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | शेप की चौड़ाई को पॉइंट में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | शेप के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेप के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | एक शेप की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला शेप लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला शेप लौटाता है। केवल-पढ़ने योग्य Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसेहोल्डर नहीं है तो नया प्लेसेहोल्डर जोड़ता है और निर्दिष्ट प्लेसेहोल्डर की प्रॉपर्टीज सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसेहोल्डर शेप लौटाता है (लेआउट या मास्टर स्लाइड से शेप जिसे वर्तमान शेप विरासत में प्राप्त करता है)। यदि वर्तमान शेप विरासत में नहीं है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | शेप थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape शेप थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेप थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए कंटेंट से गणना किए गए शेप के विज़ुअल बाउंड्स प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शेप प्लेसेहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [IInkActions](../iinkactions)
* नेमस्पेस [Aspose.Slides.Ink](../../aspose.slides.ink)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->