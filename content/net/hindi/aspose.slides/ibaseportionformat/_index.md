---
title: IBasePortionFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: यह क्लास टेक्स्ट भाग स्वरूपण गुणों को सम्मिलित करती है। IPortionFormatEffectiveData./iportionformateffectivedata के विपरीत, इस क्लास की सभी गुण लिखने योग्य हैं।
type: docs
weight: 5310
url: /hi/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat इंटरफ़ेस

यह क्लास टेक्स्ट भाग स्वरूपण गुणों को सम्मिलित करती है। [`IPortionFormatEffectiveData`](../iportionformateffectivedata) के विपरीत, इस क्लास की सभी गुण लिखने योग्य हैं।

```csharp
public interface IBasePortionFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | वैकल्पिक भाषा का Id लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | पूरबी एशियाई फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | टेक्स्ट EffectFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | उपश्रेणी या अधिश्रेणी टेक्स्ट लौटाता है या सेट करता है। मान -100% (subscript) से 100% (superscript) तक। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | टेक्स्ट FillFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | एक भाग की फ़ॉन्ट ऊँचाई लौटाता है या सेट करता है। **float.NaN** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | टेक्स्ट अंडरलाइन प्रकार लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | टेक्स्ट को हाइलाइट करने के लिए उपयोग किया गया रंग लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat गुण हैं या यह टेक्स्ट की FillFormat गुणों से विरासत में लेती है। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat गुण हैं या यह टेक्स्ट की LineFormat गुणों से विरासत में लेती है। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार लौटाता है या सेट करता है, जिसके लिए कर्निंग चालू होना चाहिए। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्या को टेक्स्ट के पूर्वी भाषा-विशिष्ट वैर्टिकल लेआउट को अनदेखा करना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। वर्तनी और व्याकरण जांच के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | लैटिन फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | टेक्स्ट आउटलाइनिंग के लिए LineFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | अंतर अक्षर स्पेसिंग वृद्धि लौटाता है या सेट करता है। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | एक मान प्राप्त या सेट करता है जो यह दर्शाता है कि टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों के लिए वर्तनी जांच दमन किया जाता है। जब true पर सेट होती है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान `false` है। |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | टेक्स्ट बड़े अक्षर स्वरूप प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | अंडरलाइन लाइन FillFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | अंडरलाइन लाइन के आउटलाइन के लिए उपयोग किए गए LineFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |

### टिप्पणी

यह क्लास विशेष भाग के लिए परिभाषित टेक्स्ट भाग स्वरूपण गुणों को लौटाने और परिवर्तित करने के लिए उपयोग होती है। इसका अर्थ है कि मान प्राप्त करने पर कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अपरिभाषित" जिसका अर्थ है "undefined" मान मिलेगा।

विरासत सहित प्रभावी स्वरूपण पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](../iportionformat/geteffective) विधि का उपयोग करना होगा जो एक [`IPortionFormatEffectiveData`](../iportionformateffectivedata) इंस्टेंस लौटाती है।

### देखें

* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंब्ली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->