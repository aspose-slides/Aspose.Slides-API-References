---
title: IBasePortionFormat
second_title: Aspose.Sildes för .NET API-referens
description: Denna klass innehåller formateringsegenskaper för textdelar. Till skillnad från IPortionFormatEffectiveData./iportionformateffectivedata är alla egenskaper i denna klass skrivbara.
type: docs
weight: 5310
url: /sv/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat gränssnitt

Denna klass innehåller formateringsegenskaper för textdelar. Till skillnad från [`IPortionFormatEffectiveData`](../iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

```csharp
public interface IBasePortionFormat
```

## Egenskaper

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Returnerar eller anger Id för ett alternativt språk. Läs/skriv String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Returnerar eller anger information om teckensnitt för komplexa skript. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Returnerar eller anger information om teckensnitt för Östasiatiskt språk. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Returnerar textens EffectFormat-egenskaper. Ingen arv tillämpas. Endast läs [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Returnerar eller anger upphöjd eller nedsänkt text. Värde från -100% (nedsänkt) till 100% (upphöjd). **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Returnerar textens FillFormat-egenskaper. Ingen arv tillämpas. Endast läs [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Bestämmer om teckensnittet är fetstil. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Returnerar eller anger teckensnittshöjden för en del. **float.NaN** betyder att höjden är odefinierad och bör ärvas från Master. Läs/skriv Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Bestämmer om teckensnittet är kursivt. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Returnerar eller anger understrykningstyp för text. Ingen arv tillämpas. Läs/skriv [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Returnerar färgen som används för att markera text. Ingen arv tillämpas. Endast läs [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Bestämmer om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Läs/skriv [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Bestämmer om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Läs/skriv [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska slås på. **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Bestämmer om siffrorna ska ignorera vertikal textlayout för östasiatiskt språk. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Returnerar eller anger Id för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Returnerar eller anger information om teckensnitt för latinska språk. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Returnerar LineFormat-egenskaper för textkontur. Ingen arv tillämpas. Endast läs [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Bestämmer om textens höjd ska normaliseras. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Bestämmer om texten inte ska korrekturläsas. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Returnerar eller anger interteckenavståndsökning. **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Hämtar eller anger ett värde som visar om stavningskontroll är aktiverad för textdelen. När denna egenskap är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Returnerar eller anger genomstrykningstyp för text. Ingen arv tillämpas. Läs/skriv [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Returnerar eller anger information om symboliskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Returnerar eller anger typ av textversalisering. Ingen arv tillämpas. Läs/skriv [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Returnerar FillFormat-egenskaper för understrykningens linje. Ingen arv tillämpas. Endast läs [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Returnerar LineFormat-egenskaper som används för att konturera understrykningens linje. Ingen arv tillämpas. Endast läs [`ILineFormat`](../ilineformat). |

### Anmärkningar

Denna klass används för att returnera och manipulera formateringsegenskaper för textdelar som är definierade för den specifika delen. Detta innebär att ingen arv tillämpas vid hämtning av värden, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparameter-värdena inklusive ärvda måste du använda [`GetEffective`](../iportionformat/geteffective)-metoden som returnerar en [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-instans.

### Se även

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->