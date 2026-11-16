---
title: IMathElement
second_title: Aspose.Sildes pro .NET – dokumentace API
description: Základní rozhraní libovolného matematického prvku, jako je zlomek, matematický text, funkce, výraz s více prvky atd
type: docs
weight: 8250
url: /cs/aspose.slides.mathtext/imathelement/
---
## IMathElement rozhraní

Základní rozhraní libovolného matematického prvku: zlomek, matematický text, funkce, výraz s více prvky atd

```csharp
public interface IMathElement
```

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Nastaví akcentovaný znak (znak umístěný nad tímto prvkem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Použije zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Použije zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Použije zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci s touto instancí jako argument a se zadaným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci s touto instancí jako argument a se zadaným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Vytvoří zlomek s tímto čitatel a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Vytvoří zlomek s tímto čitatel a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatel a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatel a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Obalí matematický prvek v závorkách |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Obalí tento prvek zadanými znaky, například závorkami nebo jinými znaky |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Použije funkci s argumentem s touto instancí jako názvem funkce |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Použije funkci s argumentem s touto instancí jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí seskupovacího znaku, například spodní složené závorky nebo jiného |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Vytvoří integrál bez mezí |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMMathElement) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Vytvoří integrál |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Nastaví čáru nad tímto prvkem |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Určuje dolní mez |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Určuje dolní mez |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMMathElement) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMMathElement) | Vytvoří dolní a horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Vytvoří dolní a horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Určuje horní mez |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Určuje horní mez |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Umístí tento prvek do rámečku |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do rámečku |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Umístí tento prvek do neviditelného rámečku (logické seskupení), který slouží k seskupení komponent rovnice nebo jiného matematického textu. Takový objekt může (například) fungovat jako emulátor operátoru s nebo bez bodu zarovnání, sloužit jako místo zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Vloží do svislého pole |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Nastaví čáru pod tímto prvkem |

### Příklady

Příklad:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Viz také

* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assemblie [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->