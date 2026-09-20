---
title: MathGroupingCharacter class
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručky API
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter třída

Určuje seskupovací symbol nad nebo pod výrazem, obvykle za účelem zvýraznění vztahu mezi prvky

**Dědičnost:**[`MathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathGroupingCharacter vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Inicializuje novou instanci třídy MathGroupingCharacter <br/>            s výchozím seskupovacím znakem U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Inicializuje novou instanci třídy MathGroupingCharacter. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/base/) | Základní argument |
| [`character`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/character/) | Seskupovací znak<br/>            Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/position/) | Pozice seskupovacího znaku.<br/>            Výchozí: Bottom |
| [`vertical_justification`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Vertikální zarovnání znaků skupiny.<br/>            Určuje zarovnání objektu vzhledem k základní lince.<br/>            Například když je znak skupiny nad objektem, <br/>            VerticalJustification s hodnotou Top znamená, že horní část objektu leží na základní lince;<br/>            když je VerticalJustification nastaveno na Bottom, spodní část objektu leží na základní lince<br/>            Default: Bottom for Position=Top, and Top for Position=Bottom |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Obalí matematický prvek do závorek |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Obalí matematický prvek ve specifikovaných znacích, jako jsou závorky nebo jiné znaky jako rámec |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Přijme funkci argumentu s použitím této instance jako názvu funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Přijme funkci argumentu s použitím této instance jako názvu funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Přijme specifikovanou funkci s použitím této instance jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Přijme specifikovanou funkci s použitím této instance jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Přijme specifikovanou funkci s použitím této instance jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme specifikovanou funkci s použitím této instance jako argumentu a specifikovaného dalšího argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme specifikovanou funkci s použitím této instance jako argumentu a specifikovaného dalšího argumentu |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Určuje matematický kořen daného stupně ze specifikovaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Určuje matematický kořen daného stupně ze specifikovaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Přijme horní limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Přijme horní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Přijme dolní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Přijme dolní limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Přijme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí seskupovacího znaku, jako je spodní složená závorka nebo jiný |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Umístí tento prvek do border-boxu |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do border-boxu |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Umístí do vertikálního pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Nastaví akcent (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Nastaví čáru nad tímto prvkem |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Nastaví čáru pod tímto prvkem |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Umístí tento prvek do neviditelného boxu (logické seskupení) <br/>            který se používá ke skupinování komponent rovnice nebo jiné instance matematického textu.<br/>            Ohrančený objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval vnitřní zalomení řádků. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* třída [`MathGroupingCharacter`](/slides/python-net/cs/aspose.slides.mathtext/mathgroupingcharacter)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)