---
title: MathBlock
second_title: Aspose.Slides für .NET API Referenz
description: Gibt eine Instanz von mathematischem Text an, die sich innerhalb eines MathParagraph befindet und in einer eigenen Zeile beginnt. Alle Mathematikzonen, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch den MathBlock dargestellt.
type: docs
weight: 8330
url: /de/aspose.slides.mathtext/mathblock/
---

## MathBlock-Klasse

Gibt eine Instanz von mathematischem Text an, die sich innerhalb eines MathParagraph befindet und in einer eigenen Zeile beginnt. Alle Mathematikzonen, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch den MathBlock dargestellt.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initialisiert eine neue Instanz der MathBlock-Klasse. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Erstellt einen neuen mathematischen Block und fügt die angegebenen Elemente hinzu. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Erstellt einen neuen mathematischen Block und fügt das angegebene Element hinzu. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Gibt die Anzahl der echten Kind-Mathematikelemente zurück, die in der Sammlung enthalten sind. Nur lesbarer Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Gibt false zurück, da die Sammlung von Kind-Elementen geändert werden kann. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Gibt das IMathElement am angegebenen Index zurück oder setzt es. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Fügt ein Mathematikelement am Ende der Sammlung hinzu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und das angegebene zusätzliche Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und das angegebene zusätzliche Argument. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Entfernt alle Elemente aus der Sammlung. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Bestimmt, ob die Sammlung einen spezifischen Wert enthält. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopiert in das angegebene Array. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Abgrenzt Kind-Elemente mit einem Trennzeichen (ohne die Klammern). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein Mathematikelement in Klammern ein. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Schließt die Kind-Elemente dieses Blocks in die angegebenen Zeichen wie Klammern oder andere Zeichen als Rahmen ein. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Schließt die Kind-Elemente dieses Blocks in die angegebenen Zeichen wie Klammern oder andere zur Rahmung ein und trennt mit einem Trennzeichen. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Holt die Kind-Elemente. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer unteren geschweiften Klammer oder einer anderen. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bestimmt den Index eines spezifischen Mathematikelements in der Sammlung. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Fügt ein MathElement an dem angegebenen Index in die Sammlung ein. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Verbindet ein mathematisches Element mit diesem mathematischen Block. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Verbindet einen mathematischen Text mit diesem mathematischen Block. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Verbindet einen anderen mathematischen Block mit diesem. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ary Operator. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ary Operator. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oben auf dieses Element. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades von dem angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades von dem angegebenen Argument an. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Entfernt das erste Vorkommen eines spezifischen Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen tiefgestellten Text. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen tiefgestellten Text. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt einen tiefgestellten und einen hochgestellten Text auf der linken Seite. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt einen tiefgestellten und einen hochgestellten Text auf der linken Seite. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt einen tiefgestellten und einen hochgestellten Text auf der rechten Seite. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt einen tiefgestellten und einen hochgestellten Text auf der rechten Seite. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt einen hochgestellten Text. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt einen hochgestellten Text. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Border-Box. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Border-Box. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder einer anderen Instanz mathematischen Textes zu gruppieren. Ein eingekästetes Objekt kann (zum Beispiel) als Operator-Emulator dienen, mit oder ohne einen Ausrichtungspunkt, als Zeilenumbruchpunkt dienen oder gruppiert werden, sodass innerhalb dessen keine Zeilenumbrüche zugelassen sind. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Stellt die Kind-Elemente in einem vertikalen Array dar. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie unten auf dieses Element. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Speichert den Inhalt dieses [`MathBlock`](../mathblock) als MathML. |

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathBlock](../imathblock)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->