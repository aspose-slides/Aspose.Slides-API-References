---
title: MathFunction class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathfunction/
---
## MathFunction třída

Specifikuje funkci argumentu.

**Dědičnost:**[`MathFunction`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathFunction poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | Inicializuje novou instanci třídy MathFunction. |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | Inicializuje novou instanci třídy MathFunction. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`name`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/name/) | Název funkce<br/>            Například názvy funkcí jsou sin a cos |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/base/) | Argument funkce |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/enclose/#) | Obalí matematický prvek do závorek |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/enclose/#char-char) | Obalí matematický prvek ve specifikovaných znacích, například v závorkách nebo jiných znacích jako rámeček |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/function/#imathelement) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/function/#str) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | Přijme specifikovanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | Přijme specifikovanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | Přijme specifikovanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme specifikovanou funkci s touto instancí jako argument a specifikovaný další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme specifikovanou funkci s touto instancí jako argument a specifikovaný další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index nalevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index nalevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/radical/#imathelement) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/radical/#str) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | Přijme horní limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | Přijme horní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | Přijme dolní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | Přijme dolní limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | Přijme integrál bez limitů |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, například dolní složené závorky nebo jiných |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/to_border_box/#) | Umístí tento prvek do rámečkového boxu |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do rámečkového boxu |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/accent/#char) | Nastaví diakritický znak (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/overbar/#) | Nastaví čáru nad tímto prvkem |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/underbar/#) | Nastaví čáru pod tímto prvkem |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/to_box/#) | Umístí tento prvek do neviditelného boxu (logické seskupení) <br/>            který se používá ke skupování komponent rovnice nebo jiného matematického textu.<br/>            Objekt v boxu může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* třída [`MathFunction`](/slides/python-net/cs/aspose.slides.mathtext/mathfunction)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)