---
title: SmartArtShape
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: SmartArt आकार का प्रतिनिधित्व करता है
type: docs
weight: 10680
url: /hi/aspose.slides.smartart/smartartshape/
---
## SmartArtShape क्लास

SmartArt आकृति का प्रतिनिधित्व करता है

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## गुणधर्म

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकार से जुड़े वैकल्पिक पाठ को लौटाता या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकार से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | गुणधर्म यह निर्दिष्ट करता है कि एक आकार काली-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकार के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल प्रभाव होते हैं। नोट: उन प्रकार के आकारों के लिए जो प्रभाव गुण नहीं रखते हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए भराव फ़ॉर्मेटिंग गुण होते हैं। नोट: उन प्रकार के आकारों के लिए जो भराव गुण नहीं रखते हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकार की ऊँचाई, पॉइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए रेखा फ़ॉर्मेटिंग गुण होते हैं। नोट: उन प्रकार के आकारों के लिए जो रेखा गुण नहीं रखते हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकार का नाम लौटाता या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप वाला अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को भरोसेमंद ढंग से संदर्भित करने देता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकार समूहित है तो पेरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पेरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ आकार फ्रेम के गुणों को लौटाता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकार के z-अक्ष के आसपास घुमाए जाने वाले डिग्री की संख्या लौटाता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | आकार के स्टाइल ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | जियोमेट्री प्रीसेट प्रकार को लौटाता या सेट करता है। नोट: मान बदलने पर सभी समायोजन मान डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ें/लिखें [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकार की पेरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | SmartArt आकार के टेक्स्ट को लौटाता है। केवल-पढ़ने योग्य [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें आकार के लिए 3D प्रभाव गुण होते हैं। नोट: उन प्रकार के आकारों के लिए जो 3D गुण नहीं रखते हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग एड-इन्स या अन्य कोड द्वारा किया जाता है। क्योंकि यह मान उपयोगकर्ता द्वारा या प्रोग्रामेटिक रूप से पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकार की चौड़ाई, पॉइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-क्रम में आकार की स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] सामने वाला आकार लौटाता है। केवल-पढ़ने योग्य Int32. |

## विधियाँ

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणधर्म सेट करता है. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | आकार के तत्वों का ऐरे बनाता और लौटाता है. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक मूल प्लेसहोल्डर आकार लौटाता है (वर्तमान आकार के विरासत में प्राप्त लेआउट या/और मास्टर स्लाइड से आकार). यदि वर्तमान आकार विरासत में नहीं मिला है तो null लौटाता है. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | जियोमेट्री आकार के पथ की कॉपी लौटाता है. निर्देशांक आकार के बायें ऊपर कोने के सापेक्ष होते हैं. |
| [GetImage](../../aspose.slides/shape/getimage)() | आकार थंबनेल लौटाता है. डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकार थंबनेल बाउंड्स प्रकार का उपयोग किया जाता है. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकार थंबनेल लौटाता है. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकार की दृश्य बाउंड्स प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई है. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../../aspose.slides/igeometrypath) ऑब्जेक्ट से आकार जियोमेट्री को अपडेट करता है. निर्देशांक आकार के बायें ऊपर कोने के सापेक्ष होने चाहिए. आकार के प्रकार ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) को कस्टम में बदलता है. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../../aspose.slides/igeometrypath) की ऐरे से आकार जियोमेट्री को अपडेट करता है. निर्देशांक आकार के बायें ऊपर कोने के सापेक्ष होने चाहिए. आकार के प्रकार ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) को कस्टम में बदलता है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकार की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |

### देखें

* क्लास [GeometryShape](../../aspose.slides/geometryshape)
* इंटरफ़ेस [ISmartArtShape](../ismartartshape)
* नेमस्पेस [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->