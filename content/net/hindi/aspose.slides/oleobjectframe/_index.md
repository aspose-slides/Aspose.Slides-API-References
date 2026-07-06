---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: स्लाइड पर OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 9230
url: /hi/aspose.slides/oleobjectframe/
---
## OleObjectFrame क्लास

शेपट पर OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | शेप से जुड़े वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | शेप से जुड़े वैकल्पिक पाठ शीर्षक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | बेस IGraphicalObject इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी यह निर्दिष्ट करती है कि एक शेप काली-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें/लिखें [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | शेप पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | शेप के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | एक EffectFormat ऑब्जेक्ट लौटाता है जिसमें शेप पर लागू पिक्सेल इफ़ेक्ट होते हैं। नोट: उन कुछ प्रकार के शेप्स जिनमें इफ़ेक्ट गुण नहीं होते, उनके लिए null लौट सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE एम्बेडेड डेटा के बारे में जानकारी प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | एम्बेडेड OLE ऑब्जेक्ट का फ़ाइल नाम लौटाता है |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | एम्बेडेड OLE ऑब्जेक्ट का पथ लौटाता है |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | एक FillFormat ऑब्जेक्ट लौटाता है जिसमें शेप के भराव स्वरूप गुण होते हैं। नोट: उन कुछ प्रकार के शेप्स जिनमें भराव गुण नहीं होते, उनके लिए null लौट सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | शेप फ्रेम के गुणों को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | शेप के लॉक को लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | पॉइंट्स में मापी गई शेप की ऊँचाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि शेप छिपा हुआ है या नहीं। पढ़ें/लिखें Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि शेप समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दिखाई देता है या नहीं। पढ़ें/लिखें Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से लिंक्ड है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | एक LineFormat ऑब्जेक्ट लौटाता है जिसमें शेप के लाइन स्वरूप गुण होते हैं। नोट: उन कुछ प्रकार के शेप्स जिनमें लाइन गुण नहीं होते, उनके लिए null लौट सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | लिंक्ड फ़ाइल का पूर्ण पथ लौटाता है। छोटा फ़ाइल नाम उपयोग किया जाएगा। केवल पढ़ने योग्य String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | लिंक्ड फ़ाइल का पूर्ण पथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ें/लिखें String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | यदि उपलब्ध हो तो लिंक्ड फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। केवल पढ़ने योग्य String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | शेप का नाम प्राप्त करता है या सेट करता है। नुल नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ें/लिखें String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | ऑब्जेक्ट का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | ऑब्जेक्ट का ProgID प्राप्त करता है। केवल पढ़ने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो शैप के पूरे जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को किसी भी स्थान से शैप को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल पढ़ने योग्य UInt32. देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि शेप समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | शेप के लिए प्लेसहोल्डर लौटाता है। यदि शेप का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड का पैरेंट प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | रॉ शेप फ्रेम के गुणों को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट शेप के Z-धुरी के चारों ओर घुमाए जाने के डिग्री संख्या को प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विरुद्ध दिशा में घुमाव दर्शाता है। पढ़ें/लिखें Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | शेप के लॉक को लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 प्रॉपर्टीज़) |
| [Slide](../../aspose.slides/shape/slide) { get; } | शेप के पैरेंट स्लाइड को लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObject आइकन के शीर्षक को प्राप्त करता है या सेट करता है। पढ़ें/लिखें String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | एक ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें शेप के 3D इफ़ेक्ट गुण होते हैं। नोट: उन कुछ प्रकार के शेप्स जिनमें 3D गुण नहीं होते, उनके लिए null लौट सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रेज़ेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। चूँकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइंड किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य UInt32. देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | निर्धारित करता है कि लिंक्ड एम्बेडेड ऑब्जेक्ट प्रस्तुति खुले या प्रिंट होने पर स्वचालित रूप से अपडेट होता है या नहीं। पढ़ें/लिखें Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | पॉइंट्स में मापी गई शेप की चौड़ाई को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | शेप के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | शेप के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त करता है या सेट करता है। पढ़ें/लिखें Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z-ऑर्डर में शेप की स्थिति को लौटाता है। Shapes[0] पीछे की ओर स्थित शेप लौटाता है, और Shapes[Shapes.Count - 1] आगे की ओर स्थित शेप लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट वाले के लिए प्लेसहोल्डर प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | बेसिक प्लेसहोल्डर शेप लौटाता है (लेआउट और/या मास्टर स्लाइड से वह शेप जिससे वर्तमान शेप विरासत में मिला है)। यदि वर्तमान शेप विरासत में नहीं मिला है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | शेप थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | शेप थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | रेंडर की गई सामग्री से गणना किए गए शेप के दृश्य बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है। यह मेथड ऑब्जेक्ट के गुणों को नए डेटा के अनुसार बदलता है और IsObjectLink फ़्लैग को false सेट करता है, यह दर्शाते हुए कि OLE ऑब्जेक्ट एम्बेडेड है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | शेप की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### उदाहरण

निम्नलिखित उदाहरण दिखाता है कि OLE ऑब्जेक्ट फ्रेम्स को कैसे एक्सेस किया जाए।

```csharp
[C#]
// PPTX को एक प्रस्तुति ऑब्जेक्ट में लोड करता है
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // पहली स्लाइड तक पहुंचता है
    ISlide sld = pres.Slides[0];
    // शेप को OleObjectFrame में कास्ट करता है
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // OLE ऑब्जेक्ट को पढ़ता है और इसे डिस्क पर लिखता है
    if (oleObjectFrame != null)
    {
        // एम्बेडेड फ़ाइल डेटा प्राप्त करता है
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // एम्बेडेड फ़ाइल एक्सटेंशन प्राप्त करता है
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // निकाले गए फ़ाइल को सहेजने के लिए पथ बनाता है
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // निकाले गए डेटा को सहेजता है
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### देखें

* क्लास [GraphicalObject](../graphicalobject)
* इंटरफ़ेस [IOleObjectFrame](../ioleobjectframe)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेम्बली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->