---
title: MathBox
second_title: Aspose.Sildes pro .NET API Reference
description: Určuje logické zabalení (balení) matematického prvku. Například zaboxovaný objekt může sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby nedovoloval zalomení řádku uvnitř. Například operátor by měl být zaboxován, aby se zabránilo zalomení řádku.
type: docs
weight: 8610
url: /cs/aspose.slides.mathtext/mathbox/
---
## MathBox třída

Specifikuje logické balení (cs) matematického prvku. Například zaboxovaný objekt může sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. Například operátor "==" by měl být zaboxován, aby se zabránilo zalomení řádku.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Konstruktory

| Name | Description |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inicializuje MathBox s uvedeným prvkem jako argumentem |

## Vlastnosti

| Name | Description |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Když je true, tento emulátor operátoru slouží jako zarovnávací bod; tj. určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Základní argument |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Diferenciál Když je true, krabice funguje jako diferenciál (např. 𝑑𝑥 v integrandu) a získává odpovídající vodorovné odsazení pro matematický diferenciál. Výchozí: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicitní přerušení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek se zalamuje na začátku objektu box. Určuje číslo operátoru na předchozím řádku matematického textu, které bude použito jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255. Výchozí: 0 (žádné explicitní přerušení) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Žádné přerušení Tato vlastnost určuje vlastnost „nepřerušitelnosti“ na objektu box. Když je true, v rámci boxu nemohou nastat zalomení řádku. To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. Když tento prvek není specifikován, mohou se v boxu vyskytovat zalomení. Výchozí: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Emulátor operátoru. Když je true, box a jeho obsah se chovají jako jediný operátor a dědí vlastnosti operátoru. To znamená například, že znak může sloužit jako bod zalomení řádku a může být zarovnán k ostatním operátorům. Emulátory operátorů se často používají, když se jeden nebo více glifů spojí do operátoru, jako je '=='. Výchozí hodnota: false |

## Metody

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví diakritický znak (znak na vrcholu tohoto prvku) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Použije specifikovanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Použije specifikovanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Použije specifikovanou funkci s touto instancí jako argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Použije specifikovanou funkci s touto instancí jako argument a uvedeným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Použije specifikovanou funkci s touto instancí jako argument a uvedeným dalším argumentem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a uvedeným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a uvedeným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a uvedeným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a uvedeným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek do závorek |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Obalí matematický prvek do zadaných znaků, například závorek nebo jiných znaků jako ohraničení |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Použije funkci argumentu s touto instancí jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Použije funkci argumentu s touto instancí jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí znaku pro seskupení, jako je dolní složená závorka nebo jiný |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vezme integrál bez limit |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vezme integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří n-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří n-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Nastaví čáru na horní část tohoto prvku |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně z uvedeného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně z uvedeného argumentu. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Vezme spodní limit |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Vezme spodní limit |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Vytvoří dolní index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Vytvoří dolní index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Vytvoří dolní a horní index vlevo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Vytvoří dolní a horní index vpravo |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Vytvoří dolní a horní index vpravo |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Vytvoří horní index |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Vytvoří horní index |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Vezme horní limit |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Vezme horní limit |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do rámečkového boxu |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do rámečkového boxu |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného boxu (logické seskupení), který slouží k seskupení komponent rovnice nebo jiného matematického textu. Zaboxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Umístí do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Nastaví čáru na spodní část tohoto prvku |

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
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->