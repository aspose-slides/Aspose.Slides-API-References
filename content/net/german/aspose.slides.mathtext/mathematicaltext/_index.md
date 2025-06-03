---
title: MathematicalText
second_title: Aspose.Slides für .NET API-Referenz
description: Mathematischer Text
type: docs
weight: 8790
url: /de/aspose.slides.mathtext/mathematicaltext/
---

## MathematischerText-Klasse

Mathematischer Text

```csharp
public sealed class MathematischerText : MathElementBase, IMathematicalText
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathematischerText](mathematischertext#constructor)() | Standardkonstruktor (erstellt String.Empty Wert) |
| [MathematischerText](mathematischertext#constructor_1)(char) | Erstellt MathText mit einem einzelnen Symbol |
| [MathematischerText](mathematischertext#constructor_2)(string) | Erstellt MathematischerText aus Text |
| [MathematischerText](mathematischertext#constructor_3)(string, IPortionFormat) | Erstellt MathematischerText aus Text und Formatierungseinstellungen |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Format](../../aspose.slides.mathtext/mathematischertext/format) { get; } | Texteigenschaften zur Formatierung |
| [Wert](../../aspose.slides.mathtext/mathematischertext/wert) { get; set; } | Textwert |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Akzent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AlsArgumentFürFunktion](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AlsArgumentFürFunktion](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AlsArgumentFürFunktion](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AlsArgumentFürFunktion](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und das angegebene zusätzliche Argument |
| [AlsArgumentFürFunktion](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und das angegebene zusätzliche Argument |
| [Teilen](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Teilen](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Teilen](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Teilen](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Einschließen](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| virtual [Einschließen](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmung ein |
| [Funktion](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |
| [Funktion](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |
| [Gruppe](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Gruppe](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe unter Verwendung eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einer anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Verbinden](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Verbinden](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [N-ary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ary-Operator |
| [N-ary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ary-Operator |
| [Oberstrich](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt einen Strich oben auf dieses Element |
| [Radikal](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [Radikal](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefenindex |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefenindex |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Tiefenindex und Hochindex auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Tiefenindex und Hochindex auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt Tiefenindex und Hochindex auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt Tiefenindex und Hochindex auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt Hochindex |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt Hochindex |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in eine Border-Box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in eine Border-Box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in eine nicht sichtbare Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder eine andere Instanz von mathematischem Text zu gruppieren. Ein umschlossenes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt dienen oder so gruppiert sein, dass Zeilenumbrüche innerhalb nicht erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Platziert in einem vertikalen Array |
| [Unterstrich](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt einen Strich unten auf dieses Element |

### Beispiele

Beispiel:

```csharp
[C#]
MathematischerText mathText = new MathematischerText("x+y");
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathematicalText](../imathematicaltext)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->