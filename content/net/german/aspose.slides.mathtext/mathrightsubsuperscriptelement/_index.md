---
title: MathRightSubSuperscriptElement
second_title: Aspose.Sildes für .NET API-Referenz
description: Gibt das Sub-Superscript-Objekt an, das aus einer Basis und einem hochgestellten und tiefgestellten Zeichen besteht, die rechts von der Basis platziert sind.
type: docs
weight: 8690
url: /de/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---

## MathRightSubSuperscriptElement-Klasse

Gibt das Sub-Superscript-Objekt an, das aus einer Basis und einem hochgestellten und tiefgestellten Zeichen besteht, die rechts von der Basis platziert sind.

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | Initialisiert eine neue Instanz der MathRightSubSuperscriptElement-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts) { get; set; } | Gibt die Ausrichtung von hochgestelltem/tiefgestelltem Zeichen an. Wenn true, sind hochgestelltes und tiefgestelltes Zeichen horizontal aufeinander ausgerichtet. Wenn false, sind sie an die Form der Basis angekoppelt. Der Standardwert ist false. |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Basis-Argument |
| [Subscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript) { get; } | Tiefgestellt-Argument |
| [Superscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript) { get; } | Hochgestellt-Argument |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Verwendet diese Instanz als Argument für die angegebene Funktion |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Verwendet diese Instanz als Argument für die angegebene Funktion |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Verwendet diese Instanz als Argument für die angegebene Funktion |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Verwendet diese Instanz als Argument für die angegebene Funktion und ein angegebenes zusätzliches Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Verwendet diese Instanz als Argument für die angegebene Funktion und ein angegebenes zusätzliches Argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Verwendet diese Instanz als Funktionsnamen für ein Argument |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Verwendet diese Instanz als Funktionsnamen für ein Argument |
| [GetChildren](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/getchildren)() | Holt Kind-Elemente |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mithilfe einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mithilfe eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einer anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Vereint ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Vereint einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ary-Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ary-Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oben auf diesem Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefgestellt- |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefgestellt- |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Hoch- und Tiefgestellt-Zeichen auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Hoch- und Tiefgestellt-Zeichen auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt Hoch- und Tiefgestellt-Zeichen auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt Hoch- und Tiefgestellt-Zeichen auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt einen Hochgestellt- |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt einen Hochgestellt- |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einen Randkasten |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einen Randkasten |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in eine nicht sichtbare Box (logische Gruppierung), die zur Gruppierung von Komponenten einer Gleichung oder anderen Instanzen mathematischen Textes verwendet wird. Ein boxiertes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt, als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass Zeilenumbrüche nicht innerhalb erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Setzt in ein vertikales Array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie unten auf diesem Element |

### Beispiele

Beispiel:

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### Siehe Auch

* Klasse [BaseScript](../basescript)
* Schnittstelle [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->