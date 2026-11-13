---
title: MathBlock
second_title: Aspose.Sildes pro .NET API referenci
description: Specifikuje instanci matematického textu, který je obsažen v MathParagraph a začíná na samostatném řádku. Všechny matematické zóny, včetně rovnic, výrazů, polí rovnic nebo výrazů a vzorců, jsou reprezentovány matematickým blokem.
type: docs
weight: 8610
url: /cs/aspose.slides.mathtext/mathblock/
---
## MathBlock třída

Specifikuje instanci matematického textu, která je obsažena v MathParagraph a začíná na samostatném řádku. Všechny matematické oblasti, včetně rovnic, výrazů, polí rovnic nebo výrazů a vzorců, jsou reprezentovány matematickým blokem.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initializes a new instance of the MathBlock class. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Creates a new mathematical block and puts specified elements in it |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Creates a new mathematical block and puts specified element in it |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Získá počet podřízených matematických prvků skutečně obsažených v kolekci. Pouze pro čtení Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Vrací false, protože kolekce podřízených prvků může být upravována. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Získá nebo nastaví IMathElement na zadaném indexu. |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví akcentovaný znak (znak na vrcholu tohoto prvku) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Přidá matematický prvek na konec kolekce. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Vykoná zadanou funkci s touto instancí jako argumentem. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Vykoná zadanou funkci s touto instancí jako argumentem. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Vykoná zadanou funkci s touto instancí jako argumentem. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Vykoná zadanou funkci s touto instancí jako argumentem a zadaným dalším argumentem. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Vykoná zadanou funkci s touto instancí jako argumentem a zadaným dalším argumentem. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Odstraní všechny prvky z kolekce. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Určuje, zda kolekce obsahuje konkrétní hodnotu. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Zkopíruje do zadaného pole. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Oddělí podřízené prvky znakem oddělovače (bez závorek). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek závorkami. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Obalí podřízené prvky tohoto bloku zadanými znaky, například závorkami nebo jinými znaky, jako rámeček. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Obalí podřízené prvky tohoto bloku zadanými znaky, například závorkami nebo jinými, jako rámec a oddělí je znakem oddělovače. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Vezme funkci argumentu s touto instancí jako názvem funkce. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Vezme funkci argumentu s touto instancí jako názvem funkce. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Získá podřízené prvky. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí znakové skupiny, například dolní složené závorky nebo jiného znaku. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Určí index konkrétního matematického prvku v kolekci. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Vloží MathElement do kolekce na zadaném indexu. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vezme integrál bez hranic. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vezme integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vezme integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vezme integrál. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vezme integrál. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Spojí matematický prvek s tímto matematickým blokem. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Spojí matematický text s tímto matematickým blokem. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Spojí další matematický blok s tímto. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví čáru na horní části tohoto prvku. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Odstraní prvek na zadaném indexu v kolekci. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Vezme dolní mez. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Vezme dolní mez. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní a horní index vlevo. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní a horní index vpravo. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Vezme horní mez. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Vezme horní mez. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do rámečkové krabice. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do rámečkové krabice. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelné krabice (logické seskupení), která slouží k seskupení komponent rovnice nebo jiné instance matematického textu. Krabicový objekt může (například) fungovat jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Umístí podřízené prvky do vertikálního pole. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru na spodní části tohoto prvku. |
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