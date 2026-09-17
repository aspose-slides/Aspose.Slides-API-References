---
title: MathNaryOperator class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator Klasse

Specifies an N-ary mathematical object, such as Summation and Integral.
            It consists of an operator, a base (or operand), and optional upper and lower limits. 
            Examples of N-ary operators are: Summation, Union, Intersection, Integral

**Vererbung:**[`MathNaryOperator`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der Typ MathNaryOperator stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Initialisiert eine neue Instanz der Klasse MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Initialisiert eine neue Instanz der Klasse MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Initialisiert eine neue Instanz der Klasse MathNaryOperator. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`base`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/base/) | Basisargument |
| [`subscript`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/subscript/) | Gibt ein Subskript-Argument an, das zum Beispiel im Fall eines Integrals die untere Grenze festlegt |
| [`superscript`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/superscript/) | Gibt ein Superskript-Argument an, das zum Beispiel im Fall eines Integrals die obere Grenze festlegt |
| [`operator`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/operator/) | Nary-Operatorzeichen<br/>            Zum Beispiel: '∑', '∫' |
| [`limit_location`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Der Ort der Grenzen (Subskript und Superskript) |
| [`grow_to_match_operand_height`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Operatorzeichen wächst vertikal, um die Höhe seines Operanden anzupassen |
| [`hide_subscript`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Subskript ausblenden |
| [`hide_superscript`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Superskript ausblenden |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/join/#str) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Schließt ein mathematisches Element in Klammern ein |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Schließt ein mathematisches Element in angegebenen Zeichen ein, wie Klammern oder andere Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/function/#str) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument sowie ein zusätzlicher übergebener Parameter verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument sowie ein zusätzlicher übergebener Parameter verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Erstellt Subskript |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Erstellt Subskript |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Erstellt Superskript |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Erstellt Superskript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Subskript und Superskript rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Erstellt Subskript und Superskript rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Subskript und Superskript links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Erstellt Subskript und Superskript links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Nimmt obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Nimmt obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Nimmt untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Nimmt untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-ary-Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-ary-Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/group/#) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, wie einer unteren geschweiften Klammer oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Platziert dieses Element in einer Rand-Box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einer Rand-Box |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Fügt in ein vertikales Array ein |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Setzt einen Balken oben auf diesem Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Setzt einen Balken unten auf diesem Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung) <br/>            die verwendet wird, um Komponenten einer Gleichung oder einer anderen Instanz mathematischen Textes zu gruppieren.<br/>            Ein in einer Box eingeschlossenes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche zulässig sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Ruft Kind-Elemente ab |

### Siehe auch
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Klasse [`MathNaryOperator`](/slides/python-net/de/aspose.slides.mathtext/mathnaryoperator)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)