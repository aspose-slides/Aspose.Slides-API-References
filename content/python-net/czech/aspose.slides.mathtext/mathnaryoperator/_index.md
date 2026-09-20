---
title: MathNaryOperator class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator třída

Specifikuje N-ární matematický objekt, například součet a integrál.  
Skládá se z operátoru, základu (nebo operandu) a volitelných horních a dolních mezí.  
Příklady N-árních operátorů jsou: součet, sjednocení, průnik, integrál

**Dědičnost:**[`MathNaryOperator`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathNaryOperator expose následující členy:

## Konstruktoři

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Inicializuje novou instanci třídy MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Inicializuje novou instanci třídy MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Inicializuje novou instanci třídy MathNaryOperator. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/base/) | Základní argument |
| [`subscript`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/subscript/) | Specifikuje argument dolního indexu, který například v případě integrálu nastaví dolní mez |
| [`superscript`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/superscript/) | Specifikuje argument horního indexu, který například v případě integrálu nastaví horní mez |
| [`operator`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/operator/) | Znak Nary operátoru<br/>            Například: '∑', '∫' |
| [`limit_location`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Umístění limit (dolní a horní index) |
| [`grow_to_match_operand_height`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Znak operátoru roste vertikálně, aby odpovídal výšce operandu |
| [`hide_subscript`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Skrýt dolní index |
| [`hide_superscript`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Skrýt horní index |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a určeným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Obalí matematický prvek závorkami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Obalí matematický prvek určenými znaky, jako jsou závorky nebo jiné znaky jako rámeček |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Použije tuto instanci jako název funkce argumentu |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/function/#str) | Použije tuto instanci jako název funkce argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Použije určenou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Použije určenou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Použije určenou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Použije určenou funkci s touto instancí jako argumentem a s dalším určeným argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Použije určenou funkci s touto instancí jako argumentem a s dalším určeným argumentem |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Přijme horní limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Přijme horní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Přijme dolní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Přijme dolní limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Přijme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, například dolní složené závorky nebo jiné |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Umístí tento prvek do ohraničeného rámečku |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do ohraničeného rámečku |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Umístí do svislé řady |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Nastaví akcentuovaný znak (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Nastaví pruh na horní části tohoto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Nastaví pruh na spodní části tohoto prvku |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Umístí tento prvek do neviditelného rámečku (logické seskupení) <br/>            který se používá k seskupení komponent rovnice nebo jiné instance matematického textu.<br/>            Objekt v rámečku může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Získá podřízené elementy |

### Viz také
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* třída [`MathNaryOperator`](/slides/python-net/cs/aspose.slides.mathtext/mathnaryoperator)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)