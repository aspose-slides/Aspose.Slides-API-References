---
title: SmartArtShape
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: SmartArt आकृति का प्रतिनिधित्व करता है
type: docs
weight: 10660
url: /hi/aspose.slides.smartart/smartartshape/
---
## SmartArtShape वर्ग

SmartArt आकृति का प्रतिनिधित्व करता है

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकृति के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | आकृति से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | आकृति से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्दिष्ट करता है कि आकृति काले-सफ़ेद प्रदर्शन मोड में कैसे दिखाई देगी। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकृति का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकृति पर लागू पिक्सेल प्रभाव होते हैं। नोट: उन कुछ प्रकार की आकृतियों के लिए जो प्रभाव गुण नहीं रखतीं, यह null वापस कर सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें आकृति के लिए भराव स्वरूप गुण होते हैं। नोट: उन कुछ प्रकार की आकृतियों के लिए जो भराव गुण नहीं रखतीं, यह null वापस कर सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकृति फ़्रेम की गुणधर्म लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकृति की ऊँचाई प्राप्त करता है या सेट करता है, जिसे पॉइंट्स में मापा जाता है। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकृति छिपी हुई है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकृति समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें आकृति के लिए रेखा स्वरूप गुण होते हैं। नोट: उन कुछ प्रकार की आकृतियों के लिए जो रेखा गुण नहीं रखतीं, यह null वापस कर सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकृति का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ने/लिखने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप वाला अनूठा पहचानकर्ता लौटाता है जो आकृति के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकृति को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32। देखें भी [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकृति समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकृति के लिए प्लेसहोल्डर लौटाता है। यदि आकृति के पास कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकृति फ़्रेम के गुण लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकृति के Z-अक्ष के चारों ओर घुमाव के डिग्री संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | आकृति की लॉक स्थितियों को लौटाता है। केवल-पढ़ने योग्य [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकृति का शैली ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | ज्यामितीय प्रीसेट प्रकार को लौटाता है या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ने/लिखने योग्य [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकृति की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | SmartArt आकृति का पाठ लौटाता है। केवल-पढ़ने योग्य [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकृति के 3D प्रभाव गुण होते हैं। नोट: उन कुछ प्रकार की आकृतियों के लिए जिनमें 3D गुण नहीं हैं, यह null वापस कर सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप वाले पहचानकर्ता को लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें भी [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकृति की चौड़ाई प्राप्त करता है या सेट करता है, जिसे पॉइंट्स में मापा जाता है। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकृति के ऊपर-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, जिसे पॉइंट्स में मापा जाता है। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकृति के ऊपर-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, जिसे पॉइंट्स में मापा जाता है। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-क्रम में आकृति की स्थिति लौटाता है। Shapes[0] z-क्रम के अंत में स्थित आकृति को लौटाता है, और Shapes[Shapes.Count - 1] z-क्रम के सामने स्थित आकृति को लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियां

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणधर्म सेट करता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकृति के तत्वों का एरे बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से प्राप्त आकृति जिससे वर्तमान आकृति विरासत में मिली है)। यदि वर्तमान आकृति विरासत में नहीं है तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ज्यामितीय आकृति के पथ की प्रतिलिपि लौटाता है। निर्देशांक आकृति के बाएँ शीर्ष कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकृति की थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape थंबनेल बाउंड प्रकार प्रयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकृति की थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकृति की दृश्य सीमाएँ प्राप्त करता है जो उसकी रेंडर की गई सामग्री से गणना की गई हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | आकृति की ज्यामिति को [`IGeometryPath`](../../aspose.slides/igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक आकृति के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। आकृति के प्रकार ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) को Custom में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | आकृति की ज्यामिति को [`IGeometryPath`](../../aspose.slides/igeometrypath) की एरे से अपडेट करता है। निर्देशांक आकृति के बाएँ शीर्ष कोने के सापेक्ष होने चाहिए। आकृति के प्रकार ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) को Custom में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें भी

* वर्ग [GeometryShape](../../aspose.slides/geometryshape)
* इंटरफ़ेस [ISmartArtShape](../ismartartshape)
* नामस्थान [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* संयोजन [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->