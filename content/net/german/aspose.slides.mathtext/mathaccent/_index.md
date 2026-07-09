---
title: MathAccent
second_title: Aspose.Sildes für .NET API-Referenz
description: Gibt die Akzentfunktion an, die aus einer Basis und einem kombinierenden diakritischen Zeichen besteht. Beispiel ́
type: docs
weight: 8530
url: /de/aspose.slides.mathtext/mathaccent/
---
## MathAccent Klasse

Gibt die Akzentfunktion an, die aus einer Basis und einem kombinierenden diakritischen Zeichen besteht. Beispiel: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathelement angewendet wird, mit dem Standardwert für das Akzentzeichen. |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathelement angewendet wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | Das Argument, auf das der Akzent angewendet wurde. |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | Akzentzeichen. Der Wert sollte im Bereich (U+0300–U+036F) oder (U+20D0–U+20EF) liegen. Standardwert: Kombinierender Zirkumflex-Akzent (U+0302). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet wird. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet wird. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Umfasst ein Mathelement in Klammern. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Umfasst ein Mathelement in den angegebenen Zeichen, wie z.B. Klammern oder anderen Rahmenzeichen. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Verwendet eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Verwendet eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird. |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | Ruft Kindelemente ab. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, wie z.B. einer geschweiften Klammer unten oder einem anderen Zeichen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Erstellt ein Integral ohne Grenzen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Erstellt ein Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Erstellt ein Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Erstellt ein Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Erstellt ein Integral. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMMathElement) | Erstellt einen N-ären Operator. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt einen Balken oben auf dieses Element. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Erfasst die untere Grenze. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Erfasst die untere Grenze. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Index. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Index. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Index und Hochstellung links. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Index und Hochstellung links. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt Index und Hochstellung rechts. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt Index und Hochstellung rechts. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt eine Hochstellung. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt eine Hochstellung. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Erfasst die obere Grenze. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Erfasst die obere Grenze. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Rahmen-Box. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Rahmen-Box. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung), die zur Gruppierung von Komponenten einer Gleichung oder anderer mathematischer Texte verwendet wird. Ein umrandetes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Setzt in ein vertikales Array. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt einen Balken unten auf dieses Element. |

### Beispiele

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathAccent](../imathaccent)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->