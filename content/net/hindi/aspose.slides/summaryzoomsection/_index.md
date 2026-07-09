---
title: SummaryZoomSection
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक Summary Zoom फ्रेम में Summary Zoom Section ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 10780
url: /hi/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection क्लास

एक Summary Zoom फ्रेम में Summary Zoom Section ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## प्रॉपर्टीज

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि एक आकार काले-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Summary Zoom Section ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: उन आकारों के प्रकार के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार की भराव फ़ॉर्मेटिंग प्रॉपर्टी होती है। नोट: उन आकारों के प्रकार के लिए null लौटाया जा सकता है जिनमें भराव प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई पॉइंट्स में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक पर परिभाषित हाइपरलिंक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर पर परिभाषित हाइपरलिंक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | ज़ूम ऑब्जेक्ट की इमेज टाइप लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`ZoomImageType`](../zoomimagetype). डिफ़ॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार ग्रुपेड है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार की लाइन फ़ॉर्मेटिंग प्रॉपर्टी होती है। नोट: उन आकारों के प्रकार के लिए null लौटाया जा सकता है जिनमें लाइन प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता है या सेट करता है। Null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | स्लाइड-स्कोप्ड यूनिक आइडेंटिफायर लौटाता है जो आकार के जीवनकाल में स्थायी रहता है और PowerPoint या इंटरोप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32. देखें also [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार ग्रुपेड है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है, अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड के पैरेंट प्रेजेंटेशन को लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ shape फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Boolean. डिफ़ॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार के Z-अक्ष के चारों ओर घुमाव की डिग्री लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान उल्टी दिशा में। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टीज़) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | निर्धारित करता है कि ज़ूम गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ने/लिखने योग्य Boolean. डिफ़ॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार के पैरेंट स्लाइड को लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Section Zoom ऑब्जेक्ट द्वारा लिंक्स किए जाने वाले सेक्शन ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D इफ़ेक्ट प्रॉपर्टी होते हैं। नोट: उन आकारों के प्रकार के लिए null लौटाया जा सकता है जिनमें 3D प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Summary Zoom Section ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है या सेट करता है। |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | ज़ूम और स्लाइड के बीच ट्रांज़िशन की अवधि लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. डिफ़ॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड आइडेंटिफ़ायर लौटाता है जिसका उपयोग ऐड-इन्स या अन्य कोड कर सकते हैं। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः निर्धारित किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32. देखें also [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई पॉइंट्स में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने का x-कोऑर्डिनेट पॉइंट्स में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने का y-कोऑर्डिनेट पॉइंट्स में लौटाता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | ज़ूम ऑब्जेक्ट के लिए इमेज लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है। केवल-पढ़ने योग्य Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जिससे वर्तमान आकार विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की विज़ुअल बाउंड्स प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [SectionZoomFrame](../sectionzoomframe)
* इंटरफ़ेस [ISummaryZoomSection](../isummaryzoomsection)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* एसेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->