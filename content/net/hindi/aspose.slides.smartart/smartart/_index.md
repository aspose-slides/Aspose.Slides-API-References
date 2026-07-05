---
title: SmartArt
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक SmartArt आरेख का प्रतिनिधित्व करता है
type: docs
weight: 10600
url: /hi/aspose.slides.smartart/smartart/
---
## SmartArt क्लास

एक SmartArt आरेख का प्रतिनिधित्व करता है

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | SmartArt ऑब्जेक्ट में सभी नोड्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`ISmartArtNodeCollection`](../ismartartnodecollection)। |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्धारित करता है कि एक shape ब्लैक-एंड-ह्वाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)। |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | SmartArt ऑब्जेक्ट की रंग शैली को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`SmartArtColorType`](../smartartcolortype)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../../aspose.slides/icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल प्रभावों को सम्मिलित करने वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: ऐसे shape प्रकारों के लिए जो प्रभाव गुण नहीं रखते, यह null लौट सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat)। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक shape के लिए भराव फॉर्मेटिंग गुणों को सम्मिलित करने वाले FillFormat ऑब्जेक्ट को लौटाता है। नोट: ऐसे shape प्रकारों के लिए जिनमें भराव गुण नहीं हैं, यह null लौट सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम के गुणों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe)। |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक को लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई को बिंदुओं में माप कर प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छुपा है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../../aspose.slides/ihyperlink)। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | SmartArt आरेख की LTR या RTL स्थिति को लौटाता है या सेट करता है, यदि आरेख उलटने का समर्थन करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | SmartArt ऑब्जेक्ट के लेआउट को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`SmartArtLayoutType`](../smartartlayouttype)। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक shape के लिए रेखा फॉर्मेटिंग गुणों को सम्मिलित करने वाले LineFormat ऑब्जेक्ट को लौटाता है। नोट: ऐसे shape प्रकारों के लिए जिनमें रेखा गुण नहीं हैं, यह null लौट सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat)। |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक shape का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग का उपयोग करें। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | SmartArt ऑब्जेक्ट में रूट नोड्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य [`ISmartArtNodeCollection`](../ismartartnodecollection)। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | shape के जीवनकाल के दौरान स्थिर रहने वाला, स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है, जिससे PowerPoint या इंटरऑप कोड दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित कर सकता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../../aspose.slides/shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../../aspose.slides/igroupshape)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक shape के लिए प्लेसहोल्डर को लौटाता है। यदि shape के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../../aspose.slides/iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति को लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../../aspose.slides/ipresentation)। |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | SmartArt ऑब्जेक्ट की क्विक स्टाइल को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`SmartArtQuickStyleType`](../smartartquickstyletype)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे shape फ्रेम के गुणों को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../../aspose.slides/ishapeframe)। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या को लौटाता है या सेट करता है। धनात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; ऋणात्मक मान प्रतिपक्ष घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक को लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)। (2 प्रॉपर्टीज़) |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट स्लाइड को लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../../aspose.slides/ibaseslide)। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक shape के लिए 3d प्रभाव गुणों को सम्मिलित करने वाले ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: ऐसे shape प्रकारों के लिए जिनमें 3d गुण नहीं हैं, यह null लौट सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../../aspose.slides/ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)। |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई को बिंदुओं में माप कर प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को बिंदुओं में माप कर प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को बिंदुओं में माप कर प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में shape की स्थिति को लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला shape लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला shape लौटाता है। केवल-पढ़ने योग्य Int32। |

## विधियां

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | बेसिक प्लेसहोल्डर shape लौटाता है (layout और/या मास्टर स्लाइड से shape जिसे वर्तमान shape विरासत में प्राप्त करता है)। यदि वर्तमान shape विरासत में नहीं मिला तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape के रेंडर किए गए कंटेंट से गणना किए गए दृश्य बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape प्लेसहोल्डर नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject)
* इंटरफ़ेस [ISmartArt](../ismartart)
* नेमस्पेस [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->