---
title: PortionFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: यह क्लास टेक्स्ट भाग फ़ॉर्मेटिंग प्रॉपर्टीज़ को शामिल करती है। IPortionFormatEffectiveData./iportionformateffectivedata के विपरीत, इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।
type: docs
weight: 9490
url: /hi/aspose.slides/portionformat/
---
## PortionFormat क्लास

यह क्लास टेक्स्ट भाग फ़ॉर्मेटिंग प्रॉपर्टीज़ को शामिल करती है। इसके विपरीत [`IPortionFormatEffectiveData`](../iportionformateffectivedata), इस क्लास की सभी प्रॉपर्टीज़ लिखने योग्य हैं।

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## कन्स्ट्रक्टर

| नाम | विवरण |
| --- | --- |
| [PortionFormat](portionformat)() | एक नया उदाहरण इनिशियलाइज़ करता है [`PortionFormat`](../portionformat) क्लास का। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | वैकल्पिक भाषा का Id लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | बुकमार्क पहचानकर्ता लौटाता या सेट करता है। पढ़ने/लिखने योग्य String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | जटिल स्क्रिप्ट फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | East Asian फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | टेक्स्ट EffectFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं हुई। केवल पढ़ने योग्य [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | सुपर्स्क्रिप्ट या उपस्क्रिप्ट टेक्स्ट लौटाता या सेट करता है। मान -100% (उपस्क्रिप्ट) से 100% (सुपर्स्क्रिप्ट) तक। **float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ने/लिखने योग्य Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | टेक्स्ट FillFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं हुई। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | निर्धारित करता है कि फ़ॉन्ट बोल्ड है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | भाग की फ़ॉन्ट ऊँचाई लौटाता या सेट करता है। **float.NaN** का अर्थ है ऊँचाई अनिर्धारित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ने/लिखने योग्य Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | निर्धारित करता है कि फ़ॉन्ट इटैलिक है या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | टेक्स्ट अंडरलाइन प्रकार लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | टेक्स्ट को हाईलाइट करने के लिए उपयोग किए गए रंग को लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | हाइपरलिंक मैनेजर। केवल पढ़ने योग्य [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी FillFormat प्रॉपर्टीज़ हैं या टेक्स्ट की FillFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | निर्धारित करता है कि अंडरलाइन शैली की अपनी LineFormat प्रॉपर्टीज़ हैं या टेक्स्ट की LineFormat प्रॉपर्टीज़ से विरासत में मिलती हैं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | न्यूनतम फ़ॉन्ट आकार लौटाता या सेट करता है, जिसके लिए करनिंग सक्रिय होनी चाहिए। **float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ने/लिखने योग्य Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | निर्धारित करता है कि संख्याएँ टेक्स्ट के पूर्वी भाषा-विशिष्ट ऊर्ध्वाधर लेआउट को अनदेखा करें या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | प्रूफ़िंग भाषा का Id लौटाता या सेट करता है। वर्तनी और व्याकरण जाँचने के लिए उपयोग किया जाता है। पढ़ने/लिखने योग्य String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | लैटिन फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | टेक्स्ट आउटलाइनिंग के लिए LineFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | निर्धारित करता है कि टेक्स्ट की ऊँचाई को सामान्यीकृत करना चाहिए या नहीं। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | निर्धारित करता है कि टेक्स्ट को प्रूफ़ नहीं किया जाना चाहिए। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | निर्धारित करता है कि स्मार्ट टैग को साफ़ किया जाना चाहिए। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | अंतराक्षर स्पेसिंग वृद्धि लौटाता या सेट करता है। **float.NaN** का अर्थ है मान अनिर्धारित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ने/लिखने योग्य Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | टेक्स्ट भाग के लिए वर्तनी जांच सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त या सेट करता है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों की वर्तनी जांच दमन कर दी जाती है। जब true पर सेट होती है, तो वर्तनी जांच अनुमति होती है। डिफ़ॉल्ट मान `false` है। |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | टेक्स्ट के स्ट्राइकथे्रू प्रकार को लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | प्रतीकात्मक फ़ॉन्ट जानकारी लौटाता या सेट करता है। Null का अर्थ है फ़ॉन्ट अनिर्धारित है और इसे मास्टर से विरासत में मिलना चाहिए। पढ़ने/लिखने योग्य [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | टेक्स्ट कैपिटलाइज़ेशन के प्रकार को लौटाता या सेट करता है। कोई विरासत लागू नहीं। पढ़ने/लिखने योग्य [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | अंडरलाइन लाइन की FillFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | अंडरलाइन लाइन को आउटलाइन करने के लिए उपयोग की जाने वाली LineFormat प्रॉपर्टीज़ लौटाता है। कोई विरासत लागू नहीं। केवल पढ़ने योग्य [`ILineFormat`](../ilineformat). |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | विरासत लागू होने के साथ प्रभावी भाग फ़ॉर्मेटिंग डेटा प्राप्त करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### टिप्पणी

यह क्लास विशेष भाग के लिए परिभाषित टेक्स्ट भाग फ़ॉर्मेटिंग प्रॉपर्टीज़ को लौटाने और संशोधित करने के लिए उपयोग की जाती है। इसका अर्थ है कि मान प्राप्त करते समय कोई विरासत लागू नहीं होती, इसलिए अधिकांश मामलों में आपको मान "अनिर्धारित" मिलेगा।

विरासत सहित प्रभावी फ़ॉर्मेटिंग पैरामीटर मान प्राप्त करने के लिए आपको [`GetEffective`](./geteffective) मेथड का उपयोग करना होगा जो एक [`IPortionFormatEffectiveData`](../iportionformateffectivedata) इंस्टेंस लौटाता है।

### उदाहरण

निम्नलिखित उदाहरण दर्शाते हैं कि PowerPoint प्रस्तुति के पैराग्राफ के भाग को लैटिन फ़ॉन्ट कैसे असाइन किया जाए।

```csharp
[C#]
//एक प्रस्तुति फ़ाइल को दर्शाने वाला प्रस्तुति ऑब्जेक्ट बनाएं
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides इन विशेष पहचानकर्ताओं का उपयोग करता है (PowerPoint में उपयोग होने वाले के समान):
// +mn-lt - बॉडी फ़ॉन्ट लैटिन (छोटा लैटिन फ़ॉन्ट)
// +mj-lt - हेडिंग फ़ॉन्ट लैटिन (मुख्य लैटिन फ़ॉन्ट)
// +mn-ea - बॉडी फ़ॉन्ट ईस्ट एशियन (छोटा ईस्ट एशियन फ़ॉन्ट)
// +mj-ea - बॉडी फ़ॉन्ट ईस्ट एशियन (छोटा ईस्ट एशियन फ़ॉन्ट)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### संबंधित

* क्लास [BasePortionFormat](../baseportionformat)
* इंटरफ़ेस [IPortionFormat](../iportionformat)
* नेमस्पेस [Aspose.Slides](../../aspose.slides)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->