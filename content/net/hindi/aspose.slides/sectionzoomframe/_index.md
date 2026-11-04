---
title: SectionZoomFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक slide में Section Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 9800
url: /hi/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame क्लास

एक स्लाइड में Section Zoom वस्तु का प्रतिनिधित्व करता है।

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि shape काला-धूसर डिस्प्ले मोड में कैसे रेंडर होगी। Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape के कस्टम डेटा को लौटाता है। Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें shape पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: उन कुछ shape प्रकारों के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टीज नहीं होतीं। Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज होती हैं। नोट: उन कुछ shape प्रकारों के लिए null लौटाया जा सकता है जिनमें भराव प्रॉपर्टीज नहीं होतीं। Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape की लॉक वापसी करता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई (पॉइंट्स में) प्राप्त करता या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छिपा हुआ है या नहीं। Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | zoom ऑब्जेक्ट की इमेज टाइप को प्राप्त या सेट करता है। Read/write [`ZoomImageType`](../zoomimagetype). डिफ़ॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त या सेट करता है। Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape ग्रुप किया गया है या नहीं। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज होती हैं। नोट: उन कुछ shape प्रकारों के लिए null लौटाया जा सकता है जिनमें लाइन प्रॉपर्टीज नहीं होतीं। Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक shape का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का उपयोग करें। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक slide-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो shape के जीवनकाल में निरंतर रहता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है। Read-only UInt32. देखें भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape ग्रुप किया गया है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक shape के लिए placeholder लौटाता है। यदि shape के पास कोई placeholder नहीं है तो null लौटाता है। Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक slide की पैरेंट प्रस्तुति लौटाता है। Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | raw shape फ्रेम की प्रॉपर्टीज लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार प्राप्त या सेट करता है। Read/write Boolean. डिफ़ॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिक्लॉकवाइज़ घुमाव दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape की लॉक लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टीज़) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom गंतव्य slide की पृष्ठभूमि का उपयोग करेगा या नहीं, यह निर्धारित करने वाला मान प्राप्त या सेट करता है। Read/write Boolean. डिफ़ॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक shape की पैरेंट slide लौटाता है। Read-only [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Section Zoom ऑब्जेक्ट जिस section ऑब्जेक्ट से लिंक करता है, उसे प्राप्त या सेट करता है। Read/write [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें shape के 3D इफ़ेक्ट प्रॉपर्टीज होती हैं। नोट: उन कुछ shape प्रकारों के लिए null लौटाया जा सकता है जिनमें 3D प्रॉपर्टीज नहीं होतीं। Read-only [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom और slide के बीच संक्रमण की अवधि प्राप्त या सेट करता है। Read/write Single. डिफ़ॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाना है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामेटिकली पुनः असाइन किया जा सकता है, इसे एक स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। Read-only UInt32. देखें भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई (पॉइंट्स में) प्राप्त या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएं कोने का x-निर्देशांक (पॉइंट्स में) प्राप्त या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएं कोने का y-निर्देशांक (पॉइंट्स में) प्राप्त या सेट करता है। Read/write Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | zoom ऑब्जेक्ट के लिए इमेज प्राप्त या सेट करता है। Read/write [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में shape की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाले shape को लौटाता है, और Shapes[Shapes.Count - 1] सामने वाले shape को लौटाता है। Read-only Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और placeholder प्रॉपर्टीज को निर्दिष्ट वाले में सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी placeholder shape लौटाता है (layout और/या master slide से shape जो वर्तमान shape से विरासत में मिली है)। यदि वर्तमान shape विरासत में नहीं मिली है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की दृश्य सीमा लौटाता है जो उसके रेंडर किए गए कंटेंट से गणना की गई है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape placeholder नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [ZoomObject](../zoomobject)
* इंटरफ़ेस [ISectionZoomFrame](../isectionzoomframe)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->