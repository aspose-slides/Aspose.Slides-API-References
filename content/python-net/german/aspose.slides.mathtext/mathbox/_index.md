---
title: MathBox class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathbox/
---
## MathBox Klasse

Gibt die logische Boxierung (Verpackung) eines mathematischen Elements an.
            Zum Beispiel kann ein verpacktes Objekt als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, 
            als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind.
            Zum Beispiel sollte der Operator "==" verpackt werden, um Zeilenumbrüche zu verhindern.

**Vererbung:**[`MathBox`](/slides/python-net/de/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der Typ MathBox stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Initialisiert MathBox mit dem angegebenen Element als Argument |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`base`](/slides/python-net/de/aspose.slides.mathtext/mathbox/base/) | Basisargument |
| [`operator_emulator`](/slides/python-net/de/aspose.slides.mathtext/mathbox/operator_emulator/) | Operator-Emulator.<br/>            Wenn true, verhalten sich die Box und ihr Inhalt wie ein einzelner Operator und übernehmen die Eigenschaften eines Operators. <br/>            Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenumbruch dienen und an andere Operatoren ausgerichtet werden kann.<br/>            Operator-Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '=='.<br/>            Standardwert: false |
| [`no_break`](/slides/python-net/de/aspose.slides.mathtext/mathbox/no_break/) | Kein Umbruch<br/>            Diese Eigenschaft legt die „unbreakable“-Eigenschaft der Objektbox fest. Wenn true, können innerhalb der Box keine Zeilenumbrüche auftreten.<br/>            Dies kann für Operator-Emulatoren wichtig sein, die aus mehr als einem binären Operator bestehen. <br/>            Wenn dieses Element nicht angegeben ist, können Umbrüche innerhalb der Box auftreten.<br/>            Standard: true |
| [`differential`](/slides/python-net/de/aspose.slides.mathtext/mathbox/differential/) | Differential<br/>            Wenn true, wirkt die Box als Differential (z. B. 𝑑𝑥 in einem Integranden) und erhält den entsprechenden <br/>            horizontalen Abstand für das mathematische Differential.<br/>            Standard: false |
| [`alignment_point`](/slides/python-net/de/aspose.slides.mathtext/mathbox/alignment_point/) | Wenn true, dient dieser Operator-Emulator als Ausrichtungspunkt; das heißt, <br/>            festgelegte Ausrichtungspunkte in anderen Gleichungen können mit ihm ausgerichtet werden.<br/>            Standard: false |
| [`explicit_break`](/slides/python-net/de/aspose.slides.mathtext/mathbox/explicit_break/) | Expliziter Umbruch gibt an, ob am Anfang des Box-Objekts ein Zeilenumbruch erfolgt, <br/>            sodass die Zeile am Anfang des Box-Objekts umbrochen wird.<br/>            Gibt die Nummer des Operators in der vorherigen Zeile des mathematischen Textes an, <br/>            der als Ausrichtungspunkt für die aktuelle Zeile des mathematischen Textes verwendet werden soll<br/>            mögliche Werte: 1..255<br/>            Standard: 0 (kein expliziter Umbruch) |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/join/#imathelement) | Fügt ein mathematisches Element zusammen und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/join/#str) | Fügt einen mathematischen Text zusammen und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/divide/#str) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/enclose/#) | Schließt ein mathematisches Element in Klammern ein |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/enclose/#char-char) | Schließt ein mathematisches Element in angegebenen Zeichen ein, wie z. B. Klammern oder andere Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/function/#imathelement) | Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/function/#str) | Erzeugt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient, und einen angegebenen zusätzlichen Parameter |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient, und einen angegebenen zusätzlichen Parameter |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Erstellt einen Tiefstellen |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_subscript/#str) | Erstellt einen Tiefstellen |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Erstellt einen Hochstellen |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_superscript/#str) | Erstellt einen Hochstellen |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Verwendet obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Verwendet obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Verwendet untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Verwendet untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-ären Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-ären Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Bildet das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Bildet das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Bildet das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Bildet das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Bildet das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/group/#) | Platziert dieses Element in einer Gruppe mittels einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, wie einer geschweiften Klammer unten oder einem anderen Zeichen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/to_border_box/#) | Platziert dieses Element in einer Rand-Box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einer Rand-Box |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/to_math_array/#) | Setzt in ein vertikales Array |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/overbar/#) | Setzt einen Strich oben auf dieses Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/underbar/#) | Setzt einen Strich unten auf dieses Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/to_box/#) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung) <br/>            die verwendet wird, um Komponenten einer Gleichung oder einer anderen Instanz mathematischen Textes zu gruppieren.<br/>            Ein verpacktes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, <br/>            als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathbox/get_children/#) | Ruft Kind-Elemente ab |

### Siehe auch
* Klasse [`MathBox`](/slides/python-net/de/aspose.slides.mathtext/mathbox)
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)