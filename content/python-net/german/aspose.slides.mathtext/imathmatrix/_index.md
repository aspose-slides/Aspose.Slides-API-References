---
title: IMathMatrix class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix Klasse

Specifiziert das Matrix-Objekt, das aus Kindelementen besteht, die in einer oder mehreren Zeilen und Spalten angeordnet sind.  
Es ist wichtig zu beachten, dass Matrizen keine integrierten Trennzeichen besitzen.  
Um die Matrix in Klammern zu setzen, sollten Sie das Trennzeichen-Objekt (IMathDelimiter) verwenden.  
Null-Argumente können verwendet werden, um Lücken in Matrizen zu erzeugen.

Der IMathMatrix-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`row_count`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/row_count/) | Anzahl der Zeilen in der Matrix |
| [`column_count`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/column_count/) | Anzahl der Spalten in der Matrix |
| [`hide_placeholders`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Verstecke die Platzhalter für leere Matrixelemente<br/>            Standard: false |
| [`base_justification`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/base_justification/) | Gibt die vertikale Ausrichtung relativ zum umgebenden Text an.<br/>            Mögliche Werte sind top, bottom und center.<br/>            Standard: Center |
| [`min_column_width`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/min_column_width/) | Minimale Spaltenbreite in Twips (1/20 eines Punktes)<br/>            Der Lückenabstand (auch bezeichnet als „Column Gap“ oder „Gap Width“) wird zu <br/>            der MinColumnWidth hinzugefügt, um den gesamten Matrixspaltenabstand zu bestimmen<br/>            (Abstand zwischen denselben Kanten verschiedener Spalten).<br/>            Standard: 0. |
| [`column_gap_rule`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Der Typ des horizontalen Abstands zwischen Spalten einer Matrix; <br/>            Horizontale Abstandseinheiten können ems oder points sein (als Twips gespeichert).<br/>            Standard: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/column_gap/) | Der Wert des horizontalen Abstands zwischen Spalten einer Matrix;<br/>            Wenn die ColumnGapRule auf 3 ("Exactly") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert<br/>            Wenn die ColumnGapRule auf 4 ("Multiple") gesetzt ist, wird die Einheit als Anzahl von 0,5-em-Schritten interpretiert.<br/>            In anderen Fällen ignoriert.<br/>            Standard: 0 |
| [`row_gap_rule`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Der Typ des vertikalen Abstands zwischen Zeilen einer Matrix; <br/>            Vertikale Abstandseinheiten können lines oder points sein (als Twips gespeichert).<br/>            Standard: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/row_gap/) | Der Wert des vertikalen Abstands zwischen Zeilen einer Matrix;<br/>            Wenn die RowGapRule auf 3 ("Exactly") gesetzt ist, wird die Einheit als Twips (1/20 eines Punktes) interpretiert<br/>            Wenn die RowGapRule auf 4 ("Multiple") gesetzt ist, wird die Einheit als halbe Zeilen interpretiert.<br/>            Standard: 0 |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Ruft die horizontale Ausrichtung der angegebenen Spalte ab |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Setzt die horizontale Ausrichtung der angegebenen Spalte |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Setzt die horizontale Ausrichtung der angegebenen Spalten |
| [`insert_row_before(self, row_index)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Fügt eine neue Zeile vor der angegebenen ein<br/>            Anfangs sind alle Elemente in der neuen Zeile None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Fügt eine neue Zeile nach der angegebenen ein<br/>            Anfangs sind alle Elemente in der neuen Zeile None. |
| [`delete_row(self, row_index)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Löscht die angegebene Zeile |
| [`insert_column_before(self, column_index)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Fügt eine neue Spalte vor der angegebenen ein<br/>            Anfangs sind alle Elemente in der neuen Spalte None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Fügt eine neue Spalte nach der angegebenen ein<br/>            Anfangs sind alle Elemente in der neuen Spalte None. |
| [`delete_column(self, column_index)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Löscht die angegebene Spalte |
| [`get_children(self)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/de/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Siehe auch
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)