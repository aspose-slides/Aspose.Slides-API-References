---
title: MathMatrix
second_title: Aspose.Sildes för .NET API-referens
description: Anger Matrix-objektet som består av barn-element placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteser bör du använda avgränsare-objektet IMathDelimiter. Null-argument kan användas för att skapa luckor i matriser.
type: docs
weight: 8830
url: /sv/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix-klass

Anger Matrix-objektet, bestående av barn-element som är placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteser bör du använda avgränsare-objektet (IMathDelimiter). Null-argument kan användas för att skapa luckor i matriser.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Initialiserar en ny instans av MathMatrix-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Anger vertikal justering i förhållande till omgivande text. Möjliga värden är top, bottom och center. Standard: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Antal kolumner i matrisen |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Värdet för horisontellt avstånd mellan kolumner i en matris; om ColumnGapRule är satt till 3 (\"Exactly\") tolkas enheten som twips (1/20 av en punkt). Om ColumnGapRule är satt till 4 (\"Multiple\") tolkas enheten som antal 0,5 em-steg. I andra fall ignoreras det. Standard: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Typen av horisontellt avstånd mellan kolumner i en matris; horisontella avståndsenheter kan vara ems eller punkter (lagrade som twips). Standard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Dölj platshållarna för tomma matriselement. Standard: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Element i matrisen |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minsta kolumnbredd i twips (1/20 av en punkt). Gap-avståndet (även kallat “Column Gap” eller “Gap Width”) läggs till MinColumnWidth för att bestämma det totala matris-kolumnavståndet (avståndet mellan samma kanter på olika kolumner). Standard: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Antal rader i matrisen |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Värdet för vertikalt avstånd mellan rader i en matris; om RowGapRule är satt till 3 (\"Exactly\") tolkas enheten som twips (1/20 av en punkt). Om RowGapRule är satt till 4 (\"Multiple\") tolkas enheten som halvlänkar. Standard: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Typen av vertikalt avstånd mellan rader i en matris; vertikala avståndsenheter kan vara linjer eller punkter (lagrade som twips). Standard: SingleSpacingGap (0) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Sätter ett accenttecken (ett tecken ovanför detta element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Tar angiven funktion och använder detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Tar angiven funktion och använder detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Tar angiven funktion och använder detta objekt som argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Tar angiven funktion och använder detta objekt som argument samt angivet extra argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Tar angiven funktion och använder detta objekt som argument samt angivet extra argument |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Tar bort den angivna kolumnen |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Tar bort den angivna raden |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Skapar en bråkdel med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Skapar en bråkdel med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Skapar en bråkdel av angiven typ med detta täljare och angiven nämnare |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Skapar en bråkdel av angiven typ med detta täljare och angiven nämnare |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Innesluter ett math-element i parenteser |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Innesluter ett math-element i angivna tecken, såsom parenteser eller andra tecken som ram |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Tar en funktion av ett argument och använder detta objekt som funktionsnamn |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Tar en funktion av ett argument och använder detta objekt som funktionsnamn |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Hämtar barn-element |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Hämtar den horisontella justeringen för den angivna kolumnen |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Placera detta element i en grupp med en nedre klammerparentes |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Placera detta element i en grupp med ett grupperingstecken, såsom nedre klammerparentes eller annat |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Infogar en ny kolumn efter den angivna. Ursprungligen är alla element i den nya kolumnen null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Infogar en ny kolumn före den angivna. Ursprungligen är alla element i den nya kolumnen null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Infogar en ny rad efter den angivna. Ursprungligen är alla element i den nya raden null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Infogar en ny rad före den angivna. Ursprungligen är alla element i den nya raden null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Tar integralen utan gränser |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Tar integralen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Tar integralen |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Sammanfogar en matematisk text och bildar ett matematiskt block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Skapar en N-är operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Skapar en N-är operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sätter ett streck över detta element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Anger den matematiska roten av given grad från angivet argument. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Anger den matematiska roten av given grad från angivet argument. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Ställ in horisontell justering för den angivna kolumnen |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Ställ in horisontell justering för de angivna kolumnerna |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Tar nedre gräns |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Tar nedre gräns |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Skapar nedsänkt index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Skapar nedsänkt index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjd text på vänster sida |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Skapar nedsänkt och upphöjd text på vänster sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Skapar nedsänkt och upphöjd text på höger sida |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Skapar nedsänkt och upphöjd text på höger sida |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Skapar upphöjd text |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Skapar upphöjd text |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Tar övre gräns |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Tar övre gräns |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Placera detta element i en kant-ruta |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Placera detta element i en kant-ruta |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan matematisk text. En inramad objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning eller grupperas så att radbrytningar inte tillåts inom den. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Placerar i en vertikal matris |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sätter ett streck under detta element |

### Exempel

Exempel:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Se även

* klass [MathElementBase](../mathelementbase)
* gränssnitt [IMathMatrix](../imathmatrix)
* namnrymd [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->