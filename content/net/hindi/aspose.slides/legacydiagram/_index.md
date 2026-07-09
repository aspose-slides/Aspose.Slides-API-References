---
title: LegacyDiagram
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक लेगेसी डाइग्राम ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 7670
url: /hi/aspose.slides/legacydiagram/
---
## LegacyDiagram क्लास

पुरानी डाइग्राम ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़े वैकल्पिक टेक्स्ट को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़े वैकल्पिक टेक्स्ट के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | आधार IGraphicalObject इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्धारित करती है कि एक आकार काले-और-सफ़ेद डिस्प्ले मोड में कैसे प्रदर्शित होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जो आकार पर लागू पिक्सेल इफ़ेक्ट्स रखता है। नोट: उन कुछ प्रकार के आकारों के लिए जो इफ़ेक्ट प्रॉपर्टीज़ नहीं रखते, null लौट सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जो आकार के लिए फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ रखता है। नोट: उन कुछ प्रकार के आकारों के लिए जो फ़िल प्रॉपर्टीज़ नहीं रखते, null लौट सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार की लॉकिंग जानकारी लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जो आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ रखता है। नोट: उन कुछ प्रकार के आकारों के लिए जो लाइन प्रॉपर्टीज़ नहीं रखते, null लौट सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम प्राप्त करता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकार के जीवनकाल के दौरान स्थायी रहने वाला स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है, जिससे PowerPoint या इंटरऑप कोड किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित कर सके। केवल-पढ़ने योग्य UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है, अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड के पैरेंट प्रस्तुति को लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्ची आकार फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को Z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार की लॉकिंग जानकारी लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टीज़) |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जो आकार के 3D इफ़ेक्ट प्रॉपर्टीज़ रखता है। नोट: उन कुछ प्रकार के आकारों के लिए जो 3D प्रॉपर्टीज़ नहीं रखते, null लौट सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापा गया। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार के Z-ऑर्डर में स्थिति लौटाता है। Shapes[0] Z-ऑर्डर के पीछे वाला आकार लौटाता है, तथा Shapes[Shapes.Count - 1] सामने वाला आकार लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और निर्दिष्ट placeholder की प्रॉपर्टीज़ सेट करता है. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | लेगेसी digram को संपादन योग्य group shape में परिवर्तित करता है। निर्मित GroupShape ऑब्जेक्ट अभिभावक group shape में समान स्थिति पर जोड़ता है. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | लेगेसी digram को संपादन योग्य SmartArt ऑब्जेक्ट में परिवर्तित करता है। निर्मित SmartArt ऑब्जेक्ट अभिभावक group shape में समान स्थिति पर जोड़ता है. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | मूल placeholder shape लौटाता है (वर्तमान shape जिस layout या master slide से विरासत में मिला है)। यदि वर्तमान shape विरासत में नहीं मिला है तो null लौटाता है. |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की दृश्य बाउंड्स प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई हैं. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकार placeholder नहीं है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |

### देखें भी

* क्लास [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [ILegacyDiagram](../ilegacydiagram)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->