---
title: MathBorderBox class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox Klasse

Zeichnet einen rechteckigen oder anderen Rahmen um das IMathElement.

**Vererbung:**[`MathBorderBox`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der MathBorderBox-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Erstellt ein MathBorderBox-Element mit rechteckigem Rahmen |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Erstellt ein MathBorderBox-Element |

## Eigenschaften

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/base/) | Basisargument |
| [`hide_top`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/hide_top/) | Obere Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der oberen Kante des Rahmenkastens an. |
| [`hide_bottom`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Untere Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der unteren Kante des Rahmenkastens an. |
| [`hide_left`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/hide_left/) | Linke Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der linken Kante des Rahmenkastens an. |
| [`hide_right`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/hide_right/) | Rechte Kante ausblenden (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand der rechten Kante des Rahmenkastens an. |
| [`strikethrough_horizontal`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Durchgestrichene horizontale Linie (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen horizontalen Linie an. |
| [`strikethrough_vertical`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Durchgestrichene vertikale Linie (Standard ist false) - gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen vertikalen Linie an. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Durchgestrichene Diagonale von unten links nach oben rechts (Standard ist false).<br/>            Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der unteren linken Ecke zur oberen rechten Ecke des Rahmenkastens an. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Durchgestrichene Diagonale von oben links nach unten rechts (Standard ist false).<br/>            Gibt den ausgeblendeten oder angezeigten Zustand einer durchgestrichenen diagonalen Linie von der oberen linken Ecke zur unteren rechten Ecke des Rahmenkastens an. |

## Methoden

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/join/#str) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/divide/#str) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/enclose/#) | Umschließt ein mathematisches Element in Klammern |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Umschließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/function/#str) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Nimmt die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Erstellt Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Erstellt Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Erstellt Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Erstellt Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Nimmt obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Nimmt obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Nimmt untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Nimmt untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-ären Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-ären Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/group/#) | Platziert dieses Element in einer Gruppe unter Verwendung einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe unter Verwendung eines Gruppierungszeichens wie einer geschweiften Klammer unten oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Platziert dieses Element in einem Rahmen-Box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einem Rahmen-Box |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/overbar/#) | Setzt einen Balken oben auf dieses Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/underbar/#) | Setzt einen Balken unten auf dieses Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/to_box/#) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung) <br/>            die dazu verwendet wird, Komponenten einer Gleichung oder anderer mathematischer Textinstanzen zu gruppieren.<br/>            Ein in einer Box platziertes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruchpunkt dienen oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox/get_children/#) | Gibt Kind-Elemente zurück |

### Siehe auch
* Klasse [`MathBorderBox`](/slides/python-net/de/aspose.slides.mathtext/mathborderbox)
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)