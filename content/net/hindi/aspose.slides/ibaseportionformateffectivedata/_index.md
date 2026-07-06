---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: प्रभावी पाठ भाग स्वरूपण गुणों को सम्मिलित करने वाले अपरिवर्तनीय वस्तुओं के लिए आधार इंटरफ़ेस।
type: docs
weight: 5320
url: /hi/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData इंटरफ़ेस

अपरिवर्तनीय वस्तुओं के लिए आधार इंटरफ़ेस जो प्रभावी पाठ भाग स्वरूपण गुणों को सम्मिलित करती हैं।

```csharp
public interface IBasePortionFormatEffectiveData
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | वैकल्पिक भाषा की Id लौटाता है। केवल पढ़ने योग्य String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता है। केवल पढ़ने योग्य [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता है। केवल पढ़ने योग्य [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | पाठ के EffectFormat गुण लौटाता है। केवल पढ़ने योग्य [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | सुपरस्क्रिप्ट या सबस्क्रिप्ट पाठ लौटाता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। केवल पढ़ने योग्य Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | पाठ के FillFormat गुण लौटाता है। केवल पढ़ने योग्य [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। केवल पढ़ने योग्य Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | पाठ भाग की फ़ॉन्ट ऊँचाई (पॉइंट में) लौटाता है। केवल पढ़ने योग्य Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। केवल पढ़ने योग्य Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | पाठ के अंडरलाइन प्रकार लौटाता है। केवल पढ़ने योग्य [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | पाठ को हाइलाइट करने के लिए प्रयुक्त रंग लौटाता है। केवल पढ़ने योग्य Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat गुण हैं या वह पाठ के FillFormat गुणों से विरासत में लेती है। केवल पढ़ने योग्य Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat गुण हैं या वह पाठ के LineFormat गुणों से विरासत में लेती है। केवल पढ़ने योग्य Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | न्यूनतम फ़ॉन्ट आकार लौटाता है, जिसके लिए कर्निंग सक्रिय किया जाना चाहिए। केवल पढ़ने योग्य Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | निर्धारित करता है कि संख्याएँ पाठ की पूर्वी भाषा-विशिष्ट लंबवत लेआउट को नजरअंदाज करें। केवल पढ़ने योग्य Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | भाषा की Id लौटाता है। केवल पढ़ने योग्य String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | लैटिन फ़ॉन्ट जानकारी लौटाता है। केवल पढ़ने योग्य [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | पाठ की रूपरेखा के लिए LineFormat गुण लौटाता है। केवल पढ़ने योग्य [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | निर्धारित करता है कि पाठ की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। केवल पढ़ने योग्य Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | निर्धारित करता है कि पाठ की प्रूफिंग नहीं होनी चाहिए। केवल पढ़ने योग्य Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | निर्धारित करता है कि स्मार्ट टैग को साफ किया जाना चाहिए। केवल पढ़ने योग्य Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | अक्षर-स्पेसिंग वृद्धि (पॉइंट में) लौटाता है। केवल पढ़ने योग्य Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | पाठ के स्ट्राइकथ्रू प्रकार को लौटाता है। केवल पढ़ने योग्य [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता है। केवल पढ़ने योग्य [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | पाठ के कैपिटलाइज़ेशन प्रकार को लौटाता है। केवल पढ़ने योग्य [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | अंडरलाइन रेखा के FillFormat गुण लौटाता है। केवल पढ़ने योग्य [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | अंडरलाइन रेखा की रूपरेखा के लिए प्रयुक्त LineFormat गुण लौटाता है। केवल पढ़ने योग्य [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### संबंधित देखें

* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->