---
title: MathAccent
second_title: Aspose.Slides für .NET API-Referenz
description: Spezifiziert die Akzentfunktion, die aus einer Basis und einem kombinierenden diakritischen Zeichen besteht Beispiel ́
type: docs
weight: 8270
url: /de/aspose.slides.mathtext/mathaccent/
---

## MathAccent-Klasse

Spezifiziert die Akzentfunktion, die aus einer Basis und einem kombinierenden diakritischen Zeichen besteht Beispiel: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathematikelement mit dem Standardwert des Akzentzeichens angewendet wird |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathematikelement angewendet wird |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | Das Argument, auf das der Akzent angewendet wurde |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | Akzentzeichen Der Wert sollte im Bereich von (U+0300–U+036F) oder (U+20D0–U+20EF) liegen. Standardwert: Kombinierender Zirkumflex-Akzent (U+0302) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt eine angegebene Funktion, die diese Instanz als Argument verwendet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt eine angegebene Funktion, die diese Instanz als Argument verwendet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt eine angegebene Funktion, die diese Instanz als Argument verwendet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt eine angegebene Funktion, die diese Instanz als Argument und ein zusätzliches angegebenes Argument verwendet |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt eine angegebene Funktion, die diese Instanz als Argument und ein zusätzliches angegebenes Argument verwendet |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein Mathematikelement in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein Mathematikelement in angegebene Zeichen wie Klammern oder andere Zeichen als Rahmen ein |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments, das diese Instanz als Funktionsname verwendet |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments, das diese Instanz als Funktionsname verwendet |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | Holt Kinderelemente |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer unteren geschweiften Klammer oder einem anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefstellung |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefstellung |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt eine Tiefstellung und Hochstellung auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt eine Tiefstellung und Hochstellung auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt eine Tiefstellung und Hochstellung auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt eine Tiefstellung und Hochstellung auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt eine Hochstellung |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt eine Hochstellung |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einem Border-Box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einem Border-Box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht visuellen Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder eines anderen mathematischen Textes zu gruppieren. Ein boxiertes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungs- punkt dienen, als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass Zeilenumbrüche nicht innerhalb erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Setzt in ein vertikales Array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie unten auf dieses Element |

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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->