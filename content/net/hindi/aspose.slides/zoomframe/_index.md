---
title: ZoomFrame
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: एक स्लाइड में Slide Zoom वस्तु को दर्शाता है।
type: docs
weight: 11840
url: /hi/aspose.slides/zoomframe/
---
## ZoomFrame क्लास

एक स्लाइड में Slide Zoom वस्तु को दर्शाता है।

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से संबंधित वैकल्पिक पाठ को प्राप्त या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से संबंधित वैकल्पिक पाठ के शीर्षक को प्राप्त या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | विधि यह निर्दिष्ट करती है कि एक आकार काले-और-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या को प्राप्त करता है। सिर्फ पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को प्राप्त करता है। सिर्फ पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat वस्तु को प्राप्त करता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। ध्यान दें: कुछ प्रकार के आकारों के लिए जो प्रभाव गुण नहीं रखते, null लौटाया जा सकता है। सिर्फ पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat वस्तु को प्राप्त करता है जिसमें आकार के लिए भराव गुण होते हैं। ध्यान दें: कुछ प्रकार के आकारों के लिए जो भराव गुण नहीं रखते, null लौटाया जा सकता है। सिर्फ पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम की गुणधर्मों को प्राप्त या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकार के लॉक को प्राप्त करता है। सिर्फ पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को पॉइंट में प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को प्राप्त करता है। सिर्फ पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | ज़ूम वस्तु की छवि प्रकार को प्राप्त या सेट करता है। पढ़ें/लिखें [`ZoomImageType`](../zoomimagetype). डिफ़ॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'सजावटी के रूप में चिह्नित' विकल्प को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। सिर्फ पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। सिर्फ पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat वस्तु को प्राप्त करता है जिसमें आकार के लिए रेखा गुण होते हैं। ध्यान दें: कुछ प्रकार के आकारों के लिए जो रेखा गुण नहीं रखते, null लौटाया जा सकता है। सिर्फ पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम प्राप्त या सेट करता है। null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकार के जीवनकाल के दौरान स्थायी रहने वाला स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता प्राप्त करता है। सिर्फ पढ़ने योग्य UInt32. देखें भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape वस्तु प्राप्त करता है, अन्यथा null लौटाता है। सिर्फ पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के प्लेसहोल्डर को प्राप्त करता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। सिर्फ पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति को प्राप्त करता है। सिर्फ पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्ची आकार फ्रेम की गुणधर्मों को प्राप्त या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. डिफ़ॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्धारित करता है कि आकार z-अक्ष के चारों ओर कितने डिग्री घुमा है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकार के लॉक को प्राप्त करता है। सिर्फ पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 गुण) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | यह निर्धारित करता है कि ज़ूम गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें/लिखें Boolean. डिफ़ॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड को प्राप्त करता है। सिर्फ पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | वह स्लाइड वस्तु प्राप्त या सेट करता है जिससे Slide Zoom वस्तु जुड़ी होती है। पढ़ें/लिखें [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat वस्तु को प्राप्त करता है जिसमें आकार के 3D प्रभाव गुण होते हैं। ध्यान दें: कुछ प्रकार के आकारों के लिए जो 3D गुण नहीं रखते, null लौटाया जा सकता है। सिर्फ पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | ज़ूम और स्लाइड के बीच संक्रमण की अवधि को प्राप्त या सेट करता है। पढ़ें/लिखें Single. डिफ़ॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता को प्राप्त करता है जो ऐड-इन या अन्य कोड द्वारा इस्तेमाल करने हेतु है। चूँकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः निर्धारित किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। सिर्फ पढ़ने योग्य UInt32. देखें भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को पॉइंट में प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी बाएँ कोने के x-निर्देशांक को पॉइंट में प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी बाएँ कोने के y-निर्देशांक को पॉइंट में प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | ज़ूम वस्तु की छवि को प्राप्त या सेट करता है। पढ़ें/लिखें [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकार की z-ऑर्डर में स्थिति को प्राप्त करता है। Shapes[0] पीछे की स्थिति देता है, और Shapes[Shapes.Count - 1] आगे की स्थिति देता है। सिर्फ पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणधर्म सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | मौजूदा आकार के लेआउट या मास्टर स्लाइड से बुनियादी प्लेसहोल्डर आकार को प्राप्त करता है। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल को प्राप्त करता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल सीमा प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल को प्राप्त करता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की रेंडर की गई सामग्री से गणना किए गए दृश्य सीमाओं को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखिए

* class [ZoomObject](../zoomobject)
* interface [IZoomFrame](../izoomframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->