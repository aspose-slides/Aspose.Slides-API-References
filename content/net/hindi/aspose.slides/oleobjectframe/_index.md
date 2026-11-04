---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक स्लाइड पर OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 9250
url: /hi/aspose.slides/oleobjectframe/
---
## OleObjectFrame क्लास

एक स्लाइड पर OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़े वैकल्पिक पाठ का शीर्षक प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | बेस IGraphicalObject इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IGraphicalObject`](../igraphicalobject)। |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | यह प्रॉपर्टी निर्दिष्ट करती है कि एक shape काले-सफेद डिस्प्ले मोड में कैसे रेंडर होगी। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode)। |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य Int32। |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [`ICustomData`](../icustomdata)। |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें shape पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: उन shape प्रकारों के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टीज़ नहीं होतीं। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE एम्बेडेड डेटा के बारे में जानकारी प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo)। |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | एम्बेडेड OLE ऑब्जेक्ट का फ़ाइल नाम लौटाता है। |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | एम्बेडेड OLE ऑब्जेक्ट का पथ लौटाता है। |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन shape प्रकारों के लिए null लौटाया जा सकता है जिनमें भराव प्रॉपर्टीज़ नहीं होतीं। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape की लॉकिंग जानकारी लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock)। |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई (पॉइंट्स में मापी गई) प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छिपा है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक लौटाता है। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager)। |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink)। |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दिखता है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से लिंक्ड है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य Boolean। |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए रेखा फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: उन shape प्रकारों के लिए null लौटाया जा सकता है जिनमें रेखा प्रॉपर्टीज़ नहीं होतीं। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | लिंक्ड फ़ाइल का पूर्ण पथ लौटाता है। छोटा फ़ाइल नाम उपयोग किया जाएगा। केवल-पढ़ने योग्य String। |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | लिंक्ड फ़ाइल का पूर्ण पथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ने/लिखने योग्य String। |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | यदि मौजूद हो तो लिंक्ड फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। केवल-पढ़ने योग्य String। |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape का नाम प्राप्त करता है या सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ने/लिखने योग्य String। |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | ऑब्जेक्ट का नाम प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | ऑब्जेक्ट का ProgID प्राप्त करता है। केवल-पढ़ने योग्य String। |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है जो shape के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरोप कोड को दस्तावेज़ के कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल-पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid)। |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो उसके पैरेंट GroupShape ऑब्जेक्ट को लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [`IGroupShape`](../igroupshape)। |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape के प्लेसहोल्डर को लौटाता है। यदि shape का कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [`IPlaceholder`](../iplaceholder)। |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | स्लाइड की पैरेंट प्रस्तुति को लौटाता है। केवल-पढ़ने योग्य [`IPresentation`](../ipresentation)। |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | कच्चे shape फ्रेम की प्रॉपर्टीज़ को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe)। |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमा देने के डिग्री की संख्या प्राप्त करता है या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान घड़ी के विपरीत दिशा में घुमाव दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape की लॉकिंग जानकारी लौटाता है। केवल-पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock)। (2 प्रॉपर्टीज़) |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट स्लाइड को लौटाता है। केवल-पढ़ने योग्य [`IBaseSlide`](../ibaseslide)। |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat)। |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObject आइकन का शीर्षक प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए 3D इफ़ेक्ट प्रॉपर्टीज़ होती हैं। नोट: उन shape प्रकारों के लिए null लौटाया जा सकता है जिनमें 3D प्रॉपर्टीज़ नहीं होतीं। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat)। |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग करने के लिए अभिप्रेत है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid)। |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | निर्धारित करता है कि लिंक्ड एम्बेडेड ऑब्जेक्ट प्रस्तुति खुलते समय या प्रिंट होते समय स्वचालित रूप से अपडेट हो जाता है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई (पॉइंट्स में मापी गई) प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को (पॉइंट्स में मापी गई) प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को (पॉइंट्स में मापी गई) प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single। |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | shape का z-ऑर्डर में स्थिती लौटाता है। Shapes[0] पीछे वाले shape को लौटाता है, और Shapes[Shapes.Count - 1] आगे वाले shape को लौटाता है। केवल-पढ़ने योग्य Int32। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की प्रॉपर्टीज़ सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बेसिक प्लेसहोल्डर shape लौटाता है (layout या मास्टर स्लाइड से वह shape जिससे वर्तमान shape विरासत में मिला है)। यदि वर्तमान shape विरासत में नहीं मिला है तो null लौटाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape का थंबनेल लौटाता है। डिफ़ॉल्ट रूप से ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape का थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की विज़ुअल बाउंड्स प्राप्त करता है जो उसके रेंडर्ड कंटेंट से गणना की गई हैं। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह shape प्लेसहोल्डर नहीं है। |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है। यह मेथड ऑब्जेक्ट की प्रॉपर्टीज़ को नए डेटा के अनुरूप बदलता है और IsObjectLink फ्लैग को false सेट करता है, दर्शाता है कि OLE ऑब्जेक्ट एम्बेडेड है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### उदाहरण

निम्नलिखित उदाहरण OLE ऑब्जेक्ट फ्रेम्स तक कैसे पहुँचें, दर्शाता है।

```csharp
[C#]
// PPTX को एक प्रस्तुति ऑब्जेक्ट में लोड करता है
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // पहले स्लाइड तक पहुँचता है
    ISlide sld = pres.Slides[0];
    // shape को OleObjectFrame में कास्ट करता है
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // OLE ऑब्जेक्ट को पढ़ता है और डिस्क पर लिखता है
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
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->