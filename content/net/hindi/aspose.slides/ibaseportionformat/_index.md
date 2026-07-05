---
title: IBasePortionFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: यह वर्ग पाठ भाग स्वरूपण गुणों को सम्मिलित करता है। IPortionFormatEffectiveData./iportionformateffectivedata के विपरीत, इस वर्ग की सभी प्रॉपर्टी लिखने योग्य हैं।
type: docs
weight: 5310
url: /hi/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat इंटरफ़ेस

यह वर्ग पाठ भाग स्वरूपण गुणों को सम्मिलित करता है। [`IPortionFormatEffectiveData`](../iportionformateffectivedata) के विपरीत, इस वर्ग की सभी प्रॉपर्टी लिखने योग्य हैं।

```csharp
public interface IBasePortionFormat
```

## गुण

| नाम | वर्णन |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | वैकल्पिक भाषा का Id लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | पूर्वी एशिया फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | पाठ के EffectFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ें [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | उपरिलिखित या अधोलेखित पाठ लौटाता है या सेट करता है। मान -100% (अधोलेख) से 100% (उपरिलिखित) तक। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | पाठ के FillFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ें [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | एक भाग की फ़ॉन्ट ऊँचाई लौटाता है या सेट करता है। **float.NaN** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | पाठ के रेखांकित प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | पाठ को हाइलाइट करने के लिए उपयोग किया गया रंग लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ें [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि रेखांकित शैली के पास अपना FillFormat है या यह पाठ के FillFormat से विरासत में लेती है। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि रेखांकित शैली के पास अपना LineFormat है या यह पाठ के LineFormat से विरासत में लेती है। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार लौटाता है या सेट करता है, जिसके लिए कर्निंग चालू होनी चाहिए। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्याएँ पाठ की पूर्वी भाषा-विशिष्ट लंबवत लेआउट को अनदेखा करें। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | प्रूफिंग भाषा का Id लौटाता है या सेट करता है। वर्तनी और व्याकरण की जाँच के लिए उपयोग किया जाता है। पढ़ें/लिखें String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | लेटिन फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | पाठ की बाहरी रेखा के लिए LineFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ें [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि पाठ की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि पाठ को प्रूफ नहीं किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | अन्तर-अक्षर अंतराल वृद्धि को लौटाता है या सेट करता है। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | एक मान सेट या प्राप्त करता है जो इंगित करता है कि पाठ भाग के लिए वर्तनी जाँच सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट होती है, तो पाठ तत्वों के लिए वर्तनी जाँच दमन की जाती है। जब true पर सेट होती है, तो वर्तनी जाँच की अनुमति होती है। डिफ़ॉल्ट मान `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | पाठ के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | पाठ के बड़े अक्षर के प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ें/लिखें [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | रेखांकित रेखा के FillFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ें [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | रेखांकित रेखा को रूपरेखा देने के लिए उपयोग किए जाने वाले LineFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ें [`ILineFormat`](../ilineformat). |

### टिप्पणियाँ

यह वर्ग विशेष भाग के लिए परिभाषित पाठ भाग स्वरूपण गुणों को लौटाने और उन्हें संशोधित करने के लिए उपयोग किया जाता है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको मान "अपरिभाषित" मिलेंगे।

विरासत सहित प्रभावी स्वरूपण पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](../iportionformat/geteffective) मेथड का उपयोग करना होगा जो एक [`IPortionFormatEffectiveData`](../iportionformateffectivedata) इंस्टेंस लौटाता है।

### देखें

* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->