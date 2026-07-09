---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: ऐसे अपरिवर्तनीय वस्तुओं के लिए आधार इंटरफ़ेस जो प्रभावी टेक्स्ट भाग फॉर्मेटिंग गुणों को शामिल करते हैं।
type: docs
weight: 5320
url: /hi/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData इंटरफ़ेस

अपरिवर्तनीय ऑब्जेक्ट्स के लिए बेस इंटरफ़ेस जो प्रभावी टेक्स्ट भाग फॉर्मेटिंग प्रॉपर्टीज़ को शामिल करते हैं।

```csharp
public interface IBasePortionFormatEffectiveData
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | वैकल्पिक भाषा की Id लौटाता है। केवल-पढ़ने योग्य String। |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [`IFontData`](../ifontdata)। |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [`IFontData`](../ifontdata)। |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | टेक्स्ट EffectFormat गुण लौटाता है। केवल-पढ़ने योग्य [`IEffectFormatEffectiveData`](../ieffectformateffectivedata)। |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट लौटाता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। केवल-पढ़ने योग्य Single। |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | टेक्स्ट FillFormat गुण लौटाता है। केवल-पढ़ने योग्य [`IFillFormatEffectiveData`](../ifillformateffectivedata)। |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | टेक्स्ट भाग की फ़ॉन्ट ऊँचाई, पॉइंट्स में लौटाता है। केवल-पढ़ने योग्य Single। |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। केवल-पढ़ने योग्य Boolean। |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | टेक्स्ट अंडरलाइन प्रकार लौटाता है। केवल-पढ़ने योग्य [`TextUnderlineType`](../textunderlinetype)। |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | टेक्स्ट को हाइलाइट करने के लिए उपयोग किया गया रंग लौटाता है। केवल-पढ़ने योग्य Color। |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat गुण हैं या यह टेक्स्ट की FillFormat गुणों से विरासत में मिलती है। केवल-पढ़ने योग्य Boolean। |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat गुण हैं या यह टेक्स्ट की LineFormat गुणों से विरासत में मिलती है। केवल-पढ़ने योग्य Boolean। |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए करनिंग चालू होनी चाहिए। केवल-पढ़ने योग्य Single। |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | निर्धारित करता है कि संख्याओं को टेक्स्ट की पूर्वी भाषा-विशिष्ट लंबवत लेआउट को नजरअंदाज़ करना चाहिए या नहीं। केवल-पढ़ने योग्य Boolean। |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | भाषा की Id लौटाता है। केवल-पढ़ने योग्य String। |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | लैटिन फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [`IFontData`](../ifontdata)। |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | टेक्स्ट आउटलाइनिंग के लिए LineFormat गुण लौटाता है। केवल-पढ़ने योग्य [`ILineFormatEffectiveData`](../ilineformateffectivedata)। |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत किया जाना चाहिए या नहीं। केवल-पढ़ने योग्य Boolean। |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए। केवल-पढ़ने योग्य Boolean। |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए। केवल-पढ़ने योग्य Boolean। |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | वर्णों के बीच अंतराल वृद्धि पॉइंट्स में लौटाता है। केवल-पढ़ने योग्य Single। |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | टेक्स्ट का स्ट्राइकथ्रू प्रकार लौटाता है। केवल-पढ़ने योग्य [`TextStrikethroughType`](../textstrikethroughtype)। |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | सिंबॉलिक फ़ॉन्ट जानकारी लौटाता है। केवल-पढ़ने योग्य [`IFontData`](../ifontdata)। |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | टेक्स्ट कैपिटलाइज़ेशन प्रकार लौटाता है। केवल-पढ़ने योग्य [`TextCapType`](../textcaptype)। |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | अंडरलाइन लाइन FillFormat गुण लौटाता है। केवल-पढ़ने योग्य [`IFillFormatEffectiveData`](../ifillformateffectivedata)। |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग किए गए LineFormat गुण लौटाता है। केवल-पढ़ने योग्य [`ILineFormatEffectiveData`](../ilineformateffectivedata)। |

### संबंधित देखें

* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->