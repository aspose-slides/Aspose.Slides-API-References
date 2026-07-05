---
title: LegacyDiagram
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक लेगसी डायग्राम ऑब्जेक्ट को दर्शाता है।
type: docs
weight: 7670
url: /hi/aspose.slides/legacydiagram/
---
## LegacyDiagram क्लास

एक legacy डायग्राम ऑब्जेक्ट को दर्शाता है।

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | बेस IGraphicalObject इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ें [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्धारित करता है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ें Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ें [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। टिप्पणी: कुछ प्रकार के आकारों के लिए जिनमें इफ़ेक्ट गुण नहीं होते, null लौटाया जा सकता है। केवल-पढ़ें [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जो आकार के लिए भरने के फ़ॉर्मेट गुण रखता है। टिप्पणी: कुछ प्रकार के आकारों के लिए जिनमें भरने के गुण नहीं होते, null लौटाया जा सकता है। केवल-पढ़ें [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टी लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ें [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई, पॉइंट्स में मापी गई, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ें [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ें Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ें Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेट गुण होते हैं। टिप्पणी: कुछ प्रकार के आकारों के लिए जिनमें लाइन गुण नहीं होते, null लौटाया जा सकता है। केवल-पढ़ें [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है जो आकार की आयु के दौरान स्थिर रहता है और PowerPoint या इंटरॉप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ें UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ें [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ें [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ें [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम की प्रॉपर्टी लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमा देने वाले डिग्री की संख्या लौटाता है या सेट करता है। एक सकारात्मक मान घड़ी की सुई के दिशा में घूर्णन दर्शाता है; एक नकारात्मक मान विपरीत दिशा में घूर्णन दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ें [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टी) |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ें [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए 3D इफ़ेक्ट गुण होते हैं। टिप्पणी: कुछ प्रकार के आकारों के लिए जिनमें 3D गुण नहीं होते, null लौटाया जा सकता है। केवल-पढ़ें [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग करने के लिए अभिप्रेत है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ें UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई, पॉइंट्स में मापी गई, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने का x-कोऑर्डिनेट, पॉइंट्स में मापी गई, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने का y-कोऑर्डिनेट, पॉइंट्स में मापी गई, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है। केवल-पढ़ें Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर के गुण सेट करता है। |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | legacy डाइग्राम को संपादन योग्य ग्रुप शॉप में परिवर्तित करता है। निर्मित GroupShape ऑब्जेक्ट को समान स्थिति पर पैरेंट ग्रुप शॉप में जोड़ा जाता है। |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | legacy डाइग्राम को संपादन योग्य SmartArt ऑब्जेक्ट में परिवर्तित करता है। निर्मित SmartArt ऑब्जेक्ट को समान स्थिति पर पैरेंट ग्रुप शॉप में जोड़ा जाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला हो)। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड प्रकार उपयोग होता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की दृश्य सीमा प्राप्त करता है जो उसके रेंडर्ड कंटेंट से गणना की गई है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### साथ में देखें

* क्लास [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [ILegacyDiagram](../ilegacydiagram)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->