---
title: MathPhantom class
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručky API
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathphantom/
---
## MathPhantom třída

Represents a phantom math object (<m:phant>) that affects the layout of its child element
            without necessarily displaying it. A phantom can hide its base expression while preserving
            its width, height, or depth to align formulas or reserve space. 
            Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, 
            ZeroDesc, and Transp.

**Inheritance:**[`MathPhantom`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

The MathPhantom type exposes the following members:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Inicializuje novou instanci třídy [`MathPhantom`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom) <br/>            pomocí zadaného základního matematického prvku. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/base/) | Základní argument |
| [`show`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/show/) | Získá nebo nastaví hodnotu určující, zda je základní prvek zobrazen. |
| [`zero_width`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/zero_width/) | Získá nebo nastaví hodnotu určující, zda má být šířka základního prvku <br/>            považována za nulu. |
| [`zero_asc`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/zero_asc/) | Získá nebo nastaví hodnotu určující, zda má být výška nad osnovou (ascent) <br/>            základního prvku považována za nulu. |
| [`zero_desc`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/zero_desc/) | Získá nebo nastaví hodnotu určující, zda má být klesání (hloubka pod osnovou)<br/>            základního prvku považováno za nulu. |
| [`transp`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/transp/) | Získá nebo nastaví hodnotu určující, zda je fázový objekt transparentní <br/>            pro pravidla odsazení založená na třídě. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/divide/#str) | Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek daného typu s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Vytvoří zlomek daného typu s tímto čitatelem a určeným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/enclose/#) | Uzavře matematický prvek do závorek |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Uzavře matematický prvek ve specifikovaných znacích, jako jsou závorky nebo jiné znaky jako rámování |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/function/#imathelement) | Přijme funkci argumentu s tímto exemplářem jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/function/#str) | Přijme funkci argumentu s tímto exemplářem jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Přijme specifikovanou funkci s tímto exemplářem jako argumentem |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Přijme specifikovanou funkci s tímto exemplářem jako argumentem |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Přijme specifikovanou funkci s tímto exemplářem jako argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme specifikovanou funkci s tímto exemplářem jako argumentem a specifikovaným dalším argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme specifikovanou funkci s tímto exemplářem jako argumentem a specifikovaným dalším argumentem |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index nalevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index nalevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Určuje matematický kořen zadaného řádu z určeného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/radical/#str) | Určuje matematický kořen zadaného řádu z určeného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Přijme horní limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Přijme horní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Přijme dolní limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Přijme dolní limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Přijme integrál bez limit |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/group/#) | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, jako je spodní složená závorka nebo jiný znak |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/to_border_box/#) | Umístí tento prvek do rámečkového boxu |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do rámečkového boxu |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/accent/#char) | Nastaví příznak (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/overbar/#) | Nastaví čáru na vrcholu tohoto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/underbar/#) | Nastaví čáru na spodní části tohoto prvku |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/to_box/#) | Umístí tento prvek do neviditelného boxu (logické seskupení) <br/>            který se používá k seskupení komponent rovnice nebo jiné instance matematického textu.<br/>            Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, <br/>            sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* třída [`MathPhantom`](/slides/python-net/cs/aspose.slides.mathtext/mathphantom)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)