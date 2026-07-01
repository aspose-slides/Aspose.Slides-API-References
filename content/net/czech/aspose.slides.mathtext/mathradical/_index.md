---
title: MathRadical
second_title: Aspose.Sildes pro .NET API Referenci
description: Určuje radikální funkci sestávající ze základu a volitelného stupně. Příklad radikálního objektu je .
type: docs
weight: 8920
url: /cs/aspose.slides.mathtext/mathradical/
---
## MathRadical třída

Určuje radikální funkci, která se skládá ze základu a volitelného stupně. Příklad radikálního objektu je √𝑥.

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | Inicializuje novou instanci třídy MathRadical. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | Argument základu |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | Argument stupně |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | Skryje stupeň. Když je true, stupeň není zobrazen, jako v √𝑥 |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví akcent (znak nad tímto prvkem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Použije zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Použije zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Použije zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci s touto instancí jako argument a s určeným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci s touto instancí jako argument a s určeným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek do závorek |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek určenými znaky, jako jsou závorky nebo jiné znaky |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Použije funkci argumentu, kde tato instance slouží jako název funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Použije funkci argumentu, kde tato instance slouží jako název funkce |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí seskupovacího znaku, např. spodní složené závorky nebo jiného |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vypočítá integrál bez mezí |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vypočítá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vypočítá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vypočítá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vypočítá integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Přidá čáru nad tímto prvkem |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen zadaného stupně ze specifikovaného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen zadaného stupně ze specifikovaného argumentu. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Získá dolní mez |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Získá dolní mez |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní a horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Získá horní mez |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Získá horní mez |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do rámečkového boxu |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do rámečkového boxu |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného boxu (logické seskupení), který se používá k seskupení komponent rovnice nebo jiného matematického textu. Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádky uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do vertikálního pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Přidá čáru pod tento prvek |

### Příklady

Example:

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathRadical](../imathradical)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->