---
title: PortionFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: यह क्लास टेक्स्ट भाग फ़ॉर्मेटिंग गुणों को रखती है। IPortionFormatEffectiveData./iportionformateffectivedata के विपरीत, इस क्लास की सभी गुण लिखने योग्य हैं।
type: docs
weight: 9490
url: /hi/aspose.slides/portionformat/
---
## PortionFormat क्लास

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [PortionFormat](portionformat)() | एक नया उदाहरण [`PortionFormat`](../portionformat) क्लास का आरंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | वैकल्पिक भाषा की Id लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | आधारभूत IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | बुकमार्क पहचानकर्ता लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | ईस्ट एशियन फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | टेक्स्ट EffectFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | सुपरस्क्रिप्ट या सबस्क्रिप्ट टेक्स्ट लौटाता या सेट करता है। मान -100% (सबस्क्रिप्ट) से 100% (सुपरस्क्रिप्ट) तक। **float.NaN** का अर्थ मान अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने/लिखने योग्य Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | टेक्स्ट FillFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | फ़ॉन्ट बोल्ड है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | एक भाग की फ़ॉन्ट ऊँचाई लौटाता या सेट करता है। **float.NaN** का अर्थ ऊँचाई अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने/लिखने योग्य Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | फ़ॉन्ट इटैलिक है या नहीं निर्धारित करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | टेक्स्ट अंडरलाइन प्रकार लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | टेक्स्ट को हाइलाइट करने के लिए उपयोग किया गया रंग लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | हाइपरलिंक प्रबंधक। केवल-पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली के अपने FillFormat गुण हैं या टेक्स्ट के FillFormat गुणों से विरासत में मिलते हैं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली के अपने LineFormat गुण हैं या टेक्स्ट के LineFormat गुणों से विरासत में मिलते हैं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार लौटाता या सेट करता है, जिसके लिए केरनिंग चालू होना चाहिए। **float.NaN** का अर्थ मान अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने/लिखने योग्य Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट वर्टिकल लेआउट को नज़रअंदाज़ करें। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | प्रूफ़िंग भाषा की Id लौटाता या सेट करता है। वर्तनी और व्याकरण जाँच के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | लैटिन फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | टेक्स्ट आउटलाइनिंग के लिए LineFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि टेक्स्ट की ऊँचाई सामान्यीकृत होनी चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि टेक्स्ट को प्रूफ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | निर्धारित करता है कि स्मार्ट टैग साफ किया जाना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | अंतर-अक्षर अंतराल वृद्धि लौटाता या सेट करता है। **float.NaN** का अर्थ मान अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने/लिखने योग्य Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | टेक्स्ट हिस्से के लिए वर्तनी जाँच सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दमन की जाती है। जब true पर सेट होती है, तो वर्तनी जाँच की अनुमति होती है। डिफ़ॉल्ट मान `false` है। |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | टेक्स्ट की स्ट्राइकथ्रू प्रकार लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | सिंबॉलिक फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ फ़ॉन्ट अपरिभाषित है और इसे मास्टर से विरासत में मिला होना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | टेक्स्ट कैपिटलाइज़ेशन प्रकार लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | अंडरलाइन लाइन FillFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग की गई LineFormat गुण लौटाता है। कोई विरासत लागू नहीं। केवल-पढ़ने योग्य [`ILineFormat`](../ilineformat). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | विरासत लागू किए गए प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### टिप्पणी

यह क्लास किसी विशेष भाग के लिए परिभाषित टेक्स्ट हिस्से के फ़ॉर्मेटिंग गुणों को लौटाने और संपादित करने के लिए उपयोग की जाती है। इसका मतलब है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको "undefined" अर्थ वाले मान मिलेंगे।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](./geteffective) मेथड का उपयोग करना चाहिए जो एक [`IPortionFormatEffectiveData`](../iportionformateffectivedata) इंस्टेंस लौटाता है।

### उदाहरण

निम्नलिखित उदाहरण दिखाते हैं कि कैसे PowerPoint प्रस्तुति के Paragraph के हिस्से को लैटिन फ़ॉन्ट सौंपा जा सकता है।

```csharp
[C#]
//एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाले प्रस्तुति ऑब्जेक्ट को इंस्टैंसिएट करें
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides इन विशेष पहचानकर्ताओं का उपयोग करता है (PowerPoint में उपयोग किए जाने वाले के समान):
// +mn-lt - बॉडी फ़ॉन्ट लैटिन (माइनर लैटिन फ़ॉन्ट)
// +mj-lt -हेडिंग फ़ॉन्ट लैटिन (मेजर लैटिन फ़ॉन्ट)
// +mn-ea - बॉडी फ़ॉन्ट ईस्ट एशियन (माइनर ईस्ट एशियन फ़ॉन्ट)
// +mj-ea - बॉडी फ़ॉन्ट ईस्ट एशियन (माइनर ईस्ट एशियन फ़ॉन्ट)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### संबंधित देखें

* क्लास [BasePortionFormat](../baseportionformat)
* इंटरफ़ेस [IPortionFormat](../iportionformat)
* नामस्थान [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->