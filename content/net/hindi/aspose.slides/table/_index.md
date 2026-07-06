---
title: Table
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक स्लाइड पर तालिका का प्रतिनिधित्व करता है।
type: docs
weight: 10860
url: /hi/aspose.slides/table/
---
## Table क्लास

एक slide पर तालिका का प्रतिनिधित्व करता है।

```csharp
public sealed class Table : GraphicalObject, ITable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़ा वैकल्पिक टेक्स्ट वापस करता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक वापस करता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी यह निर्दिष्ट करती है कि एक shape ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगी। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | कॉलम का संग्रह वापस करता है। केवल पढ़ने योग्य [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइट्स की संख्या वापस करता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape का कस्टम डेटा वापस करता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल प्रभावों को शामिल करने वाले EffectFormat ऑब्जेक्ट को वापस करता है। नोट: उन कुछ प्रकार के shapes के लिए जो प्रभाव गुण नहीं रखते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Table के लिए fill फ़ॉर्मेटिंग शामिल करने वाले TableFormat.FillFormat ऑब्जेक्ट को वापस करता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | निर्धारित करता है कि क्या टेबल का पहला कॉलम विशेष फ़ॉर्मेटिंग के साथ खींचा जाना चाहिए। पढ़ें/लिखें Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | निर्धारित करता है कि क्या टेबल की पहली पंक्ति विशेष फ़ॉर्मेटिंग के साथ खींची जानी चाहिए। पढ़ें/लिखें Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ को वापस करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक को वापस करता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई, प्वाइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि क्या shape छिपा हुआ है। पढ़ें/लिखें Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | निर्धारित करता है कि क्या सम पंक्तियों को अलग फ़ॉर्मेटिंग के साथ खींचना है। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को वापस करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को वापस करता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को वापस करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ‘Mark as decorative’ विकल्प को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि क्या shape समूहित है। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि क्या shape TextHolder_PPT है। केवल पढ़ने योग्य Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | निर्दिष्ट कॉलम और पंक्ति सूचकांक पर सेल को वापस करता है। केवल पढ़ने योग्य [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | निर्धारित करता है कि क्या टेबल का अंतिम कॉलम विशेष फ़ॉर्मेटिंग के साथ खींचा जाना चाहिए। पढ़ें/लिखें Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | निर्धारित करता है कि क्या टेबल की अंतिम पंक्ति विशेष फ़ॉर्मेटिंग के साथ खींची जानी चाहिए। पढ़ें/लिखें Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक shape के लिए लाइन फ़ॉर्मेटिंग गुणों वाले LineFormat ऑब्जेक्ट को वापस करता है। नोट: उन कुछ प्रकार के shapes के लिए जिनके पास लाइन गुण नहीं हैं, null लौटाया जा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक shape का नाम वापस करता है या सेट करता है। null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | shape के जीवनकाल के दौरान स्थिर रहने वाला, स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता वापस करता है, जिससे PowerPoint या इंटरऑप कोड दस्तावेज़ में किसी भी स्थान से shape को विश्वसनीय रूप से संदर्भित कर सकता है। केवल पढ़ने योग्य UInt32। देखिए भी [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट को वापस करता है। अन्यथा null वापस करता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक shape के लिए प्लेसहोल्डर को वापस करता है। यदि shape के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक स्लाइड की पैरेंट प्रस्तुति को वापस करता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ shape फ्रेम की प्रॉपर्टीज़ को वापस करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | निर्धारित करता है कि क्या टेबल का दाएँ-से-बाएँ पढ़ने का क्रम है। पढ़ें/लिखें Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-axis के चारों ओर घुमाने के डिग्री की संख्या को वापस करता है या सेट करता है। एक सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; एक नकारात्मक मान विरुद्ध दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | पंक्तियों का संग्रह वापस करता है। केवल पढ़ने योग्य [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक को वापस करता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक shape की पैरेंट स्लाइड को वापस करता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | इनबिल्ट टेबल शैली को प्राप्त या सेट करता है। पढ़ें/लिखें [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | इस टेबल के फ़ॉर्मेटिंग गुणों वाले TableFormat ऑब्जेक्ट को वापस करता है। केवल पढ़ने योग्य [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक shape के लिए 3D प्रभाव गुणों वाले ThreeDFormat ऑब्जेक्ट को वापस करता है। नोट: उन कुछ प्रकार के shapes के लिए जिनके पास 3D गुण नहीं हैं, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिये एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता को वापस करता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32। देखिए भी [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | निर्धारित करता है कि क्या सम कॉलम को अलग फ़ॉर्मेटिंग के साथ खींचना है। पढ़ें/लिखें Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई, प्वाइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक, प्वाइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक, प्वाइंट में मापी गई, को प्राप्त या सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-order में एक shape की स्थिति को वापस करता है। Shapes[0] z-order के पीछे वाले shape को लौटाता है, और Shapes[Shapes.Count - 1] आगे वाले shape को लौटाता है। केवल पढ़ने योग्य Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी प्लेसहोल्डर shape को वापस करता है (layout और/या मास्टर स्लाइड से वह shape जिससे वर्तमान shape विरासत में मिला है)। यदि वर्तमान shape विरासत में नहीं मिला है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल को वापस करता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बॉन्ड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल को वापस करता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की दृश्य सीमाओं को प्राप्त करता है जो उसके रेंडर किए गए कंटेंट से गणना की गई हैं। |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | पड़ोसी सेल्स को मिलाता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape प्लेसहोल्डर नहीं है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | परिभाषित पैराग्राफ फ़ॉर्मेट गुणों को सभी टेबल सेल्स के पैराग्राफ में सेट करता है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | परिभाषित पोर्शन फ़ॉर्मेट गुणों को सभी टेबल सेल्स के पोर्शन में सेट करता है। |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | परिभाषित टेक्स्ट फ्रेम फ़ॉर्मेट गुणों को सभी टेबल सेल्स के टेक्स्ट फ्रेम में सेट करता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखिए

* क्लास [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [ITable](../itable)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->