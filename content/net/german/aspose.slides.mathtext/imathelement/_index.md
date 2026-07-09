---
title: IMathElement
second_title: Aspose.Sildes für .NET API-Referenz
description: Basisschnittstelle für jedes mathematische Element: Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw.
type: docs
weight: 8230
url: /de/aspose.slides.mathtext/imathelement/
---
## IMathElement Schnittstelle

Basisschnittstelle für jedes mathematische Element: Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw.

```csharp
public interface IMathElement
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Verwendet die angegebene Funktion mit dieser Instanz als Argument und dem angegebenen zusätzlichen Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Verwendet die angegebene Funktion mit dieser Instanz als Argument und dem angegebenen zusätzlichen Argument |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Schließt ein mathematisches Element in Klammern ein |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Schließt dieses Element in den angegebenen Zeichen, zum Beispiel Klammern oder andere Zeichen als Rahmen ein |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Verwendet eine Funktion eines Arguments und nutzt diese Instanz als Funktionsnamen |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Verwendet eine Funktion eines Arguments und nutzt diese Instanz als Funktionsnamen |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Liefert Kindelemente |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, wie einer geschweiften Klammer unten oder einem anderen |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Erzeugt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Erzeugt das Integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Erzeugt das Integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Erzeugt das Integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Erzeugt das Integral |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Setzt einen Balken oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Bestimmt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Bestimmt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Ermittelt die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Ermittelt die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Erstellt einen tiefgestellten Index |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Erstellt einen tiefgestellten Index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt tief- und hochgestellten Index links |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Erstellt tief- und hochgestellten Index links |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt tief- und hochgestellten Index rechts |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Erstellt tief- und hochgestellten Index rechts |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Erstellt einen hochgestellten Index |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Erstellt einen hochgestellten Index |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Ermittelt die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Ermittelt die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Platziert dieses Element in einem Rahmenkasten |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einem Rahmenkasten |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Platziert dieses Element in einem nicht-sichtbaren Kasten (logische Gruppierung), der dazu dient, Komponenten einer Gleichung oder anderen mathematischen Textes zu gruppieren. Ein solcher Kasten kann (beispielsweise) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche zulässig sind. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Platziert in einem vertikalen Array |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Setzt einen Balken unten auf dieses Element |

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Siehe auch

* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->