---
title: IParagraphFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: यह क्लास पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ को रखती है। IParagraphFormatEffectiveData./iparagraphformateffectivedata के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखी जा सकती हैं।
type: docs
weight: 6590
url: /hi/aspose.slides/iparagraphformat/
---
## IParagraphFormat इंटरफ़ेस

यह क्लास पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ को रखती है। [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखी जा सकती हैं।

```csharp
public interface IParagraphFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | किसी पैराग्राफ में बिना विरासत के पाठ संरेखण को लौटाता है या सेट करता है। पढ़ें/लिखें [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | पैराग्राफ का बुलेट फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | पैराग्राफ का डिफ़ॉल्ट भाग फ़ॉर्मेट लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | बिना विरासत के डिफ़ॉल्ट टैबुलेशन आकार को लौटाता है या सेट करता है। पढ़ें/लिखें Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | पैराग्राफ की गहराई को लौटाता है या सेट करता है। मान 0 अनिर्दिष्ट मान को दर्शाता है। पढ़ें/लिखें Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | निर्धारित करता है कि पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | बिना विरासत के पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता है या सेट करता है। पढ़ें/लिखें [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | निर्धारित करता है कि पैराग्राफ में हैंगिंग विराम चिह्न उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | बिना विरासत के पैराग्राफ की पहली पंक्ति इन्डेंट/हैंगिंग इन्डेंट को लौटाता है या सेट करता है। नकारात्मक मानों से हैंगिंग इन्डेंट निर्धारित किया जा सकता है। पढ़ें/लिखें Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | निर्धारित करता है कि पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | बिना विरासत के पैराग्राफ में बायें मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | बिना विरासत के पैराग्राफ में दायें मार्जिन को लौटाता है या सेट करता है। पढ़ें/लिखें Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | निर्धारित करता है कि पैराग्राफ में दाएं से बाएं लेखन उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | बिना विरासत के पैराग्राफ में अंतिम पंक्ति के बाद अंतराल की मात्रा को लौटाता है या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है जो व्हाइट स्पेस होना चाहिए। नकारात्मक मान पॉइंट आकार में व्हाइट स्पेस का आकार दर्शाता है। पढ़ें/लिखें Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | बिना विरासत के पैराग्राफ में पहली पंक्ति से पहले अंतराल की मात्रा को लौटाता है या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार के प्रतिशत को दर्शाता है जो व्हाइट स्पेस होना चाहिए। नकारात्मक मान पॉइंट आकार में व्हाइट स्पेस का आकार दर्शाता है। पढ़ें/लिखें Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | पैराग्राफ में बेस लाइनों के बीच अंतराल की मात्रा को लौटाता है या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक - पॉइंट्स में आकार। कोई विरासत लागू नहीं। पढ़ें/लिखें Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | पैराग्राफ की टैबुलेशन को लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [`ITabCollection`](../itabcollection). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | विरासत लागू करके प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा को प्राप्त करता है। |

### टिप्पणी

यह क्लास विशिष्ट पैराग्राफ के लिए परिभाषित पैराग्राफ फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और संशोधित करने के लिए उपयोग किया जाता है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अनिर्दिष्ट" मान मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](./geteffective) मेथड का उपयोग करना होगा जो एक [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) इंस्टेंस लौटाता है।

### देखें

* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->