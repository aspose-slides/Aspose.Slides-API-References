---
title: MathDelimiter class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter třída

Určuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků (jako jsou závorky, složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických prvků uvnitř, oddělených zadaným znakem.  
Příklady: (𝑥2); [𝑥2|𝑦2]

**Dědičnost:**[`MathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathDelimiter vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Inicializuje MathDelimiter se zadaným prvkem jako jediným základním argumentem |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`arguments`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/arguments/) | Jeden nebo více matematických prvků oddělených znaky oddělovače |
| [`beginning_character`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Znak začátku oddělovače určuje počáteční, tedy otevírací, znak oddělovače. <br/>            Matematické oddělovače jsou ohraničující znaky jako závorky, hranaté závorky a složené závorky.<br/>            Výchozí: '('. |
| [`separator_character`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/separator_character/) | Znak oddělovače oddělovače určuje znak, který odděluje argumenty v objektu oddělovače. <br/>            Výchozí: '\|'. |
| [`ending_character`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/ending_character/) | Znak konce oddělovače určuje koncový, tedy uzavírací, znak oddělovače. <br/>            Matematické oddělovače jsou ohraničující znaky jako závorky, hranaté závorky a složené závorky.<br/>            Výchozí: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Určuje růst znaků BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Když je true, oddělovače rostou svisle tak, aby odpovídaly výšce operandu.<br/>            Výchozí hodnota je true |
| [`delimiter_shape`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Určuje tvar oddělovačů v objektu oddělovače. <br/>            Když je MathDelimiterShape.Centered, oddělovače jsou vycentrovány kolem matematické osy matematického textu <br/>            a jsou přizpůsobeny tak, aby pasovaly na celou výšku jejich obsahu.<br/>            Když je MathDelimiterShape.Match, jejich výška a tvar jsou upraveny tak, aby přesně odpovídaly jejich obsahu. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Oblení matematický prvek v zadaných znacích, jako jsou závorky nebo jiné znaky jako rámování |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/enclose/#) | Oblení matematický prvek v závorkách |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Přijme funkci argumentu s použitím této instance jako názvu funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/function/#str) | Přijme funkci argumentu s použitím této instance jako názvu funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Přijme zadanou funkci s použitím této instance jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Přijme zadanou funkci s použitím této instance jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Přijme zadanou funkci s použitím této instance jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme zadanou funkci s použitím této instance jako argumentu a zadaný další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme zadanou funkci s použitím této instance jako argumentu a zadaný další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index nalevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index nalevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Určuje matematický kořen zadaného stupně z daného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/radical/#str) | Určuje matematický kořen zadaného stupně z daného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Přijme horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Přijme horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Přijme dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Přijme dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Přijme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaku pro seskupení, jako je dolní složená závorka nebo jiný |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Umístí tento prvek do ohraničeného rámečku |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do ohraničeného rámečku |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/accent/#char) | Nastaví diakritický znak (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/overbar/#) | Nastaví čáru nahoře tohoto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/underbar/#) | Nastaví čáru dole tohoto prvku |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/to_box/#) | Umístí tento prvek do neviditelného boxu (logické seskupení) <br/>            který se používá k seskupení komponent rovnice nebo jiné instance matematického textu.<br/>            Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. |
| [`delimit(self, separator_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Odděluje argumenty pomocí zadaného znaku oddělovače |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`MathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)