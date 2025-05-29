---
title: MathMatrix
second_title: Aspose.Slides für .NET API Referenz
description: Gibt das Matrix-Objekt an, das aus Kind-Elementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen haben. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichenobjekt IMathDelimiter verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erstellen.
type: docs
weight: 8590
url: /de/aspose.slides.mathtext/mathmatrix/
---

## MathMatrix-Klasse

Gibt das Matrix-Objekt an, das aus Kind-Elementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen haben. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichenobjekt (IMathDelimiter) verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu erstellen.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Initialisiert eine neue Instanz der MathMatrix-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Gibt die vertikale Rechtfertigung in Bezug auf den umgebenden Text an. Mögliche Werte sind oben, unten und zentriert. Standard: Zentrum |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Anzahl der Spalten in der Matrix |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Der Wert des horizontalen Abstands zwischen Spalten einer Matrix; Wenn die ColumnGapRule auf 3 ("Genau") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die ColumnGapRule auf 4 ("Vielfaches") gesetzt ist, wird die Einheit als Anzahl von 0,5 em-Inkrementen interpretiert. In anderen Fällen ignoriert. Standard: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; Horizontale Abständeinheiten können em oder Punkte (als Twips gespeichert) sein. Standard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Versteckt die Platzhalter für leere Matrixelemente. Standard: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Element der Matrix |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimale Spaltenbreite in Twips (1/20 eines Punktes). Der Abstand (auch als "Spaltenabstand" oder "Abstand zwischen Lücken" bezeichnet) wird zur MinColumnWidth hinzugefügt, um den gesamten Matrixspaltenabstand (den Abstand zwischen den gleichen Kanten verschiedener Spalten) zu bestimmen. Standard: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Anzahl der Zeilen in der Matrix |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix; Wenn die RowGapRule auf 3 ("Genau") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die RowGapRule auf 4 ("Vielfaches") gesetzt ist, wird die Einheit als halbe Zeilen interpretiert. Standard: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; Vertikale Abständeinheiten können Zeilen oder Punkte (als Twips gespeichert) sein. Standard: SingleSpacingGap (0) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument sowie das angegebene zusätzliche Argument |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument sowie das angegebene zusätzliche Argument |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Löscht die angegebene Spalte |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Löscht die angegebene Zeile |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein Mathematik-Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein Mathematik-Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Umrahmung ein |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Holt Kindelemente |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Holt die horizontale Ausrichtung der angegebenen Spalte |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer unteren geschweiften Klammer oder einem anderen |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Fügt nach der angegebenen Spalte eine neue Spalte ein. Zunächst sind alle Elemente in der neuen Spalte null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Fügt vor der angegebenen Spalte eine neue Spalte ein. Zunächst sind alle Elemente in der neuen Spalte null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Fügt nach der angegebenen Zeile eine neue Zeile ein. Zunächst sind alle Elemente in der neuen Zeile null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Fügt vor der angegebenen Zeile eine neue Zeile ein. Zunächst sind alle Elemente in der neuen Zeile null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Vereint ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Vereint einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-äre Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-äre Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt einen Balken oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades vom angegebenen Argument an. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Setzt die horizontale Ausrichtung der angegebenen Spalte |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Setzt die horizontale Ausrichtung der angegebenen Spalten |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die Untergrenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die Untergrenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefgestellt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefgestellt |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt Tiefgestellt und Hochgestellt auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt Tiefgestellt und Hochgestellt auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt Tiefgestellt und Hochgestellt auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt Tiefgestellt und Hochgestellt auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt Hochgestellt |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt Hochgestellt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die Obergrenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die Obergrenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Rahmenbox |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Rahmenbox |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht-ausführbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder anderen Beispielen mathematischen Textes zu gruppieren. Ein umrahmtes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass keine Zeilenumbrüche innerhalb des Objekts erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Platziert in einem vertikalen Array |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt einen Balken unten auf dieses Element |

### Beispiele

Beispiel:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Siehe auch

* Klasse [MathElementBase](../mathelementbase)
* Schnittstelle [IMathMatrix](../imathmatrix)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->