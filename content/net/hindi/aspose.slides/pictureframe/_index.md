---
title: PictureFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक चित्र के साथ अंतर्निहित फ्रेम का प्रतिनिधित्व करता है।
type: docs
weight: 9410
url: /hi/aspose.slides/pictureframe/
---
## PictureFrame क्लास

एक फ़्रेम का प्रतिनिधित्व करता है जिसमें चित्र अंतर्भुक्त होता है।

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | शेप के एडजस्टमेंट मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection)। |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक शेप से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक शेप से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्दिष्ट करती है कि एक शेप ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर किया जाएगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat वस्तु लौटाता है जिसमें शेप पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: कुछ प्रकार के शेप्स जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होतीं, के लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat वस्तु लौटाता है जिसमें शेप के भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के शेप्स जिनमें भराव प्रॉपर्टीज़ नहीं होतीं, के लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेप की ऊँचाई प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शेप छिपा है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | निर्धारित करता है कि PictureFrame एक Cameo ऑब्जेक्ट है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शेप समूहित है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat वस्तु लौटाता है जिसमें शेप के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के शेप्स जिनमें लाइन प्रॉपर्टीज़ नहीं होतीं, के लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक शेप का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ने/लिखने योग्य String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड विशिष्ट पहचानकर्ता लौटाता है जो शेप के आयु भर स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के कहीं से भी शेप को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32। अन्य देखें [`UniqueId`](../shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेप समूहित है तो पैरेंट GroupShape वस्तु लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape)। |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | एक PictureFrame के लिए PictureFillFormat वस्तु लौटाता है। केवल-पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat)। |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | शेप के लॉक लौटाता है। केवल-पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक शेप के लिए प्लेसहोल्डर लौटाता है। यदि शेप के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड का पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्ची शेप फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | पिक्चर फ्रेम की ऊँचाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ने/लिखने योग्य Single। |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | पिक्चर फ्रेम की चौड़ाई का स्केल (मूल चित्र आकार के सापेक्ष) लौटाता है या सेट करता है। मान 1.0 100% के बराबर है। पढ़ने/लिखने योग्य Single। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शेप को z-अक्ष के चारों ओर घुमाने के डिग्री संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिक्लॉकवाइज़ घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | शेप के लॉक लौटाता है। केवल-पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock)। (2 प्रॉपर्टीज़) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | शेप की स्टाइल वस्तु लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../ishapestyle)। |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame के लिए AutoShape प्रकार को लौटाता है या सेट करता है। सेट [`ShapeType`](../shapetype) के सभी अनुमेय आइटम हैं, सिवाय सभी प्रकार की लाइनों के: |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक शेप की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat वस्तु लौटाता है जिसमें शेप के 3D इफ़ेक्ट प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के शेप्स जिनमें 3D प्रॉपर्टीज़ नहीं होतीं, के लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। चूँकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। अन्य देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | शेप की चौड़ाई प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | शेप के ऊपरी-बाएँ कोने का x-निर्देशांक प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेप के ऊपरी-बाएँ कोने का y-निर्देशांक प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | एक शेप की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पिछले भाग में शेप लौटाता है, और Shapes[Shapes.Count - 1] आगे के भाग में शेप लौटाता है। केवल-पढ़ने योग्य Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | शेप के तत्वों की एरे बनाता है और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर शेप लौटाता है (लेआउट और/या मास्टर स्लाइड से वह शेप जिससे वर्तमान शेप विरासत में मिला है)। यदि वर्तमान शेप विरासत में नहीं है तो null लौटाया जाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | जियोमेट्री शेप के पाथ की प्रति लौटाता है। निर्देशांक शेप के बाएँ ऊपरी कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | शेप थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape.shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेप थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए कंटेंट से गणना किए गए शेप के दृश्य बाउंड्स प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | शेप जियोमेट्री को [`IGeometryPath`](../igeometrypath) वस्तु से अपडेट करता है। निर्देशांक शेप के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | शेप जियोमेट्री को [`IGeometryPath`](../igeometrypath) की एरे से अपडेट करता है। निर्देशांक शेप के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को कस्टम में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### उदाहरण

निम्नलिखित उदाहरण दर्शाते हैं कि ऑडियो फ्रेम थंबनेल को कैसे बदलें।

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // स्लाइड में एक निर्दिष्ट स्थिति और आकार के साथ ऑडियो फ्रेम जोड़ता है।
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // प्रेजेंटेशन संसाधनों में एक चित्र जोड़ता है।
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // ऑडियो फ्रेम के लिए चित्र सेट करता है।
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//संशोधित प्रेजेंटेशन को डिस्क पर सहेजता है।
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### देखें

* क्लास [GeometryShape](../geometryshape)
* इंटरफ़ेस [IPictureFrame](../ipictureframe)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->