---
title: PictureFrame
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: चित्र के साथ एक फ्रेम को दर्शाता है।
type: docs
weight: 9430
url: /hi/aspose.slides/pictureframe/
---
## PictureFrame क्लास

चित्र के साथ एक फ्रेम को दर्शाता है।

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | शेप के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection)। |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | शेप से जुड़े वैकल्पिक टेक्स्ट को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | शेप से जुड़े वैकल्पिक टेक्स्ट का शीर्षक प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी निर्दिष्ट करती है कि एक शेप काले-और-सफेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें एक शेप पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: उन कुछ शेप प्रकारों के लिए null लौटाया जा सकता है जिनमें प्रभाव प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें एक शेप के लिए फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन कुछ शेप प्रकारों के लिए null लौटाया जा सकता है जिनमें फ़िल प्रॉपर्टीज़ नहीं होती। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम की प्रॉपर्टीज़ को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेप की ऊँचाई को प्राप्त करता या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शेप छिपा है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | निर्धारित करता है कि PictureFrame एक Cameo ऑब्जेक्ट है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शेप समूहित है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें एक शेप के लिए रेखा फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन कुछ शेप प्रकारों के लिए null लौटाया जा सकता है जिनमें रेखा प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | शेप का नाम प्राप्त करता या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ने/लिखने योग्य String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्तरीय अनूठा पहचानकर्ता लौटाता है जो शेप के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को कहीं से भी दस्तावेज़ में शेप को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape)। |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | एक PictureFillFormat ऑब्जेक्ट लौटाता है जो एक पिक्चर फ्रेम के लिए है। केवल-पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat)। |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | शेप के लॉक लौटाता है। केवल-पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक शेप के लिए प्लेसहोल्डर लौटाता है। यदि शेप के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ शेप फ्रेम की प्रॉपर्टीज़ को प्राप्त करता या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | पिक्चर फ्रेम की ऊँचाई (मूल पिक्चर आकार के सापेक्ष) का स्केल प्राप्त करता या सेट करता है। मान 1.0 का अर्थ 100% है। पढ़ने/लिखने योग्य Single। |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | पिक्चर फ्रेम की चौड़ाई (मूल पिक्चर आकार के सापेक्ष) का स्केल प्राप्त करता या सेट करता है। मान 1.0 का अर्थ 100% है। पढ़ने/लिखने योग्य Single। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शेप को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या प्राप्त करता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान घड़ी की उल्टी दिशा में घूर्णन दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | शेप के लॉक लौटाता है। केवल-पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock)। (2 प्रॉपर्टीज़) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | शेप के स्टाइल ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../ishapestyle)। |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame के लिए AutoShape प्रकार को प्राप्त करता या सेट करता है। सेट [`ShapeType`](../shapetype) के सभी आइटम अनुमत हैं, सिवाय सभी प्रकार की रेखाओं के: |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक शेप की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें शेप के 3d इफ़ेक्ट प्रॉपर्टीज़ होते हैं। नोट: उन कुछ शेप प्रकारों के लिए null लौटाया जा सकता है जिनमें 3d प्रॉपर्टी नहीं है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्तरीय पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग करने के लिए बनाया गया है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अनूठी कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | शेप की चौड़ाई को प्राप्त करता या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | शेप के ऊपरी बाएं कोने के x-निर्देशांक को प्राप्त करता या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेप के ऊपरी बाएं कोने के y-निर्देशांक को प्राप्त करता या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | एक शेप की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] पीछे की ओर z-ऑर्डर में स्थित शेप लौटाता है, और Shapes[Shapes.Count - 1] आगे की ओर स्थित शेप लौटाता है। केवल-पढ़ने योग्य Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | शेप के तत्वों की एरे बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर शेप लौटाता है (लेआउट और/या मास्टर स्लाइड से वह शेप जिससे वर्तमान शेप विरासत में मिला हो)। यदि वर्तमान शेप विरासत में नहीं मिला तो null लौटाया जाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति शेप के पाथ की कॉपी लौटाता है। निर्देशांक शेप के बाएँ ऊपरी कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | शेप थंबनेल लौटाता है। डिफ़ॉल्ट रूप में ShapeThumbnailBounds.Shape शेप थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेप थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए कंटेंट से गणना किए गए शेप के विज़ुअल बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से शेप ज्योमेट्री को अपडेट करता है। निर्देशांक शेप के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) की एरे से शेप ज्योमेट्री को अपडेट करता है। निर्देशांक शेप के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### उदाहरण

निम्न उदाहरण दिखाते हैं कि ऑडियो फ़्रेम थंबनेल को कैसे बदलें।

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // स्लाइड में निर्दिष्ट स्थान और आकार के साथ एक ऑडियो फ्रेम जोड़ता है।
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // प्रस्तुति संसाधनों में एक छवि जोड़ता है।
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // ऑडियो फ्रेम के लिए छवि सेट करता है.
	// संशोधित प्रस्तुति को डिस्क पर सहेजता है
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### संबंधित देखें

* क्लास [GeometryShape](../geometryshape)
* इंटरफ़ेस [IPictureFrame](../ipictureframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंब्लि [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->