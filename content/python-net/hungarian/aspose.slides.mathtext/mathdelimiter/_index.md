---
title: MathDelimiter class
second_title: Aspose.Slides a Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter osztály

Meghatározza a delimitor objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakterrel választanak el. Példák: (𝑥2); [𝑥2|𝑦2]

**Öröklés:**[`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathDelimiter típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Inicializálja a MathDelimiter objektumot a megadott elemmel, mint egyetlen alapargumentummal |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`arguments`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/arguments/) | Egy vagy több matematikai elem, amelyet delimiter karakterek választanak el |
| [`beginning_character`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/beginning_character/) | A Delimiter Beginning Character megadja a kezdeti, vagy nyitó, delimiter karaktert. <br/>            A matematikai delimiter-ek olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek.<br/>            Alapértelmezett: '(' |
| [`separator_character`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/separator_character/) | A Delimiter Separator Character megadja azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. <br/>            Alapértelmezett: '\|' |
| [`ending_character`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/ending_character/) | A Delimiter Ending Character megadja a befejező, vagy záró, delimiter karaktert. <br/>            A matematikai delimiter-ek olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek.<br/>            Alapértelmezett: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Megadja a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését<br/>            Ha igaz, a delimiter-ek függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához.<br/>            Alapértelmezett érték: true |
| [`delimiter_shape`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Megadja a delimiter-ek alakját a delimiter objektumban. <br/>            Ha a MathDelimiterShape.Centered, a delimiter-ek a matematikai szöveg matematikai tengelye köré középre helyeződnek <br/>            és úgy igazodnak, hogy a teljes magasságuk beleférjen a tartalmukba.<br/>            Ha a MathDelimiterShape.Match, a magasságuk és alakjuk pontosan a tartalomhoz igazodik. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Összekapcsol egy matematikai elemet és egy matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/join/#str) | Összekapcsol egy matematikai szöveget és egy matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/divide/#str) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Létrehoz egy adott típusú törtet a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Létrehoz egy adott típusú törtet a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/enclose/#) | Zárójelek közé helyezi a matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Megadott karakterek (például zárójelek vagy más keretező karakterek) közé helyezi a matematikai elemet |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Függvényt vesz fel egy argumentummal, ahol ez az instance a függvény neve |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/function/#str) | Függvényt vesz fel egy argumentummal, ahol ez az instance a függvény neve |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Megadott függvényt vesz fel, ahol ez az instance az argumentum |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Megadott függvényt vesz fel, ahol ez az instance az argumentum |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz fel, ahol ez az instance az argumentum |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz fel, ahol ez az instance az argumentum, és megadott további argumentumot |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz fel, ahol ez az instance az argumentum, és megadott további argumentumot |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Alsó indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Alsó indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Az elem jobb oldalán hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Az elem jobb oldalán hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Az elem bal oldalán hoz létre alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Az elem bal oldalán hoz létre alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Megadja a matematikai gyököt a megadott fokban a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/radical/#str) | Megadja a matematikai gyököt a megadott fokban a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Felülhatárt vesz fel |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Felülhatárt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Alsó határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Alsó határt vesz fel |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-áris operátort hoz létre |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | N-áris operátort hoz létre |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz fel |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Integrált vesz fel határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz fel |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Integrált vesz fel |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/group/#) | Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójel vagy más |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/accent/#char) | Akcentusjelzést állít be (egy karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/to_box/#) | A elem-et egy nem vizuális dobozba (logikai csoportosításba) helyezi <br/>            amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak.<br/>            Egy dobozos objektum (például) szolgálhat operátor emulátorként illesztési ponttal vagy anélkül, <br/>            sorvége pontként, vagy úgy csoportosítható, hogy ne engedjen szövegtöréseket belül. |
| [`delimit(self, separator_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/delimit/#char) | A megadott delimiter karakterrel határolja az argumentumokat |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/get_children/#) | Gyerek elemeket lekér |

### Lásd még
* osztály [`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)