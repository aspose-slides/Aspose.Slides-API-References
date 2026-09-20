---
title: MathLimit class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathlimit/
---
## MathLimit třída

Specifikuje objekt Limit, který se skládá z textu na základní linii a zmenšeného textu těsně nad nebo pod ní.

**Dědičnost:**[`MathLimit`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathLimit poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | Inicializuje novou instanci třídy MathLimit. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Inicializuje novou instanci třídy MathLimit s dolním limitem |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/base/) | Základní argument |
| [`limit`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/limit/) | Argument limitu |
| [`upper_limit`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/upper_limit/) | Určuje horní nebo dolní limit |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/enclose/#) | Obalí matematický prvek do závorky |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/enclose/#char-char) | Obalí matematický prvek zadanými znaky, jako jsou závorky nebo jiné znaky pro orámování |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/function/#imathelement) | Vytvoří funkci s argumentem, přičemž tato instance slouží jako název funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/function/#str) | Vytvoří funkci s argumentem, přičemž tato instance slouží jako název funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Použije zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Použije zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Použije zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Použije zadanou funkci s touto instancí jako argument a s dalším určeným argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Použije zadanou funkci s touto instancí jako argument a s dalším určeným argumentem |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index na pravé straně |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index na pravé straně |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index na levé straně |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index na levé straně |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/radical/#str) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Přijímá horní limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Přijímá horní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Přijímá dolní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Přijímá dolní limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Vytvoří integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | Vytvoří integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Vytvoří integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | Vytvoří integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | Vytvoří integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaku pro seskupení, jako je dolní složená závorka nebo jiný |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/to_border_box/#) | Umístí tento prvek do rámečkové krabice |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do rámečkové krabice |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/accent/#char) | Nastaví akcent (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/overbar/#) | Nastaví čáru nahoře na tomto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/underbar/#) | Nastaví čáru pod tímto prvkem |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/to_box/#) | Umístí tento prvek do neviditelné krabice (logické seskupení) <br/>            která se používá ke skupování komponent rovnice nebo jiného matematického textu.<br/>            Krabicový objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, <br/>            sloužit jako bod zalomení řádku nebo být seskupen tak, aby nedovoloval zalomení řádků uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* třída [`MathLimit`](/slides/python-net/cs/aspose.slides.mathtext/mathlimit)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)