---
title: MathPhantom
second_title: Aspose.Sildes pro .NET API – reference
description: Representuje fiktivní matematický objekt ltmphantgt, který ovlivňuje rozvržení svého podřízeného elementu, aniž by jej nutně zobrazoval. Fiktivní objekt může skrýt svůj základní výraz a zároveň zachovat svou šířku, výšku nebo hloubku pro zarovnání vzorců nebo rezervaci místa. Viditelnost a geometrické chování jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp.
type: docs
weight: 8900
url: /cs/aspose.slides.mathtext/mathphantom/
---
## MathPhantom třída

Reprezentuje fiktivní matematický objekt (&lt;m:phant&gt;), který ovlivňuje rozvržení svého podřízeného elementu, aniž by ho nutně zobrazoval. Fiktivní objekt může skrýt svůj základní výraz a zároveň zachovat svou šířku, výšku nebo hloubku pro zarovnání vzorců nebo rezervaci místa. Viditelnost a geometrické chování jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Konstruktor

| Název | Popis |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Inicializuje novou instanci třídy [`MathPhantom`](../mathphantom) pomocí zadaného základního matematického elementu. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Základní argument |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Získá nebo nastaví hodnotu určující, zda je základní element zobrazen. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Získá nebo nastaví hodnotu určující, zda je phantom transparentní pro pravidla mezery založená na třídě. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Získá nebo nastaví hodnotu určující, zda se výška (ascent) základního elementu má považovat za nulu. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Získá nebo nastaví hodnotu určující, zda se hloubka (descent) základního elementu má považovat za nulu. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Získá nebo nastaví hodnotu určující, zda se šířka základního elementu má považovat za nulu. |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví akcentní značku (znak nad tímto elementem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Použije zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Použije zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Použije zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci s touto instancí jako argumentem a specifikovaným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci s touto instancí jako argumentem a specifikovaným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatel a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatel a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek daného typu s tímto čitatel a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek daného typu s tímto čitatel a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zabalí matematický element do závorek |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Zabalí matematický element do zadaných znaků, například závorek nebo jiných znaků jako rámcování |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Použije funkci argumentu s touto instancí jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Použije funkci argumentu s touto instancí jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Získá podřízené elementy |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento element do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento element do skupiny pomocí skupinového znaku, například dolní složené závorky nebo jiného |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vezme integrál bez mezí |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vezme integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický element a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví čáru na horní část tohoto elementu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně z uvedeného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně z uvedeného argumentu. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Vezme dolní mez |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Vezme dolní mez |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní a horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Vezme horní mez |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Vezme horní mez |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento element do rámečku |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento element do rámečku |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento element do neviditelného rámečku (logické seskupení), které slouží ke skupování komponent rovnice nebo jiného matematického textu. Takový rámeček může například sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, jako bod přerušení řádku, nebo být seskupen tak, aby neumožňoval zalamování řádků uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru na dolní část tohoto elementu |

### Příklady

Example:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Skrýt obsah
phantom.ZeroWidth = false;     // Zachovat šířku
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathPhantom](../imathphantom)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->