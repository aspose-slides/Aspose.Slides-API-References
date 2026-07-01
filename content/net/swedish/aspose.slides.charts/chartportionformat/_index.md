---
title: ChartPortionFormat
second_title: Aspose.Sildes för .NET API-referens
description: Denna klass innehåller formateringsegenskaper för diagramdelar som används i diagram. Till skillnad från IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata är alla egenskaper i denna klass skrivbara.
type: docs
weight: 1410
url: /sv/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat klass

Denna klass innehåller formateringsegenskaper för diagramdelar som används i diagram. Till skillnad från [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Egenskaper

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Returnerar eller anger Id för ett alternativt språk. Läs/skriv String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Gör det möjligt att hämta bas-interface IPresentationComponent. Endast läs [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Returnerar eller anger information om komplex skriptfont. Null betyder att fonten är odefinierad och bör ärvas från Master. Läs/skriv [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Returnerar eller anger information om östasiatisk font. Null betyder att fonten är odefinierad och bör ärvas från Master. Läs/skriv [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Returnerar textens EffectFormat-egenskaper. Ingen arv tillämpas. Endast läs [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Returnerar eller anger upphöjd eller nedsänkt text. Värde från –100 % (nedsänkt) till 100 % (upphöjd). **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Returnerar textens FillFormat-egenskaper. Ingen arv tillämpas. Endast läs [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestämmer om teckensnittet är fetstil. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Returnerar eller anger höjden på en del. **float.NaN** betyder att höjden är odefinierad och bör ärvas från Master. Läs/skriv Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestämmer om teckensnittet är kursiv. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Returnerar eller anger typ av understrykning. Ingen arv tillämpas. Läs/skriv [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Returnerar färgen som används för att markera text. Ingen arv tillämpas. Endast läs [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestämmer om understrykningens stil har egna FillFormat-egenskaper eller ärver dem från textens FillFormat. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestämmer om understrykningens stil har egna LineFormat-egenskaper eller ärver dem från textens LineFormat. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Returnerar eller anger minimal teckensnittsstorlek där kerning ska slås på. **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestämmer om siffror ska ignorera textens specifika vertikala layout för östasiatiskt språk. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Returnerar eller anger Id för ett korrekturläsningsspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Returnerar eller anger information om latinsk font. Null betyder att fonten är odefinierad och bör ärvas från Master. Läs/skriv [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Returnerar LineFormat-egenskaper för textens kontur. Ingen arv tillämpas. Endast läs [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestämmer om textens höjd ska normaliseras. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestämmer om texten inte ska korrekturläsas. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Returnerar eller anger ökningen av mellanslag mellan tecken. **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Anger om stavningskontroll är aktiverad för textdelen. När egenskapen är falsk undertrycks stavningskontroller för textelement. När den är sann tillåts stavningskontroll. Standardvärde är `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Returnerar eller anger typ av genomstrykning för text. Ingen arv tillämpas. Läs/skriv [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Returnerar eller anger information om symbolisk font. Null betyder att fonten är odefinierad och bör ärvas från Master. Läs/skriv [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Returnerar eller anger typ av textkapitalisering. Ingen arv tillämpas. Läs/skriv [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Returnerar FillFormat-egenskaper för understrykningens linje. Ingen arv tillämpas. Endast läs [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Returnerar LineFormat-egenskaper som används för att konturera understrykningens linje. Ingen arv tillämpas. Endast läs [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metoder

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Jämför med specificerat objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returnerar hashkod. |

### Anmärkningar

Denna klass används för att returnera och manipulera formateringsegenskaper för en specifik textdel. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [`GetEffective`](../../aspose.slides/portionformat/geteffective)-metoden som returnerar en [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-instans.

### Se även

* klass [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->