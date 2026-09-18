---
title: MathBorderBox class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Reference
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox osztály

Téglalap alakú vagy más típusú keretet rajzol az IMathElement körül.

**Öröklés:**[`MathBorderBox`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathBorderBox típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Létrehozza a MathBorderBox elemet téglalap alakú kerettel |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Létrehozza a MathBorderBox elemet |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/base/) | Alap argumentum |
| [`hide_top`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/hide_top/) | Felső él elrejtése (alapértelmezett hamis) – megadja a keretdoboz felső élének rejtett vagy látható állapotát. |
| [`hide_bottom`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Alsó él elrejtése (alapértelmezett hamis) – megadja a keretdoboz alsó élének rejtett vagy látható állapotát. |
| [`hide_left`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/hide_left/) | Bal él elrejtése (alapértelmezett hamis) – megadja a keretdoboz bal élének rejtett vagy látható állapotát. |
| [`hide_right`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/hide_right/) | Jobb él elrejtése (alapértelmezett hamis) – megadja a keretdoboz jobb élének rejtett vagy látható állapotát. |
| [`strikethrough_horizontal`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Vízszintes áthúzás (alapértelmezett hamis) – megadja egy vízszintes áthúzási vonal rejtett vagy látható állapotát. |
| [`strikethrough_vertical`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Függőleges áthúzás (alapértelmezett hamis) – megadja egy függőleges áthúzási vonal rejtett vagy látható állapotát. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Bal alsó saroktól jobb felső sarokig áthúzás (alapértelmezett hamis).<br/>            Megadja a keretdoboz bal alsó sarkától jobb felső sarkáig ívelő áthúzási vonal rejtett vagy látható állapotát. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Bal felső saroktól jobb alsó sarokig áthúzás (alapértelmezett hamis).<br/>            Megadja a keretdoboz bal felső sarkától jobb alsó sarkáig ívelő áthúzási vonal rejtett vagy látható állapotát. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/join/#str) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/enclose/#) | Körülveszi egy matematikai elemet zárójelekbe |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Körülveszi a matematikai elemet megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretezve |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Függvényt vesz fel egy argumentummal, a példányt használva a függvény nevéként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/function/#str) | Függvényt vesz fel egy argumentummal, a példányt használva a függvény nevéként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Megadott függvényt vesz fel, ezt a példányt használva argumentumként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Megadott függvényt vesz fel, ezt a példányt használva argumentumként |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz fel, ezt a példányt használva argumentumként |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz fel, ezt a példányt használva argumentumként, valamint egy megadott további argumentumot |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz fel, ezt a példányt használva argumentumként, valamint egy megadott további argumentumot |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Létrehoz alsó indexet |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Létrehoz alsó indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Létrehoz felső indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Létrehoz felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Létrehoz jobb oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Létrehoz jobb oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Létrehoz bal oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Létrehoz bal oldali alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/radical/#str) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Felső határt vesz fel |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Felső határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Alsó határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Alsó határt vesz fel |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz N-áris operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Létrehoz N-áris operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz fel |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Integrált vesz fel korlátok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Integrált vesz fel |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/group/#) | Az elemet egy csoportba helyezi alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi egy csoportosító karakter, például alsó kapcsos zárójel vagy más, használatával |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Az elemet keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/accent/#char) | Akcentusjelet állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/overbar/#) | Vízszintes vonalat állít be az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/underbar/#) | Vízszintes vonalat állít be az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/to_box/#) | Az elemet nem vizuális dobozba (logikai csoportosítás) helyezi <br/>            amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak.<br/>            A dobozos objektum (például) szolgálhat operátor-emulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket benne. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/get_children/#) | Gyermekelemek lekérése |


### Lásd még
* osztály [`MathBorderBox`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)