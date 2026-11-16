---
title: IParagraphFormat
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: यह क्लास पैराग्राफ फ़ॉर्मेटिंग गुणों को समेटे हुए है। IParagraphFormatEffectiveData./iparagraphformateffectivedata के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।
type: docs
weight: 6610
url: /hi/aspose.slides/iparagraphformat/
---
## IParagraphFormat इंटरफेस

यह क्लास पैराग्राफ फ़ॉर्मेटिंग गुणों को समेटे हुए है। [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

```csharp
public interface IParagraphFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | पैराग्राफ में कोई विरासत नहीं होने पर पाठ संरेखण को लौटाता या सेट करता है। पढ़ें/लिखें [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | पैराग्राफ का बुलेट स्वरूप लौटाता है। केवल पढ़ने योग्य [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | पैराग्राफ का डिफ़ॉल्ट भाग स्वरूप लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | कोई विरासत नहीं होने पर डिफ़ॉल्ट टैबुलेशन आकार को लौटाता या सेट करता है। पढ़ें/लिखें Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | पैराग्राफ की गहराई को लौटाता या सेट करता है। मान 0 अनिर्धारित मान दर्शाता है। पढ़ें/लिखें Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | निर्धारित करता है कि क्या पैराग्राफ में ईस्ट एशियन लाइन ब्रेक उपयोग किया जाता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | कोई विरासत नहीं होने पर पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता या सेट करता है। पढ़ें/लिखें [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | निर्धारित करता है कि क्या पैराग्राफ में हैंगिंग विराम चिह्न उपयोग किया जाता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | कोई विरासत नहीं होने पर पैराग्राफ की प्रथम पंक्ति इंडेंट/हैंगिंग इंडेंट को लौटाता या सेट करता है। हैंगिंग इंडेंट नकारात्मक मानों के साथ परिभाषित किया जा सकता है। पढ़ें/लिखें Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | निर्धारित करता है कि क्या पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | कोई विरासत नहीं होने पर पैराग्राफ में बायां मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | कोई विरासत नहीं होने पर पैराग्राफ में दायां मार्जिन लौटाता या सेट करता है। पढ़ें/लिखें Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | निर्धारित करता है कि क्या पैराग्राफ में दाएं से बाएं लेखन उपयोग किया जाता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | कोई विरासत नहीं होने पर पैराग्राफ में अंतिम पंक्ति के बाद की स्थान मात्रा को लौटाता या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है जो सफ़ेद स्थान होना चाहिए। नकारात्मक मान बिंदु आकार में सफ़ेद स्थान का आकार दर्शाता है। पढ़ें/लिखें Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | कोई विरासत नहीं होने पर पैराग्राफ में पहली पंक्ति से पहले की स्थान मात्रा को लौटाता या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है जो सफ़ेद स्थान होना चाहिए। नकारात्मक मान बिंदु आकार में सफ़ेद स्थान का आकार दर्शाता है। पढ़ें/लिखें Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | पैराग्राफ में बेस लाइनों के बीच की स्थान मात्रा को लौटाता या सेट करता है। सकारात्मक मान प्रतिशत दर्शाता है, नकारात्मक - बिंदुओं में आकार। कोई विरासत लागू नहीं। पढ़ें/लिखें Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | पैराग्राफ की टैबुलेशन्स को लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [`ITabCollection`](../itabcollection). |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | विरासत लागू होते हुए प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### टिप्पणी

यह क्लास विशिष्ट पैराग्राफ के लिए परिभाषित पैराग्राफ फ़ॉर्मेटिंग गुणों को लौटाने और बदलने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अनिर्धारित" मान मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](./geteffective) मेथड का उपयोग करना होगा जो एक [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) इंस्टेंस लौटाता है।

### देखें

* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->