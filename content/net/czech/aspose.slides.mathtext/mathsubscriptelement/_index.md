---
title: MathSubscriptElement
second_title: Aspose.Sildes pro .NET API Referenci
description: Určuje objekt subscriptu, který se skládá ze základního argumentu a zmenšeného podindexu umístěného pod a napravo.
type: docs
weight: 8980
url: /cs/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement třída

Určuje objekt subscriptu, který se skládá ze základního argumentu a zmenšeného podindexu umístěného pod a napravo.

```csharp
public sealed class MathSubscriptElement : BaseScript, IMathSubscriptElement
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathSubscriptElement](mathsubscriptelement)(IMathElement, IMathElement) | Inicializuje novou instanci třídy MathSubscriptElement. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Základní argument |
| [Subscript](../../aspose.slides.mathtext/mathsubscriptelement/subscript) { get; } | Podindex |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví akcent (znak na vrcholu tohoto prvku) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Použije zadanou funkci, přičemž tuto instanci použije jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Použije zadanou funkci, přičemž tuto instanci použije jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Použije zadanou funkci, přičemž tuto instanci použije jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci, kde tuto instanci použije jako argument a použije zadaný další argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci, kde tuto instanci použije jako argument a použije zadaný další argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek v závorkách |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek zadanými znaky, jako jsou závorky nebo jiné znaky jako rámování |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Přijme funkci argumentu a použije tuto instanci jako název funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Přijme funkci argumentu a použije tuto instanci jako název funkce |
| [GetChildren](../../aspose.slides.mathtext/mathsubscriptelement/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí skupinového znaku, jako je dolní složená závorka nebo jiný |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Přijme integrál bez limitů |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Přijme integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví čáru nad tímto prvkem |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do rámečkového boxu |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do rámečkového boxu |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelné krabice (logické seskupení), která slouží ke skupinování komponent rovnice nebo jiného matematického textu. Krabicový objekt může (například) fungovat jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru pod tímto prvkem |

### Příklady

Příklad:

```csharp
[C#]
MathSubscriptElement subscriptElement = new MathematicalText("N").SetSubscript("i");
```

### Viz také

* třída [BaseScript](../basescript)
* rozhraní [IMathSubscriptElement](../imathsubscriptelement)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->