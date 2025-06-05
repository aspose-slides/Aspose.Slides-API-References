---
title: MathGroupingCharacter
second_title: Aspose.Slides für .NET API Referenz
description: Gibt ein Gruppensymbol über oder unter einem Ausdruck an, um üblicherweise die Beziehung zwischen Elementen hervorzuheben
type: docs
weight: 8500
url: /de/aspose.slides.mathtext/mathgroupingcharacter/
---

## MathGroupingCharacter-Klasse

Gibt ein Gruppensymbol über oder unter einem Ausdruck an, um üblicherweise die Beziehung zwischen Elementen hervorzuheben

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | Initialisiert eine neue Instanz der MathGroupingCharacter-Klasse mit dem standardmäßigen Gruppierungszeichen U+23DF (UNTERE GLOCKENKLAMMER) |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | Initialisiert eine neue Instanz der MathGroupingCharacter-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | Basisargument |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | Gruppierungszeichen Standardwert: U+23DF (UNTERE GLOCKENKLAMMER) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | Position des Gruppierungszeichens. Standard: Unten |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | Vertikale Rechtfertigung des Gruppenzeichens. Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an. Wenn das Gruppenzeichen über dem Objekt liegt, bedeutet die Vertikale Rechtfertigung von Oben, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn die Vertikale Rechtfertigung auf Unten eingestellt ist, ist die Unterseite des Objekts auf der Grundlinie. Standard: Unten für Position=Oben und Oben für Position=Unten |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument und das angegebene zusätzliche Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument und das angegebene zusätzliche Argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein Mathematik-Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein Mathematik-Element in angegebenen Zeichen wie Klammern oder anderen ein |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | Gibt die Kind-Elemente zurück |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer unteren geschweiften Klammer oder einer anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Fügt ein mathematisches Element zusammen und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Fügt einen mathematischen Text zusammen und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des gegebenen Grades aus dem angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des gegebenen Grades aus dem angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen tiefgestellten Text |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen tiefgestellten Text |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt tiefgestellten Text und hochgestellten Text links |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt tiefgestellten Text und hochgestellten Text links |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt tiefgestellten Text und hochgestellten Text rechts |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt tiefgestellten Text und hochgestellten Text rechts |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt einen hochgestellten Text |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt einen hochgestellten Text |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Border-Box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Border-Box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder andere Instanzen von mathematischem Text zu gruppieren. Ein eingekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass Zeilenumbrüche innerhalb nicht erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Platziert in einem vertikalen Array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie unten auf dieses Element |

### Beispiele

Beispiel:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathGroupingCharacter](../imathgroupingcharacter)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->