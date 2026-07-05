---
title: SummaryZoomSection
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक Summary Zoom फ्रेम में Summary Zoom Section ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 10780
url: /hi/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection वर्ग

एक Summary Zoom फ्रेम में Summary Zoom Section ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़ा वैकल्पिक पाठ लौटाता है या सेट करता है। Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है या सेट करता है। Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | एक shape के काला-श्वेत डिस्प्ले मोड में रेंडर होने के तरीके को निर्दिष्ट करने वाला गुण। Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape का कस्टम डेटा लौटाता है। Read-only [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Summary Zoom Section ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल प्रभावों वाले EffectFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के shape जिनके पास effect प्रॉपर्टी नहीं है, के लिए null वापस कर सकता है। Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | shape के लिए fill फॉर्मेटिंग प्रॉपर्टीज़ वाला FillFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के shape जिनके पास fill प्रॉपर्टी नहीं है, के लिए null वापस कर सकता है। Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape की locks लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई, पॉइंट्स में मापी गई, को प्राप्त करता है या सेट करता है। Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छिपा है या नहीं। Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित hyperlink को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | hyperlink manager को लौटाता है। Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित hyperlink को लौटाता है या सेट करता है। Read/write [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | zoom ऑब्जेक्ट के इमेज प्रकार को प्राप्त करता है या सेट करता है। Read/write [`ZoomImageType`](../zoomimagetype). डिफ़ॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | shape के लिए लाइन फॉर्मेटिंग प्रॉपर्टीज़ वाला LineFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के shape जिनके पास line प्रॉपर्टी नहीं है, के लिए null वापस कर सकता है। Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape का नाम लौटाता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक slide-सीमित अनूठा पहचानकर्ता लौटाता है जो shape के जीवनकाल में स्थिर रहता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। Read-only UInt32. See also [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape के लिए placeholder लौटाता है। यदि shape के पास कोई placeholder नहीं है तो null लौटाता है। Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | slide की पैरेंट प्रस्तुति लौटाता है। Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | raw shape फ्रेम की प्रॉपर्टीज़ को लौटाता है या सेट करता है। Read/write [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त करता है या सेट करता है। Read/write Boolean. डिफ़ॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या को लौटाता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिक्लॉकवाइज घूर्णन दर्शाता है। Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape की locks लौटाता है। Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom को गंतव्य slide की पृष्ठभूमि उपयोग करने का निर्धारण करने वाले मान को प्राप्त करता है या सेट करता है। Read/write Boolean. डिफ़ॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट slide को लौटाता है। Read-only [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Section Zoom ऑब्जेक्ट द्वारा लिंक किए गए सेक्शन ऑब्जेक्ट को प्राप्त करता है या सेट करता है। Read/write [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape के लिए 3D effect प्रॉपर्टीज़ वाला ThreeDFormat ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के shape जिनके पास 3d प्रॉपर्टी नहीं है, के लिए null वापस कर सकता है। Read-only [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Summary Zoom Section ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है। |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom और slide के बीच ट्रांसिशन की अवधि को प्राप्त करता है या सेट करता है। Read/write Single. डिफ़ॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-सीमित पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अनूठी कुंजी के रूप में नहीं माना जाना चाहिए। Read-only UInt32. See also [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई, पॉइंट्स में मापी गई, को प्राप्त करता है या सेट करता है। Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपर-बाएँ कोने का x-निर्देशांक, पॉइंट्स में मापी गई, को प्राप्त करता है या सेट करता है। Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपर-बाएँ कोने का y-निर्देशांक, पॉइंट्स में मापी गई, को प्राप्त करता है या सेट करता है। Read/write Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | zoom ऑब्जेक्ट के लिए इमेज को प्राप्त करता है या सेट करता है। Read/write [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-ऑर्डर में shape की स्थिति को लौटाता है। Shapes[0] z-ऑर्डर के पिछड़े shape को लौटाता है, और Shapes[Shapes.Count - 1] सामने वाले shape को लौटाता है। Read-only Int32. |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और placeholder प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक placeholder shape लौटाता है (layout और/या master slide से shape जो वर्तमान shape द्वारा विरासत में मिली है)। यदि वर्तमान shape विरासत में नहीं मिली है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की दृश्य बाउंड्स प्राप्त करता है जो उसके रेंडर किए कंटेंट से गणना की गई हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह shape placeholder नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें

* वर्ग [SectionZoomFrame](../sectionzoomframe)
* इंटरफ़ेस [ISummaryZoomSection](../isummaryzoomsection)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->