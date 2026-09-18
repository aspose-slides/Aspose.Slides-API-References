---
title: MathematicalText class
second_title: Aspose.Slides a .NET-en keresztül Python számára API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText osztály

Matematikai szöveg

**Öröklődés:**[`MathematicalText`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathematicalText típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/__init__/#) | Alapértelmezett konstruktor (String.Empty érték létrehozása) |
| [`__init__(self, math_symbol)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/__init__/#char) | MathText létrehozása egyetlen szimbólummal |
| [`__init__(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/__init__/#str) | MathematicalText létrehozása szövegből |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | MathematicalText létrehozása szövegből és formázási beállításokkal |

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`value`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/value/) | Szövegérték |
| [`format`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/format/) | Szövegformázási tulajdonságok |

## Metódusok

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/join/#str) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/enclose/#) | Zárójelek közé helyezi a matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | A matematikai elemet megadott karakterekkel zárja, például zárójelekkel vagy más karakterekkel |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | Argumentum függvényét veszi, és ezt az objektumot használja a függvény nevéként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/function/#str) | Argumentum függvényét veszi, és ezt az objektumot használja a függvény nevéként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | A megadott függvényt veszi, és ezt az objektumot használja argumentumként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | A megadott függvényt veszi, és ezt az objektumot használja argumentumként |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | A megadott függvényt veszi, és ezt az objektumot használja argumentumként |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | A megadott függvényt veszi, ezt az objektumot használja argumentumként és megadott további argumentumot ad hozzá |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | A megadott függvényt veszi, ezt az objektumot használja argumentumként és megadott további argumentumot ad hozzá |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | Alsó indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | Alsó indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | Jobb oldalon alkot alsó- és felsőindexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | Jobb oldalon alkot alsó- és felsőindexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | Bal oldalon alkot alsó- és felsőindexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | Bal oldalon alkot alsó- és felsőindexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a specifikált argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/radical/#str) | Megadja a megadott fokú matematikai gyököt a specifikált argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | Felső határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | Felső határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-áris operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | N-áris operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz fel |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | Integrált vesz fel korlátok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | Integrált vesz fel |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/group/#) | Az elemet csoportba helyezi egy alsó kapcsos záróval |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos záróval vagy más karakterrel |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | Az elemet keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/accent/#char) | Akcentusjelet állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/to_box/#) | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi <br/>            amely egyenlet vagy egyéb matematikai szöveg komponenseinek csoportosítására szolgál.<br/>            Egy dobozba helyezett objektum (például) működhet operátor emulátorként, igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedélyezzen sortöréseket belül. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathematicalText`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)