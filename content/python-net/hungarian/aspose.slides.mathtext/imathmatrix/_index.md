---
title: IMathMatrix class
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix osztály

Meghatározza a Matrix objektumot, amely gyermekelemekből áll, melyek egy vagy több sorban és oszlopban vannak elrendezve. 
            Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolójeleik. 
            A mátrix zárójelbe helyezéséhez a határoló objektumot (IMathDelimiter) kell használni. 
            Null argumentumokkal hézagok hozhatók létre a mátrixokban.

A IMathMatrix típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`row_count`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/row_count/) | A mátrix sorainak száma |
| [`column_count`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/column_count/) | A mátrix oszlopainak száma |
| [`hide_placeholders`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Elrejti az üres mátrixelemek helyőrzőit<br/>            Alapértelmezett: false |
| [`base_justification`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/base_justification/) | Megadja a függőleges igazítást a környező szöveghez képest. <br/>            Lehetséges értékek: top, bottom, és center.<br/>            Alapértelmezett: Center |
| [`min_column_width`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/min_column_width/) | Az oszlop minimális szélessége twips (1/20th of a point)<br/>            A hézag távolság (más néven “Column Gap” vagy “Gap Width”) hozzáadódik <br/>            a MinColumnWidth-hez a teljes Matrix Column Spacing meghatározásához<br/>            (a különböző oszlopok azonos széleinek távolsága).<br/>            Alapértelmezett: 0. |
| [`column_gap_rule`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | A mátrix oszlopai közötti vízszintes távolság típusa;<br/>            A vízszintes távolság egységei lehetnek ems vagy points (stored as twips).<br/>            Alapértelmezett: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/column_gap/) | A mátrix oszlopai közötti vízszintes távolság értéke;<br/>            Ha a ColumnGapRule 3-ra van állítva („Exactly”), akkor az egységet twips (1/20th of a point) értelmezi<br/>            Ha a ColumnGapRule 4-re van állítva („Multiple”), akkor az egységet 0.5 em növekmények számaként értelmezi.<br/>            Más esetekben figyelmen kívül hagyják.<br/>            Alapértelmezett: 0 |
| [`row_gap_rule`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | A mátrix sorai közötti függőleges távolság típusa;<br/>            A függőleges távolság egységei lehetnek lines vagy points (stored as twips).<br/>            Alapértelmezett: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/row_gap/) | A mátrix sorai közötti függőleges távolság értéke;<br/>            Ha a RowGapRule 3-ra van állítva („Exactly”), akkor az egységet twips (1/20th of a point) értelmezi<br/>            Ha a RowGapRule 4-re van állítva („Multiple”), akkor az egységet half-lines-ként értelmezi.<br/>            Alapértelmezett: 0 |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | A megadott oszlop vízszintes igazításának lekérése |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | A megadott oszlop vízszintes igazításának beállítása |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | A megadott oszlopok vízszintes igazításának beállítása |
| [`insert_row_before(self, row_index)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Új sor beszúrása a megadott sor elé<br/>            Kezdetben az új sor összes eleme None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Új sor beszúrása a megadott sor után<br/>            Kezdetben az új sor összes eleme None. |
| [`delete_row(self, row_index)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Törli a megadott sort |
| [`insert_column_before(self, column_index)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Új oszlop beszúrása a megadott oszlop elé<br/>            Kezdetben az új oszlop összes eleme None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Új oszlop beszúrása a megadott oszlop után<br/>            Kezdetben az új oszlop összes eleme None. |
| [`delete_column(self, column_index)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Törli a megadott oszlopot |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Lásd még
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)