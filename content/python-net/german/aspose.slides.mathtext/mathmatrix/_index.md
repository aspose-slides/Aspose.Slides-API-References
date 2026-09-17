---
title: MathMatrix class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix Klasse

Gibt das Matrix-Objekt an, das aus Kindelementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind.  
Es ist wichtig zu beachten, dass Matrizen keine eingebauten Trennzeichen haben.  
Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichen-Objekt (IMathDelimiter) verwenden.  
Null-Argumente können verwendet werden, um Lücken in Matrizen zu erzeugen.

**Vererbung:**[`MathMatrix`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)

Der MathMatrix-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Initialisiert eine neue Instanz der MathMatrix-Klasse. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`row_count`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/row_count/) | Anzahl der Zeilen in der Matrix |
| [`column_count`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/column_count/) | Anzahl der Spalten in der Matrix |
| [`hide_placeholders`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Versteckt die Platzhalter für leere Matrixelemente<br/>Standard: false |
| [`base_justification`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/base_justification/) | Gibt die vertikale Ausrichtung relativ zum umgebenden Text an.<br/>Mögliche Werte sind top, bottom und center.<br/>Standard: Center |
| [`min_column_width`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/min_column_width/) | Mindestspaltenbreite in Twips (1/20 eines Punktes)<br/>Der Abstand (auch als „Column Gap“ oder „Gap Width“ bezeichnet) wird zur <br/>MinColumnWidth addiert, um den gesamten Matrix-Spaltenabstand zu bestimmen<br/>(Abstand zwischen den jeweiligen Kanten verschiedener Spalten).<br/>Standard: 0. |
| [`column_gap_rule`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Der Typ des horizontalen Abstands zwischen Spalten einer Matrix;<br/>Horizontale Abstands-Einheiten können ems oder Punkte sein (gespeichert als Twips).<br/>Standard: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/column_gap/) | Der Wert des horizontalen Abstands zwischen Spalten einer Matrix;<br/>Wenn ColumnGapRule auf 3 ("Exactly") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert.<br/>Wenn ColumnGapRule auf 4 ("Multiple") gesetzt ist, wird die Einheit als Anzahl von 0,5-em-Schritten interpretiert.<br/>In anderen Fällen wird ignoriert.<br/>Standard: 0 |
| [`row_gap_rule`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix;<br/>Vertikale Abstandseinheiten können Zeilen oder Punkte sein (gespeichert als Twips).<br/>Standard: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/row_gap/) | Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix;<br/>Wenn RowGapRule auf 3 ("Exactly") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert.<br/>Wenn RowGapRule auf 4 ("Multiple") gesetzt ist, wird die Einheit als halbe Zeilen interpretiert.<br/>Standard: 0 |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Fügt ein mathematisches Element zusammen und bildet einen mathematischen Block |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/join/#str) | Fügt einen mathematischen Text zusammen und bildet einen mathematischen Block |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/divide/#str) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/enclose/#) | Umschließt ein Mathe-Element in Klammern |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Umschließt ein Mathe-Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Erstellt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/function/#str) | Erstellt eine Funktion eines Arguments und verwendet diese Instanz als Funktionsnamen |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Verwendet die angegebene Funktion und nutzt diese Instanz als Argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Verwendet die angegebene Funktion, nutzt diese Instanz als Argument und einen angegebenen zusätzlichen Parameter |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Verwendet die angegebene Funktion, nutzt diese Instanz als Argument und einen angegebenen zusätzlichen Parameter |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Erstellt Tiefstellung |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Erstellt Tiefstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Erstellt Hochstellung |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Erstellt Hochstellung |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Erstellt Tief- und Hochstellung rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Erstellt Tief- und Hochstellung links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Erstellt Tief- und Hochstellung links |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/radical/#str) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an. |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Nimmt obere Grenze |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Nimmt obere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Nimmt untere Grenze |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Nimmt untere Grenze |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Erstellt einen N-stelligen Operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Erstellt einen N-stelligen Operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Nimmt das Integral |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Nimmt das Integral ohne Grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Nimmt das Integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Nimmt das Integral |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/group/#) | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen wie einer geschweiften Klammer unten oder einem anderen |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Platziert dieses Element in einem Rahmen-Box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Platziert dieses Element in einem Rahmen-Box |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Fügt ein vertikales Array ein |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/accent/#char) | Setzt ein Akzentzeichen (ein Zeichen über diesem Element) |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/overbar/#) | Setzt einen Balken oben auf dieses Element |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/underbar/#) | Setzt einen Balken unten auf dieses Element |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/to_box/#) | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung)<br/>die verwendet wird, um Komponenten einer Gleichung oder anderer mathematischer Texte zu gruppieren.<br/>Ein solcher Box-Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen,<br/>als Zeilenumbruch-Punkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Liefert die horizontale Ausrichtung der angegebenen Spalte |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Setzt die horizontale Ausrichtung der angegebenen Spalte |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Setzt die horizontale Ausrichtung der angegebenen Spalten |
| [`insert_row_before(self, row_index)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Fügt vor der angegebenen Zeile eine neue Zeile ein<br/>Anfangs sind alle Elemente in der neuen Zeile None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Fügt nach der angegebenen Zeile eine neue Zeile ein<br/>Anfangs sind alle Elemente in der neuen Zeile None. |
| [`delete_row(self, row_index)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Löscht die angegebene Zeile |
| [`insert_column_before(self, column_index)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Fügt vor der angegebenen Spalte eine neue Spalte ein<br/>Anfangs sind alle Elemente in der neuen Spalte None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Fügt nach der angegebenen Spalte eine neue Spalte ein<br/>Anfangs sind alle Elemente in der neuen Spalte None. |
| [`delete_column(self, column_index)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Löscht die angegebene Spalte |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix/get_children/#) | Liefert Kindelemente |


### Siehe Auch
* Klasse [`MathElementBase`](/slides/python-net/de/aspose.slides.mathtext/mathelementbase)
* Klasse [`MathMatrix`](/slides/python-net/de/aspose.slides.mathtext/mathmatrix)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)