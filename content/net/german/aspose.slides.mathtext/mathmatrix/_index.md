---
title: MathMatrix
second_title: Aspose.Slides für .NET API-Referenz
description: Spezifiziert das Matrix-Objekt, das aus Kinderelementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen haben. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichenobjekt IMathDelimiter verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu schaffen.
type: docs
weight: 8590
url: /de/aspose.slides.mathtext/mathmatrix/
---

## MathMatrix class

Spezifiziert das Matrix-Objekt, das aus Kinderelementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind. Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen haben. Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichenobjekt (IMathDelimiter) verwenden. Null-Argumente können verwendet werden, um Lücken in Matrizen zu schaffen.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructors

| Name | Beschreibung |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Initialisiert eine neue Instanz der MathMatrix-Klasse. |

## Properties

| Name | Beschreibung |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Spezifiziert die vertikale Rechtfertigung in Bezug auf den umgebenden Text. Mögliche Werte sind oben, unten und zentriert. Standard: Zentriert |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Anzahl der Spalten in der Matrix |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Der Wert des horizontalen Abstands zwischen den Spalten einer Matrix; Wenn die ColumnGapRule auf 3 ("Genau") eingestellt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die ColumnGapRule auf 4 ("Vielfaches") eingestellt ist, wird die Einheit als Anzahl der 0,5 em-Inkremente interpretiert. In anderen Fällen ignoriert. Standard: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Der Typ des horizontalen Abstands zwischen den Spalten einer Matrix; Horizontale Abstandseinheiten können em oder Punkte (als Twips gespeichert) sein. Standard: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Versteckt die Platzhalter für leere Matrixelemente. Standard: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Element der Matrix |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Minimale Spaltenbreite in Twips (1/20 eines Punktes). Der Abstand (auch als „Spaltenabstand“ oder „Abstandbreite“ bezeichnet) wird zur MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand (Abstand zwischen den gleichen Kanten unterschiedlicher Spalten) zu bestimmen. Standard: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Anzahl der Zeilen in der Matrix |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Der Wert des vertikalen Abstands zwischen den Zeilen einer Matrix; Wenn die RowGapRule auf 3 ("Genau") eingestellt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert. Wenn die RowGapRule auf 4 ("Vielfaches") eingestellt ist, wird die Einheit als halbe Zeilen interpretiert. Standard: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Der Typ des vertikalen Abstands zwischen den Zeilen einer Matrix; Vertikale Abstandseinheiten können Zeilen oder Punkte (als Twips gespeichert) sein. Standard: SingleSpacingGap (0) |

## Methods

| Name | Beschreibung |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet wird |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument und das angegebene zusätzliche Argument verwendet wird |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Löscht die angegebene Spalte |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Löscht die angegebene Zeile |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Gibt die Kinderelemente zurück |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Gibt die horizontale Ausrichtung der angegebenen Spalte zurück |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe unter Verwendung einer unteren geschweiften Klammer |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe unter Verwendung eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einer anderen |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Fügt eine neue Spalte nach der angegebenen ein. Zunächst sind alle Elemente in der neuen Spalte null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Fügt eine neue Spalte vor der angegebenen ein. Zunächst sind alle Elemente in der neuen Spalte null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Fügt eine neue Zeile nach der angegebenen ein. Zunächst sind alle Elemente in der neuen Zeile null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Fügt eine neue Zeile vor der angegebenen ein. Zunächst sind alle Elemente in der neuen Zeile null. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen n-ären Operator |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen n-ären Operator |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oben auf dieses Element |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Spezifiziert die mathematische Wurzel des gegebenen Grades des angegebenen Arguments. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Spezifiziert die mathematische Wurzel des gegebenen Grades des angegebenen Arguments. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Setzt die horizontale Ausrichtung der angegebenen Spalte |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Setzt die horizontale Ausrichtung der angegebenen Spalten |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefgestellt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefgestellt |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt ein Tiefgestellt und Hochgestellt auf der linken Seite |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt ein Tiefgestellt und Hochgestellt auf der linken Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt ein Tiefgestellt und Hochgestellt auf der rechten Seite |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt ein Tiefgestellt und Hochgestellt auf der rechten Seite |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt ein Hochgestellt |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt ein Hochgestellt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Border-Box |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Border-Box |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder einen anderen mathematischen Text zu gruppieren. Ein eingekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne einen Ausrichtungspunkt dienen, als Punkt für Zeilenumbrüche dienen oder so gruppiert werden, dass innerhalb davon keine Zeilenumbrüche erlaubt sind. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Stellt in einem vertikalen Array dar |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie unten auf dieses Element |

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
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->