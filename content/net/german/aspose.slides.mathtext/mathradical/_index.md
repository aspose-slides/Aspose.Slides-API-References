---  
title: MathRadical
second_title: Aspose.Sildes für .NET API Referenz  
description: Spezifiziert die radikale Funktion, die aus einer Basis und einem optionalen Grad besteht. Beispiel für ein radikales Objekt ist √𝑥.
type: docs  
weight: 8670  
url: /de/aspose.slides.mathtext/mathradical/
---  

## MathRadical-Klasse  

Spezifiziert die radikale Funktion, die aus einer Basis und einem optionalen Grad besteht. Beispiel für ein radikales Objekt ist √𝑥.  

```csharp  
public sealed class MathRadical : MathElementBase, IMathRadical  
```  

## Konstruktoren  

| Name | Beschreibung |  
| --- | --- |  
| [MathRadical](mathradical)(IMathElement, IMathElement) | Initialisiert eine neue Instanz der MathRadical-Klasse. |  

## Eigenschaften  

| Name | Beschreibung |  
| --- | --- |  
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | Basisargument |  
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | Grad-Argument |  
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | Grad verstecken Wenn wahr ist, wird der Grad nicht angezeigt, wie in √𝑥 |  

## Methoden  

| Name | Beschreibung |  
| --- | --- |  
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |  
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
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Schließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen ein |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |  
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Nimmt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |  
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | Holt die Kindelemente |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Platziert dieses Element in einer Gruppe unter Verwendung einer unteren geschweiften Klammer |  
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Platziert dieses Element in einer Gruppe unter Verwendung eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder anderer |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Nimmt das Integral ohne Grenzen |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Nimmt das Integral |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Nimmt das Integral |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Nimmt das Integral |  
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Nimmt das Integral |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |  
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Erstellt einen N-ary-Operator |  
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Erstellt einen N-ary-Operator |  
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Setzt eine Linie oben auf dieses Element |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Spezifiziert die mathematische Wurzel des gegebenen Grades aus dem angegebenen Argument. |  
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Spezifiziert die mathematische Wurzel des gegebenen Grades aus dem angegebenen Argument. |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Nimmt die untere Grenze |  
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Nimmt die untere Grenze |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Erstellt einen Tiefstellung |  
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Erstellt einen Tiefstellung |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Erstellt eine Tiefstellung und Hochstellung auf der linken Seite |  
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Erstellt eine Tiefstellung und Hochstellung auf der linken Seite |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Erstellt eine Tiefstellung und Hochstellung auf der rechten Seite |  
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Erstellt eine Tiefstellung und Hochstellung auf der rechten Seite |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Erstellt eine Hochstellung |  
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Erstellt eine Hochstellung |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Nimmt die obere Grenze |  
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Nimmt die obere Grenze |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Platziert dieses Element in einer Rahmenbox |  
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Platziert dieses Element in einer Rahmenbox |  
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Platziert dieses Element in einer nicht visuellen Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder anderer Instanzen von mathematischem Text zu gruppieren. Ein eingekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne einen Ausrichtungsunkt dienen, als Zeilenumbruchpunkt dienen oder gruppiert werden, sodass innerhalb der Gruppe keine Zeilenumbrüche erlaubt sind. |  
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Fügt in ein vertikales Array ein |  
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Setzt eine Linie unten auf dieses Element |  

### Beispiele  

Beispiel:  

```csharp  
[C#]  
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));  
```  

### Siehe auch  

* Klasse [MathElementBase](../mathelementbase)  
* Schnittstelle [IMathRadical](../imathradical)  
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)  
* Assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  