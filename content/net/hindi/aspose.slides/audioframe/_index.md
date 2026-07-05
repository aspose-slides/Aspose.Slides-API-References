---
title: AudioFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: स्लाइड पर एक ऑडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
weight: 870
url: /hi/aspose.slides/audioframe/
---
## AudioFrame क्लास

एक स्लाइड पर ऑडियो क्लिप का प्रतिनिधित्व करता है।

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## प्रॉपर्टीज

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | एक संग्रह लौटाता है जिसमें आकार के समायोजन मान होते हैं। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़े वैकल्पिक पाठ को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़े वैकल्पिक पाठ के शीर्षक को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | अंतिम ट्रैक सूचकांक को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | अंतिम ट्रैक समय को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | प्रारंभिक ट्रैक सूचकांक को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | प्रारंभिक ट्रैक समय को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | गुण निर्धारित करता है कि एक आकार काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | ऑडियो फ़्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह गुण केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैकों को सम्मिलित करने वाला [`ICaptionsCollection`](../icaptionscollection) लौटाता है। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार के आकार जिनमें प्रभाव गुण नहीं होते, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | निर्धारित करता है कि प्रस्तुति में ध्वनि एम्बेडेड है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | एम्बेडेड ऑडियो ऑब्जेक्ट को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | मीडिया के प्रारंभिक फ़ेड-इन की अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ने/लिखने योग्य Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | मीडिया के समाप्ति फ़ेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ने/लिखने योग्य Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के भराव गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें भराव गुण नहीं होते, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ़्रेम की प्रॉपर्टीज़ को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई को पॉइंट में प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छुपा है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | निर्धारित करता है कि AudioFrame छुपा है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को प्राप्त करता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | निर्धारित करता है कि PictureFrame Cameo ऑब्जेक्ट है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार की रेखा फ़ॉर्मेट गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें रेखा गुण नहीं होते, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | AudioFrame से जुड़ी ऑडियो फ़ाइल का नाम प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकार का नाम प्राप्त करता या सेट करता है। null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता返回 करता है जो आकार के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार का विश्वसनीय संदर्भ देता है। केवल-पढ़ने योग्य UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है, अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | PictureFrame के लिए PictureFillFormat ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकार के प्लेसहोल्डर को प्राप्त करता है। यदि आकार का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | निर्धारित करता है कि ऑडियो लूप हो रहा है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | ऑडियो प्ले मोड को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति को प्राप्त करता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकार फ़्रेम की प्रॉपर्टीज़ को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | चित्र फ़्रेम की ऊँचाई के स्केल (मूल चित्र आकार के सापेक्ष) को प्राप्त करता या सेट करता है। मान 1.0 का अर्थ 100% है। पढ़ने/लिखने योग्य Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | चित्र फ़्रेम की चौड़ाई के स्केल (मूल चित्र आकार के सापेक्ष) को प्राप्त करता या सेट करता है। मान 1.0 का अर्थ 100% है। पढ़ने/लिखने योग्य Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | निर्धारित करता है कि ऑडियो प्लेबैक के बाद स्वचालित रूप से प्रारंभ बिंदु पर रीवाइंड हो जाता है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने की डिग्री प्राप्त करता या सेट करता है। सकारात्मक मान घड़ी दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock). (2 प्रॉपर्टीज़) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार की स्टाइल ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame के लिए AutoShape प्रकार को प्राप्त करता या सेट करता है। सेट [`ShapeType`](../shapetype) के सभी आइटम अनुमत हैं, सिवाय सभी प्रकार की रेखाओं के: |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकार की पैरेंट स्लाइड को प्राप्त करता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार के आकार जिनमें 3D गुण नहीं होते, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | प्लेबैक के दौरान मीडिया के अंत से हटाने के समय अवधि (मिलीसेकंड) को निर्धारित करता है। पढ़ने/लिखने योग्य Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | प्लेबैक के दौरान मीडिया की शुरुआत से हटाने के समय अवधि (मिलीसेकंड) को निर्धारित करता है। पढ़ने/लिखने योग्य Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन या अन्य कोड द्वारा उपयोग के लिए होता है। चूँकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | ऑडियो वॉल्यूम को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | ऑडियो वॉल्यूम को प्रतिशत में प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई को पॉइंट में प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट में प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट में प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में आकार की स्थिति को प्राप्त करता है। Shapes[0] पीछे की ओर वाले आकार को लौटाता है, और Shapes[Shapes.Count - 1] आगे की ओर वाले आकार को। केवल-पढ़ने योग्य Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों की array बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है)। यदि वर्तमान आकार विरासत में नहीं मिला तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्योमेट्री आकार के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए हुए कंटेंट से गणना किए गए आकार की दृश्य सीमा प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | यह निर्धारित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | आकार की ज्यामिति को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। आकार का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | आकार की ज्यामिति को [`IGeometryPath`](../igeometrypath) की array से अपडेट करता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। आकार का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### उदाहरण

Audio Play Options को बदलने के उदाहरण नीचे दिखाए गए हैं।

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // AudioFrame आकार प्राप्त करता है
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // प्ले मोड को क्लिक पर चलाने के लिए सेट करता है
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // वॉल्यूम को लो पर सेट करता है
    audioFrame.Volume = AudioVolumeMode.Low;
    // ऑडियो को सभी स्लाइड्स में चलाने के लिए सेट करता है
    audioFrame.PlayAcrossSlides = true;
    // ऑडियो के लिए लूप को अक्षम करता है
    audioFrame.PlayLoopMode = false;
    // स्लाइड शो के दौरान AudioFrame को छुपाता है
    audioFrame.HideAtShowing = true;
    // प्ले करने के बाद ऑडियो को शुरू में रीवाइंड करता है
    audioFrame.RewindAudio = true;
    // PowerPoint फ़ाइल को डिस्क पर सहेजता है
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### अन्य देखें

* क्लास [PictureFrame](../pictureframe)
* इंटरफ़ेस [IAudioFrame](../iaudioframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->