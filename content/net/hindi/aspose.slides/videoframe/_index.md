---
title: VideoFrame
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक स्लाइड पर वीडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
weight: 11740
url: /hi/aspose.slides/videoframe/
---
## VideoFrame क्लास

एक स्लाइड पर वीडियो क्लिप का प्रतिनिधित्व करता है।

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection)। |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकार से जुड़े वैकल्पिक टेक्स्ट को प्राप्त करता या सेट करता है। पढ़ें/लिखें String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकार से जुड़े वैकल्पिक टेक्स्ट के शीर्षक को प्राप्त करता या सेट करता है। पढ़ें/लिखें String। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्धारित करता है कि आकार काले-धुँधले प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode)। |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | वीडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह गुण केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैक्स को सम्मिलित करने वाला एक [`ICaptionsCollection`](../icaptionscollection) लौटाता है। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | वह EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: उन कुछ प्रकार के आकारों के लिए जो प्रभाव गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | एम्बेडेड वीडियो ऑब्जेक्ट को प्राप्त करता या सेट करता है। पढ़ें/लिखें [`IVideo`](../ivideo)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | वह FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए भराव फ़ॉर्मेटिंग गुण होते हैं। नोट: उन कुछ प्रकार के आकारों के लिए जो भराव गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुणों को प्राप्त करता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe)। |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | निर्धारित करता है कि वीडियो पूर्ण-स्क्रीन मोड में दिखाया जाता है या नहीं। पढ़ें/लिखें Boolean। |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को पॉइंट्स में मापकर प्राप्त करता या सेट करता है। पढ़ें/लिखें Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean। |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | निर्धारित करता है कि VideoFrame छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink)। |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | निर्धारित करता है कि PictureFrame Cameo ऑब्जेक्ट है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता या सेट करता है। पढ़ें/लिखें Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | वह LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए रेखा फ़ॉर्मेटिंग गुण होते हैं। नोट: उन कुछ प्रकार के आकारों के लिए जो रेखा गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | VideoFrame से जुड़े वीडियो फ़ाइल का नाम प्राप्त करता या सेट करता है। पढ़ें/लिखें String। |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम प्राप्त करता या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | आकार के जीवनकाल के दौरान स्थायी रहने वाला स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है, जिससे PowerPoint या इंटरॉप कोड दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित कर सकता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape)। |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | एक पिक्चर फ्रेम के लिए PictureFillFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat)। |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder)। |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | निर्धारित करता है कि वीडियो लूप में चलाया जाता है या नहीं। पढ़ें/लिखें Boolean। |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | वीडियो प्ले मोड को प्राप्त करता या सेट करता है। पढ़ें/लिखें [`VideoPlayModePreset`](../videoplaymodepreset)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड के पैरेंट प्रस्तुति को लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ्रेम के गुणों को प्राप्त करता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe)। |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | पिक्चर फ्रेम की ऊँचाई के स्केल (मूल चित्र आकार के सापेक्ष) को प्राप्त करता या सेट करता है। मान 1.0 100% के बराबर है। पढ़ें/लिखें Single। |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | पिक्चर फ्रेम की चौड़ाई के स्केल (मूल चित्र आकार के सापेक्ष) को प्राप्त करता या सेट करता है। मान 1.0 100% के बराबर है। पढ़ें/लिखें Single। |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | निर्धारित करता है कि फिल्म समाप्त होते ही वीडियो को स्वचालित रूप से शुरू से फिर से चलाया जाए। पढ़ें/लिखें Boolean। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या प्राप्त करता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में। पढ़ें/लिखें Single। |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock)। (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार की शैली ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../ishapestyle)। |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame के लिए AutoShape प्रकार प्राप्त करता या सेट करता है। सेट [`ShapeType`](../shapetype) के सभी आइटम अनुमत हैं, सिवाय सभी प्रकार की रेखाओं के: |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | आकार के 3D प्रभाव गुणों के लिए ThreeDFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए जिनमें 3D गुण नहीं होते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat)। |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | अंत ट्रिम [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | प्रारंभ ट्रिम [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है, जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिये है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामmatically पुनः सौंपा जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid)। |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | ऑडियो वॉल्यूम को प्राप्त करता या सेट करता है। पढ़ें/लिखें [`AudioVolumeMode`](../audiovolumemode)। |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | सटीक वीडियो वॉल्यूम को प्रतिशत के रूप में प्राप्त करता या सेट करता है। मान 0 से 100 प्रतिशत के बीच व्यक्त किया जाता है। इस गुण का उपयोग करके आप [`Volume`](./volume) गुण द्वारा उपलब्ध पूर्वनिर्धारित स्तरों से अधिक सटीक वॉल्यूम मान पढ़ या सेट कर सकते हैं। पढ़ें/लिखें Single। |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को पॉइंट्स में मापकर प्राप्त करता या सेट करता है। पढ़ें/लिखें Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापकर प्राप्त करता या सेट करता है। पढ़ें/लिखें Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापकर प्राप्त करता या सेट करता है। पढ़ें/लिखें Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर में पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला आकार लौटाता है। केवल-पढ़ने योग्य Int32। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों की एरे बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक मूल प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से प्राप्त आकार जिससे वर्तमान आकार विरासत में मिलता है)। यदि वर्तमान आकार विरासत में नहीं है तो null दिया जाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति आकार के पाथ की कॉपी लौटाता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स टाइप उपयोग होता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की दृश्य सीमाओं को उसके रेंडर किए गए कंटेंट से गणना कर प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | आकार की ज्यामिति को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | आकार की ज्यामिति को [`IGeometryPath`](../igeometrypath) की एरे से अपडेट करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [PictureFrame](../pictureframe)
* इंटरफेस [IVideoFrame](../ivideoframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->