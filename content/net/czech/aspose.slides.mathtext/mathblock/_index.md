---
title: MathBlock
second_title: Aspose.Sildes pro .NET API Reference
description: Určuje instanci matematického textu, který je obsažen v MathParagraph a začíná na samostatném řádku. Všechny matematické oblasti, včetně rovnic, výrazů, polí rovnic nebo výrazů a formulí, jsou reprezentovány matematickým blokem.
type: docs
weight: 8570
url: /cs/aspose.slides.mathtext/mathblock/
---
## MathBlock třída

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Inicializuje novou instanci třídy MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Vytvoří nový matematický blok a vloží do něj zadané prvky. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Vytvoří nový matematický blok a vloží do něj zadaný prvek. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Získá počet podřazených matematických prvků skutečně obsažených v kolekci. Pouze pro čtení Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Vrací false, protože kolekci podřazených prvků lze upravovat. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Získá nebo nastaví IMathElement na zadaném indexu. |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví diakritické znaménko (znak na vrcholu tohoto prvku). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Přidá matematický prvek na konec kolekce. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Použije zadanou funkci s touto instancí jako argumentem. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Použije zadanou funkci s touto instancí jako argumentem. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Použije zadanou funkci s touto instancí jako argumentem. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci s touto instancí jako argumentem a s dalším zadaným argumentem. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci s touto instancí jako argumentem a s dalším zadaným argumentem. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Odstraní všechny prvky z kolekce. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Určuje, zda kolekce obsahuje konkrétní hodnotu. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Zkopíruje do zadaného pole. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Oddělí podřazené prvky znakem oddělovače (bez závorek). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek do závorek. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Obalí podřazené prvky tohoto bloku do zadaných znaků, např. závorek nebo jiných znaků jako rámec. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Obalí podřazené prvky tohoto bloku do zadaných znaků, např. závorek nebo jiných jako rámec a oddělí znakem oddělovače. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Použije funkci argumentu s touto instancí jako názvem funkce. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Použije funkci argumentu s touto instancí jako názvem funkce. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Získá podřazené prvky. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí skupinového znaku, např. dolní složené závorky nebo jiného. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Získá index konkrétního matematického prvku v kolekci. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Vloží MathElement do kolekce na zadaném indexu. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vypočítá integrál bez mezí. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vypočítá integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vypočítá integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vypočítá integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vypočítá integrál. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Spojí matematický prvek s tímto matematickým blokem. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Spojí matematický text s tímto matematickým blokem. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Spojí další matematický blok s tímto. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví pruh na vrcholu tohoto prvku. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného řádu z uvedeného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného řádu z uvedeného argumentu. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Odstraní prvek na zadaném indexu v kolekci. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Získá spodní mez. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Získá spodní mez. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní a horní index vlevo. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní a horní index vpravo. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Získá horní mez. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Získá horní mez. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do ohraničeného rámce. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do ohraničeného rámce. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného rámečku (logické seskupení), který slouží k seskupení komponent rovnice nebo jiného matematického textu. Objekt v rámečku může (například) fungovat jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby nedovolil zalomení řádku uvnitř. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Umístí podřazené prvky do vertikálního pole. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví pruh na spodní část tohoto prvku. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Uloží obsah tohoto [`MathBlock`](../mathblock) jako MathML |

### Příklady

Příklad:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathBlock](../imathblock)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->