---
title: MathPhantom
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein Phantom-Matheobjekt ltmphantgt dar, das das Layout seines Kindelements beeinflusst, ohne es zwangsläufig anzuzeigen. Ein Phantom kann seinen Basisausdruck ausblenden, dabei jedoch seine Breite, Höhe oder Tiefe beibehalten, um Formeln auszurichten oder Platz zu reservieren. Sichtbarkeits- und Geometrieverhalten werden durch Eigenschaften wie Show, ZeroWid, ZeroAsc, ZeroDesc und Transp gesteuert.
type: docs
weight: 8920
url: /de/aspose.slides.mathtext/mathphantom/
---
## MathPhantom Klasse

Stellt ein Phantom-Matheobjekt (<m:phant>) dar, das das Layout des Kindelements beeinflusst, ohne es notwendigerweise anzuzeigen. Ein Phantom kann seinen Basisausdruck ausblenden, dabei jedoch seine Breite, Höhe oder Tiefe beibehalten, um Formeln auszurichten oder Platz zu reservieren. Sichtbarkeits- und Geometrie-Verhalten werden durch Eigenschaften wie Show, ZeroWid, ZeroAsc, ZeroDesc und Transp gesteuert.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Initialisiert eine neue Instanz der [`MathPhantom`](../mathphantom) Klasse mit dem angegebenen Basismathelement. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Basisargument |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob das Basiselement angezeigt wird. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob das Phantom für klassenbasierte Abstandsregeln transparent ist. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob der Aufstieg (Höhe über der Grundlinie) des Basiselements als null behandelt werden soll. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob der Abstieg (Tiefe unter der Grundlinie) des Basiselements als null behandelt werden soll. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Liest oder legt einen Wert fest, der angibt, ob die Breite des Basiselements als null behandelt werden soll. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Verwendet die angegebene Funktion, nutzt diese Instanz als Argument und den angegebenen zusätzlichen Parameter. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Verwendet die angegebene Funktion, nutzt diese Instanz als Argument und den angegebenen zusätzlichen Parameter. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Umfasst ein Matheelement in Klammern. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Umfasst ein Matheelement in angegebenen Zeichen, wie Klammern oder anderen Zeichen als Rahmen. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Verwendet eine Funktion eines Arguments und nutzt diese Instanz als Funktionsnamen. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Verwendet eine Funktion eines Arguments und nutzt diese Instanz als Funktionsnamen. |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Ruft die Kind-Elemente ab. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mittels einer geschweiften Klammer unten. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens, wie einer geschweiften Klammer unten oder einem anderen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Verwendet das Integral ohne Grenzen. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Verwendet das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Verwendet das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Verwendet das Integral. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Verwendet das Integral. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt einen Balken oben auf dieses Element. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Verwendet die untere Grenze. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Verwendet die untere Grenze. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Index. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Index. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Index und Hochstellung links. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Index und Hochstellung links. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt Index und Hochstellung rechts. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt Index und Hochstellung rechts. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt Hochstellung. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt Hochstellung. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Verwendet die obere Grenze. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Verwendet die obere Grenze. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Rahmenbox. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Rahmenbox. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht-sichtbaren Box (logische Gruppierung), die verwendet wird, um Bestandteile einer Gleichung oder eines anderen mathematischen Textes zu gruppieren. Ein in einer Box gefesseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruch-Punkt fungieren oder so gruppiert werden, dass keine Zeilenumbrüche innerhalb erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Platziert in ein vertikales Array. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt einen Balken unten auf dieses Element. |

### Beispiele

Beispiel:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // Verstecke den Inhalt
phantom.ZeroWidth = false;     // Breite beibehalten
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathPhantom](../imathphantom)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->