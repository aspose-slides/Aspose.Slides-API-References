---
title: PortionFormat
second_title: Aspose.Sildes för .NET API-referens
description: Denna klass innehåller formateringsegenskaper för textdelar. Till skillnad från IPortionFormatEffectiveData./iportionformateffectivedata är alla egenskaper i denna klass skrivbara.
type: docs
weight: 9490
url: /sv/aspose.slides/portionformat/
---
## PortionFormat klass

Denna klass innehåller egenskaper för formatering av textdelar. Till skillnad från [`IPortionFormatEffectiveData`](../iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktorer

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Initialiserar en ny instans av [`PortionFormat`](../portionformat) klass. |

## Egenskaper

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Returnerar eller anger Id för ett alternativt språk. Läs/skriv String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Endast läsning [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Returnerar eller anger bokmärkets identifierare. Läs/skriv String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Returnerar eller anger information om komplex skript-teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Returnerar eller anger information om Östasiatiskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Returnerar textens EffectFormat-egenskaper. Ingen ärvning tillämpas. Endast läsning [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Returnerar eller anger upphöjt eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjt). **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Returnerar textens FillFormat-egenskaper. Ingen ärvning tillämpas. Endast läsning [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Avgör om teckensnittet är fetstil. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Returnerar eller anger teckensnittshöjden för en del. **float.NaN** betyder att höjden är odefinierad och bör ärvas från Master. Läs/skriv Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Avgör om teckensnittet är kursivt. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Returnerar eller anger typ av textunderstrykning. Ingen ärvning tillämpas. Läs/skriv [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Returnerar färgen som används för att markera text. Ingen ärvning tillämpas. Endast läsning [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlänkhäntering. Endast läsning [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för musöver. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Avgör om understrykningens stil har egna FillFormat-egenskaper eller ärver dem från textens FillFormat-egenskaper. Läs/skriv [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Avgör om understrykningens stil har egna LineFormat-egenskaper eller ärver dem från textens LineFormat-egenskaper. Läs/skriv [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Returnerar eller anger minimal teckensnittsstorlek för vilken kerning ska aktiveras. **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Avgör om siffrorna ska ignorera vertikal textlayout som är specifik för östliga språk. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Returnerar eller anger Id för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs/skriv String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Returnerar eller anger information om latinskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Returnerar LineFormat-egenskaper för textkontur. Ingen ärvning tillämpas. Endast läsning [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Avgör om textens höjd ska normaliseras. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Avgör om texten inte ska korrekturläsas. Ingen ärvning tillämpas. Läs/skriv [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Avgör om smart-taggen ska rensas. Ingen ärvning tillämpas. Läs/skriv Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Returnerar eller anger ökningen av mellanrum mellan tecken. **float.NaN** betyder att värdet är odefinierat och bör ärvas från Master. Läs/skriv Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Hämtar eller anger ett värde som visar om stavningskontroll är aktiverad för textdelen. När egenskapen är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Returnerar eller anger genomstreckningstyp för en text. Ingen ärvning tillämpas. Läs/skriv [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Returnerar eller anger information om symbolteckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs/skriv [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Returnerar eller anger typ av textkapitalisering. Ingen ärvning tillämpas. Läs/skriv [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Returnerar FillFormat-egenskaper för understrykningens linje. Ingen ärvning tillämpas. Endast läsning [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Returnerar LineFormat-egenskaper som används för att konturera understrykningens linje. Ingen ärvning tillämpas. Endast läsning [`ILineFormat`](../ilineformat). |

## Metoder

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Jämför med angivet objekt. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Hämtar effektiv formateringsdata för del med ärvning tillämpad. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returnerar hashkod. |

### Anmärkningar

Denna klass används för att returnera och manipulera formateringsegenskaper för textdelar som definierats för den specifika delen. Detta innebär att ingen ärvning tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda metoden [`GetEffective`](./geteffective) som returnerar en [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-instans.

### Exempel

Följande exempel visar hur du tilldelar det latinska teckensnittet till en Paragraph-del i en PowerPoint-presentation.

```csharp
[C#]
//Instansiera ett presentationsobjekt som representerar en presentationsfil
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides använder dessa speciella identifierare (liknande de som används i PowerPoint):
// +mn-lt - Kroppstypsnitt Latin (Mindre Latin-typsnitt)
// +mj-lt - Rubriktypsnitt Latin (Större Latin-typsnitt)
// +mn-ea - Kroppstypsnitt Östasiatiskt (Mindre Östasiatiskt typsnitt)
// +mj-ea - Kroppstypsnitt Östasiatiskt (Mindre Östasiatiskt typsnitt)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Se även

* klass [BasePortionFormat](../baseportionformat)
* gränssnitt [IPortionFormat](../iportionformat)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->