---
title: SectionZoomFrame
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: स्लाइड में एक Section Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 9780
url: /hi/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame क्लास

एक स्लाइड में Section Zoom ऑब्जेक्ट को दर्शाता है।

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़े वैकल्पिक टेक्स्ट को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़े वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | एक आकार काले-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा, यह निर्दिष्ट करता है। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | वह EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार के आकार जिनके पास प्रभाव गुण नहीं होते, उनके लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | वह FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए भराव स्वरूप गुण होते हैं। नोट: कुछ प्रकार के आकार जिनके पास भराव गुण नहीं होते, उनके लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की गुणों को लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को पॉइंट में मापते हुए प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छुपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | ज़ूम ऑब्जेक्ट की इमेज प्रकार को प्राप्त या सेट करता है। पढ़ें/लिखें [`ZoomImageType`](../zoomimagetype). डिफ़ॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | वह LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन स्वरूप गुण होते हैं। नोट: कुछ प्रकार के आकार जिनके पास लाइन गुण नहीं होते, उनके लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकार का स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ने योग्य UInt32। देखें भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड के पैरेंट प्रेजेंटेशन को लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चा आकार फ्रेम की गुणों को लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. डिफ़ॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्धारित करता है कि निर्दिष्ट आकार z-अक्ष के चारों ओर कितने डिग्री घुमाया गया है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | यह निर्धारित करने वाला मान प्राप्त या सेट करता है कि ज़ूम गंतव्य स्लाइड की पृष्ठभूमि उपयोग करेगा या नहीं। पढ़ें/लिखें Boolean. डिफ़ॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Section Zoom ऑब्जेक्ट जिस सेक्शन ऑब्जेक्ट से लिंक करता है, उसे प्राप्त या सेट करता है। पढ़ें/लिखें [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | वह ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार के आकार जिनके पास 3D गुण नहीं होते, उनके लिए null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom और स्लाइड के बीच संक्रमण की अवधि प्राप्त या सेट करता है। पढ़ें/लिखें Single. डिफ़ॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन या अन्य कोड द्वारा उपयोग के लिए है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32। देखें भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को पॉइंट में मापते हुए प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने का x-निर्देशांक पॉइंट में मापते हुए प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने का y-निर्देशांक पॉइंट में मापते हुए प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | ज़ूम ऑब्जेक्ट के लिए इमेज प्राप्त या सेट करता है। पढ़ें/लिखें [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की z-क्रम में स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे का आकार लौटाता है, और Shapes[Shapes.Count - 1] z-क्रम के सामने का आकार लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणों को सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार की थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार की थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की दृश्य सीमा प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें भी

* क्लास [ZoomObject](../zoomobject)
* इंटरफ़ेस [ISectionZoomFrame](../isectionzoomframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->