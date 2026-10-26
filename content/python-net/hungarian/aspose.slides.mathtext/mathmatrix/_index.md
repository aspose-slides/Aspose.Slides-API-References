---
title: MathMatrix class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix osztály

Megadja a Matrix objektumot, amely gyermekelemekből áll, egy vagy több sorban és oszlopban elrendezve.  
Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolóik.  
A mátrixot a zárójelekbe helyezéshez a (IMathDelimiter) határolóobjektumot kell használni.  
Null argumentumok használhatók a mátrixokban hézagok létrehozására.

**Öröklés:**[`MathMatrix`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathMatrix típus a következő tagokat biztosítja:

## Konstruktorok

| Constructor | Description |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Inicializál egy új MathMatrix osztálypéldányt. |

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/row_count/) | A mátrix sorainak száma |
| [`column_count`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/column_count/) | A mátrix oszlopainak száma |
| [`hide_placeholders`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Elrejti az üres mátrixelemek helyőrzőit<br/>            Alapértelmezett: false |
| [`base_justification`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/base_justification/) | Meghatározza a függőleges igazítást a környező szöveghez képest.<br/>            Lehetséges értékek: top, bottom, center.<br/>            Alapértelmezett: Center |
| [`min_column_width`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/min_column_width/) | Minimális oszlopszélesség twipben (1/20 pont).<br/>            A hézag (más néven „Column Gap” vagy „Gap Width”) hozzáadódik a MinColumnWidth-hez a teljes mátrixoszlopszakasz meghatározásához<br/>            (a különböző oszlopok azonos élei közti távolság).<br/>            Alapértelmezett: 0. |
| [`column_gap_rule`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | A mátrix oszlopai közötti vízszintes távolság típusa;<br/>            A vízszintes távolság egysége lehet em vagy point (twipben tárolva).<br/>            Alapértelmezett: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/column_gap/) | A mátrix oszlopai közötti vízszintes távolság értéke;<br/>            Ha a ColumnGapRule 3-ra („Exactly”) van állítva, akkor az egység twipben (1/20 pont) értelmeződik.<br/>            Ha a ColumnGapRule 4-re („Multiple”) van állítva, akkor az egység 0,5 em növekmények számaként értelmeződik.<br/>            Más esetekben figyelmen kívül hagyva.<br/>            Alapértelmezett: 0 |
| [`row_gap_rule`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | A mátrix sorai közötti függőleges távolság típusa;<br/>            A függőleges távolság egysége sor vagy point (twipben tárolva).<br/>            Alapértelmezett: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/row_gap/) | A mátrix sorai közötti függőleges távolság értéke;<br/>            Ha a RowGapRule 3-ra („Exactly”) van állítva, akkor az egység twipben (1/20 pont) értelmeződik.<br/>            Ha a RowGapRule 4-re („Multiple”) van állítva, akkor az egység fél sorokként értelmeződik.<br/>            Alapértelmezett: 0 |

## Metódusok

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/join/#str) | Összekapcsol egy matematikai szöveget és egy matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/enclose/#) | Matematikai elemet zárójelek közé helyez |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Matematikai elemet meghatározott karakterek közé helyez, például zárójeleket vagy más karaktereket keretezésként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Függvényt vesz fel egy argumentummal, ennek a példánynak a neveként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/function/#str) | Függvényt vesz fel egy argumentummal, ennek a példánynak a neveként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Megadott függvényt vesz fel, ezt a példányt argumentumként használva |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Megadott függvényt vesz fel, ezt a példányt argumentumként használva |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz fel, ezt a példányt argumentumként használva |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz fel, ezt a példányt argumentumként használva, plusz megadott további argumentummal |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz fel, ezt a példányt argumentumként használva, plusz megadott további argumentummal |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Alindexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Alindexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Al- és felső indexet hoz létre a jobb oldalon |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Al- és felső indexet hoz létre a jobb oldalon |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Al- és felső indexet hoz létre a bal oldalon |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Al- és felső indexet hoz létre a bal oldalon |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/radical/#str) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Felső határt vesz fel |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Felső határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Alsó határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Alsó határt vesz fel |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-áris operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | N-áris operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz fel |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Integrált vesz fel határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Integrált vesz fel |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/group/#) | Az elemet egy csoportba helyezi alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, mint például alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/accent/#char) | Akcentus jelet állít be (a(z) elem tetejére kerülő karakter) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/to_box/#) | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi<br/>            amelyet egyenlet komponenseinek vagy más matematikai szöveg példányok csoportosítására használnak.<br/>            Egy dobozos objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül,<br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sorok törését benne. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Lekéri a megadott oszlop vízszintes igazítását |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Beállítja a megadott oszlop vízszintes igazítását |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Beállítja a megadott oszlopok vízszintes igazítását |
| [`insert_row_before(self, row_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Új sort szúr be a megadott előtt<br/>            Kezdetben az új sor minden eleme None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Új sort szúr be a megadott után<br/>            Kezdetben az új sor minden eleme None. |
| [`delete_row(self, row_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Törli a megadott sort |
| [`insert_column_before(self, column_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Új oszlopot szúr be a megadott előtt<br/>            Kezdetben az új oszlop minden eleme None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Új oszlopot szúr be a megadott után<br/>            Kezdetben az új oszlop minden eleme None. |
| [`delete_column(self, column_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Törli a megadott oszlopot |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/get_children/#) | Lekéri a gyermekelemeket |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathMatrix`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)