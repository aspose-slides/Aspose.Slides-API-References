---
title: IMathElement class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/imathelement/
---
## IMathElement třída

Základní rozhraní libovolného matematického prvku: 
            fraction, mathmatical text, function, expression with multiple elements etc

Typ IMathElement poskytuje následující členy:

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/enclose/#) | Obalí matematický prvek závorkami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/enclose/#char-char) | Obalí tento prvek určenými znaky, jako jsou závorky nebo jiné znaky jako rámeček |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/function/#imathelement) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/function/#str) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/as_argument_of_function/#imathelement) | Přijme určenou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/as_argument_of_function/#str) | Přijme určenou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsofoneargument) | Přijme určenou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme určenou funkci s touto instancí jako argument a určený další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme určenou funkci s touto instancí jako argument a určený další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/radical/#imathelement) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/radical/#str) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_upper_limit/#imathelement) | Přijme horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_upper_limit/#str) | Přijme horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_lower_limit/#imathelement) | Přijme dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/set_lower_limit/#str) | Přijme dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes) | Přijme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/group/#) | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znakové skupiny, jako je spodní složená závorka nebo jiný |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/to_border_box/#) | Umístí tento prvek do rámečkového pole |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do rámečkového pole |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/get_children/#) | Získá podřízené prvky |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/to_math_array/#) | Umístí do vertikálního pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/accent/#char) | Nastaví přízvukový znak (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/overbar/#) | Nastaví čáru nad tímto prvkem |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/underbar/#) | Nastaví čáru pod tímto prvkem |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathelement/to_box/#) | Umístí tento prvek do neviditelného boxu (logické seskupení) <br/>            který se používá k seskupení komponent rovnice nebo jiného matematického textu.<br/>            Zasazený objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |

### Viz také
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)