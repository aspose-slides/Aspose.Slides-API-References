---
title: MathAccent
second_title: Aspose.Sildes pro .NET API Reference
description: Určuje funkci akcentu složenou ze základny a kombinujícího diakritického znaku. Příklad ́
type: docs
weight: 8510
url: /cs/aspose.slides.mathtext/mathaccent/
---
## MathAccent třída

Určuje funkci akcentu, skládající se ze základny a kombinujícího diakritického znaku. Příklad: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou znaku akcentu |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | Argument, na který byl akcent aplikován |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | Znak akcentu. Hodnota by měla být v rozsahu (U+0300–U+036F) nebo (U+20D0–U+20EF). Výchozí hodnota: Kombinovaný stříškový akcent (U+0302) |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví znak akcentu (znak umístěný nad tímto prvkem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Použije zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Použije zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Použije zadanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci s touto instancí jako argumentem a specifikovaným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci s touto instancí jako argumentem a specifikovaným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek závorkami |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek určenými znaky, například závorkami nebo jinými znaky |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Použije funkci argumentu s touto instancí jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Použije funkci argumentu s touto instancí jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, například dolní složené závorky nebo jiných |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vytvoří integrál bez mezí |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vytvoří integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vytvoří integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví čáru nad tímto prvkem |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do rámečku |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do rámečku |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného rámečku (logické seskupení), který slouží ke skupování součástí rovnice nebo jiného matematického textu. Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru pod tímto prvkem |

### Příklady

Příklad:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathAccent](../imathaccent)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->