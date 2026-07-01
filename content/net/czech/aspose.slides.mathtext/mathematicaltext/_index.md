---
title: MathematicalText
second_title: Aspose.Sildes pro .NET API Reference
description: Matematický text
type: docs
weight: 9040
url: /cs/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText třída

Matematický text

```csharp
public sealed class MathematicalText : MathElementBase, IMathematicalText
```

## Konstruktorové metody

| Název | Popis |
| --- | --- |
| [MathematicalText](mathematicaltext#constructor)() | Výchozí konstruktor (vytvoří hodnotu String.Empty) |
| [MathematicalText](mathematicaltext#constructor_1)(char) | Vytvoří MathText s jedním symbolem |
| [MathematicalText](mathematicaltext#constructor_2)(string) | Vytvoří MathematicalText z textu |
| [MathematicalText](mathematicaltext#constructor_3)(string, IPortionFormat) | Vytvoří MathematicalText z textu a nastavení formátu |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Format](../../aspose.slides.mathtext/mathematicaltext/format) { get; } | Vlastnosti formátování textu |
| [Value](../../aspose.slides.mathtext/mathematicaltext/value) { get; set; } | Hodnota textu |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví akcentovaný znak (znak nad tímto prvkem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Použije zadanou funkci s tímto objektem jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Použije zadanou funkci s tímto objektem jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Použije zadanou funkci s tímto objektem jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci s tímto objektem jako argument a s určeným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci s tímto objektem jako argument a s určeným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek určeného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek určeného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek do závorek |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek do určených znaků, například závorek nebo jiných znaků |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Použije funkci argumentu s tímto objektem jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Použije funkci argumentu s tímto objektem jako názvem funkce |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí skupinového znaku, jako je dolní složená závorka nebo jiný znak |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vytvoří integrál bez mezí |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vytvoří integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Umístí čáru nad tento prvek |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného řádu z uvedeného argumentu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného řádu z uvedeného argumentu |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Přijme dolní mez |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Přijme dolní mez |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní a horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Přijme horní mez |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Přijme horní mez |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do ohraničeného rámečku |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do ohraničeného rámečku |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného rámečku (logické seskupení), který se používá ke skupování součástí rovnice nebo jiného matematického textu. Objekty v rámečku mohou (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupeny tak, aby neumožňovaly zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do vertikálního pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Umístí čáru pod tento prvek |

### Příklady

Příklad:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathematicalText](../imathematicaltext)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->