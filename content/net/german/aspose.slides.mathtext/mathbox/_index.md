---
title: MathBox
second_title: Aspose.Sildes für .NET API-Referenz
description: Bestimmt das logische Verpacken von mathematischen Elementen. Ein in einem Kasten gefasstes Objekt kann beispielsweise als Operator-Emulator mit oder ohne einen Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass Zeilenumbrüche innerhalb nicht erlaubt sind. Beispielsweise sollte der "=="-Operator in einem Kasten gefasst werden, um Zeilenumbrüche zu verhindern.
type: docs
weight: 8370
url: /de/aspose.slides.mathtext/mathbox/
---

## MathBox-Klasse

Bestimmt das logische Verpacken (Packaging) von mathematischen Elementen. Ein in einem Kasten gefasstes Objekt kann beispielsweise als Operator-Emulator mit oder ohne einen Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass Zeilenumbrüche innerhalb nicht erlaubt sind. Beispielsweise sollte der "=="-Operator in einem Kasten gefasst werden, um Zeilenumbrüche zu verhindern.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Initialisiert MathBox mit dem angegebenen Element als Argument |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, ausgewählte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden. Standard: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Basisargument |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential Wenn true, verhält sich der Kasten wie ein Differential (z.B. 𝑑𝑥 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Ein expliziter Bruch gibt an, ob es einen Zeilenumbruch am Anfang des Box-Objekts gibt, so dass der Zeilenumbruch am Anfang des Box-Objekts erfolgt. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Texts an, der als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Texts verwendet werden soll mögliche Werte: 1..255 Standard: 0 (kein expliziter Bruch) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Kein Bruch Diese Eigenschaft gibt die "unbrechbare" Eigenschaft des Objektkastens an. Wenn true, können innerhalb des Kastens keine Zeilenumbrüche auftreten. Dies kann wichtig sein für Operator-Emulatoren, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb des Kastens Brüche auftreten. Standard: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator-Emulator. Wenn true, verhalten sich der Kasten und dessen Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenumbruch dienen und mit anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z.B. '=='. Standardwert: false |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion an, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion an, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion an, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion an, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion an, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet wird |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments an, wobei diese Instanz als Funktionsname verwendet wird |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments an, wobei diese Instanz als Funktionsname verwendet wird |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Holt die Kindelemente |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer unteren geschweiften Klammer oder einem anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ary Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ary Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des gegebenen Grades vom angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des gegebenen Grades vom angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefgestellten |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefgestellten |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt einen Tiefgestellten und Hochgestellten links |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt einen Tiefgestellten und Hochgestellten links |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt einen Tiefgestellten und Hochgestellten rechts |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt einen Tiefgestellten und Hochgestellten rechts |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt einen Hochgestellten |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt einen Hochgestellten |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Border-Box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Border-Box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einem unsichtbaren Kasten (logische Gruppierung), der verwendet wird, um Komponenten einer Gleichung oder anderer Instanzen von mathematischem Text zu gruppieren. Ein in einem Kasten gefasstes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne einen Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass Zeilenumbrüche innerhalb nicht erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Setzt in ein vertikales Array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie am unteren Rand dieses Elements |

### Beispiele

Beispiel:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Siehe Auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathBox](../imathbox)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->