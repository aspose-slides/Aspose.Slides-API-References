---
title: BasePortionFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: सामान्य पाठ भाग स्वरूपण गुण।
type: docs
weight: 970
url: /hi/aspose.slides/baseportionformat/
---
## BasePortionFormat वर्ग

सामान्य पाठ भाग स्वरूपण गुण।

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | वैकल्पिक भाषा का Id लौटाता या सेट करता है। पढ़ें/लिखें String। |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | आधार IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent)। |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata)। |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | East Asian फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata)। |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | पाठ EffectFormat गुण लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat)। |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | सुपरस्क्रिप्ट या सबस्क्रिप्ट पाठ लौटाता या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें/लिखें Single। |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | पाठ FillFormat गुण लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं होती। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | एक भाग की फ़ॉन्ट ऊँचाई लौटाता या सेट करता है। **float.NaN** का अर्थ है ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें/लिखें Single। |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं होती। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | पाठ अंडरलाइन प्रकार लौटाता या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ें/लिखें [`TextUnderlineType`](../textunderlinetype)। |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | पाठ को हाइलाइट करने के लिए उपयोग किया गया रंग लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IColorFormat`](../icolorformat)। |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat गुण हैं या पाठ की FillFormat गुणों से विरासत में लेती है। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat गुण हैं या पाठ की LineFormat गुणों से विरासत में लेती है। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार लौटाता या सेट करता है, जिसके लिए करनिंग चालू हो जाना चाहिए। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें/लिखें Single। |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्याएँ पाठ के पूर्वी भाषा-विशिष्ट लंबवत लेआउट को अनदेखा करें। कोई विरासत लागू नहीं होती। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। वर्तनी और व्याकरण जांच के लिए उपयोग किया जाता है। पढ़ें/लिखें String। |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | लैटिन फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata)। |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | पाठ आउटलाइन के लिए LineFormat गुण लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि पाठ की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं होती। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि पाठ को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं होती। पढ़ें/लिखें [`NullableBool`](../nullablebool)। |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | अक्षरांतर स्पेसिंग वृद्धि लौटाता या सेट करता है। **float.NaN** का अर्थ है मान अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें/लिखें Single। |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | टेक्स्ट भाग के लिए वर्तनी जांच सक्षम है या नहीं को दर्शाता है। जब यह गुण false पर सेट किया जाता है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दबा दी जाती है। जब true पर सेट किया जाता है, तो वर्तनी जाँच की अनुमति मिलती है। डिफ़ॉल्ट मान `false` है। |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | पाठ के स्ट्राइकथ्रू प्रकार लौटाता या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ें/लिखें [`TextStrikethroughType`](../textstrikethroughtype)। |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata)। |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | पाठ के कैपिटलाइज़ेशन प्रकार लौटाता या सेट करता है। कोई विरासत लागू नहीं होती। पढ़ें/लिखें [`TextCapType`](../textcaptype)। |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | अंडरलाइन लाइन के FillFormat गुण लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat)। |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए गए LineFormat गुण लौटाता है। कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### देखिए

* वर्ग [PVIObject](../pviobject)
* इंटरफ़ेस [IBasePortionFormat](../ibaseportionformat)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंब्ली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->