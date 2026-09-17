---
title: MathFunction class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathfunction/
---
## MathFunction Klasse

Beschreibt eine Funktion eines Arguments.

**Vererbung:**[`MathFunction`](/slides/python-net/de/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der MathFunction-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | Initialisiert eine neue Instanz der MathFunction-Klasse. |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | Initialisiert eine neue Instanz der MathFunction-Klasse. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`name`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/name/) | Funktionsname<br/>            Zum Beispiel sind Funktionsnamen sin und cos |
| [`base`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/base/) | Funktionsargument |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/join/#imathelement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/join/#str) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/divide/#str) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/enclose/#) | Umfasst ein mathematisches Element in Klammern |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/enclose/#char-char) | Umfasst ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/function/#imathelement) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/function/#str) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | Erstellt Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_subscript/#str) | Erstellt Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | Erstellt Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_superscript/#str) | Erstellt Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | Nimmt obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | Nimmt obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | Nimmt untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | Nimmt untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-ären Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-ären Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/group/#) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer geschweiften Klammer unten oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/to_border_box/#) | Platziert dieses Element in einem Rahmenkasten |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einem Rahmenkasten |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/overbar/#) | Setzt einen Strich oben auf diesem Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/underbar/#) | Setzt einen Strich unten auf diesem Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/to_box/#) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung) <br/>            die verwendet wird, um Komponenten einer Gleichung oder anderer mathematischer Texte zu gruppieren.<br/>            Ein in einer Box gekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche möglich sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathfunction/get_children/#) | Gibt Kindelemente zurück |

### Siehe auch
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Klasse [`MathFunction`](/slides/python-net/de/aspose.slides.mathtext/mathfunction)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)