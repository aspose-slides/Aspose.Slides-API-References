---
title: Ink
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 7550
url: /hi/aspose.slides.ink/ink/
---
## Ink क्लास

एक स्लाइड पर इंक ऑब्जेक्ट को दर्शाता है।

```csharp
public class Ink : GraphicalObject, IInk
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | एक shape में काले-श्वेत डिस्प्ले मोड में कैसे रेंडर होगा, यह निर्धारित करने वाली प्रॉपर्टी। पढ़ें/लिखें [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ें Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape के कस्टम डेटा को लौटाता है। केवल पढ़ें [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल इफ़ेक्ट्स वाला EffectFormat ऑब्जेक्ट लौटाता है। ध्यान दें: उन shapes के प्रकारों के लिए जो effect गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ें [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक shape के लिए fill फ़ॉर्मेटिंग गुण वाले FillFormat ऑब्जेक्ट को लौटाता है। ध्यान दें: उन shapes के लिए जिनमें fill गुण नहीं हैं, null लौटाया जा सकता है। केवल पढ़ें [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक को लौटाता है। केवल पढ़ें [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई (पॉइंट में मापी गई) को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। केवल पढ़ें [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। केवल पढ़ें Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। केवल पढ़ें Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक shape के लिए लाइन फ़ॉर्मेटिंग गुण वाले LineFormat ऑब्जेक्ट को लौटाता है। ध्यान दें: उन shapes के लिए जिनमें लाइन गुण नहीं हैं, null लौटाया जा सकता है। केवल पढ़ें [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape का नाम लौटाता है या सेट करता है। नल नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | shape के जीवनकाल के दौरान स्थिर रहने वाला स्लाइड-स्कोप्ड यूनिक आइडेंटिफायर लौटाता है, जिससे PowerPoint या इंटरऑप कोड दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित कर सकता है। केवल पढ़ें UInt32। देखें [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ें [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape के लिए प्लेसहोल्डर लौटाता है। यदि shape के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ें [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ें [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | raw shape फ्रेम की प्रॉपर्टी को लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान विपरीत दिशा में घूर्णन दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक को लौटाता है। केवल पढ़ें [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। (2 प्रॉपर्टी) |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट स्लाइड को लौटाता है। केवल पढ़ें [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape के लिए 3D इफ़ेक्ट गुण वाला ThreeDFormat ऑब्जेक्ट लौटाता है। ध्यान दें: उन shapes के लिए जिनमें 3D गुण नहीं हैं, null लौटाया जा सकता है। केवल पढ़ें [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | IInk तत्व [`IInkTrace`](../iinktrace) में शामिल सभी ट्रेसेस को प्राप्त करता है। केवल पढ़ें. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रेजेंटेशन-स्कोप्ड आइडेंटिफायर लौटाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामिंग द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी नहीं माना जाना चाहिए। केवल पढ़ें UInt32। देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई (पॉइंट में मापी गई) को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है (पॉइंट में)। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है (पॉइंट में)। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में shape की स्थिति को लौटाता है। Shapes[0] पीछे की ओर shape को लौटाता है, और Shapes[Shapes.Count - 1] अग्र भाग की shape को लौटाता है। केवल पढ़ें Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | इंक ब्रशों के लिए दृश्य प्रभावों का अनुकरण करने हेतु उपयोग की गई कस्टम इमेजेस के संग्रह को प्राप्त करता है। ये इमेजेस विशिष्ट [`InkEffectType`](../inkeffecttype) मान जैसे Galaxy, Rainbow आदि के साथ इंक रेंडर करते समय उपयोग की जाती हैं। अपनी खुद की इमेजेस प्रदान करके आप प्रत्येक इंक प्रभाव के प्रकट होने को नियंत्रित कर सकते हैं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट वाले के प्लेसहोल्डर गुण सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर shape लौटाता है (layout या मास्टर स्लाइड से वह shape जिसे वर्तमान shape विरासत में प्राप्त करता है)। यदि वर्तमान shape विरासत में नहीं है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप में ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए कंटेंट से गणना किए गए shape के दृश्य बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [IInk](../iink)
* नेमस्पेस [Aspose.Slides.Ink](../../aspose.slides.ink)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->