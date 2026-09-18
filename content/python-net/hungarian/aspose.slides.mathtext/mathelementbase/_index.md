---
title: MathElementBase class
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase osztály

Alap osztály az IMathElement számára, amely néhány, az összes leszármazott osztályra jellemző metódus megvalósítását tartalmazza. Csak belső használatra. A leszármazott osztálynak IMathElement-nek kell lennie.

A MathElementBase típus a következő tagokat tartalmazza:

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/join/#imathelement) | Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/join/#str) | Összekapcsol egy matematikai szöveget és egy matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | Létrehoz egy törtet a jelenlegi számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/divide/#str) | Létrehoz egy törtet a jelenlegi számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | Létrehoz egy a megadott típusú törtet a jelenlegi számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | Létrehoz egy a megadott típusú törtet a jelenlegi számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/enclose/#) | Zárójelek közé helyezi a matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | A megadott karakterek (például zárójelek vagy más karakterek) közé helyezi a matematikai elemet |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/function/#imathelement) | Egy argumentum függvényét veszi, a függvény neve ennek a példánynak a neve |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/function/#str) | Egy argumentum függvényét veszi, a függvény neve ennek a példánynak a neve |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | Megadott függvényt vesz, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | Megadott függvényt vesz, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz, amelynek argumentuma ez a példány, valamint egy megadott további argumentum |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz, amelynek argumentuma ez a példány, valamint egy megadott további argumentum |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | Alsó indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | Alsó indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | Jobb oldalon létrehoz alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | Jobb oldalon létrehoz alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | Bal oldalon létrehoz alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | Bal oldalon létrehoz alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/radical/#str) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | Felső határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | Felső határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-értelmű operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | N-értelmű operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | Integrált vesz határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | Integrált vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/group/#) | Ezt az elemet egy csoportba helyezi, alsó kapcsos zárójelet használva |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | Ezt az elemet egy csoportba helyezi, egy csoportosító karaktert használva, például alsó kapcsos zárójelet vagy más karaktert |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/to_border_box/#) | Ezt az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Ezt az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/accent/#char) | Akcentusjelet (a elem tetejére kerülő karakternyi) állít be |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/overbar/#) | Vízszintes vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/underbar/#) | Vízszintes vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/to_box/#) | Ezt az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi <br/>            amely egyenlet vagy más matematikai szöveg komponenseinek csoportosítására szolgál.<br/>            Egy dobozba helyezett objektum (például) szolgálhat operátorémulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket belül. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### Lásd még
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)