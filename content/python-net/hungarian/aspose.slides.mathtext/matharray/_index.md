---
title: MathArray class
second_title: Aspose.Slides Pythonhoz a .NET API referenciáján keresztül
description: 
type: docs
url: /hu/aspose.slides.mathtext/matharray/
---
## MathArray osztály

Specifies a vertical array of equations or any mathematical objects

**Inheritance:**[`MathArray`](/slides/python-net/hu/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

The MathArray type exposes the following members:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/__init__/#imathelement) | Létrehoz egy matematikai tömböt, és elhelyezi benne a megadott elemet |
| [`__init__(self, elements)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`arguments`](/slides/python-net/hu/aspose.slides.mathtext/matharray/arguments/) | A tömb elemeinek halmaza |
| [`base_justification`](/slides/python-net/hu/aspose.slides.mathtext/matharray/base_justification/) | Megadja a tömb igazítását a környező szöveghez képest<br/>            A tömbön kívüli szöveg a tömb objektum aljára, tetejére vagy közepére igazítható.<br/>            Alapértelmezett érték: Center |
| [`maximum_distribution`](/slides/python-net/hu/aspose.slides.mathtext/matharray/maximum_distribution/) | Maximum elosztás<br/>            Ha true, a tömb a tartalmazó elem (page, column, cell, etc.) maximális szélességéhez van igazítva. |
| [`object_distribution`](/slides/python-net/hu/aspose.slides.mathtext/matharray/object_distribution/) | Objektum elosztás<br/>            Ha true, a tömb tartalma a tömb objektum maximális szélességéhez van igazítva. |
| [`row_spacing_rule`](/slides/python-net/hu/aspose.slides.mathtext/matharray/row_spacing_rule/) | A tömb elemei közötti függőleges távolság típusa<br/>            Alapértelmezett: SingleLineGap |
| [`row_spacing`](/slides/python-net/hu/aspose.slides.mathtext/matharray/row_spacing/) | A tömb sorai közti távolság<br/>            Csak akkor használatos, ha a RowSpacingRule értéke 3 (Exact), ebben az esetben a mértékegység pont<br/>            vagy Multiple, ebben az esetben a mértékegység fél sor.<br/>            Alapértelmezett: 0 |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/join/#imathelement) | Összekapcsol egy matematikai elemet, és létrehoz egy matematikai blokkot |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/join/#str) | Összekapcsol egy matematikai szöveget, és létrehoz egy matematikai blokkot |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/enclose/#) | Zárójelekbe helyezi a matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/enclose/#char-char) | Megadott karakterekbe, például zárójelekbe vagy más karakterekbe helyezi a matematikai elemet keretként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/function/#imathelement) | Függvényt vesz argumentummal, az aktuális példányt használva a függvény nevének |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/function/#str) | Függvényt vesz argumentummal, az aktuális példányt használva a függvény nevének |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Megadott függvényt vesz, az aktuális példányt argumentumként használva |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Megadott függvényt vesz, az aktuális példányt argumentumként használva |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz, az aktuális példányt argumentumként használva |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz, az aktuális példányt argumentumként, valamint egy megadott további argumentumot |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz, az aktuális példányt argumentumként, valamint egy megadott további argumentumot |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Létrehoz alsó indexet |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_subscript/#str) | Létrehoz alsó indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Létrehoz felső indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_superscript/#str) | Létrehoz felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Létrehoz alsó és felső indexet jobbra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Létrehoz alsó és felső indexet jobbra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Létrehoz alsó és felső indexet balra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Létrehoz alsó és felső indexet balra |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/radical/#imathelement) | Megadja a megadott argumentum adott fokszámú matematikai gyökét. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/radical/#str) | Megadja a megadott argumentum adott fokszámú matematikai gyökét. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Felső határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Felső határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz egy N-ary operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Létrehoz egy N-ary operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Integrált vesz határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Integrált vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/group/#) | Ez az elemet egy csoportba helyezi alul lévő kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Ez az elemet egy csoportba helyezi egy csoportosító karakter, például alul lévő kapcsos zárójel vagy más használatával |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/to_border_box/#) | Ez az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Ez az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/to_math_array/#) | Elhelyez egy függőleges tömbbe |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/accent/#char) | Akcentusjelzetet állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/to_box/#) | Ez az elemet egy nem látható dobozba helyezi (logikai csoportosítás) <br/>            amelyet egy egyenlet vagy más matematikai szövegrész komponenseinek csoportosítására használnak.<br/>            Egy keretes objektum (például) szolgálhat operátor-emulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sorvágó pontként, vagy úgy csoportosítható, hogy ne engedje meg a sorok törését benne. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/matharray/get_children/#) | Gyermek elemek lekérése |


### Lásd még
* osztály [`MathArray`](/slides/python-net/hu/aspose.slides.mathtext/matharray)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)