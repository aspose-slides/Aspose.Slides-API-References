---
title: IMathElement class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/imathelement/
---
## IMathElement Klasse

Basis-Schnittstelle jedes mathematischen Elements: 
            fraction, mathmatical text, function, expression with multiple elements etc

Der IMathElement-Typ stellt die folgenden Member bereit:

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/join/#imathelement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/join/#str) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/divide/#str) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/enclose/#) | Schließt ein mathematisches Element in Klammern ein |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/enclose/#char-char) | Schließt dieses Element in angegebene Zeichen ein, wie z. B. Klammern oder andere Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/function/#imathelement) | Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/function/#str) | Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/as_argument_of_function/#imathelement) | Verwendet die angegebene Funktion und verwendet diese Instanz als Argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/as_argument_of_function/#str) | Verwendet die angegebene Funktion und verwendet diese Instanz als Argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsofoneargument) | Verwendet die angegebene Funktion und verwendet diese Instanz als Argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzliches angegebenes Argument verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzliches angegebenes Argument verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_subscript/#imathelement) | Erstellt einen Tiefstellungswert |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_subscript/#str) | Erstellt einen Tiefstellungswert |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_superscript/#imathelement) | Erstellt einen Hochstellungswert |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_superscript/#str) | Erstellt einen Hochstellungswert |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_upper_limit/#imathelement) | Nimmt die obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_upper_limit/#str) | Nimmt die obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_lower_limit/#imathelement) | Nimmt die untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/set_lower_limit/#str) | Nimmt die untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-stufigen Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-stufigen Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/group/#) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, wie z. B. einer unteren geschweiften Klammer oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/to_border_box/#) | Platziert dieses Element in einer Rahmen-Box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einer Rahmen-Box |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/get_children/#) | Ruft Kindelemente ab |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/overbar/#) | Setzt einen Strich über dieses Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/underbar/#) | Setzt einen Strich unter dieses Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/imathelement/to_box/#) | Platziert dieses Element in einem nicht-visuellen Kasten (logische Gruppierung) <br/>            der verwendet wird, um Komponenten einer Gleichung oder anderer mathematischer Texte zu gruppieren.<br/>            Ein gekastetes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruch-Punkt dienen oder so gruppiert werden, dass Zeilenumbrüche darin nicht erlaubt sind. |

### Siehe auch
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)