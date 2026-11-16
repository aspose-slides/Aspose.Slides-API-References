---
title: MathBox
second_title: Aspose.Sildes pro .NET API reference
description: Specifikuje logické zabalení (balení) matematického prvku. Například zabalený objekt může sloužit jako emulátor operátoru s nebo bez bodu zarovnání, jako bod pro zalomení řádku nebo může být seskupen tak, aby neumožňoval zalomení řádků uvnitř. Například operátor by měl být zabalen, aby se zabránilo zalomení řádku.
type: docs
weight: 8650
url: /cs/aspose.slides.mathtext/mathbox/
---
## MathBox třída

Určuje logické zabalení (balení) matematického prvku. Například zabalený objekt může sloužit jako emulátor operátoru s nebo bez bodu zarovnání, jako bod pro zalomení řádku nebo může být seskupen tak, aby neumožňoval zalomení řádků uvnitř. Například operátor "==" by měl být zabalen, aby se zabránilo zalomení řádku.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicializuje MathBox se zadaným prvkem jako argumentem |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Když je true, tento emulátor operátoru slouží jako bod zarovnání; tj. označené body zarovnání v jiných rovnicích mohou být s ním zarovnány. Výchozí: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Základní argument |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Diferenciál Když je true, box působí jako diferenciál (např. 𝑑𝑥 ve funkci pod integrálem) a získá odpovídající vodorovné odsazení pro matematický diferenciál. Výchozí: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicitní zalomení určuje, zda na začátku objektu Box je zalomení řádku, takže řádek se zalamuje na začátku objektu box. Určuje číslo operátoru na předchozím řádku matematického textu, které bude použito jako bod zarovnání pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní zalomení) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Bez zalomení Tato vlastnost určuje vlastnost „nepřerušitelné“ na objektu boxu. Když je true, žádná zalomení řádku se nemohou objevit uvnitř boxu. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když není tento prvek specifikován, zalomení mohou nastat uvnitř boxu. Výchozí: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Emulátor operátoru. Když je true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k jiným operátorům. Emulátory operátorů se často používají, když se jeden nebo více glifů kombinuje do operátoru, například '=='. Výchozí hodnota: false |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví diakritický znak (znak na vrcholu tohoto prvku) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Přijme specifikovanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Přijme specifikovanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Přijme specifikovanou funkci s touto instancí jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Přijme specifikovanou funkci s touto instancí jako argumentem a s určeným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Přijme specifikovanou funkci s touto instancí jako argumentem a s určeným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a určeným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a určeným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek v závorkách |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek ve zvolených znacích, jako jsou závorky nebo jiné znaky, jako rámeček |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, jako je dolní složená závorka nebo jiný znak |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Přijme integrál bez mezí |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Přijme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Přijme integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví čáru na vršek tohoto prvku |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně z určeného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně z určeného argumentu. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného boxu (logické seskupení), který se používá k seskupení komponent rovnice nebo jiné instance matematického textu. Zabalený objekt může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, jako bod pro zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru na spodku tohoto prvku |

### Příklady

Příklad:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathBox](../imathbox)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->