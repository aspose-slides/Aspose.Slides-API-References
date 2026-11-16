---
title: IBasePortionFormat
second_title: Aspose.Sildes för .NET API-referens
description: Denna klass innehåller textavsnittsformateringsegenskaper. Till skillnad från IPortionFormatEffectiveData./iportionformateffectivedata är alla egenskaper i denna klass skrivbara.
type: docs
weight: 5330
url: /sv/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat gränssnitt

Denna klass innehåller textavsnittsformateringsegenskaper. Till skillnad från [`IPortionFormatEffectiveData`](../iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

```csharp
public interface IBasePortionFormat
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Returnerar eller anger Id för ett alternativt språk. Läs/skriv String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Returnerar eller anger komplex skript-teckensnittsinfo. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Returnerar eller anger östasiatiskt teckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Returnerar textens EffectFormat-egenskaper. Ingen ärvning tillämpas. Endast läsning [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Returnerar eller anger upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Returnerar textens FillFormat-egenskaper. Ingen ärvning tillämpas. Endast läsning [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Bestämmer om teckensnittet är fetstil. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Returnerar eller anger teckensnittshöjden för ett avsnitt. **float.NaN** betyder att höjden är odefinierad och ska ärvas från Master. Läs/skriv Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Bestämmer om teckensnittet är kursivt. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Returnerar eller anger typen av understrykning för texten. Ingen ärvning tillämpas. Läs/skriv [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Returnerar färgen som används för att markera text. Ingen ärvning tillämpas. Endast läsning [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Bestämmer om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat. Läs/skriv [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Bestämmer om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat. Läs/skriv [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Returnerar eller anger minsta teckensnittsstorlek för vilken kerning ska slås på. **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Bestämmer om siffror ska ignorera språk-specifik vertikal textlayout för östasiatisk text. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Returnerar eller anger Id för ett korrekturlägningsspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Returnerar eller anger latin-teckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Returnerar LineFormat-egenskaper för textkontur. Ingen ärvning tillämpas. Endast läsning [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Bestämmer om textens höjd ska normaliseras. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Bestämmer om texten inte ska korrekturläggas. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Returnerar eller anger avståndet mellan tecken. **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Hämtar eller anger om stavningskontroll är aktiverad för textavsnittet. När egenskapen är falsk undertrycks stavningskontroll för textelement. När den är sann tillåts stavningskontroll. Standardvärdet är `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Returnerar eller anger typ av genomstrykning för en text. Ingen ärvning tillämpas. Läs/skriv [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Returnerar eller anger symbolteckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Returnerar eller anger typ av textkapitalisering. Ingen ärvning tillämpas. Läs/skriv [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Returnerar FillFormat-egenskaper för understrykningens linje. Ingen ärvning tillämpas. Endast läsning [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Returnerar LineFormat-egenskaper som används för att konturera understrykningens linje. Ingen ärvning tillämpas. Endast läsning [`ILineFormat`](../ilineformat). |

### Anmärkningar

Denna klass används för att returnera och manipulera textavsnittsformateringsegenskaper som definierats för det specifika avsnittet. Det betyder att ingen ärvning tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparameter-värdena inklusive ärvda måste du använda [`GetEffective`](../iportionformat/geteffective)-metoden som returnerar en [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-instans.

### Se även

* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->