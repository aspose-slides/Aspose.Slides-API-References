---
title: MathElementBase class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase Klasse

Basisklasse für IMathElement mit der Implementierung einiger Methoden, die allen abgeleiteten Klassen gemeinsam sind. Nur für den internen Gebrauch. Abgeleitete Klasse muss IMathElement sein.

Der MathElementBase-Typ stellt die folgenden Mitglieder bereit:

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/join/#imathelement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/join/#str) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/divide/#str) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/enclose/#) | Umgibt ein mathematisches Element mit Klammern |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | Umgibt ein mathematisches Element mit angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/function/#imathelement) | Erstellt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/function/#str) | Erstellt eine Funktion eines Arguments unter Verwendung dieser Instanz als Funktionsnamen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | Erstellt einen Subskript |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | Erstellt einen Subskript |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | Erstellt einen Superskript |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | Erstellt einen Superskript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Subskript und Superskript rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | Erstellt Subskript und Superskript rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Subskript und Superskript links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | Erstellt Subskript und Superskript links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | Bestimmt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/radical/#str) | Bestimmt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | Setzt obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | Setzt obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | Setzt untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | Setzt untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-ären Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-ären Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/group/#) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer geschweiften Klammer unten oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/to_border_box/#) | Platziert dieses Element in einer Randbox |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einer Randbox |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/to_math_array/#) | Fügt ein vertikales Array ein |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/overbar/#) | Setzt einen Strich oben auf dieses Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/underbar/#) | Setzt einen Strich unten auf dieses Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/to_box/#) | Platziert dieses Element in einer nicht-sichtbaren Box (logische Gruppierung) <br/> die verwendet wird, um Komponenten einer Gleichung oder einer anderen Instanz mathematischen Textes zu gruppieren.<br/> Ein in einer Box befindliches Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/> als Zeilenumbruch-Punkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### Siehe auch
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)