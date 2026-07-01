---
title: MathBorderBox
second_title: Aspose.Sildes pro .NET API Reference
description: Vykresluje obdélníkový nebo jiný rámeček kolem IMathElement.
type: docs
weight: 8590
url: /cs/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox třída

Vykresluje obdélníkový nebo jiný rámeček kolem IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | Vytváří prvek MathBorderBox s obdélníkovým rámečkem |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | Vytváří prvek MathBorderBox |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Základní argument |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Skryje spodní okraj (výchozí je false) – určuje skrytý nebo zobrazený stav spodního okraje rámečku. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Skryje levý okraj (výchozí je false) – určuje skrytý nebo zobrazený stav levého okraje rámečku. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Skryje pravý okraj (výchozí je false) – určuje skrytý nebo zobrazený stav pravého okraje rámečku. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Skryje horní okraj (výchozí je false) – určuje skrytý nebo zobrazený stav horního okraje rámečku. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Přeškrtnutí od levého dolního ke pravému hornímu (výchozí je false). Určuje skrytý nebo zobrazený stav přeškrtnuté úhlopříčky od levého dolního rohu k pravému hornímu rohu rámečku. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Přeškrtnutí vodorovné čáry (výchozí je false) – určuje skrytý nebo zobrazený stav přeškrtnuté vodorovné čáry. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Přeškrtnutí od levého horního ke pravému dolnímu (výchozí je false). Určuje skrytý nebo zobrazený stav přeškrtnuté úhlopříčky od levého horního rohu k pravému dolnímu rohu rámečku. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Přeškrtnutí svislé čáry (výchozí je false) – určuje skrytý nebo zobrazený stav přeškrtnuté svislé čáry. |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví akcent (znak na vrcholu tohoto prvku) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Přebírá specifikovanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Přebírá specifikovanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Přebírá specifikovanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Přebírá specifikovanou funkci s touto instancí jako argumentem a zadaným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Přebírá specifikovanou funkci s touto instancí jako argumentem a zadaným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek závorkami |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek zadanými znaky, například závorkami nebo jinými znaky |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Přebírá funkci argumentu s touto instancí jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Přebírá funkci argumentu s touto instancí jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí seskupovacího znaku, jako je dolní složená závorka nebo jiný |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Přebírá integrál bez limitů |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Přebírá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Přebírá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Přebírá integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Přebírá integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Umístí čáru na horní část tohoto prvku |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně zadaného argumentu |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně zadaného argumentu |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Přebírá dolní limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Přebírá dolní limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní a horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Přebírá horní limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Přebírá horní limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do rámečku |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do rámečku |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného rámečku (logické seskupení), který slouží k seskupení komponent rovnice nebo jiného matematického textu. Zkrabikovaný objekt může (například) fungovat jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Vloží do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Umístí čáru na spodní část tohoto prvku |

### Příklady

Příklad:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathBorderBox](../imathborderbox)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->