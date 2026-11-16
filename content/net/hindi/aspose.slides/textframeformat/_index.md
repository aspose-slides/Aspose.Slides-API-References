---
title: TextFrameFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: TextFrames के formatTextFrameFormatting गुणों को सम्मिलित करता है।
type: docs
weight: 10980
url: /hi/aspose.slides/textframeformat/
---
## TextFrameFormat क्लास

TextFrame की formatTextFrameFormatting गुणों को सम्मिलित करता है।

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TextFrameFormat](textframeformat)() | नया [`TextFrameFormat`](../textframeformat) क्लास का एक नया उदाहरण आरंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | TextFrame में ऊर्ध्वाधर एंकर टेक्स्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | आधार IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल पढ़ें [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | टेक्स्ट के ऑटोफिट मोड को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | यदि NullableBool.True है तो टेक्स्ट को बॉक्स में क्षैतिज रूप से केंद्रित किया जाना चाहिए। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | टेक्स्ट क्षेत्र में कॉलम की संख्या को प्राप्त करता है या सेट करता है। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य पर सेट किया जाएगा। मान 0 अनिर्धारित मान दर्शाता है। पढ़ें/लिखें Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | टेक्स्ट क्षेत्र में टेक्स्ट कॉलमों के बीच का अंतर (पॉइंट में) प्राप्त करता है या सेट करता है। यह केवल तब लागू होना चाहिए जब एक से अधिक कॉलम موجود हों। यह मान एक सकारात्मक संख्या होना चाहिए। अन्यथा, मान शून्य पर सेट किया जाएगा। पढ़ें/लिखें Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | 3-D रोटेशन प्रभाव लागू होने पर भी टेक्स्ट को सपाट रखने को प्राप्त करता है या सेट करता है। पढ़ें/लिखें Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | TextFrame में नीचे का मार्जिन (पॉइंट) प्राप्त करता है या सेट करता है। पढ़ें/लिखें Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | TextFrame में बायाँ मार्जिन (पॉइंट) प्राप्त करता है या सेट करता है। पढ़ें/लिखें Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | TextFrame में दायाँ मार्जिन (पॉइंट) प्राप्त करता है या सेट करता है। पढ़ें/लिखें Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | TextFrame में ऊपर का मार्जिन (पॉइंट) प्राप्त करता है या सेट करता है। पढ़ें/लिखें Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | बाउंडिंग बॉक्स के भीतर टेक्स्ट पर लागू होने वाले कस्टम रोटेशन को निर्दिष्ट करता है। यदि निर्दिष्ट नहीं किया गया, तो साथ वाले आकार का रोटेशन उपयोग किया जाता है। यदि निर्दिष्ट किया गया, तो यह आकार से स्वतंत्र रूप से लागू होता है। अर्थात् आकार में रोटेशन लागू हो सकता है और टेक्स्ट पर भी अलग रोटेशन लागू हो सकता है। इस प्रॉपर्टी और TextVerticalType प्रॉपर्टी में पूर्वनिर्धारित ऊर्ध्वाधर प्रकार से संयुक्त दृश्य टेक्स्ट रोटेशन का परिणाम मान प्राप्त होता है। पढ़ें/लिखें Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | टेक्स्ट अभिविन्यास निर्धारित करता है। इस प्रॉपर्टी और RotationAngle प्रॉपर्टी में कस्टम कोण से संयुक्त दृश्य टेक्स्ट रोटेशन का परिणाम मान प्राप्त होता है। पढ़ें/लिखें [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | टेक्स्ट के 3D इफ़ेक्ट गुणों को दर्शाने वाले ThreeDFormat ऑब्जेक्ट को प्राप्त करता है। केवल पढ़ें [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | टेक्स्ट रैपिंग आकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** यदि टेक्स्ट TextFrame की मार्जिन पर रैप किया गया हो। पढ़ें/लिखें [`NullableBool`](../nullablebool). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | विरासत लागू होने के साथ प्रभावी टेक्स्ट फ्रेम फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### संबंधित देखें

* क्लास [PVIObject](../pviobject)
* इंटरफ़ेस [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* इंटरफ़ेस [ITextFrameFormat](../itextframeformat)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->