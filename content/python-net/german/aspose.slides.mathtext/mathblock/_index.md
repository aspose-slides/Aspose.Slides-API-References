---
title: MathBlock class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathblock/
---
## MathBlock class

Gibt eine Instanz von mathematischem Text an, die innerhalb eines MathParagraph enthalten ist und in einer eigenen Zeile beginnt.
            Alle mathematischen Zonen, einschließlich Gleichungen, Ausdrücke, Arrays von Gleichungen oder Ausdrücken und Formeln, werden durch einen MathBlock dargestellt.

**Vererbung:**[`MathBlock`](/slides/python-net/de/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der MathBlock-Typ stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/__init__/#) | Initialisiert eine neue Instanz der MathBlock-Klasse. |
| [`__init__(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Erstellt einen neuen mathematischen Block und legt das angegebene Element darin ab |
| [`__init__(self, math_elements)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`count`](/slides/python-net/de/aspose.slides.mathtext/mathblock/count/) | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen untergeordneten Math-Elemente zurück.<br/>            Nur lesbar **int**. |
| [`is_read_only`](/slides/python-net/de/aspose.slides.mathtext/mathblock/is_read_only/) | Gibt false zurück, weil die Sammlung von Kind-Elementen modifiziert werden kann. |

Liest oder setzt IMathElement am angegebenen Index.

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides.mathtext/mathblock/__getitem__/) | Der nullbasierte Index des Elements |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/join/#imathelement) | Verknüpft ein mathematisches Element mit diesem MathBlock |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/join/#str) | Verknüpft einen mathematischen Text mit diesem MathBlock |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/divide/#str) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/enclose/#char-char) | Umschließt Kind-Elemente dieses Blocks in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Umschließt Kind-Elemente dieses Blocks in angegebenen Zeichen wie Klammern oder anderen als Rahmen<br/>            und trennt sie mit einem Trennzeichen |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/enclose/#) | Umschließt ein Math-Element in Klammern |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/function/#imathelement) | Verwendet diese Instanz als Funktionsnamen für eine Funktion mit einem Argument |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/function/#str) | Verwendet diese Instanz als Funktionsnamen für eine Funktion mit einem Argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Verwendet diese Instanz als Argument für die angegebene Funktion |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Verwendet diese Instanz als Argument für die angegebene Funktion |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Verwendet diese Instanz als Argument für die angegebene Funktion |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Verwendet diese Instanz als Argument für die angegebene Funktion und einen zusätzlichen angegebenen Parameter |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Verwendet diese Instanz als Argument für die angegebene Funktion und einen zusätzlichen angegebenen Parameter |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Erstellt Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_subscript/#str) | Erstellt Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Erstellt Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_superscript/#str) | Erstellt Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts vom Element |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts vom Element |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links vom Element |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links vom Element |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Fügt eine obere Grenze hinzu |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Fügt eine obere Grenze hinzu |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Fügt eine untere Grenze hinzu |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Fügt eine untere Grenze hinzu |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-ären Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-ären Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Fügt das Integral ein |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Fügt das Integral ein |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Fügt das Integral ohne Grenzen ein |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Fügt das Integral ein |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Fügt das Integral ein |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/group/#) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer geschweiften Klammer unten oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/to_border_box/#) | Platziert dieses Element in einem Rahmenkästchen |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einem Rahmenkästchen |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/to_math_array/#) | Ordnet Kind-Elemente in einem vertikalen Array an |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/overbar/#) | Setzt einen Balken über diesem Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/underbar/#) | Setzt einen Balken unter diesem Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/to_box/#) | Platziert dieses Element in einem nicht-visuellen Kästchen (logische Gruppierung) <br/>            das zur Gruppierung von Komponenten einer Gleichung oder anderer Instanzen mathematischen Textes verwendet wird.<br/>            Ein gekastenes Objekt kann (beispielsweise) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruch-Punkt dienen oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/get_children/#) | Gibt Kind-Elemente zurück |
| [`add(self, item)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/add/#imathelement) | Fügt ein Math-Element am Ende der Sammlung hinzu. |
| [`clear(self)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/clear/#) | Entfernt alle Elemente aus der Sammlung. |
| [`contains(self, item)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/contains/#imathelement) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [`copy_to(self, array, array_index)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Kopiert in das angegebene Array. |
| [`remove(self, item)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/remove/#imathelement) | Entfernt das erste Auftreten eines bestimmten Objekts aus der Sammlung. |
| [`index_of(self, item)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Bestimmt den Index eines bestimmten Math-Elements in der Sammlung. |
| [`insert(self, index, item)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Fügt ein MathElement an der angegebenen Indexposition in die Sammlung ein. |
| [`remove_at(self, index)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/remove_at/#int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [`join_block(self, other)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Verknüpft einen anderen mathematischen Block mit diesem |
| [`delimit(self, separator_character)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/delimit/#char) | Trennt Kind-Elemente mit einem Trennzeichen (ohne Klammern) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/de/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Speichert den Inhalt dieses [`MathBlock`](/slides/python-net/de/aspose.slides.mathtext/mathblock) als MathML |

### Siehe auch
* Klasse [`MathBlock`](/slides/python-net/de/aspose.slides.mathtext/mathblock)
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)