---
title: MathAccent class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathaccent/
---
## MathAccent třída

Určuje funkci akcentu, skládající se ze základny a kombinujícího diakritického znaku<br/>            Příklad: 𝑎́

**Dědičnost:**[`MathAccent`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathAccent poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou znaku akcentu |
| [`__init__(self, element, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/base/) | Argument, na který byl akcent aplikován |
| [`character`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/character/) | Znak akcentu<br/>            Hodnota by měla být v rozsahu (U+0300–U+036F) nebo (U+20D0–U+20EF)<br/>            Výchozí hodnota: Kombinovaný střelkový akcent (U+0302) |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/enclose/#) | Uzavře matematický prvek v závorkách |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/enclose/#char-char) | Uzavře matematický prvek ve specifikovaných znacích, například v závorkách nebo jiných znacích jako rámeček |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/function/#imathelement) | Vytvoří funkci argumentu s tímto výskytem jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/function/#str) | Vytvoří funkci argumentu s tímto výskytem jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | Použije zadanou funkci s tímto výskytem jako argumentem |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | Použije zadanou funkci s tímto výskytem jako argumentem |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | Použije zadanou funkci s tímto výskytem jako argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Použije zadanou funkci s tímto výskytem jako argumentem a s dalším specifikovaným argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Použije zadanou funkci s tímto výskytem jako argumentem a s dalším specifikovaným argumentem |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/radical/#imathelement) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/radical/#str) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | Přijme horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | Přijme horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | Přijme dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | Přijme dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | Přijme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/group/#) | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, například spodní složené závorky nebo jiných |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/to_border_box/#) | Umístí tento prvek do ohraničeného rámečku |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do ohraničeného rámečku |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/accent/#char) | Nastaví akcentový znak (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/overbar/#) | Nastaví čáru na vrcholu tohoto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/underbar/#) | Nastaví čáru na spodku tohoto prvku |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/to_box/#) | Umístí tento prvek do neviditelného boxu (logické seskupení) <br/>            který se používá ke seskupení komponent rovnice nebo jiné instance matematického textu.<br/>            Objekt v boxu může (například) sloužit jako emulátor operátoru s či bez zarovnávacího bodu, <br/>            sloužit jako bod pro zalomení řádku, nebo být seskupen tak, aby neumožnil zalomení řádku uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent/get_children/#) | Získá podřízené prvky |


### Viz také
* třída [`MathAccent`](/slides/python-net/cs/aspose.slides.mathtext/mathaccent)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)