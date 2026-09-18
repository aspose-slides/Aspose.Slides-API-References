---
title: MathLimit class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathlimit/
---
## MathLimit osztály

Meghatározza a Limit objektumot, amely a kiinduló vonalon lévő szöveget és a közvetlenül fölötte vagy alatta elhelyezkedő kisebb méretű szöveget tartalmazza.

**Öröklődés:**[`MathLimit`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathLimit típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | Új példányt hoz létre a MathLimit osztályból. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Új példányt hoz létre a MathLimit osztályból alsó korláttal |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/base/) | Alap argumentum |
| [`limit`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/limit/) | Korlát argumentum |
| [`upper_limit`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/upper_limit/) | Megadja a felső vagy alsó korlátot |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/join/#imathelement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/join/#str) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/enclose/#) | Zárójelek közé helyezi a matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/enclose/#char-char) | A matematikai elemet megadott karakterek közé helyezi, például zárójelekbe vagy más keretező karakterekbe |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/function/#imathelement) | Függvényt vesz fel egy argumentummal, a példányt a függvény nevének használja |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/function/#str) | Függvényt vesz fel egy argumentummal, a példányt a függvény nevének használja |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Megadott függvényt vesz fel, a példányt argumentumként használja |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Megadott függvényt vesz fel, a példányt argumentumként használja |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz fel, a példányt argumentumként használja |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz fel, a példányt argumentumként használja és egy további argumentumot |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz fel, a példányt argumentumként használja és egy további argumentumot |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Alsó indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Alsó indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Jobb oldalon hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Jobb oldalon hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Bal oldalon hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Bal oldalon hoz létre alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/radical/#str) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Felső korlátot vesz fel |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Felső korlátot vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Alsó korlátot vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Alsó korlátot vesz fel |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-értelmű operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | N-értelmű operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz fel |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Határolás nélküli integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | Integrált vesz fel |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/group/#) | A elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | A elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/accent/#char) | Akcentus jelet állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/to_box/#) | Elhelyezi ezt az elemet egy nem látható dobozban (logikai csoportosítás) <br/>            amelyet egy egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak.<br/>            Egy keretezett objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedélyezzen sortöréseket a belsejében. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/get_children/#) | Gyermek elemek lekérdezése |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathLimit`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)