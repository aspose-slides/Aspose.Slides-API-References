---
title: MathMatrix
second_title: Aspose.Sildes pro .NET API Reference
description: Specifikuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné oddělovače. Pro umístění matice do závorek byste měli použít objekt oddělovače IMathDelimiter. Null argumenty lze použít k vytvoření mezer v maticích.
type: docs
weight: 8850
url: /cs/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix třída

Specifikuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné oddělovače. Pro umístění matice do závorek byste měli použít objekt oddělovače (IMathDelimiter). Null argumenty lze použít k vytvoření mezer v maticích.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktory

| Name | Description |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Inicializuje novou instanci třídy MathMatrix. |

## Vlastnosti

| Name | Description |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Určuje svislé zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Počet sloupců v matici |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaven na 3 ("Exactly"), jednotka se interpretuje jako twip (1/20 bodu). pokud je ColumnGapRule nastaven na 4 ("Multiple"), jednotka se interpretuje jako počet 0,5 em kroků. V ostatních případech se ignoruje. Výchozí: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být ems nebo body (uloženy jako twipy). Výchozí: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Skryje zástupné symboly pro prázdné prvky matice. Výchozí: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Prvek matice |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimální šířka sloupce v twipech (1/20 bodu). Prostor mezi sloupci (také nazývaný „Column Gap“ nebo „Gap Width“) se přičítá k MinColumnWidth pro určení celkového rozestupu sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). Výchozí: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Počet řádků v matici |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Hodnota svislého rozestupu mezi řádky matice; pokud je RowGapRule nastaven na 3 ("Exactly"), jednotka se interpretuje jako twip (1/20 bodu). pokud je RowGapRule nastaven na 4 ("Multiple"), jednotka se interpretuje jako půl řádky. Výchozí: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Typ svislého rozestupu mezi řádky matice; jednotky svislého rozestupu mohou být řádky nebo body (uloženy jako twipy). Výchozí: SingleSpacingGap (0) |

## Metody

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví akcent (znak na vrcholu tohoto prvku) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Přijme určenou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Přijme určenou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Přijme určenou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Přijme určenou funkci s touto instancí jako argument a specifikovaný další argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Přijme určenou funkci s touto instancí jako argument a specifikovaný další argument |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Odstraní zadaný sloupec |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Odstraní zadaný řádek |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Uzavře matematický prvek do závorek |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Uzavře matematický prvek do zadaných znaků, jako jsou závorky nebo jiné znaky jako rámování |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Přijme funkci s argumentem, kde tato instance slouží jako název funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Přijme funkci s argumentem, kde tato instance slouží jako název funkce |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Získá podřazené prvky |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Získá vodorovné zarovnání zadaného sloupce |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí znakové skupiny, například dolní složené závorky nebo jiného znaku |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Vloží nový sloupec za zadaný. Na začátku jsou všechny prvky v novém sloupci null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Vloží nový sloupec před zadaný. Na začátku jsou všechny prvky v novém sloupci null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Vloží nový řádek za zadaný. Na začátku jsou všechny prvky v novém řádku null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Vloží nový řádek před zadaný. Na začátku jsou všechny prvky v novém řádku null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Přijme integrál bez hranic |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Přijme integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví čáru na vrcholu tohoto prvku |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně z určeného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně z určeného argumentu. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Nastaví vodorovné zarovnání zadaného sloupce |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Nastaví vodorovné zarovnání zadaných sloupců |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Přijme dolní limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Přijme dolní limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní i horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní i horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní i horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní i horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Přijme horní limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Přijme horní limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do ohraničeného rámečku |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do ohraničeného rámečku |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného rámečku (logické seskupení), který se používá k seskupení komponent rovnice nebo jiného matematického textu. Obdélníkový objekt může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby nedovolil zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru na dně tohoto prvku |

### Příklady

Příklad:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathMatrix](../imathmatrix)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->