---
title: IParagraphFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: यह वर्ग पैराग्राफ फ़ॉर्मेटिंग गुणों को सम्मिलित करता है। IParagraphFormatEffectiveData./iparagraphformateffectivedata के विपरीत इस वर्ग की सभी गुण लिखने योग्य हैं।
type: docs
weight: 6590
url: /hi/aspose.slides/iparagraphformat/
---
## IParagraphFormat इंटरफ़ेस

यह वर्ग पैराग्राफ प्रारूपण गुणों को सम्मिलित करता है। [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) के विपरीत, इस वर्ग की सभी गुण लिखने योग्य हैं।

```csharp
public interface IParagraphFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | एक पैराग्राफ में कोई विरासत न होने पर पाठ संरेखण को लौटाता है या सेट करता है। पढ़ें/लिखें [`TextAlignment`](../textalignment)। |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | पैराग्राफ का बुलेट स्वरूप लौटाता है। केवल-पढ़ने योग्य [`IBulletFormat`](../ibulletformat)। |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | एक पैराग्राफ का डिफ़ॉल्ट भाग स्वरूप लौटाता है। कोई विरासत लागू नहीं हुई। केवल-पढ़ने योग्य [`IPortionFormat`](../iportionformat)। |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | कोई विरासत न होने पर डिफ़ॉल्ट टैब्यूलेशन आकार को लौटाता है या सेट करता है। पढ़ें/लिखें Single। |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | पैराग्राफ की गहराई को लौटाता है या सेट करता है। मान 0 का अर्थ अपरिभाषित है। पढ़ें/लिखें Int16। |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | निर्धारित करता है कि पैराग्राफ में पूर्वी एशियाई लाइन ब्रेक उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं हुई। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | कोई विरासत न होने पर पैराग्राफ में फ़ॉन्ट संरेखण को लौटाता है या सेट करता है। पढ़ें/लिखें [`FontAlignment`](../fontalignment)। |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | निर्धारित करता है कि पैराग्राफ में लटकता विराम चिह्न उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं हुई। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | कोई विरासत न होने पर पैराग्राफ का पहला लाइन इंडेंट/हैंगिंग इंडेंट लौटाता है या सेट करता है। हैंगिंग इंडेंट को नकारात्मक मानों से परिभाषित किया जा सकता है। पढ़ें/लिखें Single। |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | निर्धारित करता है कि पैराग्राफ में लैटिन लाइन ब्रेक उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं हुई। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | कोई विरासत न होने पर पैराग्राफ में बायाँ मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें Single। |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | कोई विरासत न होने पर पैराग्राफ में दायाँ मार्जिन लौटाता है या सेट करता है। पढ़ें/लिखें Single। |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | निर्धारित करता है कि पैराग्राफ में दाएँ से बाएँ लेखन उपयोग किया जाता है या नहीं। कोई विरासत लागू नहीं हुई। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | कोई विरासत न होने पर पैराग्राफ में अंतिम लाइन के बाद की जगह की मात्रा लौटाता है या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है जिसे whitespace होना चाहिए। नकारात्मक मान whitespace का आकार पॉइंट में दर्शाता है। पढ़ें/लिखें Single। |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | कोई विरासत न होने पर पैराग्राफ में पहली लाइन से पहले की जगह की मात्रा लौटाता है या सेट करता है। सकारात्मक मान फ़ॉन्ट आकार का प्रतिशत दर्शाता है जिसे whitespace होना चाहिए। नकारात्मक मान whitespace का आकार पॉइंट में दर्शाता है। पढ़ें/लिखें Single। |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | पैराग्राफ में बेस लाइनों के बीच की जगह की मात्रा लौटाता है या सेट करता है। सकारात्मक मान प्रतिशत है, नकारात्मक - पॉइंट में आकार। कोई विरासत लागू नहीं हुई। पढ़ें/लिखें Single। |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | पैराग्राफ की टैब्यूलेशन लौटाता है। कोई विरासत लागू नहीं हुई। केवल-पढ़ने योग्य [`ITabCollection`](../itabcollection)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | विरासत लागू होते हुए प्रभावी पैराग्राफ फ़ॉर्मेटिंग डेटा प्राप्त करता है। |

### टिप्पणी

इस वर्ग का उपयोग किसी विशिष्ट पैराग्राफ के लिए परिभाषित पैराग्राफ फ़ॉर्मेटिंग गुणों को लौटाने और बदलने के लिए किया जाता है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अपरिभाषित" मान प्राप्त होंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](./geteffective) मेथड उपयोग करना होगा जो एक [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) इंस्टेंस लौटाता है।

### देखें

* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->