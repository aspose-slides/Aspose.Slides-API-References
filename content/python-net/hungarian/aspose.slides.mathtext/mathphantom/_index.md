---
title: MathPhantom class
second_title: Aspose.Slides Python számára .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathphantom/
---
## MathPhantom osztály

Egy fantom matematikai objektumot (<m:phant>) reprezentál, amely befolyásolja a gyermekelem elrendezését anélkül, hogy feltétlenül megjelenítené azt. A fantom elrejtheti az alapkifejezését, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy hely lefoglalásához. A láthatóságot és a geometriai viselkedést olyan tulajdonságok szabályozzák, mint a Show, ZeroWid, ZeroAsc, ZeroDesc és a Transp.

**Öröklés:**[`MathPhantom`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathPhantom típus a következő tagokat biztosítja:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Initializál egy új példányt a [`MathPhantom`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom) osztályból <br/> a megadott alap matematikai elemmel. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/base/) | Alap argumentum |
| [`show`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/show/) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem megjelenik-e. |
| [`zero_width`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/zero_width/) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem szélességét <br/> nullaként kell kezelni. |
| [`zero_asc`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/zero_asc/) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem feljebb emelkedése (a bázisszint feletti magasság) <br/> nullaként kell kezelni. |
| [`zero_desc`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/zero_desc/) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy az alap elem süllyedése (a bázisszint alatti mélység)<br/> nullaként kell kezelni. |
| [`transp`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/transp/) | Értéket ad vissza vagy állít be, amely azt jelzi, hogy a fantom átlátszó <br/> az osztály-alapú térköz szabályok esetén. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/join/#imathelement) | Összekapcsol egy matematikai elemet, és matematikai blokkot hoz létre. |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/join/#str) | Összekapcsol egy matematikai szöveget, és matematikai blokkot hoz létre. |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Létrehoz egy törtet az aktuális számlálóval és a megadott nevezővel. |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/divide/#str) | Létrehoz egy törtet az aktuális számlálóval és a megadott nevezővel. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Létrehoz egy adott típusú törtet az aktuális számlálóval és a megadott nevezővel. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Létrehoz egy adott típusú törtet az aktuális számlálóval és a megadott nevezővel. |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/enclose/#) | Zárójelez egy matematikai elemet. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretez. |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/function/#imathelement) | Készít egy függvényt egy argumentummal, ahol ezt az példányt használja a függvény nevének. |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/function/#str) | Készít egy függvényt egy argumentummal, ahol ezt az példányt használja a függvény nevének. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Megadott függvényt vesz, ahol ezt az példányt használja argumentumként. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Megadott függvényt vesz, ahol ezt az példányt használja argumentumként. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz, ahol ezt az példányt használja argumentumként. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz, ahol ezt az példányt használja argumentumként, és megadott további argumentumot. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz, ahol ezt az példányt használja argumentumként, és megadott további argumentumot. |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Alindexet hoz létre. |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Alindexet hoz létre. |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Felső indexet hoz létre. |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Felső indexet hoz létre. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Al- és felső indexet hoz létre jobbra. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Al- és felső indexet hoz létre jobbra. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Al- és felső indexet hoz létre balra. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Al- és felső indexet hoz létre balra. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/radical/#str) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Vállal felső határt. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Vállal felső határt. |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Vállal alsó határt. |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Vállal alsó határt. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-áris operátort hoz létre. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | N-áris operátort hoz létre. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Vállal integrált. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Vállal integrált. |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Vállal integrált korlátok nélkül. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Vállal integrált. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Vállal integrált. |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/group/#) | Elhelyezi ezt az elemet egy csoportban, az alsó kapcsos zárójelet használva. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Elhelyezi ezt az elemet egy csoportban, egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más karakter. |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/to_border_box/#) | Elhelyezi ezt az elemet egy keretdobozban. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Elhelyezi ezt az elemet egy keretdobozban. |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/to_math_array/#) | Függőleges tömbbe helyezi. |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/accent/#char) | Akcentus jelet állít be (karakter az elem tetején). |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/overbar/#) | Felső vonalat állít be az elem tetején. |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/underbar/#) | Alsó vonalat állít be az elem alján. |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/to_box/#) | Elhelyezi ezt az elemet egy nem látható dobozban (logikai csoportosítás) <br/>            amely egyenlet vagy más matematikai szöveg komponenseinek csoportosítására szolgál.<br/>            Egy dobozba helyezett objektum (például) szolgálhat operátor emulátorral, igazítási ponttal vagy anélkül, <br/>            sorvége pontként használható, vagy olyan módon csoportosítható, hogy ne engedélyezze a sorok törését benne. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/get_children/#) | Gyermekelemek lekérése |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathPhantom`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)