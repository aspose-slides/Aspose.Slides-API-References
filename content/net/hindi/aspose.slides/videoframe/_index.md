---
title: VideoFrame
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक स्लाइड पर वीडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
weight: 11720
url: /hi/aspose.slides/videoframe/
---
## VideoFrame क्लास

एक स्लाइड पर वीडियो क्लिप को दर्शाता है।

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | शेप के समायोजन मानों का संग्रह लौटाता है। Read-only [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक शेप से संबद्ध वैकल्पिक टेक्स्ट को प्राप्त करता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक शेप से संबद्ध वैकल्पिक टेक्स्ट के शीर्षक को प्राप्त करता है या सेट करता है। Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्दिष्ट करती है कि एक शेप ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | वीडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल पढ़ने योग्य है और सभी कैप्शन ट्रैक का समावेश करने वाला [`ICaptionsCollection`](../icaptionscollection) लौटाती है। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइटों की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप के कस्टम डेटा को लौटाता है। Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat वस्तु लौटाता है जिसमें एक शेप पर लागू पिक्सेल इफेक्ट्स होते हैं। नोट: उन कुछ प्रकार के शेप्स के लिए जो इफेक्ट प्रॉपर्टीज़ नहीं रखते, यह null वापिस कर सकता है। Read-only [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | एम्बेडेड वीडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। Read/write [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat वस्तु लौटाता है जिसमें एक शेप के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: उन कुछ प्रकार के शेप्स के लिए जो भराव प्रॉपर्टीज़ नहीं रखते, यह null वापिस कर सकता है। Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | निर्धारित करता है कि क्या वीडियो पूर्ण स्क्रीन मोड में दिखाया जाता है। Read/write Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेप की ऊँचाई को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि क्या शेप छिपा हुआ है। Read/write Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | निर्धारित करता है कि PictureFrame एक Cameo ऑब्जेक्ट है या नहीं। Read only Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | डेकोरेटिव के रूप में मार्क करने वाले विकल्प को प्राप्त करता है या सेट करता है। Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि क्या शेप समूहित है। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि क्या शेप TextHolder_PPT है। Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat वस्तु लौटाता है जिसमें एक शेप के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: उन कुछ प्रकार के शेप्स के लिए जिनमें लाइन प्रॉपर्टीज़ नहीं होते, यह null लौटाता है। Read-only [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | VideoFrame से जुड़े वीडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है। Read/write String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | शेप का नाम प्राप्त करता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग का उपयोग करें। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो इस शेप के जीवनकाल के दौरान स्थायी रहता है और किसी भी स्थान से PowerPoint या इंटरऑप कोड द्वारा भरोसेमंद रूप से रेफ़रेंस किया जा सकता है। Read-only UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | पिक्चर फ्रेम के लिए PictureFillFormat ऑब्जेक्ट लौटाता है। Read-only [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | शेप के लॉक लौटाता है। Read-only [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक शेप के लिए प्लेसहोल्डर लौटाता है। यदि शेप के पास प्लेसहोल्डर नहीं है तो null लौटाता है। Read-only [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | निर्धारित करता है कि क्या वीडियो लूप किया गया है। Read/write Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | वीडियो प्ले मोड को प्राप्त करता है या सेट करता है। Read/write [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे शेप फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | पिक्चर फ्रेम की ऊँचाई का स्केल (मूल चित्र आकार से सापेक्ष) प्राप्त करता है या सेट करता है। मान 1.0 100% के बराबर है। Read/write Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | पिक्चर फ्रेम की चौड़ाई का स्केल (मूल चित्र आकार से सापेक्ष) प्राप्त करता है या सेट करता है। मान 1.0 100% के बराबर है। Read/write Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | निर्धारित करता है कि क्या वीडियो समाप्त होने पर तुरंत शुरू से रीवाइंड हो जाता है। Read/write Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शेप के z-अक्ष के चारों ओर घुमाव के डिग्री संख्या को प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी की उल्टी दिशा में घुमाव दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | शेप के लॉक लौटाता है। Read-only [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | शेप की शैली ऑब्जेक्ट लौटाता है। Read-only [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame के लिए AutoShape प्रकार को प्राप्त करता है या सेट करता है। सेट [`ShapeType`](../shapetype) के सभी मान्य आइटम उपलब्ध हैं, सिवाय सभी प्रकार की लाइनों के: |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक शेप की पैरेंट स्लाइड लौटाता है। Read-only [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें शेप के 3D इफेक्ट प्रॉपर्टीज़ होते हैं। नोट: उन कुछ प्रकार के शेप्स के लिए जिनमें 3D प्रॉपर्टीज़ नहीं होते, यह null लौटाता है। Read-only [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | अंत को ट्रिम करें [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | प्रारंभ को ट्रिम करें [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक अंतर्निहित, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन या अन्य कोड द्वारा उपयोग के लिए होता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। Read-only UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। Read/write [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | शेप की चौड़ाई को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | शेप के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेप के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में एक शेप की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला शेप लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला शेप लौटाता है। Read-only Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | शेप के तत्वों का एरे बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर शेप लौटाता है (लेआउट या मास्टर स्लाइड से वह शेप जिससे वर्तमान शेप विरासत में मिला है)। यदि वर्तमान शेप विरासत में नहीं मिला है तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्योमेट्री शेप के पाथ की प्रति लौटाता है। निर्देशांक शेप के बाएँ ऊपर कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | शेप का थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape का थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेप का थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | शेप की विज़ुअल बाउंड्स प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | शेप ज्योमेट्री को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक शेप के बाएँ ऊपर कोने के सापेक्ष होना चाहिए। शेप का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | शेप ज्योमेट्री को [`IGeometryPath`](../igeometrypath) की एरे से अपडेट करता है। निर्देशांक शेप के बाएँ ऊपर कोने के सापेक्ष होना चाहिए। शेप का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [PictureFrame](../pictureframe)
* इंटरफ़ेस [IVideoFrame](../ivideoframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->