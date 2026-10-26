---
title: MathBlock class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathblock/
---
## MathBlock třída

Určuje instanci matematického textu, která je obsažena v MathParagraph a začíná na vlastním řádku.
            Všechny matematické zóny, včetně rovnic, výrazů, polí rovnic nebo výrazů a vzorců, jsou reprezentovány matematickým blokem.

**Inheritance:**[`MathBlock`](/slides/python-net/cs/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

The MathBlock type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/__init__/#) | Inicializuje novou instanci třídy MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Vytvoří nový matematický blok a vloží do něj zadaný prvek |
| [`__init__(self, math_elements)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Properties

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/count/) | Získá počet podřízených matematických elementů skutečně obsažených ve sbírce.<br/>            Pouze ke čtení **int**. |
| [`is_read_only`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/is_read_only/) | Vrací false, protože kolekci podřízených elementů lze upravovat. |

Získá nebo nastaví IMathElement na zadaném indexu.

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/__getitem__/) | Nulový index položky |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/join/#imathelement) | Spojí matematický prvek s tímto matematickým blokem |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/join/#str) | Spojí matematický prvek s tímto matematickým blokem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/divide/#imathelement) | Vytvoří zlomky s tímto čitatel a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/divide/#str) | Vytvoří zlomky s tímto čitatel a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Vytvoří zlomky zadaného typu s tímto čitatel a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Vytvoří zlomky zadaného typu s tímto čitatel a zadaným jmenovatelem |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/enclose/#char-char) | Obalí podřízené elementy tohoto bloku v zadaných znacích, jako jsou závorky nebo jiné znaky jako rámeček |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Obalí podřízené elementy tohoto bloku v zadaných znacích, jako jsou závorky nebo jiné jako rámeček<br/>            a oddělí je znakem oddělovače |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/enclose/#) | Obalí matematický prvek do závorek |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/function/#imathelement) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/function/#str) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Přijme zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Přijme zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Přijme zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme zadanou funkci s touto instancí jako argument a zadaný další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme zadanou funkci s touto instancí jako argument a zadaný další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/radical/#imathelement) | Určuje matematický kořen zadaného stupně ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/radical/#str) | Určuje matematický kořen zadaného stupně ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Přijme horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Přijme horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Přijme dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Přijme dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Přijme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků seskupení, jako je dolní složená závorka nebo jiný |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/to_border_box/#) | Umístí tento prvek do ohraničené krabice |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do ohraničené krabice |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/to_math_array/#) | Umístí podřízené elementy do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/accent/#char) | Nastaví akcent (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/overbar/#) | Nastaví pruh nad tímto prvkem |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/underbar/#) | Nastaví pruh pod tímto prvkem |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/to_box/#) | Umístí tento prvek do neviditelné krabice (logické seskupení) <br/>            která slouží k seskupení komponent rovnice nebo jiné instance matematického textu.<br/>            Boxovaný objekt může (například) fungovat jako emulátor operátoru s nebo bez bodu zarovnání, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/get_children/#) | Získá podřízené elementy |
| [`add(self, item)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/add/#imathelement) | Přidá matematický prvek na konec kolekce. |
| [`clear(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/clear/#) | Odstraní všechny prvky z kolekce. |
| [`contains(self, item)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/contains/#imathelement) | Určuje, zda kolekce obsahuje konkrétní hodnotu. |
| [`copy_to(self, array, array_index)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Zkopíruje do zadaného pole. |
| [`remove(self, item)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/remove/#imathelement) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [`index_of(self, item)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Určuje index konkrétního matematického prvku v kolekci. |
| [`insert(self, index, item)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Vloží MathElement do kolekce na zadaném indexu. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/remove_at/#int) | Odstraní prvek na zadaném indexu v kolekci. |
| [`join_block(self, other)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Spojí další matematický blok s tímto |
| [`delimit(self, separator_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/delimit/#char) | Oddělí podřízené elementy znakem oddělovače (bez závorek) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/cs/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Uloží obsah tohoto [`MathBlock`](/slides/python-net/cs/aspose.slides.mathtext/mathblock) jako MathML |


### Viz také
* třída [`MathBlock`](/slides/python-net/cs/aspose.slides.mathtext/mathblock)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)