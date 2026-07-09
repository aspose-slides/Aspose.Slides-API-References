---
title: MathBlock
second_title: Aspose.Sildes für .NET API-Referenz
description: Gibt eine Instanz mathematischen Textes an, die innerhalb eines MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch einen MathBlock dargestellt.
type: docs
weight: 8590
url: /de/aspose.slides.mathtext/mathblock/
---
## MathBlock Klasse

Gibt eine Instanz mathematischen Textes an, die innerhalb eines MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücken, Arrays von Gleichungen oder Ausdrücken und Formeln werden durch einen MathBlock dargestellt.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initialisiert eine neue Instanz der MathBlock Klasse. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Erstellt einen neuen mathematischen Block und fügt die angegebenen Elemente ein. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Erstellt einen neuen mathematischen Block und fügt das angegebene Element ein. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Gibt die Anzahl der untergeordneten Math-Elemente zurück, die tatsächlich in der Sammlung enthalten sind. Nur-Lese Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Gibt false zurück, weil die Sammlung der Kindelemente verändert werden kann. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Liefert oder setzt das IMathElement am angegebenen Index. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Fügt ein Math-Element am Ende der Sammlung hinzu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Verwendet die angegebene Funktion unter Verwendung dieser Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Verwendet die angegebene Funktion unter Verwendung dieser Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Verwendet die angegebene Funktion unter Verwendung dieser Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Verwendet die angegebene Funktion unter Verwendung dieser Instanz als Argument und dem angegebenen zusätzlichen Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Verwendet die angegebene Funktion unter Verwendung dieser Instanz als Argument und dem angegebenen zusätzlichen Argument. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Entfernt alle Elemente aus der Sammlung. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopiert in das angegebene Array. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Trennt Kindelemente mit einem Trennzeichen (ohne die Klammern). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein Math-Element in Klammern ein. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Schließt die Kindelemente dieses Blocks in den angegebenen Zeichen, wie Klammern oder anderen Zeichen, ein. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Schließt die Kindelemente dieses Blocks in den angegebenen Zeichen, wie Klammern oder anderen, ein und trennt sie mit einem Trennzeichen. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Verwendet eine Funktion eines Arguments, wobei diese Instanz als Funktionsname dient. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Verwendet eine Funktion eines Arguments, wobei diese Instanz als Funktionsname dient. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Ruft Kindelemente ab. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe unter Verwendung eines Gruppierungszeichens, wie einer geschweiften Klammer unten oder einem anderen. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bestimmt den Index eines bestimmten Math-Elements in der Sammlung. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Fügt ein MathElement an dem angegebenen Index in die Sammlung ein. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Erzeugt das Integral ohne Grenzen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Erzeugt das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Erzeugt das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Erzeugt das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Erzeugt das Integral. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Verbindet ein mathematisches Element mit diesem mathematischen Block. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Verbindet einen mathematischen Text mit diesem mathematischen Block. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Verbindet einen anderen mathematischen Block mit diesem. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt einen Strich oben auf dieses Element. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Erzeugt die untere Grenze. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Erzeugt die untere Grenze. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt eine Tiefstellung. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt eine Tiefstellung. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Tief- und Hochstellung links. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Tief- und Hochstellung links. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt Tief- und Hochstellung rechts. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt Tief- und Hochstellung rechts. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt eine Hochstellung. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt eine Hochstellung. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Erzeugt die obere Grenze. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Erzeugt die obere Grenze. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einem Rahmenkasten. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einem Rahmenkasten. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einem nicht-visuellen Kasten (logische Gruppe), der verwendet wird, um Komponenten einer Gleichung oder einer anderen Instanz mathematischen Textes zu gruppieren. Ein in einem Kasten befindliches Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Ordnet die Kindelemente in einer vertikalen Anordnung. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt einen Strich unten auf dieses Element. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Speichert den Inhalt dieses [`MathBlock`](../mathblock) als MathML. |

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathBlock](../imathblock)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->