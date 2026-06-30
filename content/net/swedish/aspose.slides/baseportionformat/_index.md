---
title: BasePortionFormat
second_title: Aspose.Sildes för .NET API-referens
description: Vanliga egenskaper för textdelens formatering.
type: docs
weight: 950
url: /sv/aspose.slides/baseportionformat/
---
## BasePortionFormat klass

Vanliga textdelformat egenskaper.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Returnerar eller anger Id för ett alternativt språk. Läs/skriv String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Endast läs [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Returnerar eller anger information om komplex skriptfont. Null betyder att fonten är odefinierad och ska ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Returnerar eller anger information om östasiatisk font. Null betyder att fonten är odefinierad och ska ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Returnerar textens EffectFormat-egenskaper. Ingen arv tillämpas. Endast läs [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Returnerar eller anger upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Returnerar textens FillFormat-egenskaper. Ingen arv tillämpas. Endast läs [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Avgör om fonten är fet. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Returnerar eller anger fontens höjd för en del. **float.NaN** betyder att höjden är odefinierad och ska ärvas från Master. Läs/skriv Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Avgör om fonten är kursiv. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Returnerar eller anger textens understrykningstyp. Ingen arv tillämpas. Läs/skriv [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Returnerar färgen som används för att markera text. Ingen arv tillämpas. Endast läs [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Avgör om understrykningsstilen har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Läs/skriv [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Avgör om understrykningsstilen har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Läs/skriv [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Returnerar eller anger minsta fontstorlek för vilken kerning ska aktiveras. **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Avgör om siffrorna ska ignorera vertikal textlayout specifik för östasiatiskt språk. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Returnerar eller anger Id för ett korrekturläsningsspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Returnerar eller anger information om latinsk font. Null betyder att fonten är odefinierad och ska ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Returnerar LineFormat-egenskaper för textkontur. Ingen arv tillämpas. Endast läs [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Avgör om textens höjd ska normaliseras. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Avgör om texten inte ska korrekturläsas. Ingen arv tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Returnerar eller anger ökning av interteckenavstånd. **float.NaN** betyder att värdet är odefinierat och ska ärvas från Master. Läs/skriv Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Hämtar eller anger ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När denna egenskap är falsk undertrycks stavningskontroller för tekstselement. När den är sann är stavningskontroll tillåten. Standardvärdet är `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Returnerar eller anger genomstrykningstyp för en text. Ingen arv tillämpas. Läs/skriv [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Returnerar eller anger information om symbolisk font. Null betyder att fonten är odefinierad och ska ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Returnerar eller anger typ av textkapitalisering. Ingen arv tillämpas. Läs/skriv [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Returnerar understrykningslinjens FillFormat-egenskaper. Ingen arv tillämpas. Endast läs [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Returnerar LineFormat-egenskaper som används för att konturera understrykningslinjen. Ingen arv tillämpas. Endast läs [`ILineFormat`](../ilineformat). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Jämför med specificerat objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returnerar hashkod. |

### Se också

* klass [PVIObject](../pviobject)
* gränssnitt [IBasePortionFormat](../ibaseportionformat)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->