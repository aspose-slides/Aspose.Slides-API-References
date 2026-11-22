---
title: MathBlock class
second_title: Aspose.Slides a Python számára .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathblock/
---
## MathBlock osztály

Megad egy matematikai szövegpéldányt, amely egy MathParagraph-ban szerepel, és saját sorban kezdődik.  
Minden matematikai zóna, beleértve egyenleteket, kifejezéseket, egyenletek vagy kifejezések tömbjeit és képleteket, a math block-kal van ábrázolva.

**Öröklés:**[`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathBlock típus a következő tagokkal rendelkezik:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/__init__/#) | Új példányt inicializál a MathBlock osztályból. |
| [`__init__(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Új matematikai blokkot hoz létre, és a megadott elemet belehelyezi. |
| [`__init__(self, math_elements)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`count`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/count/) | A ténylegesen a gyűjteményben lévő gyermek matematikai elemek számát adja vissza.<br/>            Csak olvasható **int**. |
| [`is_read_only`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/is_read_only/) | Hamisan tér vissza, mert a gyermek elemek gyűjteménye módosítható. |

Lekéri vagy beállítja az IMathElement-et a megadott indexnél.

## Indexer

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/__getitem__/) | A tétel nulla-alapú indexe |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/join/#imathelement) | Összekapcsol egy matematikai elemet ezzel a matematikai blokkal |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/join/#str) | Összekapcsol egy matematikai szöveget ezzel a matematikai blokkal |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/divide/#imathelement) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/divide/#str) | Létrehoz egy törtet a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Létrehoz a megadott típusú törtet a számlálóval és a megadott nevezővel |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Létrehoz a megadott típusú törtet a számlálóval és a megadott nevezővel |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/enclose/#) | Zárójelbe tesz egy matematikai elemet |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/enclose/#char-char) | A blokk gyermek elemeit a megadott karakterekkel, például zárójelekkel vagy egyéb karakterekkel keretezi |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | A blokk gyermek elemeit a megadott karakterekkel, például zárójelekkel vagy egyébként keretezi<br/>            és elválasztó karakterrel választja el |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/function/#imathelement) | Egy függvényt vesz argumként, és ezt a példányt használja a függvény nevének |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/function/#str) | Egy függvényt vesz argumként, és ezt a példányt használja a függvény nevének |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Megadott függvényt hív meg, ezt a példányt használva argumentumként |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Megadott függvényt hív meg, ezt a példányt használva argumentumként |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt hív meg, ezt a példányt használva argumentumként |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt hív meg, ezt a példányt használva argumentumként, illetve egy további argumentummal |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt hív meg, ezt a példányt használva argumentumként, illetve egy további argumentummal |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Létrehoz alsó indexet |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_subscript/#str) | Létrehoz alsó indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Létrehoz felső indexet |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_superscript/#str) | Létrehoz felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Létrehoz jobb oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Létrehoz jobb oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Létrehoz bal oldali alsó és felső indexet |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Létrehoz bal oldali alsó és felső indexet |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/radical/#imathelement) | A megadott argumentumból a megadott fokú matematikai gyököt adja meg. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/radical/#str) | A megadott argumentumból a megadott fokú matematikai gyököt adja meg. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Felül határt vesz |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Felül határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Alul határt vesz |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Alul határt vesz |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz N-értékű operátort |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Létrehoz N-értékű operátort |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Integrált vesz korlátok nélkül |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Integrált vesz |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/group/#) | Az elemet egy csoportba helyezi, alsó kapcsos zárójelet használva |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi, egy csoportosító karakterrel, például alsó kapcsos zárójelezve vagy egyébként |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/to_border_box/#) | Az elemet egy keret-dobozba helyezi |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keret-dobozba helyezi |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/to_math_array/#) | A gyermek elemeket függőleges tömbbe helyezi |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/accent/#char) | Akcentusjelet állít be (egy karaktert az elem tetejére) |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/overbar/#) | Vonalat helyez az elem tetejére |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/underbar/#) | Vonalat helyez az elem aljára |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/to_box/#) | Az elemet egy nem-vizuális dobozba (logikai csoportosításba) helyezi <br/>            amely egyenlet vagy más matematikai szöveg-példány komponenseit csoportosítja.<br/>            Egy keretezett objektum például operátor-emulátorként szolgálhat igazítási ponttal vagy anélkül, <br/>            sor-törés pontként használható, vagy úgy csoportosítható, hogy a sor-töréseket megakadályozza. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/get_children/#) | Gyermek elemek lekérése |
| [`add(self, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/add/#imathelement) | Egy matematikai elemet ad a gyűjtemény végéhez. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/clear/#) | Az összes elemet eltávolítja a gyűjteményből. |
| [`contains(self, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/contains/#imathelement) | Meghatározza, hogy a gyűjtemény tartalmaz-e egy meghatározott értéket. |
| [`copy_to(self, array, array_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Másol egy megadott tömbbe. |
| [`remove(self, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/remove/#imathelement) | Eltávolítja egy adott objektum első előfordulását a gyűjteményből. |
| [`index_of(self, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Meghatározza egy adott matematikai elem indexét a gyűjteményben. |
| [`insert(self, index, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Egy MathElement-et szúr be a gyűjteménybe a megadott indexnél. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/remove_at/#int) | Eltávolítja az elemet a megadott indexnél a gyűjteményből. |
| [`join_block(self, other)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Egy másik matematikai blokkot fűz össze ezzel a blokkal |
| [`delimit(self, separator_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/delimit/#char) | A gyermek elemeket elválasztó karakterrel (a zárójelek nélkül) választja el |
| [`write_as_math_ml(self, stream)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Elmenti ennek a [`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock) tartalmát MathML-ként |

### Lásd még
* osztály [`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)