---
title: MathDelimiter
second_title: Aspose.Sildes pro .NET API referenci
description: Určuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků, jako jsou závorky, složené závorky, hranaté závorky a svislé čáry, a jednoho nebo více matematických prvků uvnitř oddělených specifikovaným znakem. Příklady 2 2x7C2
type: docs
weight: 8630
url: /cs/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter třída

Určuje objekt oddělovače, který se skládá z otevíracích a závěrečných znaků (jako jsou závorky, složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických prvků uvnitř, oddělených specifikovaným znakem. Příklady: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Inicializuje MathDelimiter s určeným prvkem jako jediným základním argumentem |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Jeden nebo více matematických prvků oddělených znaky oddělovače |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character určuje počáteční, tedy otevírací, znak oddělovače. Matematické oddělovače jsou obklopující znaky jako závorky, hranaté závorky a složené závorky. Výchozí hodnota: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Určuje tvar oddělovačů v objektu oddělovače. Když je MathDelimiterShape.Centered, jsou oddělovače centrovány kolem matematické osy textu a lze je upravit tak, aby odpovídaly celé výšce jejich obsahu. Když je MathDelimiterShape.Match, jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character určuje koncový, tedy uzavírací, znak oddělovače. Matematické oddělovače jsou obklopující znaky jako závorky, hranaté závorky a složené závorky. Výchozí hodnota: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Určuje, zda se Growing of BeginningCharacter, SeparatorCharacter, EndingCharacter. Pokud je true, oddělovače se vertikálně rozšiřují tak, aby odpovídaly výšce operandů. Výchozí hodnota je true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character určuje znak, který odděluje argumenty v objektu oddělovače. Výchozí hodnota: '&#x7C;'. |

## Metody

| Název | Popis |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Nastaví diakritický znak (znak na vrcholu tohoto prvku) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Použije zadanou funkci s tímto exemplářem jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Použije zadanou funkci s tímto exemplářem jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Použije zadanou funkci s tímto exemplářem jako argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Použije zadanou funkci s tímto exemplářem jako argumentem a uvedeným dalším argumentem |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Použije zadanou funkci s tímto exemplářem jako argumentem a uvedeným dalším argumentem |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Oddělí argumenty pomocí určeného znaku oddělovače |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Obalí matematický prvek v závorkách |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Obalí matematický prvek v určených znacích, jako jsou závorky nebo jiné znaky jako rámec |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Použije funkci argumentu s tímto exemplářem jako názvem funkce |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Použije funkci argumentu s tímto exemplářem jako názvem funkce |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Získá podřízené prvky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Umístí tento prvek do skupiny pomocí znaku skupiny, jako je dolní složená závorka nebo jiný znak |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Vezme integrál bez mezí |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Vezme integrál |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Vezme integrál |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Spojí matematický prvek a vytvoří matematický blok |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Spojí matematický text a vytvoří matematický blok |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Vytvoří N-ární operátor |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Vytvoří N-ární operátor |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Umístí čáru na vrchol tohoto prvku |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Umístí tento prvek do ohraničeného rámečku |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Umístí tento prvek do ohraničeného rámečku |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Umístí tento prvek do neviditelného rámečku (logické seskupení), který slouží k seskupení komponent rovnice nebo jiného matematického textu. Objekt v rámečku může (například) fungovat jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Vloží do svislého pole |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Umístí čáru na spodní část tohoto prvku |

### Příklady

Příklad:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Viz také

* třída [MathElementBase](../mathelementbase)
* rozhraní [IMathDelimiter](../imathdelimiter)
* jmenný prostor [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->