---
title: MathBlock
second_title: Aspose.Sildes für .NET API-Referenz
description: Gibt eine Instanz von mathematischem Text an, die innerhalb eines MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch einen MathBlock dargestellt.
type: docs
weight: 8610
url: /de/aspose.slides.mathtext/mathblock/
---
## MathBlock Klasse

Specifiziert eine Instanz von mathematischem Text, die in einem MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken und Formeln werden durch einen MathBlock dargestellt.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktoren

| Name | Description |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initialisiert eine neue Instanz der MathBlock Klasse. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Erstellt einen neuen mathematischen Block und fügt die angegebenen Elemente ein |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Erstellt einen neuen mathematischen Block und fügt das angegebene Element ein |

## Eigenschaften

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Liefert die Anzahl der tatsächlich in der Sammlung enthaltenen Kind-Matheelemente. Nur-Lesen Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Gibt false zurück, weil die Sammlung der Kind-Elemente modifiziert werden kann. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Liefert oder setzt IMathElement am angegebenen Index. |

## Methoden

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Fügt ein mathematisches Element am Ende der Sammlung hinzu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Verwendet die angegebene Funktion mit dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Verwendet die angegebene Funktion mit dieser Instanz als Argument und dem angegebenen zusätzlichen Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Verwendet die angegebene Funktion mit dieser Instanz als Argument und dem angegebenen zusätzlichen Argument |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Entfernt alle Elemente aus der Sammlung. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Kopiert in das angegebene Array. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Trennt Kind-Elemente mit Trennzeichen (ohne Klammern) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Umschließt ein Mathe-Element in Klammern |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Umschließt Kind-Elemente dieses Blocks in den angegebenen Zeichen, z. B. Klammern oder andere Zeichen als Rahmen |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Umschließt Kind-Elemente dieses Blocks in den angegebenen Zeichen, z. B. Klammern oder andere, und trennt sie mit einem Trennzeichen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Verwendet eine Funktion eines Arguments, wobei diese Instanz als Funktionsname dient |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Verwendet eine Funktion eines Arguments, wobei diese Instanz als Funktionsname dient |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Gibt Kind-Elemente zurück |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, z. B. einer unteren geschweiften Klammer oder einem anderen |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bestimmt den Index eines bestimmten Mathe-Elements in der Sammlung. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Fügt ein MathElement an der angegebenen Position in die Sammlung ein. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Verwendet das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Verwendet das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Verwendet das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Verwendet das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Verwendet das Integral |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Verknüpft ein mathematisches Element mit diesem mathematischen Block |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Verknüpft mathematischen Text mit diesem mathematischen Block |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Verknüpft einen anderen mathematischen Block mit diesem |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt einen Strich über diesem Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Verwendet die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Verwendet die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefstellung (Subscript) |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefstellung (Subscript) |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Tiefstellung und Hochstellung links |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Tiefstellung und Hochstellung links |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt Tiefstellung und Hochstellung rechts |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt Tiefstellung und Hochstellung rechts |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt Hochstellung |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt Hochstellung |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Verwendet die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Verwendet die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Rahmen-Box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Rahmen-Box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung), die zum Gruppieren von Komponenten einer Gleichung oder anderen mathematischen Text verwendet wird. Ein umrandetes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass Zeilenumbrüche darin nicht erlaubt sind. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Ordnet Kind-Elemente in einem vertikalen Array an |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt einen Strich unter diesem Element |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Speichert den Inhalt dieses [`MathBlock`](../mathblock) als MathML |

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Siehe Auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathBlock](../imathblock)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->