---
title: MathSuperscriptElement class
second_title: Aspose.Slides Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement osztály

Megadja a felső index objektumot, amely egy alapból és egy kisebb méretű felső indexből áll, amely a jobb felső részén helyezkedik el.

**Öröklés:**[`MathSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement) → [`BaseScript`](/slides/python-net/hu/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathSuperscriptElement típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, base_arg, super_script)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/__init__/#imathelement-imathelement) | Inicializál egy új példányt a MathSuperscriptElement osztályból. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/base/) | Alap argumentum |
| [`superscript`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/superscript/) | Felső index |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/join/#imathelement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/join/#str) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/divide/#str-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/enclose/#) | Zárójelek közé helyezi a matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/enclose/#char-char) | A megadott karakterek (például zárójelek vagy más karakterek) közé helyezi a matematikai elemet keretként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/function/#imathelement) | Függvényt vesz egy argumentumból, amelyben ez a példány a függvény neve |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/function/#str) | Függvényt vesz egy argumentumból, amelyben ez a példány a függvény neve |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#imathelement) | Megadott függvényt vesz, amelyben ez a példány az argumentum |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#str) | Megadott függvényt vesz, amelyben ez a példány az argumentum |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz, amelyben ez a példány az argumentum |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz, amelyben ez a példány az argumentum, és egy megadott további argumentumot is |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz, amelyben ez a példány az argumentum, és egy megadott további argumentumot is |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#imathelement) | Al-indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#str) | Al-indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Jobb oldalon hoz létre al-indexet és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Jobb oldalon hoz létre al-indexet és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Bal oldalon hoz létre al-indexet és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Bal oldalon hoz létre al-indexet és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/radical/#imathelement) | Megadja a megadott argumentum adott fokú matematikai gyökét. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/radical/#str) | Megadja a megadott argumentum adott fokú matematikai gyökét. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#imathelement) | Felső határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#str) | Felső határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-áris operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | N-áris operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes) | Integrált vesz határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str) | Integrált vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/group/#) | Ez az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Ez az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#) | Ez az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Ez az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/accent/#char) | Kiemelő jelzést állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/to_box/#) | Ez az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi <br/>            amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak.<br/>            A dobozos objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedjen sortörést a belsejében. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/get_children/#) | Gyermek elemeket kap |

### Lásd még
* osztály [`BaseScript`](/slides/python-net/hu/aspose.slides.mathtext/basescript)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)