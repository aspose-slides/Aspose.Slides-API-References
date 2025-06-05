---
title: IMathElement
second_title: Aspose.Slides für .NET API Referenz
description: Basis-Schnittstelle für jedes mathematische Element Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw.
type: docs
weight: 7980
url: /de/aspose.slides.mathtext/imathelement/
---

## IMathElement-Schnittstelle

Basis-Schnittstelle für jedes mathematische Element: Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw.

```csharp
public interface IMathElement
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet wird |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Schließt ein mathematisches Element in Klammern ein |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Schließt dieses Element in den angegebenen Zeichen ein, wie z.B. Klammern oder andere Zeichen als Rahmen |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Liest die Kind-Elemente |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, wie z.B. einer unteren geschweiften Klammer oder einem anderen |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Setzt eine Linie oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Nimmt die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Nimmt die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Erstellt einen tiefgestellten Text |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Erstellt einen tiefgestellten Text |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt tiefgestellten und hochgestellten Text auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Erstellt tiefgestellten und hochgestellten Text auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt tiefgestellten und hochgestellten Text auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Erstellt tiefgestellten und hochgestellten Text auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Erstellt hochgestellten Text |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Erstellt hochgestellten Text |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Nimmt die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Nimmt die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Platziert dieses Element in einem Rahmen-Box |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einem Rahmen-Box |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Platziert dieses Element in einer nicht sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder eine andere Instanz von mathematischem Text zu gruppieren. Ein gekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungs Punkt dienen, als Zeilenumbruch Punkt dienen oder so gruppiert sein, dass keine Zeilenumbrüche innerhalb erfolgen. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Platziert in einem vertikalen Array |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Setzt eine Linie unten auf dieses Element |

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Siehe Auch

* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->