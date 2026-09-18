---
title: MathBar class
second_title: Aspose.Slides Pythonhoz az .NET API hivatkozásán keresztül
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathbar/
---
## MathBar osztály

Meghatározza a vonalfüggvényt, amely egy alapargumentumból és egy felül- vagy alulvonalból áll

**Inheritance:**[`MathBar`](/slides/python-net/hu/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathBar típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Inicializálja a MathBar-t felülvonallal (Felső pozíció) |
| [`__init__(self, element, position)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Inicializálja a MathBar-t megadott pozícióval |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/base/) | Alap argumentum |
| [`position`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/position/) | A vonal pozíciója. <br/>            Alapértelmezett: Felső |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/join/#imathelement) | Összekapcsol egy matematikai elemet, és egy matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/join/#str) | Összekapcsol egy matematikai szöveget, és egy matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/enclose/#) | Zárja be a matematikai elemet zárójelbe |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/enclose/#char-char) | Zárja be a matematikai elemet megadott karakterekkel, például zárójelek vagy más karakterek közé |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/function/#imathelement) | Egy argumentumfüggvényt vesz fel, amelynek a függvény neve ez a példány |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/function/#str) | Egy argumentumfüggvényt vesz fel, amelynek a függvény neve ez a példány |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Megadott függvényt vesz fel, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Megadott függvényt vesz fel, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz fel, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz fel, amelynek argumentuma ez a példány és egy megadott további argumentum |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz fel, amelynek argumentuma ez a példány és egy megadott további argumentum |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Létrehoz alsó indexet |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_subscript/#str) | Létrehoz alsó indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Létrehoz felső indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_superscript/#str) | Létrehoz felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Létrehoz jobbra elhelyezett alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Létrehoz jobbra elhelyezett alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Létrehoz balra elhelyezett alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Létrehoz balra elhelyezett alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/radical/#imathelement) | Meghatározza a megadott fokú matematikai gyökeret a megadott argumentumból |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/radical/#str) | Meghatározza a megadott fokú matematikai gyökeret a megadott argumentumból |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Felső határt vesz fel |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Felső határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Alsó határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Alsó határt vesz fel |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz egy N-áris operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Létrehoz egy N-áris operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz fel |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Integrált vesz fel korlátok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Integrált vesz fel |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/group/#) | Az elemet egy csoportba helyezi alulra lévő kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi csoportosító karakterrel, például alulra lévő kapcsos zárójelet vagy más karaktert használva |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/accent/#char) | Akcentusjelet állít be (egy karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/to_box/#) | Egy nem látható dobozba (logikai csoportosítás) helyezi ezt az elemet <br/>            amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak.<br/>            Egy dobozos objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedjen sortöréseket a belsejében. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/get_children/#) | Gyermekelemek lekérése |

### Lásd még
* osztály [`MathBar`](/slides/python-net/hu/aspose.slides.mathtext/mathbar)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)