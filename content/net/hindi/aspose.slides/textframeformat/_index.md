---
title: TextFrameFormat
second_title: Aspose.Sildes for .NET API रेफ़रेंस
description: TextFrames के formatTextFrameFormatting गुणधर्म शामिल करता है।
type: docs
weight: 10960
url: /hi/aspose.slides/textframeformat/
---
## TextFrameFormat क्लास

TextFrame की formatTextFrameFormatting गुणधर्म समाहित करता है।

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [TextFrameFormat](textframeformat)() | नए [`TextFrameFormat`](../textframeformat) क्लास का एक नया उदाहरण प्रारम्भ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | एक TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | टेक्स्ट के ऑटॉफ़िट मोड को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | यदि NullableBool.True हो तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केन्द्रित किया जाना चाहिए। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | टेक्स्ट क्षेत्र में स्तंभों की संख्या को प्राप्त करता है या सेट करता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य पर सेट किया जाएगा। मान 0 अपरिभाषित मान को दर्शाता है। पढ़ें/लिखें Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | टेक्स्ट क्षेत्र में टेक्स्ट स्तंभों के बीच की दूरी (पॉइंट्स में) को प्राप्त करता है या सेट करता है। यह केवल तभी लागू होना चाहिए जब 1 से अधिक स्तंभ मौजूद हों। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य पर सेट किया जाएगा। पढ़ें/लिखें Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | भले ही 3-डी रोटेशन प्रभाव लागू किया गया हो, टेक्स्ट को सपाट रखने को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | एक TextFrame में नीचे की मार्जिन (पॉइंट्स) को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | एक TextFrame में बायाँ मार्जिन (पॉइंट्स) को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | एक TextFrame में दायाँ मार्जिन (पॉइंट्स) को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | एक TextFrame में ऊपर की मार्जिन (पॉइंट्स) को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू की जा रही कस्टम रोटेशन को निर्दिष्ट करता है। यदि यह निर्दिष्ट नहीं है, तो साथ वाली आकृति की रोटेशन उपयोग की जाती है। यदि निर्दिष्ट है, तो यह आकृति से स्वतंत्र रूप से लागू होती है। अर्थात आकृति पर रोटेशन लागू हो सकता है, साथ ही टेक्स्ट पर भी रोटेशन लागू हो सकता है। इस गुण और TextVerticalType गुण में पूर्वनिर्धारित ऊर्ध्वाधर प्रकार से संक्षिप्त विज़ुअल टेक्स्ट रोटेशन का परिणामस्वरूप मान प्राप्त होता है। पढ़ें/लिखें Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | टेक्स्ट की अभिविन्यास निर्धारित करता है। इस गुण और RotationAngle गुण में कस्टम एंगल से प्राप्त विज़ुअल टेक्स्ट रोटेशन का संक्षिप्त परिणाम प्राप्त होता है। पढ़ें/लिखें [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | टेक्स्ट के लिए 3D प्रभाव गुणों को प्रतिनिधित्व करने वाले ThreeDFormat ऑब्जेक्ट को प्राप्त करता है। केवल-पढ़ने योग्य [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | टेक्स्ट रैपिंग स्वरूप को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** यदि टेक्स्ट TextFrame की मार्जिन पर रैप किया गया हो। पढ़ें/लिखें [`NullableBool`](../nullablebool). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | इनहेरिटेंस लागू किए गए प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा को प्राप्त करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### देखें

* क्लास [PVIObject](../pviobject)
* इंटरफ़ेस [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* इंटरफ़ेस [ITextFrameFormat](../itextframeformat)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->