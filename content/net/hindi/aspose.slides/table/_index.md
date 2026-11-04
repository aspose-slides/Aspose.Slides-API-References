---
title: Table
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: स्लाइड पर एक टेबल का प्रतिनिधित्व करता है।
type: docs
weight: 10880
url: /hi/aspose.slides/table/
---
## Table क्लास

एक slide पर टेबल का प्रतिनिधित्व करता है।

```csharp
public sealed class Table : GraphicalObject, ITable
```

## गुण

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ को लौटाता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है या सेट करता है। Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | एक shape के काले-सफ़ेद प्रदर्शन मोड में रेंडर होने का तरीका निर्दिष्ट करता है। Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | कॉलमों का संग्रह लौटाता है। Read-only [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape का कस्टम डेटा लौटाता है। Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें shape पर लागू पिक्सेल प्रभाव होते हैं। नोट: कुछ प्रकार की shapes जिनमें प्रभाव विशेषताएँ नहीं होतीं, उनके लिए null लौटाया जा सकता है। Read-only [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Table के लिए fill फ़ॉर्मेटिंग वाला TableFormat.FillFormat ऑब्जेक्ट लौटाता है। Read-only [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | टेबल के पहले कॉलम को विशेष फ़ॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं निर्धारित करता है। Read/write Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | टेबल की पहली पंक्ति को विशेष फ़ॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं निर्धारित करता है। Read/write Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की विशेषताओं को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई (पॉइंट्स में मापी गई) को प्राप्त करता है या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape छिपा है या नहीं निर्धारित करता है। Read/write Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | सम पंक्तियों को विभिन्न फ़ॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं निर्धारित करता है। Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक को लौटाता है। Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त करता है या सेट करता है। Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape समूहित है या नहीं निर्धारित करता है। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape TextHolder_PPT है या नहीं निर्धारित करता है। Read-only Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | निर्दिष्ट कॉलम और पंक्ति सूचकांकों पर स्थित सेल को लौटाता है। Read-only [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | टेबल के अंतिम कॉलम को विशेष फ़ॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं निर्धारित करता है। Read/write Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | टेबल की अंतिम पंक्ति को विशेष फ़ॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं निर्धारित करता है। Read/write Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए रेखा फ़ॉर्मेटिंग गुण होते हैं। नोट: कुछ प्रकार की shapes जिनमें रेखा विशेषताएँ नहीं होतीं, उनके लिए null लौटाया जा सकता है। Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape का नाम लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक slide-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो shape के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है। Read-only UInt32। See also [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape का placeholder लौटाता है। यदि shape के पास placeholder नहीं है तो null लौटाता है। Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | slide की पैरेंट प्रस्तुति लौटाता है। Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | raw shape फ्रेम की विशेषताओं को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | टेबल की दाएँ-से-बाएँ पढ़ने क्रम है या नहीं निर्धारित करता है। Read-write Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-axis के आसपास घुमाए जाने वाले डिग्रीज़ की संख्या को लौटाता है या सेट करता है। सकारात्मक मान clockwise घूर्णन दर्शाता है; नकारात्मक मान counterclockwise घूर्णन दर्शाता है। Read/write Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | पंक्तियों का संग्रह लौटाता है। Read-only [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक को लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट slide लौटाता है। Read-only [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | builtin टेबल शैली को प्राप्त करता है या सेट करता है। Read/write [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | इस टेबल के फ़ॉर्मेटिंग गुणों वाला TableFormat ऑब्जेक्ट लौटाता है। Read-only [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें shape के 3d इफ़ेक्ट गुण होते हैं। नोट: कुछ प्रकार की shapes जिनमें 3d गुण नहीं होते, उनके लिए null लौटाया जा सकता है। Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए बनाया गया है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः निर्धारित किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। Read-only UInt32। See also [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | सम कॉलमों को विभिन्न फ़ॉर्मेटिंग के साथ चित्रित किया जाना चाहिए या नहीं निर्धारित करता है। Read/write Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई (पॉइंट्स में मापी गई) को प्राप्त करता है या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के बाएँ-ऊपर कोने के x-निर्देशांक को (पॉइंट्स में मापा) प्राप्त करता है या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के बाएँ-ऊपर कोने के y-निर्देशांक को (पॉइंट्स में मापा) प्राप्त करता है या सेट करता है। Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | shape की z-order में स्थिति लौटाता है। Shapes[0] z-order के पीछे वाले shape को लौटाता है, और Shapes[Shapes.Count - 1] सामने वाले shape को लौटाता है। Read-only Int32. |

## विधियां

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और placeholder की विशेषताओं को निर्दिष्ट वाले पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी placeholder shape लौटाता है (layout और/या master slide से shape जो वर्तमान shape द्वारा विरासत में मिली है)। यदि वर्तमान shape विरासत में नहीं मिली है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की दृश्य सीमाएँ प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई हैं। |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | पड़ोसी सेल्स को मिलाता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape placeholder नहीं है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | परिभाषित पैराग्राफ फ़ॉर्मेट गुणों को सभी टेबल सेल्स के पैराग्राफ पर सेट करता है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | परिभाषित पोर्शन फ़ॉर्मेट गुणों को सभी टेबल सेल्स के पोर्शन पर सेट करता है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | परिभाषित टेक्स्ट फ्रेम फ़ॉर्मेट गुणों को सभी टेबल सेल्स के टेक्स्ट फ्रेम पर सेट करता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* क्लास [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [ITable](../itable)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->