---
title: IMathElement class
second_title: Aspose.Slides a Python számára .NET API hivatkozással
description: 
type: docs
url: /hu/aspose.slides.mathtext/imathelement/
---
## IMathElement osztály

Bármely matematikai elem alap interfésze: tört, matematikai szöveg, függvény, több elemből álló kifejezés stb

Az IMathElement típus a következő tagokat teszi elérhetővé:

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/join/#imathelement) | Egy matematikai elemet kapcsol össze, és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/join/#str) | Egy matematikai szöveget kapcsol össze, és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/divide/#imathelement) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/divide/#str) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/divide/#imathelement-mathfractiontypes) | A megadott típusú törtet hozza létre ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/divide/#str-mathfractiontypes) | A megadott típusú törtet hozza létre ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/enclose/#) | Egy matematikai elemet zárójelek közé helyez |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/enclose/#char-char) | Az elemet a megadott karakterekkel zárja körül, például zárójelekkel vagy más karakterekkel |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/function/#imathelement) | Ezzel a példánnyal függvény nevet használva egy argumentum funkciót vesz |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/function/#str) | Ezzel a példánnyal függvény nevet használva egy argumentum funkciót vesz |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/as_argument_of_function/#imathelement) | Megadott függvényt vesz, ezzel a példánnyal argumentumként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/as_argument_of_function/#str) | Megadott függvényt vesz, ezzel a példánnyal argumentumként |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz, ezzel a példánnyal argumentumként |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz, ezzel a példánnyal argumentumként, és megadott további argumentummal |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz, ezzel a példánnyal argumentumként, és megadott további argumentummal |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_subscript/#imathelement) | Alsó indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_subscript/#str) | Alsó indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | A jobb oldalon hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#str-str) | A jobb oldalon hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | A bal oldalon hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#str-str) | A bal oldalon hoz létre alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/radical/#str) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_upper_limit/#imathelement) | Felülhatárt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_upper_limit/#str) | Felülhatárt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-áris operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-str-str) | N-áris operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes) | Integrált vesz határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str) | Integrált vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/group/#) | Az elemet egy csoportba helyezi, alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi, egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/get_children/#) | Gyermekelemeket kap |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/to_math_array/#) | Függőleges tömbben helyezi el |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/accent/#char) | Akcentusjelet állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/overbar/#) | Sávot helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/underbar/#) | Sávot helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/to_box/#) | Az elemet egy nem vizuális dobozba (logikai csoportosítás) <br/> amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak.<br/> Egy dobozba helyezett objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, <br/> szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy a belsejében ne legyenek sortörések. |

### Lásd még
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)