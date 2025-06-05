---  
title: MathArray
second_title: Aspose.Slides für .NET API Referenz  
description: Gibt ein vertikales Array von Gleichungen oder anderen mathematischen Objekten an
type: docs  
weight: 8290  
url: /de/aspose.slides.mathtext/matharray/
---  

## MathArray-Klasse  

Gibt ein vertikales Array von Gleichungen oder anderen mathematischen Objekten an  

```csharp  
public sealed class MathArray : MathElementBase, IMathArray  
```  

## Konstruktoren  

| Name | Beschreibung |  
| --- | --- |  
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | Erstellt ein mathematisches Array und platziert die angegebenen Elemente darin |  
| [MathArray](matharray#constructor)(IMathElement) | Erstellt ein mathematisches Array und platziert das angegebene Element darin |  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | Die Menge von Elementen im Array |  
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an. Text außerhalb des Arrays kann am unteren, oberen oder in der Mitte eines Array-Objekts ausgerichtet werden. Standardwert: Zentriert |  
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Maximale Verteilung. Wenn wahr, wird das Array auf die maximale Breite des umgebenden Elements (Seite, Spalte, Zelle usw.) verteilt. |  
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Objektdistribution. Wenn wahr, werden die Inhalte des Arrays bis zur maximalen Breite des Array-Objekts verteilt. |  
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | Abstand zwischen den Zeilen eines Arrays. Er wird nur verwendet, wenn RowSpacingRule auf 3 Genau eingestellt ist, in diesem Fall ist die Einheit der Maßeinheit Punkte oder Vielfache, wobei die Einheit der Maßeinheit halbe Linien ist. Standard: 0 |  
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | Der Typ des vertikalen Abstands zwischen den Array-Elementen. Standard: SingleLineGap |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oberhalb dieses Elements) |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und dem angegebenen zusätzlichen Argument |  
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Nimmt die angegebene Funktion unter Verwendung dieser Instanz als Argument und dem angegebenen zusätzlichen Argument |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |  
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |  
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Schließt ein mathematisches Element in Klammern ein |  
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen zur Einrahmung ein |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |  
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | Holt die Kindelemente |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe unter Verwendung einer unteren geschweiften Klammer |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe unter Verwendung eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ären Operator |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ären Operator |  
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oberhalb dieses Elements |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefgestellt |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefgestellt |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt ein Tiefgestellt und ein Hochgestellt auf der linken Seite |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt ein Tiefgestellt und ein Hochgestellt auf der linken Seite |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt ein Tiefgestellt und ein Hochgestellt auf der rechten Seite |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt ein Tiefgestellt und ein Hochgestellt auf der rechten Seite |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt ein Hochgestellt |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt ein Hochgestellt |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Rahmenbox |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Rahmenbox |  
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht sichtbaren Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder einer anderen Instanz von mathematischem Text zu gruppieren. Ein eingekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenwechselpunkt dienen oder so gruppiert werden, dass es keine Zeilenumbrüche innerhalb zulässt. |  
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Stellt in einem vertikalen Array dar |  
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie unterhalb dieses Elements |  

### Beispiele  

Beispiel:  

```csharp  
[C#]  
MathArray mathArray = new MathArray(new MathematicalText("item1"));  
```  

### Siehe auch  

* Klasse [MathElementBase](../mathelementbase)  
* Schnittstelle [IMathArray](../imatharray)  
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  