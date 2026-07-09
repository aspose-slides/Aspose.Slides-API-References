---
title: OleObjectFrame
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: स्लाइड पर OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 9230
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
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | एक shape से जुड़ा वैकल्पिक टेक्स्ट लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | एक shape से जुड़ी वैकल्पिक टेक्स्ट के शीर्षक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | आधार IGraphicalObject इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | प्रॉपर्टी यह निर्दिष्ट करती है कि एक shape काली-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ने/लिखने योग्य [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | EffectFormat ऑब्जेक्ट लौटाता है जिसमें shape पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। ध्यान दें: कुछ shape प्रकारों के लिए जिनमें इफ़ेक्ट गुण नहीं होते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | OLE एम्बेडेड डेटा के बारे में जानकारी प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | एंबेडेड OLE ऑब्जेक्ट की फ़ाइल नाम लौटाता है |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | एंबेडेड OLE ऑब्जेक्ट का पाथ लौटाता है |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | FillFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ शामिल हैं। ध्यान दें: कुछ shape प्रकारों के लिए जिनमें भराव प्रॉपर्टीज़ नहीं होते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | shape के लॉक लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape की ऊँचाई, पॉइंट में मापी गई, प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | निर्धारित करता है कि shape छुपा हुआ है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर को लौटाता है। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' विकल्प को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | निर्धारित करता है कि shape समूहित है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | निर्धारित करता है कि कोई ऑब्जेक्ट आइकन के रूप में दिखता है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से जुड़ा है या नहीं। केवल पढ़ने योग्य Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | निर्धारित करता है कि shape TextHolder_PPT है या नहीं। केवल पढ़ने योग्य Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | LineFormat ऑब्जेक्ट लौटाता है जिसमें shape के लिए रेखा फ़ॉर्मेटिंग प्रॉपर्टीज़ शामिल हैं। ध्यान दें: कुछ shape प्रकारों के लिए जिनमें रेखा प्रॉपर्टीज़ नहीं होते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | लिंक्ड फ़ाइल का पूर्ण पाथ लौटाता है। छोटा फ़ाइल नाम उपयोग किया जाएगा। केवल पढ़ने योग्य String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | लिंक्ड फ़ाइल का पूर्ण पाथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ने/लिखने योग्य String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | यदि मौजूद है तो लिंक्ड फ़ाइल का सापेक्ष पाथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। केवल पढ़ने योग्य String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape के नाम को लौटाता है या सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ने/लिखने योग्य String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | ऑब्जेक्ट के नाम को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | ऑब्जेक्ट का ProgID लौटाता है। केवल पढ़ने योग्य String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | एक slide-परिधीय अद्वितीय पहचानकर्ता लौटाता है जो shape के पूरे जीवनकाल में स्थिर रहता है और PowerPoint या interop कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ने योग्य UInt32। देखें [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | यदि shape समूहित है तो पैरेंट GroupShape ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape के लिए placeholder लौटाता है। यदि shape के पास placeholder नहीं है तो null लौटाता है। केवल पढ़ने योग्य [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | slide की पैरेंट प्रस्तुतिकरण लौटाता है। केवल पढ़ने योग्य [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | raw shape फ्रेम की प्रॉपर्टीज़ लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाए गए डिग्री संख्या को लौटाता है या सेट करता है। एक सकारात्मक मान clockwise घूर्णन को दर्शाता है; एक नकारात्मक मान counterclockwise घूर्णन को दर्शाता है। पढ़ने/लिखने योग्य Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | shape के लॉक लौटाता है। केवल पढ़ने योग्य [`IGraphicalObjectLock`](../igraphicalobjectlock)। (2 प्रॉपर्टीज़) |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape की पैरेंट slide लौटाता है। केवल पढ़ने योग्य [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | OleObject इमेज़ भराव प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | OleObject आइकन के शीर्षक को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ThreeDFormat ऑब्जेक्ट लौटाता है जिसमें shape के 3d इफ़ेक्ट प्रॉपर्टीज़ होते हैं। ध्यान दें: कुछ shape प्रकारों के लिए जिनमें 3d प्रॉपर्टीज़ नहीं होते, null लौटाया जा सकता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | एक आंतरिक, प्रस्तुति-परिधीय पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाता है। चूँकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं मानना चाहिए। केवल पढ़ने योग्य UInt32। देखें [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | निर्धारित करता है कि लिंक्ड एम्बेडेड ऑब्जेक्ट प्रस्तुति खुले या प्रिंट होते समय स्वचालित रूप से अपडेट होता है या नहीं। पढ़ने/लिखने योग्य Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape की चौड़ाई, पॉइंट में मापी गई, प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ने/लिखने योग्य Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है या सेट करता है, पॉइंट में मापी गई। पढ़ने/लिखने योग्य Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | shape की z-क्रम में स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे वाला shape लौटाता है, और Shapes[Shapes.Count - 1] आगे वाला shape लौटाता है। केवल पढ़ने योग्य Int32. |

## विधियां

| नाम | विवरण |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | यदि कोई placeholder नहीं है तो एक नया placeholder जोड़ता है और placeholder प्रॉपर्टीज़ को निर्दिष्ट वाले पर सेट करता है। |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | एक बुनियादी placeholder shape लौटाता है (layout और/या master slide से shape जो वर्तमान shape द्वारा विरासत में लिया गया है)। यदि वर्तमान shape विरासत में नहीं है तो null लौटाया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप में ShapeThumbnailBounds.Shape shape थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape थंबनेल लौटाता है। |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | shape की रेंडर की गई सामग्री से गणना किए गए दृश्य बाउंड्स को प्राप्त करता है। |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | निर्धारित करता है कि यह shape placeholder नहीं है। |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है। यह मेथड ऑब्जेक्ट की प्रॉपर्टीज़ को नए डेटा को दर्शाने के लिए बदलता है और IsObjectLink फ़्लैग को false सेट करता है, जिससे यह संकेत मिलता है कि OLE ऑब्जेक्ट एम्बेडेड है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |

### उदाहरण

निम्न उदाहरण दिखाता है कि OLE ऑब्जेक्ट फ़्रेम तक कैसे पहुंचा जाए।

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
        // एंबेडेड फ़ाइल डेटा प्राप्त करता है
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // एंबेडेड फ़ाइल एक्सटेंशन प्राप्त करता है
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // निकाली गई फ़ाइल को सहेजने के लिए पाथ बनाता है
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // निकाला गया डेटा सहेजता है
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
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->