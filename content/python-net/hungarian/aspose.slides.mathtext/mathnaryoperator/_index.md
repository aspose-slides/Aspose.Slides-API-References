---
title: MathNaryOperator class
second_title: Aspose.Slides a Python számára .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator osztály

Egy N-áris matematikai objektumot határoz meg, például Összegzést és Integrált.  
Egy operátorból, egy bázisból (vagy operandusból) és opcionális felső és alsó határból áll.  
Az N-áris operátorok példái: Összegzés, Unió, Metszet, Integrál

**Inheritance:**[`MathNaryOperator`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathNaryOperator típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Új példányt hoz létre a MathNaryOperator osztályból. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Új példányt hoz létre a MathNaryOperator osztályból. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Új példányt hoz létre a MathNaryOperator osztályból. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/base/) | Alap argumentum |
| [`subscript`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/subscript/) | Megadja a alsó index argumentumot, amely például integrál esetén az alsó határt állítja be |
| [`superscript`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/superscript/) | Megadja a felső index argumentumot, amely például integrál esetén a felső határt állítja be |
| [`operator`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/operator/) | N-áris operátor karakter<br/>            For example: '∑', '∫' |
| [`limit_location`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Határok helye (alsó index és felső index) |
| [`grow_to_match_operand_height`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Az operátor karakter függőlegesen nő, hogy illeszkedjen az operandus magasságához |
| [`hide_subscript`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Alsó index elrejtése |
| [`hide_superscript`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Felső index elrejtése |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Összekapcsol egy matematikai elemet, és matematikai blokkot hoz létre |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/join/#str) | Összekapcsol egy matematikai szöveget, és matematikai blokkot hoz létre |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Létrehozza a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Egy matematikai elemet zárójelbe helyez |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretezi |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Egy argumentumú függvényt vesz, amelynek a függvényneve ez az példány |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/function/#str) | Egy argumentumú függvényt vesz, amelynek a függvényneve ez az példány |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Egy megadott függvényt vesz, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Egy megadott függvényt vesz, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Egy megadott függvényt vesz, amelynek argumentuma ez a példány |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Egy megadott függvényt vesz, amelynek argumentuma ez a példány, és egy megadott további argumentum |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Egy megadott függvényt vesz, amelynek argumentuma ez a példány, és egy megadott további argumentum |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Alsó indexet hoz létre |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Alsó indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Felső indexet hoz létre |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Felső indexet hoz létre |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | A jobb oldalon létrehozza az alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | A jobb oldalon létrehozza az alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Bal oldalon létrehozza az alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Bal oldalon létrehozza az alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Megadja a megadott argumentumból a megadott fokú matematikai gyököt. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Megadja a megadott argumentumból a megadott fokú matematikai gyököt. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Felső határt vesz fel |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Felső határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Alsó határt vesz fel |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Alsó határt vesz fel |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz egy N-áris operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Létrehoz egy N-áris operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Az integrált veszi |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Az integrált veszi |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Integrált vesz határok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Az integrált veszi |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Az integrált veszi |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/group/#) | Az elemet egy csoportba helyezi egy alsó kapcsos zárójelet használva |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például egy alsó kapcsos zárójelet vagy más karaktert |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Az elemet egy keretdobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Ékezetjelet állít be (karakter az elem tetején) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi <br/>            amelyet egyenlet komponenseinek vagy egyéb matematikai szöveg példányainak csoportosítására használnak.<br/>            Egy keretezett objektum (például) szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sortöréseket benne. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Gyermekelemek lekérése |

### Lásd még
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* osztály [`MathNaryOperator`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)