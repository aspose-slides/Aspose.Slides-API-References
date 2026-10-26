---
title: MathLimit class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathlimit/
---
## MathLimit Klasse

Gibt das Limit-Objekt an, das aus Text auf der Grundlinie und verkleinertem Text unmittelbar darüber oder darunter besteht.

**Vererbung:**[`MathLimit`](/slides/python-net/de/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der MathLimit-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | Initialisiert eine neue Instanz der MathLimit Klasse. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Initialisiert eine neue Instanz der MathLimit Klasse mit Untergrenze |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`base`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/base/) | Basisargument |
| [`limit`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/limit/) | Limit-Argument |
| [`upper_limit`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/upper_limit/) | Gibt obere oder untere Grenze an |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/join/#imathelement) | Fügt ein mathematisches Element zusammen und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/join/#str) | Fügt mathematischen Text zusammen und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/divide/#str) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/enclose/#) | Schließt ein mathematisches Element in Klammern ein |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/enclose/#char-char) | Schließt ein mathematisches Element in angegebenen Zeichen, wie Klammern oder anderen Zeichen, ein |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/function/#imathelement) | Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/function/#str) | Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Verwendet die angegebene Funktion, nutzt diese Instanz als Argument und einen zusätzlichen angegebenen Parameter |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Verwendet die angegebene Funktion, nutzt diese Instanz als Argument und einen zusätzlichen angegebenen Parameter |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Erstellt eine Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Erstellt eine Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Erstellt eine Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Erstellt eine Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Erfasst obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Erfasst obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Erfasst untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Erfasst untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-stelligen Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-stelligen Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Erfasst das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | Erfasst das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Erfasst das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | Erfasst das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | Erfasst das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/group/#) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, wie einer geschweiften Klammer unten oder einem anderen Zeichen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/to_border_box/#) | Platziert dieses Element in einer Rand-Box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einer Rand-Box |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/overbar/#) | Setzt einen Balken oben auf dieses Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/underbar/#) | Setzt einen Balken unten auf dieses Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/to_box/#) | Platziert dieses Element in einer nicht-sichtbaren Box (logische Gruppierung) <br/>            die verwendet wird, um Komponenten einer Gleichung oder anderen mathematischen Textes zu gruppieren.<br/>            Ein umschlossenes Objekt kann (z. B.) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruchstelle fungieren oder so gruppiert werden, dass Innen keine Zeilenumbrüche erlaubt sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathlimit/get_children/#) | Liefert Kindelemente |

### Siehe auch
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Klasse [`MathLimit`](/slides/python-net/de/aspose.slides.mathtext/mathlimit)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)