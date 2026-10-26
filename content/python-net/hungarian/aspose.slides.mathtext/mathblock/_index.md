---
title: MathBlock class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathblock/
---
## MathBlock osztály

Meghatároz egy matematikai szövegelem példányát, amely egy MathParagraph-ban szerepel, és saját soron kezdődik.
            Az összes matematikai zóna, beleértve a képleteket, kifejezéseket, egyenletek vagy kifejezések tömbjeit, valamint a formulákat, a math block által van ábrázolva.

**Öröklődés:**[`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)

A MathBlock típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/__init__/#) | Inicializál egy új MathBlock osztály példányt. |
| [`__init__(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Létrehoz egy új matematikai blokkot, és a megadott elemet belehelyezi. |
| [`__init__(self, math_elements)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`count`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/count/) | Megkapja a gyerek matematikaelemek ténylegesen a gyűjteményben lévő számát.<br/>            Csak olvasható **int**. |
| [`is_read_only`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/is_read_only/) | Hamis értéket ad vissza, mert a gyerek elemek gyűjteménye módosítható. |

Lekérdezi vagy beállítja az IMathElement-et a megadott indexen.

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/__getitem__/) | Az elem 0-alapú indexe |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/join/#imathelement) | Összekapcsol egy matematikai elemet ezzel a MathBlock-kel. |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/join/#str) | Összekapcsol egy matematikai szöveget ezzel a MathBlock-kel. |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/divide/#imathelement) | Létrehoz egy törtet a számlálójával és a megadott nevezővel. |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/divide/#str) | Létrehoz egy törtet a számlálójával és a megadott nevezővel. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Létrehoz egy meghatározott típusú törtet a számlálójával és a megadott nevezővel. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Létrehoz egy meghatározott típusú törtet a számlálójával és a megadott nevezővel. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/enclose/#char-char) | A blokk gyerek elemeit megadott karakterekkel (pl. zárójelek vagy más karakterek) keretezi. |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | A blokk gyerek elemeit megadott karakterekkel (pl. zárójelek vagy más karakterek) keretezi<br/>            és egy elválasztó karakterrel határolja. |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/enclose/#) | Matematikai elemet zárójelek közé helyez. |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/function/#imathelement) | Egy argumentum függvényét veszi, ezt az objektumot használva függvényneveként. |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/function/#str) | Egy argumentum függvényét veszi, ezt az objektumot használva függvényneveként. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Megadott függvényt vesz, ezt az instance-t használva argumentumként. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Megadott függvényt vesz, ezt az instance-t használva argumentumként. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Megadott függvényt vesz, ezt az instance-t használva argumentumként. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Megadott függvényt vesz, ezt az instance-t használva argumentumként, valamint egy megadott további argumentumot. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Megadott függvényt vesz, ezt az instance-t használva argumentumként, valamint egy megadott további argumentumot. |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Létrehoz alsó indexet. |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_subscript/#str) | Létrehoz alsó indexet. |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Létrehoz felső indexet. |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_superscript/#str) | Létrehoz felső indexet. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Létrehoz alsó és felső indexet jobbra. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Létrehoz alsó és felső indexet jobbra. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Létrehoz alsó és felső indexet balra. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Létrehoz alsó és felső indexet balra. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/radical/#imathelement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/radical/#str) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Felső határt vesz. |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Felső határt vesz. |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Alsó határt vesz. |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Alsó határt vesz. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Létrehoz egy N-áris operátort. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Létrehoz egy N-áris operátort. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrált vesz. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Integrált vesz. |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Integrált vesz korlátok nélkül. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrált vesz. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Integrált vesz. |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/group/#) | Az elemet egy csoportba helyezi, alul görbe zárójelet használva. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Az elemet egy csoportba helyezi, egy csoportosító karaktert használva, például alul görbe zárójelet vagy más karaktert. |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/to_border_box/#) | Az elemet egy keretdobozba helyezi. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Az elemet egy keretdobozba helyezi. |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/to_math_array/#) | A gyerek elemeket függőleges sorba helyezi. |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/accent/#char) | Akcentus jelet állít be (egy karakter az elem tetején). |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/overbar/#) | Vonalat helyez az elem tetejére. |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/underbar/#) | Vonalat helyez az elem aljára. |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/to_box/#) | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi <br/>            amely egy egyenlet vagy más matematikai szöveg példány komponenseinek csoportosítására szolgál.<br/>            Egy dobozba helyezett objektum (például) szolgálhat operátor emulátorként egy illesztési ponttal vagy anélkül, <br/>            szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje a sortöréseket benne. |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/get_children/#) | Gyerek elemek lekérése. |
| [`add(self, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/add/#imathelement) | Matematikai elemet ad a gyűjtemény végéhez. |
| [`clear(self)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/clear/#) | Eltávolítja az összes elemet a gyűjteményből. |
| [`contains(self, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/contains/#imathelement) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy meghatározott értéket. |
| [`copy_to(self, array, array_index)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Másolás a megadott tömbbe. |
| [`remove(self, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/remove/#imathelement) | Eltávolítja a gyűjteményből egy adott objektum első előfordulását. |
| [`index_of(self, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Megállapítja egy adott matematikai elem indexét a gyűjteményben. |
| [`insert(self, index, item)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | MathElement-et szúr be a gyűjteménybe a megadott indexen. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/remove_at/#int) | Eltávolítja a gyűjteményben a megadott indexű elemet. |
| [`join_block(self, other)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Egy másik matematikai blokkot összekapcsol ezzel. |
| [`delimit(self, separator_character)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/delimit/#char) | Gyerek elemeket elválasztó karakterrel határol (zárójelek nélkül). |
| [`write_as_math_ml(self, stream)`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Elmenti ennek a [`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock) tartalmát MathML-ként. |

### Lásd még
* osztály [`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock)
* osztály [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)