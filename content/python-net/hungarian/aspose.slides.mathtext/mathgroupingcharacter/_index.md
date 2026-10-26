---
title: MathGroupingCharacter class
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter osztály

Megad egy csoportosító szimbólumot egy kifejezés felett vagy alatt, általában az elemek közötti kapcsolat kiemelésére

**Öröklés:**[`MathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathGroupingCharacter típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Inicializál egy új MathGroupingCharacter osztálypéldányt <br/>            az alapértelmezett csoportosító karakterrel: U+23DF (ALSÓ GÖRCSÖS ZÁRÓJELE) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Inicializál egy új MathGroupingCharacter osztálypéldányt. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/base/) | Alap argumentum |
| [`character`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/character/) | Csoportosító karakter<br/>            Alapérték: U+23DF (ALSÓ GÖRCSÖS ZÁRÓJELE) |
| [`position`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/position/) | Csoportosító karakter pozíciója.<br/>            Alapértelmezett: Alsó |
| [`vertical_justification`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Csoportosító karakter függőleges igazítása.<br/>            Meghatározza az objektum igazítását az alapvonalhoz képest.<br/>            Például, ha a csoportosító karakter az objektum felett van, <br/>            a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el;<br/>            ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van<br/>            Alapértelmezett: Bottom, ha Position=Top, és Top, ha Position=Bottom |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Zárójelez egy matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Zárójelez egy matematikai elemet megadott karakterekkel, például zárójelek vagy más keretező karakterek |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Függvényként használja ezt a példányt egy argumentumra, a példány neve a függvény neve |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Függvényként használja ezt a példányt egy argumentumra, a példány neve a függvény neve |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Meghív egy megadott függvényt, ahol ez a példány az argumentum |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Meghív egy megadott függvényt, ahol ez a példány az argumentum |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Meghív egy megadott függvényt, ahol ez a példány az argumentum |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Meghív egy megadott függvényt, ahol ez a példány az argumentum, és egy megadott további argumentumot is használ |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Meghív egy megadott függvényt, ahol ez a példány az argumentum, és egy megadott további argumentumot is használ |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Alsóindexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Alsóindexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Felsőindexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Felsőindexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Jobb oldalon hoz létre alsó- és felsőindexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Jobb oldalon hoz létre alsó- és felsőindexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Bal oldalon hoz létre alsó- és felsőindexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Bal oldalon hoz létre alsó- és felsőindexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Megadja a megadott argumentum adott fokú matematikai gyökét. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Megadja a megadott argumentum adott fokú matematikai gyökét. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Felső határt vesz fel |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Felső határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Alsó határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Alsó határt vesz fel |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-értelmű operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | N-értelmű operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz fel |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Integrált vesz fel határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Integrált vesz fel |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Az elemet egy csoportba helyezi alsó kapcsos zárójel segítségével |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi csoportosító karakterrel, például alsó kapcsos zárójel vagy más karakter |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Akcentus jelet állít be (egy karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Az elemet egy nem-vizuális dobozba (logikai csoportosítás) helyezi <br/>            amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak.<br/>            Egy dobozba helyezett objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket belül. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Gyermekelemek lekérése |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)