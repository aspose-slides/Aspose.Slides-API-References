---
title: GraphicalObject
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक अमूर्त ग्राफ़िकल ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 5070
url: /hi/aspose.slides/graphicalobject/
---
## GraphicalObject वर्ग

एक अमूर्त ग्राफ़िकल ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकृति से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकृति से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्धारित करता है कि एक आकृति काली-सफ़ेद डिस्प्ले मोड में कैसे प्रदर्शित होगी। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकृति के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | आकृति पर लागू पिक्सेल प्रभावों वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो प्रभाव गुण नहीं रखतीं, null वापस कर सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | आकृति के लिए फ़िल फ़ॉर्मेट गुणधर्म रखने वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो फ़िल गुण नहीं रखतीं, null वापस कर सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकृति फ्रेम की गुणधर्म लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकृति के लॉक लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकृति की ऊँचाई, पॉइंट में मापी गई, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकृति छिपी है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकृति समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | आकृति के लिए लाइन फ़ॉर्मेट गुणधर्म रखने वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो लाइन गुण नहीं रखतीं, null वापस कर सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | आकृति का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकृति के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के कहीं से भी आकृति को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ने योग्य UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकृति समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | आकृति के लिए प्लेसहोल्डर लौटाता है। यदि आकृति में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ shape फ्रेम की गुणधर्म लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घुमा जाने वाले डिग्री की संख्या लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घूर्णन दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकृति के लॉक को लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 गुणधर्म) |
| [Slide](../../aspose.slides/shape/slide) { get; } | आकृति की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | आकृति के 3D प्रभाव गुणधर्म रखने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो 3D गुण नहीं रखतीं, null वापस कर सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग करने हेतु अभिप्रेत है। चूँकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकृति की चौड़ाई, पॉइंट में मापी गई, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | आकृति के ऊपरी-बाएँ कोने का x-निर्देशांक, पॉइंट में मापी गई, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकृति के ऊपरी-बाएँ कोने का y-निर्देशांक, पॉइंट में मापी गई, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | आकृति की z-क्रम में स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे की आकृति लौटाता है, और Shapes[Shapes.Count - 1] z-क्रम के सामने की आकृति लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणधर्म सेट करता है. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक मूल प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकृति जिससे वर्तमान आकृति विरासत में मिली है)। यदि वर्तमान आकृति विरासत में नहीं मिली है तो null लौटाया जाता है. |
| [GetImage](../../aspose.slides/shape/getimage)() | आकृति थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape आकृति थंबनेल बाउंड्स टाइप उपयोग किया जाता है. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकृति थंबनेल लौटाता है. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकृति की दृश्य सीमा प्राप्त करता है, जो उसके रेंडर किए गए कंटेंट से गणना की गई है. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है. |

### देखें

* वर्ग [Shape](../shape)
* इंटरफ़ेस [IGraphicalObject](../igraphicalobject)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->