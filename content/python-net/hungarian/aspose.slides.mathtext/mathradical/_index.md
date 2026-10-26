---
title: MathRadical class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathradical/
---
## MathRadical osztály

Megadja a gyökfüggvényt, mely egy alappal és egy opcionális kitevővel rendelkezik.  
A radikális objektum példája √𝑥.

**Öröklés:**[`MathRadical`](/slides/python-net/hu/aspose.slides.mathtext/mathradical) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathRadical típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, base_argument, degree_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/__init__/#imathelement-imathelement) | Új MathRadical osztálypéldányt inicializál. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/base/) | Alap argumentum |
| [`degree`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/degree/) | Kitevő argumentum |
| [`hide_degree`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/hide_degree/) | Kitevő elrejtése<br/>            Ha igaz, a kitevő nem jelenik meg, például √𝑥 |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/join/#imathelement) | Összekapcsol egy matematikai elemet, és egy matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/join/#str) | Összekapcsol egy matematikai szöveget, és egy matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/divide/#imathelement) | Létrehozza a törtet az aktuális számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/divide/#str) | Létrehozza a törtet az aktuális számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/divide/#imathelement-mathfractiontypes) | Létrehozza a megadott típusú törtet az aktuális számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/divide/#str-mathfractiontypes) | Létrehozza a megadott típusú törtet az aktuális számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/enclose/#) | Zárójelekbe helyezi a matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/enclose/#char-char) | A matematikai elemet megadott karakterek közé helyezi, például zárójelek vagy más karakterek közé keretezve |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/function/#imathelement) | Argumentumfüggvényt vesz, a példányt használva függvénynévként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/function/#str) | Argumentumfüggvényt vesz, a példányt használva függvénynévként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/as_argument_of_function/#imathelement) | A megadott függvényt veszi, a példányt argumentumként használva |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/as_argument_of_function/#str) | A megadott függvényt veszi, a példányt argumentumként használva |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsofoneargument) | A megadott függvényt veszi, a példányt argumentumként használva |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | A megadott függvényt veszi, a példányt argumentumként, és egy megadott további argumentumot |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-str) | A megadott függvényt veszi, a példányt argumentumként, és egy megadott további argumentumot |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_subscript/#imathelement) | Alsó indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_subscript/#str) | Alsó indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#imathelement-imathelement) | Jobbra helyezi az alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#str-str) | Jobbra helyezi az alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#imathelement-imathelement) | Balra helyezi az alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#str-str) | Balra helyezi az alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/radical/#imathelement) | Megadja a megadott fokszámú matematikai gyököt a specifikált argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/radical/#str) | Megadja a megadott fokszámú matematikai gyököt a specifikált argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_upper_limit/#imathelement) | Felső határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_upper_limit/#str) | Felső határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-áris operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-str-str) | N-áris operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrálást vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement) | Integrálást vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes) | Integrálást vesz korlátok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrálást vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str) | Integrálást vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/group/#) | Az elemet egy csoportba helyezi, alsó kapcsos zárójelet használva |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi, egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/accent/#char) | Akcentus jelet állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/overbar/#) | Felső vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/underbar/#) | Alsó vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/to_box/#) | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi <br/>            amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak.<br/>            A keretezett objektum például szolgálhat operátor emulátorként egy igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje a sortöréseket belül. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/get_children/#) | Gyermek elemek lekérése |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathRadical`](/slides/python-net/hu/aspose.slides.mathtext/mathradical)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)