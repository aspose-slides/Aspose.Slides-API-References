---
title: MathBorderBox class
second_title: Aspose.Slides pro Python přes .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox třída

Vykresluje obdélníkový nebo jiný rámeček kolem IMathElement.

**Dědičnost:**[`MathBorderBox`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathBorderBox obsahuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Vytvoří prvek MathBorderBox s obdélníkovým rámečkem |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Vytvoří prvek MathBorderBox |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/base/) | Základní argument |
| [`hide_top`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/hide_top/) | Skrýt horní okraj (výchozí je false) - určuje skrytý nebo zobrazený stav horního okraje rámečku. |
| [`hide_bottom`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Skrýt spodní okraj (výchozí je false) - určuje skrytý nebo zobrazený stav spodního okraje rámečku. |
| [`hide_left`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/hide_left/) | Skrýt levý okraj (výchozí je false) - určuje skrytý nebo zobrazený stav levého okraje rámečku. |
| [`hide_right`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/hide_right/) | Skrýt pravý okraj (výchozí je false) - určuje skrytý nebo zobrazený stav pravého okraje rámečku. |
| [`strikethrough_horizontal`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Přeškrtnutí horizontální (výchozí je false) - určuje skrytý nebo zobrazený stav horizontální přeškrtnuté linie. |
| [`strikethrough_vertical`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Přeškrtnutí vertikální (výchozí je false) - určuje skrytý nebo zobrazený stav vertikální přeškrtnuté linie. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Přeškrtnutí spodní levé k pravému hornímu (výchozí je false).<br/>            Určuje skrytý nebo zobrazený stav přeškrtnuté úhlopříčky od spodního levého rohu k pravému hornímu rohu rámečku. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Přeškrtnutí horního levého k pravému dolnímu (výchozí je false).<br/>            Určuje skrytý nebo zobrazený stav přeškrtnuté úhlopříčky od horního levého rohu k pravému dolnímu rohu rámečku. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/enclose/#) | Obalí matematický prvek do závorek |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Obalí matematický prvek zadanými znaky, jako jsou závorky nebo jiné znaky jako rámeček |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Vytvoří funkci argumentu s touto instancí jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/function/#str) | Vytvoří funkci argumentu s touto instancí jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Použije zadanou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Použije zadanou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Použije zadanou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Použije zadanou funkci s touto instancí jako argumentem a zadaným dalším argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Použije zadanou funkci s touto instancí jako argumentem a zadaným dalším argumentem |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index nalevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index nalevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/radical/#str) | Určuje matematický kořen daného stupně ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Přijme horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Přijme horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Přijme dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Přijme dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Vytvoří integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Vytvoří integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Vytvoří integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Vytvoří integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Vytvoří integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/group/#) | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků seskupení, jako je spodní složená závorka nebo jiný znak |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Umístí tento prvek do rámečkového boxu |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do rámečkového boxu |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/accent/#char) | Nastaví akcent (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/overbar/#) | Nastaví čáru nad tímto prvkem |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/underbar/#) | Nastaví čáru pod tímto prvkem |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/to_box/#) | Umístí tento prvek do neviditelného boxu (logické seskupení) <br/>            který se používá k seskupení komponent rovnice nebo jiného matematického textu.<br/>            Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`MathBorderBox`](/slides/python-net/cs/aspose.slides.mathtext/mathborderbox)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)