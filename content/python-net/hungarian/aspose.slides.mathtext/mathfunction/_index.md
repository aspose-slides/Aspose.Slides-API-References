---
title: MathFunction class
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathfunction/
---
## MathFunction osztály

Megad egy függvényt egy argumentummal.

**Öröklés:**[`MathFunction`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathFunction típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | Inicializál egy új MathFunction osztálypéldányt. |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | Inicializál egy új MathFunction osztálypéldányt. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`name`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/name/) | Függvény neve<br/>Például a függvénynevek a sin és a cos |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/base/) | Függvény argumentum |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/join/#imathelement) | Összekapcsol egy matematikai elemet és létrehoz egy matematikai blokkot |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/join/#str) | Összekapcsol egy matematikai szöveget és létrehoz egy matematikai blokkot |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/enclose/#) | Egy matematikai elemet zárójelek közé helyez |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/enclose/#char-char) | Egy matematikai elemet megadott karakterek közé, például zárójelek vagy más keretező karakterek közé helyez |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/function/#imathelement) | Függvényt vesz egy argumentummal, ahol ez a példány a függvény neve |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/function/#str) | Függvényt vesz egy argumentummal, ahol ez a példány a függvény neve |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | Megadott függvényt vesz, ahol ez a példány az argumentum |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | Megadott függvényt vesz, ahol ez a példány az argumentum |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz, ahol ez a példány az argumentum |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz, ahol ez a példány az argumentum, és megadott további argumentumot is használ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz, ahol ez a példány az argumentum, és megadott további argumentumot is használ |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | Aláindexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_subscript/#str) | Aláindexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | Felsőindexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_superscript/#str) | Felsőindexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Jobb oldalon alá- és felsőindexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | Jobb oldalon alá- és felsőindexet hoz létre |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Bal oldalon alá- és felsőindexet hoz létre |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | Bal oldalon alá- és felsőindexet hoz létre |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/radical/#str) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | Felső határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | Felső határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-áris operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | N-áris operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | Integrált vesz határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | Integrált vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/group/#) | Az elemet egy csoportra helyezi, alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportra helyezi, olyan csoportosító karakterrel, mint az alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/accent/#char) | Akcentus jelet (egy karaktert az elem tetejére) állít be |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/to_box/#) | Az elemet egy nem-visualizálható dobozba (logikai csoportosítás) helyezi <br/>            amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak.<br/>            Egy dobozba helyezett objektum (például) szolgálhat operátor emulátorként rendezési ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedje meg a sortöréseket benne. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/get_children/#) | Gyermek elemek lekérése |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathFunction`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)