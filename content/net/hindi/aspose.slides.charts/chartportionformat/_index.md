---
title: ChartPortionFormat
second_title: Aspose.Sildes .NET API संदर्भ के लिए
description: यह वर्ग चार्ट में उपयोग की जाने वाली चार्ट भाग स्वरूपण गुणधर्मों को समेटे हुए है। IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata के विपरीत, इस वर्ग की सभी गुणधर्म लिखने योग्य हैं।
type: docs
weight: 1440
url: /hi/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat वर्ग

यह वर्ग चार्ट में उपयोग किए जाने वाले चार्ट भाग स्वरूपण गुणधर्मों को समेटे हुए है। [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) के विपरीत, इस वर्ग की सभी गुणधर्म लिखने योग्य हैं।

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | वैकल्पिक भाषा की Id को लौटाता है या सेट करता है। पढ़ने-और-लिखने योग्य String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | आधार IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने-और-लिखने योग्य [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | East Asian फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने-और-लिखने योग्य [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | पाठ EffectFormat गुणधर्मों को लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | उपर-लेख या अधो-लेख पाठ को लौटाता है या सेट करता है। मान -100% (अधो-लेख) से 100% (उपर-लेख) तक होता है। **float.NaN** का अर्थ मान अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने-और-लिखने योग्य Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | पाठ FillFormat गुणधर्मों को लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं होती। पढ़ने-और-लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | किसी भाग के फ़ॉन्ट की ऊँचाई को लौटाता है या सेट करता है। **float.NaN** का अर्थ ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने-और-लिखने योग्य Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | निर्धारित करता है कि फ़ॉन्ट itallic है या नहीं। कोई विरासत लागू नहीं होती। पढ़ने-और-लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | पाठ अंडरलाइन प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ने-और-लिखने योग्य [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | पाठ को हाइलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली के अपने FillFormat गुणधर्म हैं या यह पाठ के FillFormat गुणधर्मों से विरासत में मिलता है। पढ़ने-और-लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली के अपने LineFormat गुणधर्म हैं या यह पाठ के LineFormat गुणधर्मों से विरासत में मिलता है। पढ़ने-और-लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार को लौटाता है या सेट करता है, जिसके लिए करनिंग चालू होनी चाहिए। **float.NaN** का अर्थ मान अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने-और-लिखने योग्य Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्याएँ पाठ के पूर्वी भाषा-विशिष्ट लंबवत लेआउट को नज़रअंदाज़ करें। कोई विरासत लागू नहीं होती। पढ़ने-और-लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | प्रूफ़िंग भाषा की Id को लौटाता है या सेट करता है। वर्तनी और व्याकरण जाँचने के लिए उपयोग किया जाता है। पढ़ने-और-लिखने योग्य String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Latin फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने-और-लिखने योग्य [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | पाठ के आउटलाइनिंग के लिए LineFormat गुणधर्मों को लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि पाठ की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत लागू नहीं होती। पढ़ने-और-लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि पाठ को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं होती। पढ़ने-और-लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | अक्षर-के-बिच के अंतराल वृद्धि को लौटाता है या सेट करता है। **float.NaN** का अर्थ मान अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने-और-लिखने योग्य Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | पाठ भाग के लिए वर्तनी जाँच सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। जब यह गुण false पर सेट किया जाता है, तो पाठ तत्वों के लिए वर्तनी जाँच दमन की जाती है। जब true पर सेट किया जाता है, तो वर्तनी जाँच अनुमति देती है। डिफ़ॉल्ट मान `false` है। |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | पाठ की स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ने-और-लिखने योग्य [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | प्रतीकात्मक फ़ॉन्ट जानकारी को लौटाता है या सेट करता है। Null का अर्थ फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने-और-लिखने योग्य [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | पाठ के कैपिटलाइज़ेशन प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ने-और-लिखने योग्य [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | अंडरलाइन लाइन के FillFormat गुणधर्मों को लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | अंडरलाइन लाइन के आउटलाइनिंग के लिए उपयोग किए जाने वाले LineFormat गुणधर्मों को लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### टिप्पणी

यह वर्ग विशेष भाग के लिए परिभाषित पाठ भाग स्वरूपण गुणधर्मों को लौटाने और परिवर्तित करने के लिए उपयोग किया जाता है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अपरिभाषित" मान प्राप्त होंगे।

विरासत सहित प्रभावी स्वरूपण पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](../../aspose.slides/portionformat/geteffective) मेथड का उपयोग करना होगा जो एक [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) इंस्टेंस लौटाता है।

### अन्य देखें

* वर्ग [BasePortionFormat](../../aspose.slides/baseportionformat)
* इंटरफ़ेस [IChartPortionFormat](../ichartportionformat)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->