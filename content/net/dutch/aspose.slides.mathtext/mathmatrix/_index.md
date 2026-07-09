---
title: MathMatrix
second_title: Aspose.Sildes voor .NET API-referentie
description: Specificeert het Matrix-object dat bestaat uit kindelementen die in één of meer rijen en kolommen zijn gerangschikt. Het is belangrijk op te merken dat matrices geen ingebouwde delimiters hebben. Om de matrix in de haakjes te plaatsen, moet u het delimiter-object IMathDelimiter gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.
type: docs
weight: 8850
url: /nl/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix klasse

Specificeert het Matrix-object, bestaande uit kindelementen die in één of meer rijen en kolommen zijn gerangschikt. Het is belangrijk op te merken dat matrices geen ingebouwde delimiters hebben. Om de matrix in haakjes te plaatsen, moet u het delimiter-object (IMathDelimiter) gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Initialiseert een nieuw exemplaar van de MathMatrix klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Specificeert de verticale uitlijning ten opzichte van de omringende tekst. Mogelijke waarden zijn top, bottom en center. Standaard: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Aantal kolommen in de matrix |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | De waarde van de horizontale spatiëring tussen kolommen van een matrix; Als de ColumnGapRule is ingesteld op 3 ("Exactly"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de ColumnGapRule is ingesteld op 4 ("Multiple"), wordt de eenheid geïnterpreteerd als een aantal 0,5-em-stappen. In andere gevallen wordt genegeerd. Standaard: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Het type horizontale spatiëring tussen kolommen van een matrix; Horizontale spatiëringseenheden kunnen ems of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Verberg de tijdelijke aanduidingen voor lege matrixelementen Standaard: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Element van matrix |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimumkolombreedte in twips (1/20ste van een punt) De ruimte tussen kolommen (ook wel “Column Gap” of “Gap Width” genoemd) wordt toegevoegd aan de MinColumnWidth om de totale Matrix Column Spacing (afstand tussen dezelfde randen van verschillende kolommen) te bepalen. Standaard: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Aantal rijen in de matrix |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | De waarde van de verticale spatiëring tussen rijen van een matrix; Als de RowGapRule is ingesteld op 3 ("Exactly"), wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt). Als de RowGapRule is ingesteld op 4 ("Multiple"), wordt de eenheid geïnterpreteerd als halve regels. Standaard: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Het type verticale spatiëring tussen rijen van een matrix; Verticale spatiëringseenheden kunnen lijnen of punten zijn (opgeslagen als twips). Standaard: SingleSpacingGap (0) |

## Methodes

| Naam | Beschrijving |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Stelt een accentteken in (een teken boven dit element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Neemt de opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Verwijdert de opgegeven kolom |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Verwijdert de opgegeven rij |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Creëert een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Creëert een breuk met deze teller en de opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Creëert een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Creëert een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Omvat een wiskundig element in haakjes |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Omvat een wiskundig element in opgegeven tekens, zoals haakjes of andere tekens als omkadering |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Haal kindelementen op |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Haal de horizontale uitlijning op van de opgegeven kolom |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Plaatst dit element in een groep met een onderste accolade |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Plaatst dit element in een groep met een groepeerteken, zoals een onderste accolade of een ander teken |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Voegt een nieuwe kolom in na de opgegeven. Aanvankelijk zijn alle elementen in de nieuwe kolom null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Voegt een nieuwe kolom in vóór de opgegeven. Aanvankelijk zijn alle elementen in de nieuwe kolom null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Voegt een nieuwe rij in na de opgegeven. Aanvankelijk zijn alle elementen in de nieuwe rij null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Voegt een nieuwe rij in vóór de opgegeven. Aanvankelijk zijn alle elementen in de nieuwe rij null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Neemt het integraal zonder limieten |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Neemt het integraal |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Neemt het integraal |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Creëert een N-aire operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Creëert een N-aire operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Stelt een balk boven dit element in |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specificeert de wiskundige wortel van de gegeven graad van het opgegeven argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specificeert de wiskundige wortel van de gegeven graad van het opgegeven argument. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Stel de horizontale uitlijning in van de opgegeven kolom |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Stel de horizontale uitlijning in van de opgegeven kolommen |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Neemt de ondergrens |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Neemt de ondergrens |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Creëert subscript |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Creëert subscript |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Creëert subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Creëert subscript en superscript aan de linkerkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Creëert subscript en superscript aan de rechterkant |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Creëert subscript en superscript aan de rechterkant |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Creëert superscript |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Creëert superscript |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Neemt de bovengrens |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Neemt de bovengrens |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Plaatst dit element in een randvak |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Plaatst dit element in een randvak |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Plaatst dit element in een niet-visueel vak (logische groepering) dat wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen. Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of worden gegroepeerd zodat geen regeleinden binnen toegestaan zijn. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Plaatst in een verticale reeks |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Stelt een balk onder dit element in |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Zie ook

* klasse [MathElementBase](../mathelementbase)
* interface [IMathMatrix](../imathmatrix)
* naamruimte [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->