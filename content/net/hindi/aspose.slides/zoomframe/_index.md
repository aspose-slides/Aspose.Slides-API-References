---
title: ZoomFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक slide में Slide Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 11860
url: /hi/aspose.slides/zoomframe/
---
## ZoomFrame क्लास

Represents a Slide Zoom object in a slide.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | गुण बताता है कि एक shape ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape के कस्टम डेटा को लौटाता है। Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल इफेक्ट्स वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: उन shape प्रकारों के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टी नहीं होती। Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक shape के फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: उन shape प्रकारों के लिए null लौटाया जा सकता है जिनमें फ़िल प्रॉपर्टी नहीं होती। Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape छिपा है या नहीं निर्धारित करता है। Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | एक ज़ूम ऑब्जेक्ट की इमेज प्रकार को प्राप्त करता है या सेट करता है। Read/write [`ZoomImageType`](../zoomimagetype)। डिफ़ॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape समूहित है या नहीं निर्धारित करता है। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape TextHolder_PPT है या नहीं निर्धारित करता है। Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक shape के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: उन shape प्रकारों के लिए null लौटाया जा सकता है जिनमें लाइन प्रॉपर्टी नहीं होती। Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक shape का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का प्रयोग करें। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक slide-स्कोप्ड अनन्य पहचानकर्ता लौटाता है जो shape के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। Read-only UInt32। देखें [`UniqueId`](../shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक shape के लिए प्लेसहोल्डर लौटाता है। यदि shape के पास प्लेसहोल्डर नहीं है तो null लौटाता है। Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक slide की पैरेंट प्रस्तुति लौटाता है। Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे shape फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त करता है या सेट करता है। Read/write Boolean। डिफ़ॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock)। (2 प्रॉपर्टीज़) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom गंतव्य slide की पृष्ठभूमि का उपयोग करेगा या नहीं, यह निर्धारित करने वाला मान प्राप्त करता है या सेट करता है। Read/write Boolean। डिफ़ॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक shape की पैरेंट slide लौटाता है। Read-only [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | Slide Zoom ऑब्जेक्ट जिस slide ऑब्जेक्ट से लिंक होता है, उसे प्राप्त करता है या सेट करता है। Read/write [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक shape के 3D इफ़ेक्ट प्रॉपर्टीज़ वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: उन shape प्रकारों के लिए null लौटाया जा सकता है जिनमें 3D प्रॉपर्टी नहीं होती। Read-only [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom और slide के बीच ट्रांज़िशन की अवधि को प्राप्त करता है या सेट करता है। Read/write Single। डिफ़ॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाना है। चूँकि यह मान उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी अनन्य कुंजी नहीं माना जाना चाहिए। Read-only UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपर-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपर-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | zoom ऑब्जेक्ट की छवि को प्राप्त करता है या सेट करता है। Read/write [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-order में एक shape की स्थिति को लौटाता है। Shapes[0] z-order के पीछे वाला shape लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला shape लौटाता है। Read-only Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर shape लौटाता है (layout या मास्टर slide से वह shape जो वर्तमान shape से विरासत में मिला हो)। यदि वर्तमान shape विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप में ShapeThumbnailBounds.Shape shape थंबनेल बॉउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की रेंडर की गई सामग्री से गणना किए गए विज़ुअल बॉउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें भी

* क्लास [ZoomObject](../zoomobject)
* इंटरफ़ेस [IZoomFrame](../izoomframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->