---
title: IMathElement
second_title: Aspose.Sildes pro .NET API Reference
description: Základní rozhraní libovolného matematického prvku, jako je zlomek, matematický text, funkce, výraz s více prvky atd.
type: docs
weight: 8210
url: /cs/aspose.slides.mathtext/imathelement/
---
## Rozhraní IMathElement

Základní rozhraní libovolného matematického prvku: zlomek, matematický text, funkce, výraz s více prvky atd.

```csharp
public interface IMathElement
```

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Nastaví diakritický znak (znak na vrcholu tohoto prvku) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Použije zadanou funkci s tímto výskytem jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Použije zadanou funkci s tímto výskytem jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Použije zadanou funkci s tímto výskytem jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci s tímto výskytem jako argument a zadaným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci s tímto výskytem jako argument a zadaným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Obalí matematický prvek závorkami |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Obalí tento prvek zadanými znaky, např. závorkami nebo jinými znaky jako ohraničením |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Použije funkci argumentu s tímto výskytem jako názvem funkce |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Použije funkci argumentu s tímto výskytem jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, jako je dolní složená závorka nebo jiný znak |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Vytvoří integrál bez limitů |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Vytvoří integrál |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Umístí čáru nad tento prvek |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Určuje matematický kořen zadaného stupně ze zadaného argumentu |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Určuje matematický kořen zadaného stupně ze zadaného argumentu |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Nastaví spodní limit |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Nastaví spodní limit |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Vytvoří dolní a horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Nastaví horní limit |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Nastaví horní limit |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Umístí tento prvek do rámečku |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do rámečku |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Umístí tento prvek do neviditelné krabice (logického seskupení), která se používá ke skupování komponent rovnice nebo jiného matematického textu. Krabicový objekt může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Vloží do svislého pole |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Umístí čáru pod tento prvek |

### Příklady

Příklad:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Viz také

* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->