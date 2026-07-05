---
title: ZoomObject
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक स्लाइड में Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 11870
url: /hi/aspose.slides/zoomobject/
---
## ZoomObject वर्ग

एक स्लाइड में Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से संबद्ध वैकल्पिक टेक्स्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से संबद्ध वैकल्पिक टेक्स्ट के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्धारित करती है कि एक shape ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या को प्राप्त करता है। केवल पढ़ें Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape का कस्टम डेटा प्राप्त करता है। केवल पढ़ें [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक shape पर लागू पिक्सेल इफ़ेक्ट्स को सम्मिलित करने वाला EffectFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ shape प्रकारों के लिए जो इफ़ेक्ट प्रॉपर्टीज़ नहीं रखते, null लौटाया जा सकता है। केवल पढ़ें [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक shape के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ को समाहित करने वाला FillFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ shape प्रकारों के लिए जो भराव प्रॉपर्टीज़ नहीं रखते, null लौटाया जा सकता है। केवल पढ़ें [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक को प्राप्त करता है। केवल पढ़ें [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई को पॉइंट्स में मापा जाता है, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | स्थापित करता है कि shape छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को प्राप्त करता है। केवल पढ़ें [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | एक zoom ऑब्जेक्ट की इमेज टाइप को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`ZoomImageType`](../zoomimagetype)। डिफॉल्ट मान: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | स्थापित करता है कि shape समूहित है या नहीं। केवल पढ़ें Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | स्थापित करता है कि shape TextHolder_PPT है या नहीं। केवल पढ़ें Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक shape के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ को सम्मिलित करने वाला LineFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ shape प्रकारों के लिए जो लाइन प्रॉपर्टीज़ नहीं रखते, null लौटाया जा सकता है। केवल पढ़ें [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | एक shape का नाम प्राप्त करता है या सेट करता है। null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग मान का उपयोग करें। पढ़ें/लिखें String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक slide-स्कोप्ड यूनिक आइडेंटिफायर लौटाता है जो shape के जीवनकाल के दौरान स्थायी रहता है और PowerPoint या इंटरऑप कोड को डॉक्यूमेंट में कहीं से भी shape को विश्वसनीय रूप से रेफ़र करने देता है। केवल पढ़ें UInt32। देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ें [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | एक shape के लिए प्लेसहोल्डर लौटाता है। यदि shape का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ें [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | एक slide की पैरेंट प्रस्तुति लौटाता है। केवल पढ़ें [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे shape फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean। डिफॉल्ट मान: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाने के डिग्री की संख्या को प्राप्त करता है या सेट करता है। सकारात्मक मान क्लॉकवाइज़ रोटेशन दर्शाता है; नकारात्मक मान एंटी-क्लॉकवाइज़ रोटेशन दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक को प्राप्त करता है। केवल पढ़ें [`IGraphicalObjectLock`](../igraphicalobjectlock)। (2 प्रॉपर्टीज़) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom लक्ष्य स्लाइड की बैकग्राउंड का उपयोग करेगा या नहीं को निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean। डिफॉल्ट मान: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | एक shape की पैरेंट स्लाइड को प्राप्त करता है। केवल पढ़ें [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक shape के लिए 3D इफ़ेक्ट प्रॉपर्टीज़ को समाहित करने वाला ThreeDFormat ऑब्जेक्ट लौटाता है। नोट: उन कुछ shape प्रकारों के लिए जो 3D प्रॉपर्टीज़ नहीं रखते, null लौटाया जा सकता है। केवल पढ़ें [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single। डिफॉल्ट मान: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक अंतर्निहित, प्रस्तुति-स्कोप्ड आइडेंटिफायर लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ें UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई को पॉइंट्स में मापा जाता है, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट्स में मापा जाता है, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट्स में मापा जाता है, प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | zoom ऑब्जेक्ट के लिए इमेज को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z-order में shape की स्थिति को लौटाता है। Shapes[0] z-order के पीछे वाला shape लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला shape लौटाता है। केवल पढ़ें Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder नहीं है तो एक नया placeholder जोड़ता है और निर्दिष्ट placeholder की प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक placeholder shape लौटाता है (shape लेआउट और/या मास्टर स्लाइड से जो वर्तमान shape को इनहेरिट करता है)। यदि वर्तमान shape इनहेरिट नहीं किया गया है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए shape के विज़ुअल बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | परिभाषित करता है कि यह shape placeholder नहीं है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### देखें भी

* वर्ग [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [IZoomObject](../izoomobject)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->