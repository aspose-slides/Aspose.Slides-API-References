---
title: MathAccent
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt die Akzentfunktion an, die aus einer Basis und einem kombinierenden diakritischen Zeichen besteht Beispiel ́
type: docs
weight: 8270
url: /de/aspose.slides.mathtext/mathaccent/
---

## MathAccent-Klasse

Gibt die Akzentfunktion an, die aus einer Basis und einem kombinierenden diakritischen Zeichen besteht Beispiel: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element mit dem Standardwert des Akzentzeichens angewendet wird |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | Das Argument, auf das der Akzent angewendet wurde |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | Akzentzeichen Der Wert sollte im Bereich von (U+0300–U+036F) oder (U+20D0–U+20EF) liegen. Standardwert: Kombinierender Zirkumflexakzent (U+0302) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion, die diese Instanz als Argument verwendet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion, die diese Instanz als Argument verwendet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion, die diese Instanz als Argument verwendet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion, die diese Instanz als Argument und das angegebene zusätzliche Argument verwendet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion, die diese Instanz als Argument und das angegebene zusätzliche Argument verwendet |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen zur Umrahmung ein |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments, die diese Instanz als Funktionsnamen verwendet |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments, die diese Instanz als Funktionsnamen verwendet |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | Holt die Kind-Elemente |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe unter Verwendung eines Gruppierungszeichens, wie einer geschweiften Klammer unten oder einem anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie auf das obere Ende dieses Elements |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefenindex |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefenindex |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt einen Tiefen- und Hochstelltaste auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt einen Tiefen- und Hochstelltaste auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt einen Tiefen- und Hochstelltaste auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt einen Tiefen- und Hochstelltaste auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt einen Hochstelltaste |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt einen Hochstelltaste |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in eine Rahmenbox |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in eine Rahmenbox |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in eine nicht sichtbare Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder eines anderen Beispiels mathematischen Textes zu gruppieren. Ein eingekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne einen Ausrichtungs-Punkt dienen, als Zeilenumbruch-Punkt dienen oder so gruppiert werden, dass Zeilenumbrüche darin nicht erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Platziert in ein vertikales Array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie auf die Unterseite dieses Elements |

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathAccent](../imathaccent)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)