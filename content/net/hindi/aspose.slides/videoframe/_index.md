---
title: VideoFrame
second_title: Aspose.Sildes .NET API संदर्भ
description: स्लाइड पर एक वीडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
weight: 11720
url: /hi/aspose.slides/videoframe/
---
## VideoFrame क्लास

स्लाइड पर एक वीडियो क्लिप को दर्शाता है।

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | शेप के समायोजन मानों के संग्रह को लौटाता है। केवल पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | शेप से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | शेप से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | संपत्ति निर्धारित करती है कि एक शेप काली-सफ़ेद डिस्प्ले मोड में कैसे प्रस्तुत होगी। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | वीडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह संपत्ति केवल पढ़ने योग्य है और सभी कैप्शन ट्रैक्स को शामिल करने वाला [`ICaptionsCollection`](../icaptionscollection) लौटाती है। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | वह EffectFormat ऑब्जेक्ट लौटाता है जिसमें शेप पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार के शेप जिनमें प्रभाव गुण नहीं होते हैं, उनके लिए null लौटा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | एम्बेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | वह FillFormat ऑब्जेक्ट लौटाता है जिसमें शेप के लिए भरने की फ़ॉर्मेटिंग गुण होते हैं। नोट: कुछ प्रकार के शेप जिनमें भरने के गुण नहीं होते हैं, उनके लिए null लौटा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम की गुणधर्मों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | निर्धारित करता है कि वीडियो पूर्ण-स्क्रीन मोड में दिखाया जाए या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेप की ऊँचाई को पॉइंट में मापता है। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शेप छिपा हुआ है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | निर्धारित करता है कि VideoFrame छिपा हुआ है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | निर्धारित करता है कि PictureFrame Cameo ऑब्जेक्ट है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शेप समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | वह LineFormat ऑब्जेक्ट लौटाता है जिसमें शेप के लिए रेखा फ़ॉर्मेटिंग गुण होते हैं। नोट: कुछ प्रकार के शेप जिनमें रेखा के गुण नहीं होते हैं, उनके लिए null लौटा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | VideoFrame से लिंक किए गये वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | शेप का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो शेप की आयु-काल तक स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से भरोसेमंद रूप से रेफ़रेंस करने की अनुमति देता है। केवल पढ़ने योग्य UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | PictureFrame के लिए PictureFillFormat ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | शेप के लॉक को लौटाता है। केवल पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | शेप के प्लेसहोल्डर को लौटाता है। यदि शेप का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | निर्धारित करता है कि वीडियो लूप किया जाए या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | वीडियो प्ले मोड को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेज़ेंटेशन को लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे शेप फ्रेम की गुणधर्मों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | चित्र फ्रेम की ऊँचाई (मूल चित्र आकार के अनुपात में) के स्केल को लौटाता है या सेट करता है। मान 1.0 का अर्थ 100% है। पढ़ने/लिखने योग्य Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | चित्र फ्रेम की चौड़ाई (मूल चित्र आकार के अनुपात में) के स्केल को लौटाता है या सेट करता है। मान 1.0 का अर्थ 100% है। पढ़ने/लिखने योग्य Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | निर्धारित करता है कि वीडियो समाप्त होने पर स्वचालित रूप से शुरू से रीवाइंड किया जाए। पढ़ने/लिखने योग्य Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शेप को Z-अक्ष के चारों ओर घुमाने के डिग्री संख्या को लौटाता या सेट करता है। सकारात्मक मान घड़ी दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी दिशा में। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | शेप के लॉक को लौटाता है। केवल पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock). (2 गुण) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | शेप की स्टाइल ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame के लिए AutoShape प्रकार को लौटाता या सेट करता है। सेट [`ShapeType`](../shapetype) के सभी आइटम वैध हैं, सिवाय सभी प्रकार की रेखाओं के: |
| [Slide](../../aspose.slides/shape/slide) { get; } | शेप के पैरेंट स्लाइड को लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | वह ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें शेप के 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार के शेप जिनमें 3D गुण नहीं होते हैं, उनके लिए null लौटा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | अंत समाप्ति [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | प्रारंभ समाप्ति [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | आंतरिक, प्रेज़ेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिये अभिप्रेत है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुन: असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | ऑडियो वॉल्यूम को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | शेप की चौड़ाई को पॉइंट में मापता है। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | शेप के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में मापता है। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेप के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में मापता है। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में शेप की स्थिति को लौटाता है। Shapes[0] पीछे की ओर स्थित शेप लौटाता है, और Shapes[Shapes.Count - 1] आगे की ओर स्थित शेप लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट एक के प्लेसहोल्डर गुण सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | शेप के तत्वों का ऐरे बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | बुनियादी प्लेसहोल्डर शेप (लेआउट या मास्टर स्लाइड से वह शेप जिसका वर्तमान शेप विरासत में मिला है) लौटाता है। यदि वर्तमान शेप विरासत में नहीं मिला है तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति शेप के पथ की प्रतिलिपि लौटाता है। निर्देशांक शेप के बाएँ-ऊपरी कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | शेप थंबनेल लौटाता है। ShapeThumbnailBounds.Shape शेप थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेप थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर्ड सामग्री से गणना किए गये शेप की दृश्य सीमा प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | शेप ज्यामिति को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक शेप के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। शेप प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | शेप ज्यामिति को [`IGeometryPath`](../igeometrypath) के ऐरे से अपडेट करता है। निर्देशांक शेप के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। शेप प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [PictureFrame](../pictureframe)
* इंटरफ़ेस [IVideoFrame](../ivideoframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंब्ली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->