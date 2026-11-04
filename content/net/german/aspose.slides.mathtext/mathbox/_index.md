---
title: MathBox
second_title: Aspose.Sildes für .NET API-Referenz
description: Gibt die logische Kapselung (Verpackung) eines mathematischen Elements an. Zum Beispiel kann ein gekapseltes Objekt als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass keine Zeilenumbrüche innerhalb erlaubt sind. Zum Beispiel sollte der Operator gekapselt werden, um Zeilenbrüche zu verhindern.
type: docs
weight: 8650
url: /de/aspose.slides.mathtext/mathbox/
---
## MathBox Klasse

Gibt die logische Kapselung (Verpackung) eines mathematischen Elements an. Zum Beispiel kann ein gekapseltes Objekt als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass keine Zeilenumbrüche innerhalb erlaubt sind. Zum Beispiel sollte der "=="-Operator gekapselt werden, um Zeilenumbrüche zu verhindern.

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
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, benannte Ausrichtungspunkte in anderen Gleichungen können an ihm ausgerichtet werden. Standard: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Basisargument |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differential Wenn true, wirkt die Box als Differential (z. B. 𝑑𝑥 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch stattfindet, sodass die Zeile am Anfang des Box-Objekts umbrochen wird. Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, die als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll. Mögliche Werte: 1..255 Standard: 0 (kein expliziter Umbruch) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Kein Umbruch Diese Eigenschaft legt die „unbreakable“-Eigenschaft des Objekt-Box fest. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten. Dies kann bei Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. Wenn dieses Element nicht angegeben ist, können innerhalb der Box Umbrüche auftreten. Standard: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator-Emulator. Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenumbruch dienen und an anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, z. B. '=='. Standardwert: false |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet werden |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet werden |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebene Zeichen ein, wie z. B. Klammern oder andere Zeichen als Rahmen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Gibt Kind-Elemente zurück |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, wie einer unteren geschweiften Klammer oder einem anderen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMMathElement, IMathElement) | Erstellt einen N-ären Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt einen Balken oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem spezifizierten Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades aus dem spezifizierten Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt Tiefstellung |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt Tiefstellung |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Tief- und Hochstellung links |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Tief- und Hochstellung links |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt Tief- und Hochstellung rechts |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt Tief- und Hochstellung rechts |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt Hochstellung |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt Hochstellung |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Rahmen-Box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Rahmen-Box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder einer anderen Instanz mathematischen Textes zu gruppieren. Ein gekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass keine Zeilenumbrüche innerhalb erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Platziert in einem vertikalen Array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt einen Balken unten auf dieses Element |

### Beispiele

Beispiel:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathBox](../imathbox)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->