---
title: ZoomObject
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक स्लाइड में Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 11890
url: /hi/aspose.slides/zoomobject/
---
## ZoomObject क्लास

एक स्लाइड में Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से संबद्ध वैकल्पिक टेक्स्ट को लौटाता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से संबद्ध वैकल्पिक टेक्स्ट के शीर्षक को लौटाता है या सेट करता है। Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि एक shape ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे प्रस्तुत होगा। Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape का कस्टम डेटा लौटाता है। Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल इफ़ेक्ट्स वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ shape प्रकारों के लिए null लौटाया जा सकता है जिनमें effect प्रॉपर्टी नहीं होती। Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | shape के fill फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ shape प्रकारों के लिए null लौटाया जा सकता है जिनमें fill प्रॉपर्टी नहीं होती। Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई को, पॉइंट्स में मापी गई, प्राप्त या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छिपा हुआ है या नहीं। Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Zoom ऑब्जेक्ट के इमेज प्रकार को प्राप्त या सेट करता है। Read/write [`ZoomImageType`](../zoomimagetype). Default value: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त या सेट करता है। Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | shape के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ shape प्रकारों के लिए null लौटाया जा सकता है जिनमें line प्रॉपर्टी नहीं होती। Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक slide-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो shape के जीवनकाल में स्थिर रहता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है। Read-only UInt32. See also [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape के लिए प्लेसहोल्डर लौटाता है। यदि shape के पास प्लेसहोल्डर नहीं है तो null लौटाता है। Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | slide का पैरेंट प्रस्तुति लौटाता है। Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | raw shape फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है। Read/write Boolean. Default value: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिगड़ी दिशा में घूर्णन दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | यह मान प्राप्त या सेट करता है जो यह निर्दिष्ट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। Read/write Boolean. Default value: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट स्लाइड लौटाता है। Read-only [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape के 3D इफ़ेक्ट प्रॉपर्टीज़ वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ shape प्रकारों के लिए null लौटाया जा सकता है जिनमें 3d प्रॉपर्टी नहीं होती। Read-only [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom और स्लाइड के बीच संक्रमण की अवधि को प्राप्त या सेट करता है। Read/write Single. Default value: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एड-इन्स या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी नहीं माना जाना चाहिए। Read-only UInt32. See also [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई, पॉइंट्स में मापी गई, को प्राप्त या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपर-बाएँ कोने के x-निर्देशांक को, पॉइंट्स में मापी गई, प्राप्त या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपर-बाएँ कोने के y-निर्देशांक को, पॉइंट्स में मापी गई, प्राप्त या सेट करता है। Read/write Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Zoom ऑब्जेक्ट के लिए इमेज को प्राप्त या सेट करता है। Read/write [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | एक shape की z-order में स्थिति को लौटाता है। Shapes[0] z-order के पीछे वाले shape को लौटाता है, और Shapes[Shapes.Count - 1] सामने वाले shape को लौटाता है। Read-only Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट वाले के लिए प्लेसहोल्डर प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर shape लौटाता है (layout और/या मास्टर स्लाइड से shape जिसे वर्तमान shape विरासत में प्राप्त करता है)। यदि वर्तमान shape विरासत में नहीं मिला तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की दृश्य बाउंड्स को प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की जाती हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [IZoomObject](../izoomobject)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->