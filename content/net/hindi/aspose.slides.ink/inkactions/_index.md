---
title: InkActions
second_title: Aspose.Sildes for .NET API संदर्भ
description: इंक एक्शन की जड़ का प्रतिनिधित्व करता है।
type: docs
weight: 7580
url: /hi/aspose.slides.ink/inkactions/
---
## InkActions वर्ग

इंक एक्शन का मूल प्रतिनिधित्व करता है।

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक आकृति से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक आकृति से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्धारित करता है कि एक आकृति काले-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगी। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। पढ़ने-के-लिए-केवल Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | आकृति के कस्टम डेटा को लौटाता है। पढ़ने-के-लिए-केवल [`ICustomData`](../../aspose.slides/icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट को लौटाता है जिसमें एक आकृति पर लागू पिक्सेल प्रभाव होते हैं। नोट: उन कुछ आकृतियों के लिए जो प्रभाव गुण नहीं रखतीं, यह null लौटा सकता है। पढ़ने-के-लिए-केवल [`IEffectFormat`](../../aspose.slides/ieffectformat)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट को लौटाता है जिसमें एक आकृति के लिए भराव फ़ॉर्मेटिंग गुण होते हैं। नोट: उन कुछ आकृतियों के लिए जो भराव गुण नहीं रखतीं, यह null लौटा सकता है। पढ़ने-के-लिए-केवल [`IFillFormat`](../../aspose.slides/ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | आकृति फ्रेम के गुणों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe)। |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | आकृति के तालों को लौटाता है। पढ़ने-के-लिए-केवल [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | आकृति की ऊँचाई को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि आकृति छिपी हुई है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। पढ़ने-के-लिए-केवल [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink)। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘सजावटी के रूप में चिह्नित करें’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि आकृति समूहित है या नहीं। पढ़ने-के-लिए-केवल Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। पढ़ने-के-लिए-केवल Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट को लौटाता है जिसमें एक आकृति के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं। नोट: उन कुछ आकृतियों के लिए जो लाइन गुण नहीं रखतीं, यह null लौटा सकता है। पढ़ने-के-लिए-केवल [`ILineFormat`](../../aspose.slides/ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक आकृति का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ने/लिखने योग्य String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकृति के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकृति को विश्वसनीय रूप से संदर्भित करने देता है। पढ़ने-के-लिए-केवल UInt32। देखें [`UniqueId`](../../aspose.slides/shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि आकृति समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। पढ़ने-के-लिए-केवल [`IGroupShape`](../../aspose.slides/igroupshape)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक आकृति के लिए प्लेसहोल्डर को लौटाता है। यदि आकृति में प्लेसहोल्डर नहीं है तो null लौटाता है। पढ़ने-के-लिए-केवल [`IPlaceholder`](../../aspose.slides/iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेजेंटेशन को लौटाता है। पढ़ने-के-लिए-केवल [`IPresentation`](../../aspose.slides/ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे आकृति फ्रेम के गुणों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe)। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट आकृति को z-अक्ष के आसपास घुमाए जाने के डिग्री संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घूर्णन दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | आकृति के तालों को लौटाता है। पढ़ने-के-लिए-केवल [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। (2 गुण) |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक आकृति की पैरेंट स्लाइड को लौटाता है। पढ़ने-के-लिए-केवल [`IBaseSlide`](../../aspose.slides/ibaseslide)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट को लौटाता है जिसमें एक आकृति के लिए 3D प्रभाव गुण होते हैं। नोट: उन कुछ आकृतियों के लिए जो 3D गुण नहीं रखतीं, यह null लौटा सकता है। पढ़ने-के-लिए-केवल [`IThreeDFormat`](../../aspose.slides/ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। क्योंकि यह मान उपयोगकर्ता द्वारा या प्रोग्रामmatically पुनः निर्धारित किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। पढ़ने-के-लिए-केवल UInt32। देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | आकृति की चौड़ाई को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापते हुए प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में एक आकृति की स्थिति को लौटाता है। Shapes[0] z-ऑर्डर के पीछे की आकृति लौटाता है, और Shapes[Shapes.Count - 1] z-ऑर्डर के सामने की आकृति लौटाता है। पढ़ने-के-लिए-केवल Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं हो तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट एक में सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर आकृति लौटाता है (वर्तमान आकृति जिस लेआउट और/या मास्टर स्लाइड से विरासत में मिली है)। यदि वर्तमान आकृति विरासत में नहीं मिली है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | आकृति थंबनेल लौटाता है। डिफॉल्ट रूप से ShapeThumbnailBounds.Shape आकृति थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | आकृति थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | आकृति की रेंडर किए गए कंटेंट से गणना किए गए दृश्य बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | आकृति की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* वर्ग [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [IInkActions](../iinkactions)
* नामस्थान [Aspose.Slides.Ink](../../aspose.slides.ink)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->