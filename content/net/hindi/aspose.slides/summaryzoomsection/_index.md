---
title: SummaryZoomSection
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: Summary Zoom फ्रेम में Summary Zoom Section ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 10800
url: /hi/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection क्लास

Summary Zoom फ्रेम में Summary Zoom Section ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से जुड़ा वैकल्पिक टेक्स्ट प्राप्त या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से जुड़ी वैकल्पिक टेक्स्ट का शीर्षक प्राप्त या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि आकार काले-और-सफेद डिस्प्ले मोड में कैसे प्रदर्शित होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Summary Zoom Section ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | वह EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: उन कुछ प्रकार के आकारों के लिए जो इफ़ेक्ट प्रॉपर्टी नहीं रखते, null लौटाया सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | वह FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार की भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन कुछ प्रकार के आकारों के लिए जो भराव प्रॉपर्टी नहीं रखते, null लौटाया सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ प्राप्त या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार की लॉक जानकारी लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई (पॉइंट्स में) प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | ज़ूम ऑब्जेक्ट की इमेज प्रकार प्राप्त या सेट करता है। पढ़ें/लिखें [`ZoomImageType`](../zoomimagetype). डिफॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | वह LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार की लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन कुछ प्रकार के आकारों के लिए जो लाइन प्रॉपर्टी नहीं रखते, null लौटाया सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम प्राप्त या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का प्रयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32. देखें भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम की प्रॉपर्टीज़ प्राप्त या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. डिफॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार की z-अक्ष के चारों ओर घुमाव की डिग्री संख्या प्राप्त या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार की लॉक जानकारी लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टी) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | यह मान प्राप्त या सेट करता है जो निर्धारित करता है कि ज़ूम गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें/लिखें Boolean. डिफॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | वह सेक्शन ऑब्जेक्ट प्राप्त या सेट करता है जिससे Section Zoom ऑब्जेक्ट लिंक्ड है। पढ़ें/लिखें [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | वह ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D इफ़ेक्ट प्रॉपर्टीज़ होते हैं। नोट: उन कुछ प्रकार के आकारों के लिए जो 3D प्रॉपर्टी नहीं रखते, null लौटाया सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Summary Zoom Section ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है। |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | ज़ूम और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त या सेट करता है। पढ़ें/लिखें Single. डिफॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जा सकता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम से पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32. देखें भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई (पॉइंट्स में) प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट (पॉइंट्स में) को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट (पॉइंट्स में) को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | ज़ूम ऑब्जेक्ट की इमेज प्राप्त या सेट करता है। पढ़ें/लिखें [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की z-order में स्थिति लौटाता है। Shapes[0] z-order के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है। केवल-पढ़ने योग्य Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला हो)। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार का प्रयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए आकार की विज़ुअल बाउंड्स प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [SectionZoomFrame](../sectionzoomframe)
* इंटरफ़ेस [ISummaryZoomSection](../isummaryzoomsection)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->