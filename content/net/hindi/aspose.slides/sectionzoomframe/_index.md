---
title: SectionZoomFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक स्लाइड में Section Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 9780
url: /hi/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame क्लास

एक स्लाइड में Section Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से जुड़ा वैकल्पिक पाठ प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से जुड़ा वैकल्पिक पाठ का शीर्षक प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्धारित करता है कि आकार काले-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या प्राप्त करता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को प्राप्त करता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | वह EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार के आकारों के लिए जो प्रभाव गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | वह FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए भराव स्वरूपण गुण होते हैं। नोट: कुछ प्रकार के आकारों के लिए जो भराव गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुणों को प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक प्राप्त करता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | बिंदुओं में मापी गई आकार की ऊँचाई प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को प्राप्त करता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | ज़ूम ऑब्जेक्ट की इमेज प्रकार प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें [`ZoomImageType`](../zoomimagetype). डिफ़ॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | वह LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए रेखा स्वरूपण गुण होते हैं। नोट: कुछ प्रकार के आकारों के लिए जो रेखा गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम प्राप्त करता है या निर्धारित करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता प्राप्त करता है जो आकार के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल पढ़ने योग्य UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट प्राप्त करता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर प्राप्त करता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति प्राप्त करता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम के गुणों को प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें Boolean. डिफ़ॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को Z-अक्ष के चारों ओर घुमाने के डिग्री प्राप्त करता है या निर्धारित करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विरुद्ध दिशा में घुमाव। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक प्राप्त करता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 गुण) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | निर्धारित करता है कि ज़ूम गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें/लिखें Boolean. डिफ़ॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड प्राप्त करता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | वह सेक्शन ऑब्जेक्ट प्राप्त करता है जिससे Section Zoom ऑब्जेक्ट जुड़ा है। पढ़ें/लिखें [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | वह ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार के आकारों के लिए जो 3D गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | ज़ूम और स्लाइड के बीच संक्रमण की अवधि प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें Single. डिफ़ॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता प्राप्त करता है जो ऐड-इन या अन्य कोड द्वारा उपयोग के लिये अभिप्रेत है। चूँकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | बिंदुओं में मापी गई आकार की चौड़ाई प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के x-निर्देशांक प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | बिंदुओं में मापे गए आकार के ऊपर-बाएँ कोने के y-निर्देशांक प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | ज़ूम ऑब्जेक्ट की छवि प्राप्त करता है या निर्धारित करता है। पढ़ें/लिखें [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की z-ऑर्डर में स्थिति प्राप्त करता है। Shapes[0] पीछे की z-ऑर्डर वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे की z-ऑर्डर वाला आकार लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर मौजूद नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर गुण सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार (लेआउट या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है) लौटाता है। यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल प्राप्त करता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बॉन्ड टाइप उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल प्राप्त करता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की दृश्य सीमाओं को उसके रेंडर किए गए कंटेंट से गणना करके प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [ZoomObject](../zoomobject)
* इंटरफ़ेस [ISectionZoomFrame](../isectionzoomframe)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->