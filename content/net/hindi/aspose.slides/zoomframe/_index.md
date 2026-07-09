---
title: ZoomFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक स्लाइड में स्लाइड ज़ूम ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 11840
url: /hi/aspose.slides/zoomframe/
---
## ZoomFrame क्लास

Represents a Slide Zoom object in a slide.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## प्रॉपर्टीज

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | एक shape को काले-और-सफ़ेद प्रदर्शनी मोड में कैसे रेंडर किया जाएगा, यह निर्दिष्ट करने वाली प्रॉपर्टी। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर उपलब्ध कनेक्शन साइट्स की संख्या को प्राप्त करता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape के कस्टम डेटा को प्राप्त करता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल प्रभावों को शामिल करने वाले EffectFormat ऑब्जेक्ट को प्राप्त करता है। नोट: उन shape प्रकारों के लिए जो प्रभाव गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक shape के फ़िल फ़ॉर्मेट गुणों को शामिल करने वाले FillFormat ऑब्जेक्ट को प्राप्त करता है। नोट: उन shape प्रकारों के लिए जो फ़िल गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape की लॉक जानकारी को प्राप्त करता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई को, पॉइंट्स में मापा गया, प्राप्त या निर्धारित करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape छिपा है या नहीं, यह निर्धारित करता है। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को प्राप्त करता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त या सेट करता है। पढ़یں/लिखें [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Zoom ऑब्जेक्ट के इमेज प्रकार को प्राप्त या सेट करता है। पढ़ें/लिखें [`ZoomImageType`](../zoomimagetype). डिफ़ॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape समूहित है या नहीं, यह निर्धारित करता है। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape TextHolder_PPT है या नहीं, यह निर्धारित करता है। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक shape के लाइन फ़ॉर्मेट गुणों को शामिल करने वाले LineFormat ऑब्जेक्ट को प्राप्त करता है। नोट: उन shape प्रकारों के लिए जो लाइन गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape का नाम प्राप्त या सेट करता है। null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | shape के जीवनकाल में स्थायी रहने वाला स्लाइड-स्कोप्ड यूनिक पहचानकर्ता प्रदान करता है, जिससे PowerPoint या interop कोड दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित कर सके। केवल-पढ़ने योग्य UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है, अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape के प्लेसहोल्डर को प्राप्त करता है। यदि shape के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेजेंटेशन को प्राप्त करता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे shape फ्रेम की प्रॉपर्टीज को प्राप्त या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. डिफ़ॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को प्राप्त या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूमना दर्शाता है; नकारात्मक मान घड़ी के विपरीत दिशा में घूमना दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape की लॉक जानकारी को प्राप्त करता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टीज) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom द्वारा गंतव्य स्लाइड की पृष्ठभूमि का उपयोग किया जाएगा या नहीं, यह निर्धारित करने वाला मान प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. डिफ़ॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट स्लाइड को प्राप्त करता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | Slide Zoom ऑब्जेक्ट के लिंक किए गए स्लाइड ऑब्जेक्ट को प्राप्त या सेट करता है। पढ़ें/लिखें [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक shape के 3D प्रभाव गुणों को शामिल करने वाले ThreeDFormat ऑब्जेक्ट को प्राप्त करता है। नोट: उन shape प्रकारों के लिए जो 3D गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom और स्लाइड के बीच संक्रमण की अवधि को प्राप्त या सेट करता है। पढ़ें/लिखें Single. डिफ़ॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है। चूंकि इस मान को उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई को, पॉइंट्स में मापा गया, प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को, पॉइंट्स में मापा गया, प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को, पॉइंट्स में मापा गया, प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Zoom ऑब्जेक्ट के लिए इमेज को प्राप्त या सेट करता है। पढ़ें/लिखें [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में shape की स्थिति को प्राप्त करता है। Shapes[0] z-ऑर्डर के पीछे वाला shape लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला shape लौटाता है। केवल-पढ़ने योग्य Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर shape लौटाता है (लेआउट और/या मास्टर स्लाइड से shape जो वर्तमान shape से विरासत में मिला है)। यदि वर्तमान shape विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की रेंडर की गई सामग्री से गणना किए गए विज़ुअल बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | यह निर्धारित करता है कि यह shape प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित लिंक

* क्लास [ZoomObject](../zoomobject)
* इंटरफ़ेस [IZoomFrame](../izoomframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->