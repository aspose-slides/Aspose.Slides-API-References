---
title: MathSubscriptElement class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement třída

Specifies the subscript object, which consists of a base 
            and a reduced-size subscript placed below and to the right.

**Inheritance:**[`MathSubscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement) → [`BaseScript`](/slides/python-net/cs/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathSubscriptElement vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, base_arg, sub_script)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/__init__/#imathelement-imathelement) | Inicializuje novou instanci třídy MathSubscriptElement. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/base/) | Základní argument |
| [`subscript`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/subscript/) | Dolní index |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/enclose/#) | Obalí matematický prvek v závorkách |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/enclose/#char-char) | Obalí matematický prvek do určených znaků, například závorek nebo jiných znaků jako rámeček |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/function/#imathelement) | Přijme funkci argumentu s tímto exemplářem jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/function/#str) | Přijme funkci argumentu s tímto exemplářem jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#imathelement) | Přijme zadanou funkci s tímto exemplářem jako argumentem |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#str) | Přijme zadanou funkci s tímto exemplářem jako argumentem |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Přijme zadanou funkci s tímto exemplářem jako argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme zadanou funkci s tímto exemplářem jako argument a další zadaný argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme zadanou funkci s tímto exemplářem jako argument a další zadaný argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index naprava |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index naprava |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index nalevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index nalevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/radical/#imathelement) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/radical/#str) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#imathelement) | Přijme horní limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#str) | Přijme horní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#imathelement) | Přijme dolní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#str) | Přijme dolní limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes) | Přijme integrál bez limitů |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, jako je dolní složená závorka nebo jiný znak |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#) | Umístí tento prvek do okrajového rámečku |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do okrajového rámečku |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/accent/#char) | Nastaví diakritický znak (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/overbar/#) | Nastaví pruh na vrcholu tohoto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/underbar/#) | Nastaví pruh na spodku tohoto prvku |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/to_box/#) | Umístí tento prvek do neviditelného rámečku (logického seskupení) <br/>            který se používá k seskupení komponent rovnice nebo jiného matematického textu.<br/>            Objekt v rámečku může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`BaseScript`](/slides/python-net/cs/aspose.slides.mathtext/basescript)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* třída [`MathSubscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathsubscriptelement)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)