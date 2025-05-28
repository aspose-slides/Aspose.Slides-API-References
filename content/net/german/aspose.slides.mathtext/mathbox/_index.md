---
title: MathBox
second_title: Aspose.Slides für .NET API Referenz
description: Gibt die logische Verpackung Boxing von mathematischen Elementen an. Ein verpacktes Objekt kann beispielsweise als Operator-Emulator mit oder ohne einen Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert sein, dass innerhalb der Box keine Zeilenumbrüche erlaubt sind. Beispielsweise sollte der "==" Operator verpackt werden, um Zeilenumbrüche zu verhindern.
type: docs
weight: 8370
url: /de/aspose.slides.mathtext/mathbox/
---

## MathBox Klasse

Gibt die logische Verpackung (Boxing) von mathematischen Elementen an. Ein verpacktes Objekt kann beispielsweise als Operator-Emulator mit oder ohne einen Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert sein, dass innerhalb der Box keine Zeilenumbrüche erlaubt sind. Beispielsweise sollte der "==" Operator verpackt werden, um Zeilenumbrüche zu verhindern.

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
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Wenn wahr, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, bestimmte Ausrichtungs­punkte in anderen Gleichungen können mit ihm ausgerichtet werden. Standardwert: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Basisargument |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential Wenn wahr, fungiert die Box als Differential (z.B. 𝑑𝑥 in einem Integranden) und erhält den passenden horizontalen Abstand für das mathematische Differential. Standardwert: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Expliziter Bruch gibt an, ob es einen Zeilenumbruch am Anfang des Box-Objekts gibt, sodass die Zeile am Anfang des Box-Objekts umbricht. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, die als Ausrichtungs­punkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255. Standardwert: 0 (kein expliziter Bruch) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Kein Bruch Diese Eigenschaft gibt die "nicht unterbrechbare" Eigenschaft des Objekt-Box an. Wenn wahr, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann wichtig sein für Operator-Emulatoren, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können Brüche innerhalb der Box auftreten. Standardwert: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator-Emulator. Wenn wahr, verhält sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Dies bedeutet beispielsweise, dass das Zeichen als Punkt für einen Zeilenumbruch dienen und an andere Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen kombiniert werden, um einen Operator zu bilden, wie z.B. '=='. Standardwert: false |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und einem angegebenen zusätzlichen Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und einem angegebenen zusätzlichen Argument |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen ein, wie z.B. Klammern oder andere Zeichen als Rahmen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Gibt untergeordnete Elemente zurück |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit geschweiftem Klammer unten |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie geschweiftem Klammer oder einem anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie auf die Oberseite dieses Elements |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des gegebenen Grades vom angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des gegebenen Grades vom angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt eine Untergrenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt eine Untergrenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen tiefgestellten Text |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen tiefgestellten Text |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt einen tiefgestellten und einen hochgestellten Text auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt einen tiefgestellten und einen hochgestellten Text auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt einen tiefgestellten und einen hochgestellten Text auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt einen tiefgestellten und einen hochgestellten Text auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt einen hochgestellten Text |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt einen hochgestellten Text |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt eine Obergrenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt eine Obergrenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einem Rahmen-Box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einem Rahmen-Box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht visuellen Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder anderer mathematischer Texte zu gruppieren. Ein verpacktes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne einen Ausrichtungs­punkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert sein, dass innerhalb der Box keine Zeilenumbrüche erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Setzt in ein vertikales Array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie am unteren Ende dieses Elements |

### Beispiele

Beispiel:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathBox](../imathbox)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->