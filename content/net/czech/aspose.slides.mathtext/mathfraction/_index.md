---
title: MathFraction
second_title: Aspose.Sildes pro .NET API Reference
description: Specifikuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených zlomkovou čarou. Zlomková čára může být vodorovná nebo úhlopříčná v závislosti na vlastnostech zlomku. Objekt zlomku se také používá k reprezentaci zásobníkové funkce, která umisťuje jeden prvek nad druhý bez zlomkové čáry.
type: docs
weight: 8670
url: /cs/aspose.slides.mathtext/mathfraction/
---
## MathFraction třída

Definuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených zlomkovou čárou. Zlomková čára může být vodorovná nebo úhlopříčná, v závislosti na vlastnostech zlomku. Objekt zlomku se také používá k reprezentaci zásobníkové funkce, která umisťuje jeden prvek nad druhý, bez zlomkové čáry.

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | Inicializuje MathFraction typu 'Bar' s uvedeným čitatelem a jmenovatelem |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | Inicializuje MathFraction s uvedeným čitatelem, jmenovatelem a typem |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | Jmenovatel |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | Typ zlomku. Výchozí: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | Čitatel |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví diakritický znak (znak umístěný nad tímto prvkem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Přebírá zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Přebírá zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Přebírá zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Přebírá zadanou funkci s touto instancí jako argumentem a specifikovaným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Přebírá zadanou funkci s touto instancí jako argumentem a specifikovaným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek v závorky |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek ve specifikovaných znacích, jako jsou závorky nebo jiné znaky jako rámeček |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí skupinového znaku, jako je spodní složená závorka nebo jiný |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Přebírá integrál bez limitů |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Přebírá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Přebírá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Přebírá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Přebírá integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví čáru na horní část tohoto prvku |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen zadaného řádu z daného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen zadaného řádu z daného argumentu. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Přijme spodní limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Přijme spodní limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní a horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Přijme horní limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Přijme horní limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do ohraničené krabice |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do ohraničené krabice |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelné krabice (logické seskupení), která slouží k seskupení komponent rovnice nebo jiného matematického textu. Objekt v krabici může (například) fungovat jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod konce řádku nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do vertikálního pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru na spodní část tohoto prvku |

### Příklady

Příklad:

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathFraction](../imathfraction)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->