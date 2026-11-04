---
title: IBasePortionFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: यह वर्ग पाठ भाग फ़ॉर्मेटिंग गुणों को रखता है। IPortionFormatEffectiveData./iportionformateffectivedata के विपरीत इस वर्ग की सभी गुण लिखने योग्य हैं।
type: docs
weight: 5330
url: /hi/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat इंटरफ़ेस

यह वर्ग पाठ भाग फ़ॉर्मेटिंग प्रॉपर्टीज़ को रखता है। [`IPortionFormatEffectiveData`](../iportionformateffectivedata) के विपरीत, इस वर्ग की सभी प्रॉपर्टीज़ लिखी जा सकती हैं।

```csharp
public interface IBasePortionFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | वैकल्पिक भाषा की Id को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata)। |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | पूर्व एशियाई फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata)। |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | पाठ EffectFormat गुणों को लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | सुपरस्क्रिप्ट या सबस्क्रिप्ट पाठ को लौटाता है या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **float.NaN** का मतलब है मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य Single। |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | पाठ FillFormat गुणों को लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool)। |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | एक भाग की फ़ॉन्ट ऊँचाई को लौटाता है या सेट करता है। **float.NaN** का मतलब है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य Single। |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool)। |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | पाठ अंडरलाइन प्रकार को लौटाता है या सेट करता है। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [`TextUnderlineType`](../textunderlinetype)। |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | पाठ को हाईलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`IColorFormat`](../icolorformat)। |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली के अपने FillFormat गुण हैं या यह पाठ के FillFormat गुणों से विरासत में प्राप्त करता है। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool)। |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली के अपने LineFormat गुण हैं या यह पाठ के LineFormat गुणों से विरासत में प्राप्त करता है। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool)। |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए केरनिंग चालू होनी चाहिए। **float.NaN** का मतलब है मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य Single। |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्याएँ पाठ के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज करें। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool)। |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | प्रूफिंग भाषा की Id को लौटाता है या सेट करता है। वर्तनी और व्याकरण जांच के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String। |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | लैटिन फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata)। |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | पाठ आउटलाइनिंग के लिए LineFormat गुणों को लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि पाठ की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool)। |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि पाठ को प्रूफ नहीं किया जाना चाहिए या नहीं। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool)। |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | अंतर-चरित्र अंतराल वृद्धि को लौटाता है या सेट करता है। **float.NaN** का मतलब है मान अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य Single। |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | पाठ भाग के लिए स्पेल चेकिंग सक्षम है या नहीं, यह दर्शाने वाला मान को प्राप्त करता है या सेट करता है। जब यह गुण false पर सेट किया जाता है, तो पाठ तत्वों के लिए स्पेलिंग जांच दबी रहती है। जब true पर सेट किया जाता है, तो स्पेल चेकिंग अनुमति दी जाती है। डिफ़ॉल्ट मान `false` है। |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | पाठ के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [`TextStrikethroughType`](../textstrikethroughtype)। |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | प्रतीकात्मक फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में प्राप्त किया जाना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata)। |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | पाठ के कैपिटलाइज़ेशन प्रकार को लौटाता है या सेट करता है। कोई विरासत नहीं लागू। पढ़ने/लिखने योग्य [`TextCapType`](../textcaptype)। |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | अंडरलाइन लाइन के FillFormat गुणों को लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | अंडरलाइन लाइन को आउटलाइन करने के लिए इस्तेमाल किए गए LineFormat गुणों को लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |

### टिप्पणी

इस वर्ग का उपयोग विशिष्ट भाग के लिए परिभाषित पाठ भाग फ़ॉर्मेटिंग गुणों को लौटाने और बदलने के लिए किया जाता है। इसका मतलब है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अपरिभाषित" मान प्राप्त होंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](../iportionformat/geteffective) मेथड का उपयोग करना होगा जो एक [`IPortionFormatEffectiveData`](../iportionformateffectivedata) इंस्टेंस लौटाता है।

### देखें भी

* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->