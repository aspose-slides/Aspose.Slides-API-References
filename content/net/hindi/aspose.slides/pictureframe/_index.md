---
title: PictureFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक फ्रेम को दर्शाता है जिसमें अंदर एक चित्र होता है।
type: docs
weight: 9410
url: /hi/aspose.slides/pictureframe/
---
## PictureFrame क्लास

एक फ्रेम को दर्शाता है जिसमें एक चित्र सम्मिलित होता है।

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | शेपी के समायोजन मानों का संग्रह लौटाता है। केवल पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक शेपी से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक शेपी से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्दिष्ट करता है कि एक शेपी ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेपी पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेपी का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat वस्तु लौटाता है जिसमें एक शेपी पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: कुछ प्रकार की शेपियों के लिए जो इफ़ेक्ट गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat वस्तु लौटाता है जिसमें एक शेपी के लिए भराव फ़ॉर्मेटिंग गुण होते हैं। नोट: कुछ प्रकार की शेपियों के लिए जो भराव गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेपी फ्रेम की गुणधर्म लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | शेपी की ऊँचाई प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शेपी छिपा है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | निर्धारित करता है कि PictureFrame एक Cameo वस्तु है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शेपी समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शेपी TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat वस्तु लौटाता है जिसमें एक शेपी के लिए रेखा फ़ॉर्मेटिंग गुण होते हैं। नोट: कुछ प्रकार की शेपियों के लिए जो रेखा गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | शेपी का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो शेपी के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के कहीं से भी विश्वसनीय रूप से शेपी का संदर्भ देने देता है। केवल पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेपी समूहित है तो पैरेंट GroupShape वस्तु लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Picture frame के लिए PictureFillFormat वस्तु लौटाता है। केवल पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | शेपी के लॉक लौटाता है। केवल पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | शेपी के लिए प्लेसहोल्डर लौटाता है। यदि शेपी का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे शेपी फ्रेम की गुणधर्म लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Picture frame की ऊँचाई (मूल चित्र आकार के सापेक्ष) के स्केल को लौटाता है या सेट करता है। मान 1.0 का अर्थ 100% है। पढ़ने/लिखने योग्य Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Picture frame की चौड़ाई (मूल चित्र आकार के सापेक्ष) के स्केल को लौटाता है या सेट करता है। मान 1.0 का अर्थ 100% है। पढ़ने/लिखने योग्य Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शेपी को z-अक्ष के चारों ओर घुमा देने के डिग्री की संख्या लौटाता है या सेट करता है। धनात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; ऋणात्मक मान विपरीत दिशा दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | शेपी के लॉक लौटाता है। केवल पढ़ने योग्य [`IPictureFrameLock`](../ipictureframelock). (2 गुण) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | शेपी की शैली वस्तु लौटाता है। केवल पढ़ने योग्य [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame के लिए AutoShape प्रकार लौटाता है या सेट करता है। सेट के सभी आइटम अनुमत हैं [`ShapeType`](../shapetype), सिवाय सभी प्रकार की रेखाओं के: |
| [Slide](../../aspose.slides/shape/slide) { get; } | शेपी की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat वस्तु लौटाता है जिसमें एक शेपी के लिए 3D प्रभाव गुण होते हैं। नोट: कुछ प्रकार की शेपियों के लिए जो 3D गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जा सकता है। चूँकि यह मान उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | शेपी की चौड़ाई प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | शेपी के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेपी के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट्स में मापी गई। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | एक शेपी के z-क्रम में स्थिति लौटाता है। Shapes[0] पीछे की स्थिति वाला शेपी लौटाता है, और Shapes[Shapes.Count - 1] आगे की स्थिति वाला शेपी लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | एक नया प्लेसहोल्डर जोड़ता है यदि कोई मौज़ूद नहीं है और प्लेसहोल्डर गुणों को निर्दिष्ट वस्तु पर सेट करता है. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | शेपि के तत्वों की एरे बनाता है और लौटाता है. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर शेपी लौटाता है (लेआउट और/या मास्टर स्लाइड से वह शेपी जिससे वर्तमान शेपी विरासत में मिला है). यदि वर्तमान शेपी विरासत में नहीं मिला है तो null लौटाया जाता है. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामिति शेपी के पाथ की प्रतिलिपि लौटाता है। निर्देशांक शेपी के बाएँ-ऊपरी कोने के सापेक्ष होते हैं. |
| [GetImage](../../aspose.slides/shape/getimage)() | शेपी थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape थंबनेल बॉन्ड्स प्रकार उपयोग किया जाता है. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेपी थंबनेल लौटाता है. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर किए गए कंटेंट से गणना किए गए शेपी की दृश्य बॉन्ड्स प्राप्त करता है. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह शेपी प्लेसहोल्डर नहीं है. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | शेपी जिओमेट्री को [`IGeometryPath`](../igeometrypath) वस्तु से अपडेट करता है। निर्देशांक शेपी के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। शेपी का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | शेपी जिओमेट्री को [`IGeometryPath`](../igeometrypath) की एरे से अपडेट करता है। निर्देशांक शेपी के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। शेपी का प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शेपी की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शेपी की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |

### उदाहरण

निम्नलिखित उदाहरण दिखाते हैं कि ऑडियो फ्रेम थंबनेल को कैसे बदलें।

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // निर्दिष्ट स्थिति और आकार के साथ स्लाइड में एक ऑडियो फ्रेम जोड़ता है।
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // प्रेजेंटेशन संसाधनों में एक छवि जोड़ता है।
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // ऑडियो फ्रेम के लिए छवि सेट करता है।
	//संशोधित प्रेजेंटेशन को डिस्क पर सहेजता है
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### देखें

* वर्ग [GeometryShape](../geometryshape)
* इंटरफ़ेस [IPictureFrame](../ipictureframe)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->