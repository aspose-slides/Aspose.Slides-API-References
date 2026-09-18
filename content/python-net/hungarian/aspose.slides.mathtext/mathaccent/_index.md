---
title: MathAccent class
second_title: Aspose.Slides for Python a .NET API hivatkozás segítségével
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathaccent/
---
## MathAccent osztály

Megadja a hangsúlyozó függvényt, amely egy alapból és egy kombináló diakritikus jelből áll. Példa: 𝑎́

**Öröklődés:**[`MathAccent`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathAccent típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | Létrehoz egy matematika hangsúlyt, amely egy megadott matematika elemre alkalmazza az alapértelmezett hangsúly karakter értékét |
| [`__init__(self, element, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | Létrehoz egy matematika hangsúlyt, amely egy megadott matematika elemre alkalmazódik |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/base/) | Az argumentum, amelyre a hangsúly alkalmazva lett |
| [`character`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/character/) | Hangsúly karakter<br/>            Az értéknek a (U+0300–U+036F) vagy (U+20D0–U+20EF) tartományon belül kell lennie<br/>            Alapértelmezett érték: Kombináló körülírás hangsúly (U+0302) |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/join/#imathelement) | Összevon egy matematikai elemet és egy matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/join/#str) | Összevon egy matematikai szöveget és egy matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | Létrehoz egy meghatározott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | Létrehoz egy meghatározott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/enclose/#) | Zárja be egy matematikai elemet zárójelek közé |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/enclose/#char-char) | Zárja be egy matematikai elemet meghatározott karakterekkel, például zárójelek vagy más karakterek keretezéseként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/function/#imathelement) | Felvesz egy argumentum függvényt, ez az példány a függvény neveként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/function/#str) | Felvesz egy argumentum függvényt, ez az példány a függvény neveként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | Felvesz egy meghatározott függvényt, ez az példány az argumentumként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | Felvesz egy meghatározott függvényt, ez az példány az argumentumként |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | Felvesz egy meghatározott függvényt, ez az példány az argumentumként |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Felvesz egy meghatározott függvényt, ez az példány az argumentumként, és egy megadott további argumentumot |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Felvesz egy meghatározott függvényt, ez az példány az argumentumként, és egy megadott további argumentumot |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | Létrehoz alsó indexet |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_subscript/#str) | Létrehoz alsó indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | Létrehoz felső indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_superscript/#str) | Létrehoz felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | Létrehoz alsó és felső indexet jobbra |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | Létrehoz alsó és felső indexet jobbra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | Létrehoz alsó és felső indexet balra |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | Létrehoz alsó és felső indexet balra |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/radical/#imathelement) | Megadja a megadott argumentumból származó matematikai gyököt a megadott fokban. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/radical/#str) | Megadja a megadott argumentumból származó matematikai gyököt a megadott fokban. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | Felvesz felső határt |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | Felvesz felső határt |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | Felvesz alsó határt |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | Felvesz alsó határt |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz egy N-árnyalatos operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | Létrehoz egy N-árnyalatos operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Felveszi az integrált |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | Felveszi az integrált |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | Felveszi az integrált határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | Felveszi az integrált |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | Felveszi az integrált |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/group/#) | Elhelyezi ezt az elemet egy csoportba alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | Elhelyezi ezt az elemet egy csoportba egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/to_border_box/#) | Elhelyezi ezt az elemet egy keretdobozban |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Elhelyezi ezt az elemet egy keretdobozban |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/accent/#char) | Beállít egy hangsúly jelet (egy karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/overbar/#) | Beállít egy vonalat az elem tetején |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/underbar/#) | Beállít egy vonalat az elem alján |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/to_box/#) | Elhelyezi ezt az elemet egy nem látható dobozba (logikai csoportosítás) <br/>            amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak.<br/>            Egy dobozba helyezett objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedélyezzen sortöréseket benne. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/get_children/#) | Lekéri a gyermek elemeket |

### Lásd még
* osztály [`MathAccent`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)