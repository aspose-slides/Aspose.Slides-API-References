---
title: MathArray class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/matharray/
---
## MathArray třída

Specifikuje vertikální pole rovnic nebo jakýchkoli matematických objektů

**Dědičnost:**[`MathArray`](/slides/python-net/cs/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathArray vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/__init__/#imathelement) | Vytvoří matematické pole a umístí do něj zadaný prvek |
| [`__init__(self, elements)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`arguments`](/slides/python-net/cs/aspose.slides.mathtext/matharray/arguments/) | Množina položek pole |
| [`base_justification`](/slides/python-net/cs/aspose.slides.mathtext/matharray/base_justification/) | Určuje zarovnání pole vzhledem k okolnímu textu<br/>            Text mimo pole může být zarovnán se spodkem, horní částí nebo středem objektu pole.<br/>            Výchozí hodnota: Center |
| [`maximum_distribution`](/slides/python-net/cs/aspose.slides.mathtext/matharray/maximum_distribution/) | Maximum Distribution<br/>            Když je true, pole je rozloženo na maximální šířku obsahujícího prvku (page, column, cell, atd.). |
| [`object_distribution`](/slides/python-net/cs/aspose.slides.mathtext/matharray/object_distribution/) | Object Distribution<br/>            Když je true, obsah pole je rozložen na maximální šířku objektu pole. |
| [`row_spacing_rule`](/slides/python-net/cs/aspose.slides.mathtext/matharray/row_spacing_rule/) | Typ vertikálního odsazení mezi prvky pole<br/>            Výchozí: SingleLineGap |
| [`row_spacing`](/slides/python-net/cs/aspose.slides.mathtext/matharray/row_spacing/) | Rozestupy mezi řádky pole<br/>            Používá se jen když je RowSpacingRule nastaven na 3 Exactly, v takovém případě je jednotkou míry body <br/>            nebo Multiple, v takovém případě je jednotkou míry půlřádky.<br/>            Výchozí: 0 |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/divide/#str) | Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek daného typu s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Vytvoří zlomek daného typu s tímto čitatelem a určeným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/enclose/#) | Obalí matematický prvek závorkami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/enclose/#char-char) | Obalí matematický prvek určenými znaky, například závorkami nebo jinými znaky jako rámečkem |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/function/#imathelement) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/function/#str) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Přijme určenou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Přijme určenou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Přijme určenou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme určenou funkci s touto instancí jako argument a určený další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme určenou funkci s touto instancí jako argument a určený další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/radical/#imathelement) | Určuje matematický kořen dané stupně ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/radical/#str) | Určuje matematický kořen dané stupně ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Přijme horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Přijme horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Přijme dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Přijme dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Přijme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znakové skupiny, například dolní složené závorky nebo jiné |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/to_border_box/#) | Umístí tento prvek do ohraničeného rámečku |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do ohraničeného rámečku |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/to_math_array/#) | Umístí do vertikálního pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/accent/#char) | Nastaví diakritický znak (znak na vrcholu tohoto prvku) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/overbar/#) | Nastaví čáru na vrcholu tohoto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/underbar/#) | Nastaví čáru na spodku tohoto prvku |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/to_box/#) | Umístí tento prvek do neviditelného rámečku (logické seskupení) <br/>            který se používá ke skupení komponent rovnice nebo jiného výrazu matematického textu.<br/>            Objekt v rámečku může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/matharray/get_children/#) | Získá podřízené prvky |


### Viz také
* třída [`MathArray`](/slides/python-net/cs/aspose.slides.mathtext/matharray)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)