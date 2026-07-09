---
title: ChartPortionFormat
second_title: Aspose.Sildes för .NET API-referens
description: Denna klass innehåller formateringsegenskaper för diagramdelar som används i diagram. Till skillnad från IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata är alla egenskaper i den här klassen skrivbara.
type: docs
weight: 1430
url: /sv/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat klass

Denna klass innehåller formateringsegenskaper för diagramdelar som används i diagram. Till skillnad från [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Returnerar eller anger Id för ett alternativt språk. Läs/skriv String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Skrivskyddad [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Returnerar eller anger information om komplexa skriptfonter. Null betyder att fonten är odefinierad och ska ärvas från Master. Läs/skriv [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Returnerar eller anger information om östasiatiska fonter. Null betyder att fonten är odefinierad och ska ärvas från Master. Läs/skriv [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Returnerar textens EffectFormat-egenskaper. Ingen arv tillämpas. Skrivskyddad [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Returnerar eller anger text som är upphöjd eller nedsänkt. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Returnerar textens FillFormat-egenskaper. Ingen arv tillämpas. Skrivskyddad [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestämmer om fonten är fet. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Returnerar eller anger fontens höjd för en del. **float.NaN** betyder att höjden är odefinierad och ska ärvas från Master. Läs/skriv Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestämmer om fonten är kursiv. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Returnerar eller anger typ av understrykning för text. Ingen arv tillämpas. Läs/skriv [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Returnerar färgen som används för att markera en text. Ingen arv tillämpas. Skrivskyddad [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestämmer om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestämmer om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Returnerar eller anger minimal fontstorlek för vilken kerning ska slås på. **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestämmer om siffrorna ska ignorera den specifika vertikala textlayouten för östasiatiskt språk. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Returnerar eller anger Id för ett korrekturspråk. Används för rättstavnings- och grammatikkontroll. Läs/skriv String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Returnerar eller anger information om latinska fonter. Null betyder att fonten är odefinierad och ska ärvas från Master. Läs/skriv [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Returnerar LineFormat-egenskaper för textkontur. Ingen arv tillämpas. Skrivskyddad [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestämmer om textens höjd ska normaliseras. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestämmer om texten inte ska korrekturläsas. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Returnerar eller anger ökning av interteckenavstånd. **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Hämtar eller anger ett värde som visar om stavningskontroll är aktiverad för textdelen. När denna egenskap är inställd på false, undertrycks stavningskontroller för textelement. När den är inställd på true, tillåts stavningskontroll. Standardvärdet är `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Returnerar eller anger typ av genomstrykning för en text. Ingen arv tillämpas. Läs/skriv [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Returnerar eller anger information om symboliska fonter. Null betyder att fonten är odefinierad och ska ärvas från Master. Läs/skriv [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Returnerar eller anger typ av textversalisering. Ingen arv tillämpas. Läs/skriv [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Returnerar FillFormat-egenskaper för understrykningens linje. Ingen arv tillämpas. Skrivskyddad [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Returnerar LineFormat-egenskaper som används för att konturera understrykningens linje. Ingen arv tillämpas. Skrivskyddad [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Jämför med specificerat objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returnerar hash-kod. |

### Anmärkningar

Denna klass används för att returnera och manipulera formateringsegenskaper för en textdel som definierats för den specifika delen. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [`GetEffective`](../../aspose.slides/portionformat/geteffective)-metoden som returnerar en [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-instans.

### Se även

* klass [BasePortionFormat](../../aspose.slides/baseportionformat)
* gränssnitt [IChartPortionFormat](../ichartportionformat)
* namnutrymme [Aspose.Slides.Charts](../../aspose.slides.charts)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->