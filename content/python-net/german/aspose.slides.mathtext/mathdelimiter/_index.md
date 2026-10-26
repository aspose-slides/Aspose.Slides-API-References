---
title: MathDelimiter class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter Klasse

Gibt das Trennzeichenobjekt an, das aus öffnenden und schließenden Zeichen (wie Klammern, geschweiften Klammern, eckigen Klammern und senkrechten Strichen) besteht und ein oder mehrere mathematische Elemente enthält, die durch ein angegebenes Zeichen getrennt sind.  
Beispiele: (𝑥2); [𝑥2|𝑦2]

**Vererbung:**[`MathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der Typ MathDelimiter stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Initialisiert MathDelimiter mit dem angegebenen Element als einziges Basisargument |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`arguments`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/arguments/) | Ein oder mehrere mathematische Elemente, die durch Trennzeichen getrennt sind |
| [`beginning_character`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character gibt das Anfangs- bzw. öffnende Trennzeichen an. <br/>Mathematische Trennzeichen sind einschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern.<br/>Standard: '('. |
| [`separator_character`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character gibt das Zeichen an, das Argumente im Trennzeichenobjekt trennt. <br/>Standard: '\|'. |
| [`ending_character`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character gibt das Schluss- bzw. schließende Trennzeichen an. <br/>Mathematische Trennzeichen sind einschließende Zeichen wie Klammern, eckige Klammern und geschweifte Klammern.<br/>Standard: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>Wenn true, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzupassen.<br/>Standardwert ist true |
| [`delimiter_shape`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Gibt die Form der Trennzeichen im Trennzeichenobjekt an. <br/>Wenn MathDelimiterShape.Centered, sind die Trennzeichen um die mathematische Achse des mathematischen Textes zentriert <br/>und werden so angepasst, dass sie die gesamte Höhe ihres Inhalts füllen.<br/>Wenn MathDelimiterShape.Match, werden ihre Höhe und Form exakt an den Inhalt angepasst. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/join/#str) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/divide/#str) | Erstellt einen Bruch mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und angegebenem Nenner |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Umfasst ein mathematisches Element mit angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/enclose/#) | Umfasst ein mathematisches Element in Klammern |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/function/#str) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Erstellt Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Erstellt Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Erstellt Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Erstellt Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Nimmt obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Nimmt obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Nimmt untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Nimmt untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen n-stelligen Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Erstellt einen n-stelligen Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/group/#) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer geschweiften Klammer unten oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Platziert dieses Element in einem Rahmen-Kasten |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einem Rahmen-Kasten |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/overbar/#) | Setzt einen Balken oben auf dieses Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/underbar/#) | Setzt einen Balken unten auf dieses Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/to_box/#) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung) <br/>die verwendet wird, um Komponenten einer Gleichung oder eines anderen mathematischen Textes zu gruppieren.<br/>Ein umrandetes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>als Zeilenumbruch-Punkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| [`delimit(self, separator_character)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Grenzt Argumente mit dem angegebenen Trennzeichen ab |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter/get_children/#) | Gibt Kind-Elemente zurück |

### Siehe auch
* Klasse [`MathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter)
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)