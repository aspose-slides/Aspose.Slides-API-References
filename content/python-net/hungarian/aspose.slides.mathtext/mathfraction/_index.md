---
title: MathFraction class
second_title: Aspose.Slides Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathfraction/
---
## MathFraction osztály

Meghatározza a tört objektumot, amely egy számlálóból és nevezőből áll, és egy törtvonal választja el őket.
            A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően.
            A tört objektumot a stack függvény ábrázolására is használják, amely egy elemet egy másik fölé helyez el, törtvonal nélkül.

**Inheritance:**[`MathFraction`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathFraction típus a következő tagokat biztosítja:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | Inicializálja a MathFraction-t a megadott számlálóval, nevezővel és típussal |
| [`__init__(self, numerator, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | Inicializál egy 'Bar' típusú MathFraction-t a megadott számlálóval és nevezővel |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`fraction_type`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/fraction_type/) | Tört típus<br/>            Default: Bar |
| [`numerator`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/numerator/) | Számláló |
| [`denominator`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/denominator/) | Nevező |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/join/#imathelement) | Összekapcsol egy matematikai elemet és létrehoz egy matematikai blokkot |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/join/#str) | Összekapcsol egy matematikai szöveget és létrehoz egy matematikai blokkot |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | Létrehoz egy törtet a megadott típusban ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | Létrehoz egy törtet a megadott típusban ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/enclose/#) | Zárójelez egy matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/enclose/#char-char) | Zárójelez egy matematikai elemet meghatározott karakterekkel, például zárójelekkel vagy más karakterekkel keretként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/function/#imathelement) | Vesz egy függvényt egy argumentummal, a példányt a függvény nevének használva |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/function/#str) | Vesz egy függvényt egy argumentummal, a példányt a függvény nevének használva |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | Vesz egy megadott függvényt, a példányt argumentumként használva |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | Vesz egy megadott függvényt, a példányt argumentumként használva |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | Vesz egy megadott függvényt, a példányt argumentumként használva |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Vesz egy megadott függvényt, a példányt argumentumként és egy megadott további argumentumot használva |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Vesz egy megadott függvényt, a példányt argumentumként és egy megadott további argumentumot használva |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | Létrehoz alsó indexet |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_subscript/#str) | Létrehoz alsó indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | Létrehoz felső indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_superscript/#str) | Létrehoz felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Létrehoz jobb oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | Létrehoz jobb oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Létrehoz bal oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | Létrehoz bal oldali alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a specifikált argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/radical/#str) | Megadja a megadott fokú matematikai gyököt a specifikált argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | Vesz felső határt |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | Vesz felső határt |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | Vesz alsó határt |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | Vesz alsó határt |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz egy N-értelmű operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | Létrehoz egy N-értelmű operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Vesz integrált |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | Vesz integrált |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | Vesz integrált határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Vesz integrált |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | Vesz integrált |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/group/#) | Elhelyezi ezt az elemet egy csoportban alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | Elhelyezi ezt az elemet egy csoportban egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más karakter |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/to_border_box/#) | Elhelyezi ezt az elemet egy keretdobozban |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Elhelyezi ezt az elemet egy keretdobozban |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/accent/#char) | Beállít egy akcentus jelet (karakter a elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/overbar/#) | Beállít egy sávot az elem tetején |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/underbar/#) | Beállít egy sávot az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/to_box/#) | Elhelyezi ezt az elemet egy nem vizuális dobozba (logikai csoportosítás) <br/>            amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak.<br/>            Egy keretezett objektum (például) szolgálhat operátoros emulátorként illeszkedési ponttal vagy anélkül, <br/>            sorvége pontként, vagy csoportosítható úgy, hogy ne engedélyezze a sortöréseket belül. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/get_children/#) | Gyermekelemek lekérése |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathFraction`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)