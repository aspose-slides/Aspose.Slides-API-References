---
title: MathPhantom class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathphantom/
---
## MathPhantom Klasse

Stellt ein Phantom-Matheobjekt (<m:phant>) dar, das das Layout seines Kindelements
            beeinflusst, ohne es zwingend anzuzeigen. Ein Phantom kann seinen Basisausdruck verbergen, während es seine Breite, Höhe oder Tiefe beibehält, um Formeln auszurichten oder Platz zu reservieren.
            Sichtbarkeits- und Geometrieverhalten werden durch Eigenschaften wie Show, ZeroWid, ZeroAsc,
            ZeroDesc und Transp gesteuert.

**Vererbung:**[`MathPhantom`](/slides/python-net/de/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der MathPhantom-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Initialisiert eine neue Instanz der [`MathPhantom`](/slides/python-net/de/aspose.slides.mathtext/mathphantom) Klasse <br/>            unter Verwendung des angegebenen Basismathelements. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`base`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/base/) | Basisargument |
| [`show`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/show/) | Liest oder setzt einen Wert, der angibt, ob das Basiselement angezeigt wird. |
| [`zero_width`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/zero_width/) | Liest oder setzt einen Wert, der angibt, ob die Breite des Basiselements <br/>            als null behandelt werden soll. |
| [`zero_asc`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/zero_asc/) | Liest oder setzt einen Wert, der angibt, ob der Aufstieg (Höhe über der Grundlinie) <br/>            des Basiselements als null behandelt werden soll. |
| [`zero_desc`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/zero_desc/) | Liest oder setzt einen Wert, der angibt, ob der Abstieg (Tiefe unter der Grundlinie)<br/>            des Basiselements als null behandelt werden soll. |
| [`transp`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/transp/) | Liest oder setzt einen Wert, der angibt, ob das Phantom für klassenbasierte Abstandregeln transparent <br/>            ist. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/join/#imathelement) | Verknüpft ein mathematisches Element und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/join/#str) | Verknüpft einen mathematischen Text und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Erzeugt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/divide/#str) | Erzeugt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Erzeugt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Erzeugt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/enclose/#) | Umschließt ein Mathe-Element in Klammern |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Umschließt ein Mathe-Element in angegebenen Zeichen, wie Klammern oder anderen Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/function/#imathelement) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsnamen verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/function/#str) | Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsnamen verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument und ein zusätzlicher angegebener Parameter verwendet wird |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Erzeugt eine Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Erzeugt eine Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Erzeugt eine Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Erzeugt eine Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erzeugt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Erzeugt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erzeugt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Erzeugt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Nimmt die obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Nimmt die obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Nimmt die untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Nimmt die untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erzeugt einen N-stellig-Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Erzeugt einen N-stellig-Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/group/#) | Platziert dieses Element in einer Gruppe mittels einer unteren geschweiften Klammer |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mittels eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/to_border_box/#) | Platziert dieses Element in einer Rand-Box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einer Rand-Box |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/overbar/#) | Setzt einen Balken oben auf diesem Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/underbar/#) | Setzt einen Balken unten auf diesem Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/to_box/#) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung) <br/>            die verwendet wird, um Bestandteile einer Gleichung oder einer anderen Instanz mathematischen Textes zu gruppieren.<br/>            Ein eingeschlossenes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathphantom/get_children/#) | Ruft Kindelemente ab |

### Siehe Auch
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Klasse [`MathPhantom`](/slides/python-net/de/aspose.slides.mathtext/mathphantom)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)