---
title: MathDelimiter class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter třída

Určuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků (např. závorky, 
            složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických prvků uvnitř, oddělených zadaným znakem.
            Příklady: (𝑥2); [𝑥2|𝑦2]

**Dědičnost:**[`MathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathDelimiter poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Inicializuje MathDelimiter se zadaným prvkem jako jediným základním argumentem |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`arguments`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/arguments/) | Jeden nebo více matematických prvků oddělených znaky oddělovače |
| [`beginning_character`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Znak počátečního oddělovače určuje počáteční, tj. otevírací, znak oddělovače. <br/>            Matematické oddělovače jsou ohraničovací znaky, jako jsou závorky, hranaté závorky a složené závorky.<br/>            Výchozí: '('. |
| [`separator_character`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/separator_character/) | Znak oddělovače separátoru určuje znak, který odděluje argumenty v objektu oddělovače. <br/>            Výchozí: '\|'. |
| [`ending_character`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/ending_character/) | Znak koncového oddělovače určuje koncový, tj. uzavírací, znak oddělovače. <br/>            Matematické oddělovače jsou ohraničovací znaky, jako jsou závorky, hranaté závorky a složené závorky.<br/>            Výchozí: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Když je true, oddělovače se roztahují vertikálně, aby odpovídaly výšce operandů.<br/>            Výchozí hodnota je true |
| [`delimiter_shape`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Určuje tvar oddělovačů v objektu oddělovače. <br/>            Když je MathDelimiterShape.Centered, oddělovače jsou centrovány kolem matematické osy textu <br/>            a lze je upravit tak, aby odpovídaly celé výšce jejich obsahu.<br/>            Když je MathDelimiterShape.Match, jejich výška a tvar jsou změněny tak, aby přesně odpovídaly jejich obsahu. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Vytvoří zlomek daného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/enclose/#) | Obalí matematický prvek do závorek |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Obalí matematický prvek ve specifikovaných znacích, například v závorkách nebo jiných znacích jako rámování |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Přebírá funkci argumentu s touto instancí jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/function/#str) | Přebírá funkci argumentu s touto instancí jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Přebírá zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Přebírá zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Přebírá zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přebírá zadanou funkci s touto instancí jako argument a zadaný další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přebírá zadanou funkci s touto instancí jako argument a zadaný další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/radical/#str) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Přebírá horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Přebírá horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Přebírá dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Přebírá dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přebírá integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Přebírá integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Přebírá integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přebírá integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Přebírá integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupení, jako je dolní složená závorka nebo jiný znak |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Umístí tento prvek do ohraničené krabice |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do ohraničené krabice |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/accent/#char) | Nastaví akcent (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/overbar/#) | Nastaví čáru nad tímto prvkem |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/underbar/#) | Nastaví čáru pod tímto prvkem |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/to_box/#) | Umístí tento prvek do neviditelné krabice (logické seskupení) <br/>            která se používá k seskupení komponent rovnice nebo jiného matematického textu.<br/>            Krabicový objekt může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání, <br/>            sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| [`delimit(self, separator_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Odděluje argumenty pomocí zadaného znaku oddělovače |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`MathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)