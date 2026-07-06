---
title: TextFrameFormat
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: TextFrames के formatTextFrameFormatting गुण सम्मिलित करता है।
type: docs
weight: 10960
url: /hi/aspose.slides/textframeformat/
---
## TextFrameFormat क्लास

TextFrame की formatTextFrameFormatting प्रॉपर्टीज़ शामिल करता है।

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## कंस्ट्रक्टर्स

| नाम | वर्णन |
| --- | --- |
| [TextFrameFormat](textframeformat)() | एक नया इंस्टेंस प्रारंभ करता है [`TextFrameFormat`](../textframeformat) क्लास का। |

## प्रॉपर्टीज़

| नाम | वर्णन |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | एक TextFrame में वर्टिकल एंकर टेक्स्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TextAnchorType`](../textanchortype)। |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | आधार IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent)। |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | टेक्स्ट के ऑटोफिट मोड को प्राप्त या सेट करता है। पढ़ें/लिखें [`TextAutofitType`](../textautofittype)। |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | यदि NullableBool.True हो तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | टेक्स्ट एरिया में कॉलमों की संख्या को प्राप्त या सेट करता है। यह मान सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य पर सेट किया जाएगा। मान 0 अनिर्दिष्ट मान दर्शाता है। पढ़ें/लिखें Int32। |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | टेक्स्ट एरिया में टेक्स्ट कॉलमों के बीच का अंतराल (पॉइंट्स में) प्राप्त या सेट करता है। यह केवल तभी लागू होगा जब एक से अधिक कॉलम मौजूद हों। यह मान सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य पर सेट किया जाएगा। पढ़ें/लिखें Double। |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | 3-D रोटेशन प्रभाव लागू होने पर भी टेक्स्ट को सपाट रखने को प्राप्त या सेट करता है। पढ़ें/लिखें Boolean। |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | एक TextFrame में नीचे की मार्जिन (पॉइंट्स) को प्राप्त या सेट करता है। पढ़ें/लिखें Double। |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | एक TextFrame में बाईं मार्जिन (पॉइंट्स) को प्राप्त या सेट करता है। पढ़ें/लिखें Double। |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | एक TextFrame में दाईं मार्जिन (पॉइंट्स) को प्राप्त या सेट करता है। पढ़ें/लिखें Double। |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | एक TextFrame में शीर्ष मार्जिन (पॉइंट्स) को प्राप्त या सेट करता है। पढ़ें/लिखें Double। |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू घुमाव को कस्टम रूप से निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया, तो संलग्न आकार का घुमाव उपयोग किया जाता है। यदि निर्दिष्ट किया गया, तो यह आकार से स्वतंत्र रूप से लागू होता है। अर्थात् आकार पर घुमाव लागू हो सकता है और टेक्स्ट पर भी अलग से घुमाव लागू हो सकता है। इस प्रॉपर्टी और TextVerticalType में पूर्वनिर्धारित वर्टिकल टाइप से प्राप्त दृश्य टेक्स्ट घुमाव का समग्र मान यहाँ दिया गया है। पढ़ें/लिखें Single। |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | टेक्स्ट अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और RotationAngle में कस्टम एंगल से प्राप्त दृश्य टेक्स्ट घुमाव का संक्षिप्त मान यहाँ प्रस्तुत है। पढ़ें/लिखें [`TextVerticalType`](../textverticaltype)। |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | टेक्स्ट के 3D इफ़ेक्ट प्रॉपर्टीज़ का प्रतिनिधित्व करने वाला ThreeDFormat ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [`IThreeDFormat`](../ithreedformat)। |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | टेक्स्ट रैपिंग आकार को प्राप्त या सेट करता है। पढ़ें/लिखें [`TextShapeType`](../textshapetype)। |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | यदि टेक्स्ट TextFrame की मार्जिन पर रैप किया गया हो तो **True**। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |

## मेथड्स

| नाम | वर्णन |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट object के साथ तुलना करता है। |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | इनहेरिटेंस लागू होते हुए प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### संबंधित देखें

* क्लास [PVIObject](../pviobject)
* इंटरफ़ेस [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* इंटरफ़ेस [ITextFrameFormat](../itextframeformat)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->