---
title: MathFraction
second_title: Aspose.Sildes für .NET API Referenz
description: Definiert das Bruchobjekt, das aus einem Zähler und einem Nenner besteht, die durch eine Bruchlinie getrennt sind. Die Bruchlinie kann je nach den Eigenschaften des Bruchs horizontal oder diagonal sein. Das Bruchobjekt wird auch verwendet, um die Stapelfunktion darzustellen, die ein Element über ein anderes ohne Bruchlinie legt.
type: docs
weight: 8430
url: /de/aspose.slides.mathtext/mathfraction/
---

## MathFraction-Klasse

Definiert das Bruchobjekt, das aus einem Zähler und einem Nenner besteht, die durch eine Bruchlinie getrennt sind. Die Bruchlinie kann je nach den Eigenschaften des Bruchs horizontal oder diagonal sein. Das Bruchobjekt wird auch verwendet, um die Stapelfunktion darzustellen, die ein Element über ein anderes legt, ohne eine Bruchlinie.

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | Initialisiert ein MathFraction vom Typ 'Bar' mit dem angegebenen Zähler und Nenner |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | Initialisiert MathFraction mit dem angegebenen Zähler, Nenner und Typ |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | Nenner |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | Bruchtyp Standard: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | Zähler |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und das angegebene zusätzliche Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und das angegebene zusätzliche Argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Rahmenzeichen ein |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | Holt Kinder-Elemente |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe unter Verwendung einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe unter Verwendung eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-är Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-är Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des gegebenen Grades aus dem angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des gegebenen Grades aus dem angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefgestellt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefgestellt |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt einen Tiefgestellt und Hochgestellt auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt einen Tiefgestellt und Hochgestellt auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt einen Tiefgestellt und Hochgestellt auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt einen Tiefgestellt und Hochgestellt auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt einen Hochgestellt |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt einen Hochgestellt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Randbox |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Randbox |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder anderen Instanzen von mathematischem Text zu gruppieren. Ein boxed Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne einen Ausrichtungs Punkt dienen, als Zeilenumbruchs Punkt dienen oder so gruppiert werden, dass Zeilenumbrüche innerhalb nicht erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Stellt in einem vertikalen Array dar |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie unten auf dieses Element |

### Beispiele

Beispiel:

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathFraction](../imathfraction)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->