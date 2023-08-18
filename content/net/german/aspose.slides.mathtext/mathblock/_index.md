---
title: MathBlock
second_title: Aspose.Slides für .NET-API-Referenz
description: Gibt eine Instanz von mathematischem Text an der in einem MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Bereiche einschließlich Gleichungen Ausdrücke Arrays von Gleichungen oder Ausdrücken und Formeln werden durch mathematische Blöcke dargestellt.
type: docs
weight: 7900
url: /de/aspose.slides.mathtext/mathblock/
---
## MathBlock class

Gibt eine Instanz von mathematischem Text an, der in einem MathParagraph enthalten ist und in einer eigenen Zeile beginnt. Alle mathematischen Bereiche, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken, und Formeln werden durch mathematische Blöcke dargestellt.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Initialisiert eine neue Instanz der MathBlock-Klasse. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Erstellt einen neuen mathematischen Block und fügt bestimmte Elemente darin ein |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Erstellt einen neuen mathematischen Block und fügt das angegebene Element darin ein |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Ruft die Anzahl der untergeordneten mathematischen Elemente ab, die tatsächlich in der Sammlung enthalten sind. SchreibgeschütztInt32 . |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Gibt „false“ zurück, da die Sammlung untergeordneter Elemente geändert werden kann. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Ruft IMathElement am angegebenen Index ab oder legt es fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Fügt ein mathematisches Element am Ende der Sammlung hinzu. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Akzeptiert die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Akzeptiert die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Akzeptiert die angegebene Funktion unter Verwendung dieser Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Akzeptiert die angegebene Funktion mit dieser Instanz als Argument und dem angegebenen zusätzlichen Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Akzeptiert die angegebene Funktion mit dieser Instanz als Argument und dem angegebenen zusätzlichen Argument |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Entfernt alle Elemente aus der Sammlung. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | In angegebenes Array kopieren. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Begrenzt untergeordnete Elemente mit Trennzeichen (ohne Klammern) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erzeugt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erzeugt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erzeugt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erzeugt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Schließt untergeordnete Elemente dieses Blocks in bestimmte Zeichen wie Klammern oder andere Zeichen wie framing ein |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Schließt untergeordnete Elemente dieses Blocks in bestimmte Zeichen wie Klammern oder andere als Rahmen ein und begrenzt sie mit einem Trennzeichen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsname |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsname |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Holen Sie sich untergeordnete Elemente |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie z. B. untere geschweifte Klammer oder other |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Fügt ein MathElement am angegebenen Index in die Sammlung ein. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Verbindet ein mathematisches Element mit diesem mathematischen Block |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Verbindet einen mathematischen Text mit diesem mathematischen Block |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Verbindet einen anderen mathematischen Block mit diesem |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-stelligen Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-stelligen Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Leiste oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grads aus dem angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grads aus dem angegebenen Argument an. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | nimmt untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | nimmt untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt Index |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt Index |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Tief- und Hochstellung auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Tief- und Hochstellung auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erzeugt tiefgestellt und hochgestellt auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erzeugt tiefgestellt und hochgestellt auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt hochgestellte |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt hochgestellte |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | nimmt Obergrenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | nimmt Obergrenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Rahmenbox |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Rahmenbox |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht sichtbaren Box (logische Gruppierung) , die verwendet wird, um Komponenten einer Gleichung oder eines anderen mathematischen Textes zu gruppieren. Ein Box-Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtung dienen Punkt, dienen als Zeilenumbruchpunkt oder werden so gruppiert, dass keine Zeilenumbrüche innerhalb von zulässig sind. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Fügt untergeordnete Elemente in ein vertikales Array ein |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt einen Balken am unteren Rand dieses Elements |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Speichert den Inhalt davon[`MathBlock`](../mathblock) als MathML |

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Siehe auch

* class [MathElementBase](../mathelementbase)
* interface [IMathBlock](../imathblock)
* namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
