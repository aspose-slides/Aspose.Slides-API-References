---
title: Table
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक स्लाइड पर तालिका का प्रतिनिधित्व करता है।
type: docs
weight: 10860
url: /hi/aspose.slides/table/
---
## Table वर्ग

स्लाइड पर एक तालिका का प्रतिनिधित्व करता है।

```csharp
public sealed class Table : GraphicalObject, ITable
```

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | शैप से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | शैप से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह गुण निर्दिष्ट करता है कि शैप काले-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | कॉलम्स का संग्रह लौटाता है। केवल-पठन [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शैप पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पठन Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शैप का कस्टम डेटा लौटाता है। केवल-पठन [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें शैप पर लागू पिक्सेल प्रभाव होते हैं। नोट: ऐसे शैप के प्रकारों के लिए जो प्रभाव गुण नहीं रखते, null लौटाया जा सकता है। केवल-पठन [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Table के लिए fill फॉर्मेटिंग वाला TableFormat.FillFormat ऑब्जेक्ट लौटाता है। केवल-पठन [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | निर्धारित करता है कि तालिका का पहला कॉलम विशेष फॉर्मेटिंग के साथ खींचा जाना चाहिए या नहीं। पढ़ें/लिखें Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | निर्धारित करता है कि तालिका की पहली पंक्ति विशेष फॉर्मेटिंग के साथ खींची जानी चाहिए या नहीं। पढ़ें/लिखें Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शैप फ्रेम के गुण लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | शैप की लॉकिंग जानकारी लौटाता है। केवल-पठन [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | शैप की ऊँचाई प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शैप छिपा है या नहीं। पढ़ें/लिखें Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | निर्धारित करता है कि सम पंक्तियों को अलग फॉर्मेटिंग के साथ खींचा जाना चाहिए या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर लौटाता है। केवल-पठन [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शैप समूहित है या नहीं। केवल-पठन Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शैप TextHolder_PPT है या नहीं। केवल-पठन Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | निर्दिष्ट कॉलम और पंक्ति अनुक्रमणिकाओं पर सेल लौटाता है। केवल-पठन [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | निर्धारित करता है कि तालिका का अंतिम कॉलम विशेष फॉर्मेटिंग के साथ खींचा जाना चाहिए या नहीं। पढ़ें/लिखें Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | निर्धारित करता है कि तालिका की अंतिम पंक्ति विशेष फॉर्मेटिंग के साथ खींची जानी चाहिए या नहीं। पढ़ें/लिखें Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें शैप के लिए रेखा फॉर्मेटिंग गुण होते हैं। नोट: ऐसे शैप के प्रकारों के लिए जो रेखा गुण नहीं रखते, null लौटाया जा सकता है। केवल-पठन [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | शैप का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो शैप के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी शैप को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पठन UInt32. देखें भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शैप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पठन [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | शैप के लिए प्लेसहोल्डर लौटाता है। यदि शैप के पास कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पठन [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पठन [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे शैप फ्रेम के गुण लौटाता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | निर्धारित करता है कि तालिका का राइट-टू-लेफ़्ट पढ़ने क्रम है या नहीं। पढ़ें/लिखें Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शैप को z-अक्ष के चारों ओर घुमा देने के डिग्री संख्या लौटाता है या सेट करता है। एक सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; एक नकारात्मक मान घड़ी की उल्टी दिशा में घूर्णन दर्शाता है। पढ़ें/लिखें Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | पंक्तियों का संग्रह लौटाता है। केवल-पठन [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | शैप की लॉकिंग जानकारी लौटाता है। केवल-पठन [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 गुण) |
| [Slide](../../aspose.slides/shape/slide) { get; } | शैप की पैरेंट स्लाइड लौटाता है। केवल-पठन [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | बिल्ट-इन तालिका शैली प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | इस तालिका के लिए फॉर्मेटिंग गुण वाला TableFormat ऑब्जेक्ट लौटाता है। केवल-पठन [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें शैप के 3D प्रभाव गुण होते हैं। नोट: ऐसे शैप के प्रकारों के लिए जिनमें 3D गुण नहीं होते, null लौटाया जा सकता है। केवल-पठन [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामिंग द्वारा पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पठन UInt32. देखें भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | निर्धारित करता है कि सम कॉलम को अलग फॉर्मेटिंग के साथ खींचा जाना चाहिए या नहीं। पढ़ें/लिखें Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | शैप की चौड़ाई प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | शैप के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | शैप के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-क्रम में शैप की स्थिति लौटाता है। Shapes[0] z-क्रम में सबसे पीछे वाला शैप लौटाता है, और Shapes[Shapes.Count - 1] सबसे आगे वाला शैप लौटाता है। केवल-पठन Int32. |

## विधियां

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर शैप लौटाता है (लेआउट और/या मास्टर स्लाइड से शैप जिससे वर्तमान शैप विरासत में मिला है)। यदि वर्तमान शैप विरासत में नहीं मिला है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | शैप थंबनेल लौटाता है। डिफ़ॉल्ट रूप में ShapeThumbnailBounds.Shape शैप थंबनेल बाउंड्स प्रकार का उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शैप थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | शैप की दृश्य सीमाओं को प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई हैं। |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | पड़ोसी सेल्स को मिलाता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह शैप प्लेसहोल्डर नहीं है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | परिभाषित पैराग्राफ फॉर्मेट गुणों को सभी तालिका सेल्स के पैराग्राफ पर सेट करता है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | परिभाषित पोर्शन फॉर्मेट गुणों को सभी तालिका सेल्स के पोर्शन पर सेट करता है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | परिभाषित टेक्स्ट फ्रेम फॉर्मेट गुणों को सभी तालिका सेल्स के टेक्स्ट फ्रेम पर सेट करता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शैप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शैप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### संबंधित देखें

* वर्ग [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [ITable](../itable)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->