---
title: ChartPortionFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: यह क्लास चार्ट में उपयोग किए जाने वाले चार्ट पोर्शन फ़ॉर्मेटिंग प्रॉपर्टीज़ को रखती है। IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।
type: docs
weight: 1430
url: /hi/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat क्लास

यह क्लास चार्ट में उपयोग किए जाने वाले चार्ट पोर्शन फ़ॉर्मेटिंग प्रॉपर्टीज़ को रखती है। [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | किसी वैकल्पिक भाषा का Id लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String। |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent)। |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का मतलब है फ़ॉन्ट अनिर्धारित है और मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../../aspose.slides/ifontdata)। |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | पूर्वी एशियाई फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का मतलब है फ़ॉन्ट अनिर्धारित है और मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../../aspose.slides/ifontdata)। |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | टेक्स्ट EffectFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IEffectFormat`](../../aspose.slides/ieffectformat)। |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | ऊपर-या-नीचे-लिखित टेक्स्ट लौटाता है या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **float.NaN** का मतलब है मान अनिर्धारित है और मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य Single। |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | टेक्स्ट FillFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat)। |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं होती। पढ़ने/लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool)। |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | एक पोर्शन की फ़ॉन्ट ऊँचाई लौटाता है या सेट करता है। **float.NaN** का मतलब है ऊँचाई अनिर्धारित है और मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य Single। |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | निर्धारित करता है कि फ़ॉन्ट इटालिक है या नहीं। कोई विरासत लागू नहीं होती। पढ़ने/लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool)। |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | टेक्स्ट अंडरलाइन प्रकार लौटाता है या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ने/लिखने योग्य [`TextUnderlineType`](../../aspose.slides/textunderlinetype)। |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | टेक्स्ट को हाईलाइट करने के लिए उपयोग किए जाने वाले रंग को लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IColorFormat`](../../aspose.slides/icolorformat)। |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में प्राप्त करती है। पढ़ने/लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool)। |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में प्राप्त करती है। पढ़ने/लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool)। |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार लौटाता है या सेट करता है, जिसके लिए करनिंग चालू किया जाना चाहिए। **float.NaN** का मतलब है मान अनिर्धारित है और मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य Single। |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को नज़रअंदाज़ करें। कोई विरासत लागू नहीं होती। पढ़ने/लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool)। |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। वर्तनी और व्याकरण की जाँच के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String। |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | लैटिन फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का मतलब है फ़ॉन्ट अनिर्धारित है और मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../../aspose.slides/ifontdata)। |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | टेक्स्ट आउटलाइनिंग के लिए LineFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat)। |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं होती। पढ़ने/लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool)। |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं होती। पढ़ने/लिखने योग्य [`NullableBool`](../../aspose.slides/nullablebool)। |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | अंतर-चरित्र स्पेसिंग वृद्धि लौटाता है या सेट करता है। **float.NaN** का मतलब है मान अनिर्धारित है और मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य Single। |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | टेक्स्ट पोर्शन के लिए स्पेल-चेकिंग सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों के लिए स्पेलिंग जाँच दमन की जाती है। जब true पर सेट होती है, तो स्पेल-चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान `false` है। |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | टेक्स्ट के स्ट्राइकथ्रू प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ने/लिखने योग्य [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype)। |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का मतलब है फ़ॉन्ट अनिर्धारित है और मास्टर से विरासत में प्राप्त होना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../../aspose.slides/ifontdata)। |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | टेक्स्ट कैपिटलाइज़ेशन के प्रकार को लौटाता है या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ने/लिखने योग्य [`TextCapType`](../../aspose.slides/textcaptype)। |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | अंडरलाइन लाइन FillFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IFillFormat`](../../aspose.slides/ifillformat)। |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए जाने वाले LineFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`ILineFormat`](../../aspose.slides/ilineformat)। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट वस्तु से तुलना करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### टिप्पणियाँ

इस क्लास का उपयोग विशिष्ट पोर्शन के लिए परिभाषित टेक्स्ट पोर्शन फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और संशोधित करने के लिए किया जाता है। इसका अर्थ है कि मान प्राप्त करने पर कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "अनिर्धारित" मान मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](../../aspose.slides/portionformat/geteffective) मेथड का उपयोग करना होगा जो एक [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) इंस्टेंस लौटाता है।

### देखें

* क्लास [BasePortionFormat](../../aspose.slides/baseportionformat)
* इंटरफ़ेस [IChartPortionFormat](../ichartportionformat)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->