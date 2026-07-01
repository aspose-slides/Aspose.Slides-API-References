---
title: MathGroupingCharacter
second_title: Aspose.Sildes pro .NET API Reference
description: Určuje znak seskupení nad nebo pod výrazem, který obvykle zvýrazňuje vztah mezi prvky
type: docs
weight: 8740
url: /cs/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter třída

Určuje symbol seskupení nad nebo pod výrazem, obvykle za účelem zvýraznění vztahu mezi prvky

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | Inicializuje novou instanci třídy MathGroupingCharacter s výchozím znakem seskupení U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | Inicializuje novou instanci třídy MathGroupingCharacter. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | Základní argument |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | Znak seskupení Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | Pozice znaku seskupení. Výchozí: Bottom |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | Vertikální zarovnání znaku seskupení. Určuje zarovnání objektu vzhledem k základní lince. Například když je znak seskupení nad objektem, VertikálníJustification Top znamená, že horní část objektu leží na základní lince; když je VertikálníJustification nastaveno na Bottom, spodní část objektu je na základní lince Výchozí: Bottom pro Position=Top a Top pro Position=Bottom |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví diakritický znak (znak umístěný nad tímto prvkem) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Přijme zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Přijme zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Přijme zadanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Přijme zadanou funkci s touto instancí jako argument a zadaný další argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Přijme zadanou funkci s touto instancí jako argument a zadaný další argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek v závorkách |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek v určených znacích, jako jsou závorky nebo jiné znaky jako rámec |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí znaku seskupení, jako je dolní složená závorka nebo jiný znak |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vezme integrál bez mezí |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vezme integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ary operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ary operátor |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do okrajové krabice |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do okrajové krabice |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelné krabice (logické seskupení), která se používá ke seskupení komponent rovnice nebo jiného matematického textu. Krabicový objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby nepovoloval zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru pod tímto prvkem |

### Příklady

Příklad:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathGroupingCharacter](../imathgroupingcharacter)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->