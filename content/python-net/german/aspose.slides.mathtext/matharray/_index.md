---
title: MathArray class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/matharray/
---
## MathArray Klasse

Gibt ein vertikales Array von Gleichungen oder beliebigen mathematischen Objekten an

**Vererbung:**[`MathArray`](/slides/python-net/de/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der MathArray-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/de/aspose.slides.mathtext/matharray/__init__/#imathelement) | Erstellt ein mathematisches Array und legt das angegebene Element darin ab |
| [`__init__(self, elements)`](/slides/python-net/de/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`arguments`](/slides/python-net/de/aspose.slides.mathtext/matharray/arguments/) | Die Menge der Elemente des Arrays |
| [`base_justification`](/slides/python-net/de/aspose.slides.mathtext/matharray/base_justification/) | Gibt die Ausrichtung des Arrays relativ zum umgebenden Text an<br/>            Text außerhalb des Arrays kann mit dem unteren Rand, oberen Rand oder der Mitte eines Array-Objekts ausgerichtet werden.<br/>            Standardwert: Mitte |
| [`maximum_distribution`](/slides/python-net/de/aspose.slides.mathtext/matharray/maximum_distribution/) | Maximale Verteilung<br/>            Wenn true, wird das Array auf die maximale Breite des enthaltenden Elements (Seite, Spalte, Zelle usw.) ausgedehnt. |
| [`object_distribution`](/slides/python-net/de/aspose.slides.mathtext/matharray/object_distribution/) | Objektverteilung<br/>            Wenn true, wird der Inhalt des Arrays auf die maximale Breite des Array-Objekts ausgedehnt. |
| [`row_spacing_rule`](/slides/python-net/de/aspose.slides.mathtext/matharray/row_spacing_rule/) | Der Typ des vertikalen Abstands zwischen Array-Elementen<br/>            Standard: SingleLineGap |
| [`row_spacing`](/slides/python-net/de/aspose.slides.mathtext/matharray/row_spacing/) | Abstand zwischen Zeilen eines Arrays<br/>            Wird nur verwendet, wenn RowSpacingRule auf 3 Exact gesetzt ist, wobei die Maßeinheit Punkte ist <br/>            oder Multiple, wobei die Maßeinheit halbe Zeilen ist.<br/>            Standard: 0 |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/matharray/join/#imathelement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/matharray/join/#str) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/matharray/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/matharray/divide/#str) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/matharray/enclose/#) | Schließt ein mathematisches Element in Klammern ein |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/matharray/enclose/#char-char) | Umfasst ein mathematisches Element in angegebenen Zeichen, wie Klammern oder anderen Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/matharray/function/#imathelement) | Nimmt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/matharray/function/#str) | Nimmt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Nimmt die angegebene Funktion und verwendet diese Instanz als Argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und ein weiterer angegebener Parameter verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und ein weiterer angegebener Parameter verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Erstellt Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_subscript/#str) | Erstellt Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Erstellt Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_superscript/#str) | Erstellt Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/matharray/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/matharray/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Nimmt obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Nimmt obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Nimmt untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Nimmt untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-ären Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-ären Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/matharray/group/#) | Platziert dieses Element in einer Gruppe mittels einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens, wie einer unteren geschweiften Klammer oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/matharray/to_border_box/#) | Platziert dieses Element in einer Rand-Box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einer Rand-Box |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/matharray/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/matharray/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/matharray/overbar/#) | Setzt einen Balken oben auf dieses Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/matharray/underbar/#) | Setzt einen Balken unten auf dieses Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/matharray/to_box/#) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung) <br/>            die verwendet wird, um Komponenten einer Gleichung oder anderer Instanzen mathematischen Textes zu gruppieren.<br/>            Ein eingekapseltes Objekt kann (beispielsweise) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass innerhalb kein Zeilenumbruch erlaubt ist. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/matharray/get_children/#) | Gibt Kindelemente zurück |

### Siehe auch
* Klasse [`MathArray`](/slides/python-net/de/aspose.slides.mathtext/matharray)
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)