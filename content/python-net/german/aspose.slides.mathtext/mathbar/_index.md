---
title: MathBar class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathbar/
---
## MathBar Klasse

Specifies the bar function, consisting of a base argument and an overbar or underbar

**Vererbung:**[`MathBar`](/slides/python-net/de/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der Typ MathBar stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Initialisiert MathBar mit Überbalken (Position oben) |
| [`__init__(self, element, position)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Initialisiert MathBar mit angegebener Position |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`base`](/slides/python-net/de/aspose.slides.mathtext/mathbar/base/) | Basisargument |
| [`position`](/slides/python-net/de/aspose.slides.mathtext/mathbar/position/) | Position der Balkenlinie.<br/>            Standard: Oben |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/join/#imathelement) | Verbindet ein mathematisches Element und erzeugt einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/join/#str) | Verbindet einen mathematischen Text und erzeugt einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/divide/#str) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/enclose/#) | Schließt ein mathematisches Element in Klammern ein |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/enclose/#char-char) | Schließt ein mathematisches Element in angegebene Zeichen ein, wie Klammern oder andere Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/function/#imathelement) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/function/#str) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nimmt eine angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Erstellt Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_subscript/#str) | Erstellt Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Erstellt Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_superscript/#str) | Erstellt Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Nimmt obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Nimmt obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Nimmt untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Nimmt untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen n-stelligen Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Erstellt einen n-stelligen Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/group/#) | Platziert dieses Element in einer Gruppe mit einer unteren geschweiften Klammer |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer unteren geschweiften Klammer oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/to_border_box/#) | Platziert dieses Element in einem Rahmenfeld |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einem Rahmenfeld |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/overbar/#) | Setzt einen Balken oben an diesem Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/underbar/#) | Setzt einen Balken unten an diesem Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/to_box/#) | Platziert dieses Element in einer nicht-sichtbaren Box (logische Gruppierung)<br/>            die verwendet wird, um Komponenten einer Gleichung oder anderer mathematischer Texte zu gruppieren.<br/>            Ein boxed-Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen,<br/>            als Zeilenumbruch-Punkt fungieren oder so gruppiert werden, dass keine Zeilenumbrüche innerhalb erlaubt sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbar/get_children/#) | Gibt Kindelemente zurück |

### Siehe auch
* Klasse [`MathBar`](/slides/python-net/de/aspose.slides.mathtext/mathbar)
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)