---
title: MathRightSubSuperscriptElement class
second_title: Aspose.Slides pro Python prostřednictvím .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement třída

Specifikuje objekt Sub-Superscript, který se skládá ze základu a dolního a horního indexu umístěného napravo od základu.

**Dědičnost:**[`MathRightSubSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement) → [`BaseScript`](/slides/python-net/cs/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathRightSubSuperscriptElement vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | Inicializuje novou instanci třídy MathRightSubSuperscriptElement. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/base/) | Základní argument |
| [`subscript`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/) | Argument dolního indexu |
| [`superscript`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/) | Argument horního indexu |
| [`align_scripts`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/align_scripts/) | Specifikuje zarovnání dolního/horního indexu. <br/>            Když je true, dolní a horní index jsou vodorovně zarovnány k sobě.<br/>            Když je false, jsou přizpůsobeny tvaru základu.<br/>            Výchozí hodnota je false. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#) | Uzavře matematický prvek do závorek |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#char-char) | Uzavře matematický prvek ve specifikovaných znacích, jako jsou závorky nebo jiné znaky jako rámec |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#imathelement) | Vezme funkci argumentu s touto instancí jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#str) | Vezme funkci argumentu s touto instancí jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#imathelement) | Vezme specifikovanou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#str) | Vezme specifikovanou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Vezme specifikovanou funkci s touto instancí jako argumentem |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Vezme specifikovanou funkci s touto instancí jako argumentem a zadá další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Vezme specifikovanou funkci s touto instancí jako argumentem a zadá další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index napravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index nalevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index nalevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#imathelement) | Specifikuje matematický kořen daného řádu ze specifikovaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#str) | Specifikuje matematický kořen daného řádu ze specifikovaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#imathelement) | Vezme horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#str) | Vezme horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#imathelement) | Vezme dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#str) | Vezme dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Vezme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Vezme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes) | Vezme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Vezme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str) | Vezme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#) | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znakové skupiny, jako je spodní složená závorka nebo jiný znak |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#) | Umístí tento prvek do rámečkového pole |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do rámečkového pole |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_math_array/#) | Umístí do svislého pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/accent/#char) | Nastaví diakritiku (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/overbar/#) | Nastaví čáru nahoře tohoto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/underbar/#) | Nastaví čáru dole tohoto prvku |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_box/#) | Umístí tento prvek do neviditelného pole (logické seskupení) <br/>            které se používá k seskupení komponent rovnice nebo jiného výskytu matematického textu.<br/>            Obraný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, <br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`BaseScript`](/slides/python-net/cs/aspose.slides.mathtext/basescript)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* třída [`MathRightSubSuperscriptElement`](/slides/python-net/cs/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)