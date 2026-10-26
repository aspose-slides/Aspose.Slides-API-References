---
title: MathBox class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathbox/
---
## MathBox osztály

Megadja a matematikai elem logikai dobozolását (csomagolását). Például egy dobozos objektum szolgálhat operátoremulátorként illesztési ponttal vagy anélkül, szolgálhat sortörési pontként, vagy csoportosítható úgy, hogy ne engedjen sortörést belül. Például a "==" operátort dobozni kell a sortörések megelőzése érdekében.

**Öröklődés:**[`MathBox`](/slides/python-net/hu/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathBox típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Inicializálja a MathBox-ot a megadott elemmel argumentumként |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/base/) | Alap argumentum |
| [`operator_emulator`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/operator_emulator/) | Operator Emulator.<br/>            Ha true, a doboz és tartalma egyetlen operátorként viselkedik, és örökli az operátor tulajdonságait.<br/>            Ez azt jelenti, például, hogy a karakter szolgálhat sortörési pontként, és igazítható más operátorokhoz.<br/>            Az Operator Emulatorokat gyakran használják, amikor egy vagy több glif kombinálódik operátorrá, például '=='.<br/>            Alapértelmezett érték: false |
| [`no_break`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/no_break/) | No break<br/>            Ez a tulajdonság határozza meg a "unbreakable" (törhetetlen) tulajdonságot az objektumdobozon. Ha true, sorok nem törhetnek a dobozon belül.<br/>            Ez fontos lehet operátoremulátorok esetén, amelyek több bináris operátorból állnak.<br/>            Ha ez az elem nincs megadva, a törés előfordulhat a dobozon belül.<br/>            Alapértelmezett: true |
| [`differential`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/differential/) | Differential<br/>            Ha true, a doboz differenciálként működik (pl. 𝑑𝑥 egy integrandusban), és megkapja a megfelelő<br/>            vízszintes távolságot a matematikai differenciálhoz.<br/>            Alapértelmezett: false |
| [`alignment_point`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/alignment_point/) | Ha true, ez az operátoremulátor igazítási pontként szolgál; azaz<br/>            más egyenletek kijelölt igazítási pontjai ehhez igazíthatók.<br/>            Alapértelmezett: false |
| [`explicit_break`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/explicit_break/) | Explicit break megadja, hogy van-e sortörés a Box objektum elején,<br/>            így a sor a doboz elején törik.<br/>            Megadja az előző sor matematikai szövegének operátorának számát, amely<br/>            a jelenlegi sor matematikai szövegének igazítási pontjaként szolgál<br/>            lehetséges értékek: 1..255<br/>            Alapértelmezett: 0 (nincs explicit törés) |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/join/#imathelement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/join/#str) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Létrehoz egy adott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/enclose/#) | Zárójelek közé helyezi a matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/enclose/#char-char) | Zárójelek vagy egyéb karakterek közé helyezi a matematikai elemet keretként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/function/#imathelement) | Függvényt vesz fel egy argumentummal, ezzel az példánnyal mint függvénynév |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/function/#str) | Függvényt vesz fel egy argumentummal, ezzel az példánnyal mint függvénynév |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Az adott függvényt veszi argumentumként ezzel a példánnyal |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Az adott függvényt veszi argumentumként ezzel a példánnyal |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Az adott függvényt veszi argumentumként ezzel a példánnyal |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Az adott függvényt veszi argumentumként ezzel a példánnyal, és egy megadott további argumentumot |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Az adott függvényt veszi argumentumként ezzel a példánnyal, és egy megadott további argumentumot |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Alulindexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_subscript/#str) | Alulindexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Felsőindexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_superscript/#str) | Felsőindexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Jobb oldalon alul- és felsőindexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Jobb oldalon alul- és felsőindexet hoz létre |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Bal oldalon alul- és felsőindexet hoz létre |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Bal oldalon alul- és felsőindexet hoz létre |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/radical/#imathelement) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/radical/#str) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Felső határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Felső határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz egy N-értékű operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Létrehoz egy N-értékű operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Integrált vesz határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Integrált vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/group/#) | Az elemet egy csoportba helyezi alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/accent/#char) | Akcentus jelet állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/to_box/#) | Az elemet egy nem vizuális dobozba helyezi (logikai csoportosítás) <br/>            amelyet egyenlet komponenseinek vagy más matematikai szöveg példányainak csoportosítására használnak.<br/>            Egy dobozos objektum (például) szolgálhat operátoremulátorként illesztési ponttal vagy anélkül, <br/>            szolgálhat sortörési pontként, vagy csoportosítható úgy, hogy ne engedjen sortörést. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/get_children/#) | Gyermekelemek lekérése |

### Lásd még
* osztály [`MathBox`](/slides/python-net/hu/aspose.slides.mathtext/mathbox)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)