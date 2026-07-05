---
title: BasePortionFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: सामान्य टेक्स्ट भाग फ़ॉर्मैटिंग गुण।
type: docs
weight: 970
url: /hi/aspose.slides/baseportionformat/
---
## BasePortionFormat क्लास

सामान्य टेक्स्ट भाग फ़ॉर्मैटिंग गुण।

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | वैकल्पिक भाषा का Id लौटाता है या सेट करता है। पढ़ें/लिखें String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का मतलब फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | पूर्वी एशियाई फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का मतलब फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | टेक्स्ट EffectFormat गुण लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट लौटाता है या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **float.NaN** का मतलब मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | टेक्स्ट FillFormat गुण लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत नहीं लागू। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | किसी भाग का फ़ॉन्ट ऊँचाई लौटाता है या सेट करता है। **float.NaN** का मतलब ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत नहीं लागू। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | टेक्स्ट अंडरलाइन प्रकार लौटाता है या सेट करता है। कोई विरासत नहीं लागू। पढ़ें/लिखें [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | टेक्स्ट को हाइलाइट करने के लिए उपयोग किया गया रंग लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली के अपने FillFormat गुण हैं या टेक्स्ट के FillFormat गुणों से विरासत में लेती है। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली के अपने LineFormat गुण हैं या टेक्स्ट के LineFormat गुणों से विरासत में लेती है। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार लौटाता है या सेट करता है, जिसके लिए कर्निंग सक्षम होनी चाहिए। **float.NaN** का मतलब मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्याएँ टेक्स्ट की पूर्वी भाषा-विशिष्ट लंबवत लेआउट को अनदेखा करें। कोई विरासत नहीं लागू। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | प्रूफ़िंग भाषा का Id लौटाता है या सेट करता है। वर्तनी और व्याकरण जांच के लिए उपयोग किया जाता है। पढ़ें/लिखें String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | लैटिन फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का मतलब फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | टेक्स्ट रूपरेखा के लिए LineFormat गुण लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत नहीं लागू। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत नहीं लागू। पढ़ें/लिखें [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | अंतराक्षर अंतराल वृद्धि लौटाता है या सेट करता है। **float.NaN** का मतलब मान अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि टेक्स्ट भाग के लिए वर्तनी जांच सक्षम है या नहीं। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों के लिए वर्तनी जांच दमन होती है। जब true पर सेट होती है, तो वर्तनी जांच की अनुमति होती है। डिफ़ॉल्ट मान `false` है। |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | टेक्स्ट का स्ट्राइकथ्रू प्रकार लौटाता है या सेट करता है। कोई विरासत नहीं लागू। पढ़ें/लिखें [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | सिंबॉलिक फ़ॉन्ट जानकारी लौटाता है या सेट करता है। Null का मतलब फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में लेना चाहिए। पढ़ें/लिखें [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | टेक्स्ट कैपिटलाइज़ेशन प्रकार लौटाता है या सेट करता है। कोई विरासत नहीं लागू। पढ़ें/लिखें [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | अंडरलाइन लाइन FillFormat गुण लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | अंडरलाइन लाइन के रूपरेखा के लिए उपयोग किए जाने वाले LineFormat गुण लौटाता है। कोई विरासत नहीं लागू। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### देखें

* क्लास [PVIObject](../pviobject)
* इंटरफ़ेस [IBasePortionFormat](../ibaseportionformat)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->