---
title: MathDelimiter class
second_title: Aspose.Slides for Python .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter osztály

Meghatározza a delimiter objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz belül, amelyeket egy meghatározott karakter választ el.  
Példák: (𝑥2); [𝑥2|𝑦2]

**Inheritance:**[`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathDelimiter típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Inicializálja a MathDelimiter-t a megadott elemként egyetlen alap argumentummal |

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/arguments/) | Egy vagy több matematikai elem, amelyet elválasztó karakterek választanak el |
| [`beginning_character`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character megadja a kezdő, vagy nyitó, delimiter karaktert. <br/>            A matematikai delimiterok olyan körülvevő karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek.<br/>            Az alapértelmezett: '('. |
| [`separator_character`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character megadja azt a karaktert, amely elválasztja az argumentumokat a delimiter objektumban. <br/>            Az alapértelmezett: '\|'. |
| [`ending_character`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character megadja a záró, vagy befejező, delimiter karaktert. <br/>            A matematikai delimiterok olyan körülvevő karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek.<br/>            Az alapértelmezett: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Ha true, a delimiterok függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához.<br/>            Az alapértelmezett érték true |
| [`delimiter_shape`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Specifies the shape of delimiters in the delimiter object. <br/>            Ha MathDelimiterShape.Centered, a delimiterok a matematikai szöveg tengelye köré középre vannak helyezve <br/>            és még mindig úgy vannak méretezve, hogy illeszkedjenek a tartalmaik teljes magasságához.<br/>            Ha MathDelimiterShape.Match, a magasságuk és alakjuk pontosan a tartalmukhoz igazodik. |

## Metódusok

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/join/#str) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/divide/#str) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Egy matematikai elemet a megadott karakterek közé zár be, például zárójelek vagy más karakterek keretezésként |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/enclose/#) | Egy matematikai elemet zárójelek közé helyez |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Egy argumentum függvényét veszi, az aktuális példányt használva függvénynévként |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/function/#str) | Egy argumentum függvényét veszi, az aktuális példányt használva függvénynévként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Megadott függvényt vesz, az aktuális példányt használva argumentumként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Megadott függvényt vesz, az aktuális példányt használva argumentumként |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz, az aktuális példányt használva argumentumként |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz, az aktuális példányt használva argumentumként és egy további argumentummal |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz, az aktuális példányt használva argumentumként és egy további argumentummal |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Alsó indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Alsó indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Balra helyez alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Balra helyez alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Jobbra helyez alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Jobbra helyez alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/radical/#str) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Felső határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Felső határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Alsó határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Alsó határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz egy N-árnyalékú operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Létrehoz egy N-árnyalékú operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Integrált vesz határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Integrált vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/group/#) | Az elemet egy csoportba helyezi egy alsó kapcsos zárójelezéssel |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójelezéssel vagy másvalamivel |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/accent/#char) | Akcentusjelet állít be (egy karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/overbar/#) | Egy sávot helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/underbar/#) | Egy sávot helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/to_box/#) | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi <br/>            amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak.<br/>            Egy keretezett objektum például operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, <br/>            vonalhatás pontként funkcionálhat, vagy úgy csoportosítható, hogy ne engedje a sortöréseket benne. |
| [`delimit(self, separator_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/delimit/#char) | A megadott delimiter karakterrel választja el az argumentumokat |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/get_children/#) | Gyermekelemeket kér le |

### Lásd még
* osztály [`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)