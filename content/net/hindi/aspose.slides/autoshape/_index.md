---
title: AutoShape
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: एक AutoShape का प्रतिनिधित्व करता है।
type: docs
weight: 900
url: /hi/aspose.slides/autoshape/
---
## AutoShape class

एक AutoShape का प्रतिनिधित्व करता है।

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Properties

| नाम | विवरण |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Shape के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Shape से संबंधित वैकल्पिक पाठ को लौटाता या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Shape से संबंधित वैकल्पिक पाठ का शीर्षक लौटाता या सेट करता है। पढ़ें/लिखें String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | autoshape की locks को लौटाता है। केवल-पढ़ने योग्य [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी यह निर्दिष्ट करती है कि एक shape काला-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगी। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें shape पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। ध्यान दें: कुछ प्रकार के shapes जिनमें effect प्रॉपर्टी नहीं है, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए fill फ़ॉर्मेटिंग प्रॉपर्टी होती हैं। ध्यान दें: कुछ प्रकार के shapes जिनमें fill प्रॉपर्टी नहीं है, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टी को लौटाता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई को पॉइंट में लौटाता या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छिपी हुई है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | mouse click के लिए परिभाषित hyperlink को लौटाता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | hyperlink manager को लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | mouse over के लिए परिभाषित hyperlink को लौटाता या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | निर्धारित करता है कि shape एक टेक्स्ट बॉक्स है या नहीं। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टी होते हैं। ध्यान दें: कुछ प्रकार के shapes जिनमें line प्रॉपर्टी नहीं है, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape का नाम लौटाता या सेट करता है। Null नहीं होना चाहिए। आवश्यक हो तो खाली स्ट्रिंग उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | slide-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो shape के जीवनकाल में स्थिर रहता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल-पढ़ने योग्य UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape के लिए placeholder लौटाता है। यदि shape के पास placeholder नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | slide की पैरेंट प्रस्तुति को लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | raw shape फ्रेम की प्रॉपर्टी को लौटाता या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | shape को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या लौटाता या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | shape की locks को लौटाता है। केवल-पढ़ने योग्य [`IAutoShapeLock`](../iautoshapelock). (2 प्रॉपर्टी) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | shape की style ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | geometry preset प्रकार को लौटाता या सेट करता है। ध्यान दें: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मान पर रीसेट हो जाएंगे। पढ़ें/लिखें [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट slide को लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | AutoShape के लिए TextFrame ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें shape के 3D इफ़ेक्ट प्रॉपर्टी होते हैं। ध्यान दें: कुछ प्रकार के shapes जिनमें 3D प्रॉपर्टी नहीं है, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | निर्धारित करता है कि यह autoshape slide की पृष्ठभूमि fill से भरा जाए या शैली/fill फ़ॉर्मेट द्वारा निर्दिष्ट हो। पढ़ें/लिखें Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई को पॉइंट में लौटाता या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में लौटाता या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में लौटाता या सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | shape की z-क्रम में स्थिति को लौटाता है। Shapes[0] सबसे पीछे की shape लौटाता है, और Shapes[Shapes.Count - 1] सबसे आगे की shape लौटाता है। केवल-पढ़ने योग्य Int32. |

## Methods

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder नहीं है तो एक नया placeholder जोड़ता है और placeholder प्रॉपर्टी को निर्दिष्ट वाले पर सेट करता है। |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | shape में एक नया TextFrame जोड़ता है। यदि shape में पहले से TextFrame है तो केवल उसका पाठ बदलता है। |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | shape के तत्वों का एरे बनाता और लौटाता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | मूल placeholder shape लौटाता है (layout या master slide से वह shape जिससे वर्तमान shape विरासत में मिला है)। यदि वर्तमान shape विरासत में नहीं मिली है तो null लौटाता है। |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | geometry shape के पथ की प्रतिलिपि लौटाता है। निर्देशांक shape के बाएँ ऊपर कोने के सापेक्ष होते हैं। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape की थंबनेल लौटाता है। ShapeThumbnailBounds.Shape shape थंबनेल सीमाओं का प्रकार डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape की थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की दृश्य सीमाएँ प्राप्त करता है जो उसके रेंडर्ड कंटेंट से गणना की गई हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह shape placeholder नहीं है। |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | shape की geometry को [`IGeometryPath`](../igeometrypath) ऑब्जेक्ट से अपडेट करता है। निर्देशांक shape के बाएँ ऊपर कोने के सापेक्ष होना चाहिए। shape के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है। |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | shape की geometry को [`IGeometryPath`](../igeometrypath) की एरे से अपडेट करता है। निर्देशांक shape के बाएँ ऊपर कोने के सापेक्ष होना चाहिए। shape के प्रकार ([`ShapeType`](../geometryshape/shapetype)) को Custom में बदलता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* वर्ग [GeometryShape](../geometryshape)
* इंटरफ़ेस [IAutoShape](../iautoshape)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->