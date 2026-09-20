---
title: MathBox class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathbox/
---
## MathBox třída

Určuje logické zabalení (balení) matematického prvku.  
            Například zabalený objekt může sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu,  
            sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř.  
            Například operátor „==“ by měl být zabalen, aby se zabránilo zalomení řádku.

**Dědičnost:**[`MathBox`](/slides/python-net/cs/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathBox obsahuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Inicializuje MathBox s určeným prvkem jako argumentem |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/base/) | Základní argument |
| [`operator_emulator`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/operator_emulator/) | Emulátor operátoru.<br/>            Když je true, krabice a její obsah se chovají jako jeden operátor a dědí vlastnosti operátoru. <br/>            To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k dalším operátorům.<br/>            Emulátory operátorů se často používají, když jeden nebo více glyphů tvoří operátor, například '=='.<br/>            Výchozí hodnota: false |
| [`no_break`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/no_break/) | Žádné zalomení<br/>            Tato vlastnost určuje vlastnost „unbreakable“ na objektové krabici. Když je true, v krabici nemohou nastat žádná zalomení řádku.<br/>            To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. <br/>            Pokud není tento prvek specifikován, mohou v krabici nastat zalomení.<br/>            Výchozí: true |
| [`differential`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/differential/) | Diferenciál<br/>            Když je true, krabice funguje jako diferenciál (např. 𝑑𝑥 v integrandu) a získává odpovídající <br/>            vodorovné odsazení pro matematický diferenciál.<br/>            Výchozí: false |
| [`alignment_point`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/alignment_point/) | Když je true, tento emulátor operátoru slouží jako zarovnávací bod; tj., <br/>            určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány.<br/>            Výchozí: false |
| [`explicit_break`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/explicit_break/) | Explicitní zalomení určuje, zda na začátku objektu Box existuje zalomení řádku, <br/>            takže řádek se zalamuje na začátku objektu box.<br/>            Určuje číslo operátoru na předchozím řádku matematického textu, které má<br/>            být použito jako zarovnávací bod pro aktuální řádek matematického textu<br/>            možné hodnoty: 1..255<br/>            Výchozí: 0 (žádné explicitní zalomení) |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/join/#imathelement) | Spojí matematický prvek a vytvoří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/join/#str) | Spojí matematický text a vytvoří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/divide/#str) | Vytvoří zlomek s tímto čitatelem a určeným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čiatelem a určeným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čiatelem a určeným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/enclose/#) | Obalí matematický prvek závorkami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/enclose/#char-char) | Obalí matematický prvek určenými znaky, jako jsou závorky nebo jiné znaky jako rámeček |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/function/#imathelement) | Přijímá funkci argumentu pomocí této instance jako názvu funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/function/#str) | Přijímá funkci argumentu pomocí této instance jako názvu funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Přijímá určenou funkci pomocí této instance jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Přijímá určenou funkci pomocí této instance jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Přijímá určenou funkci pomocí této instance jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijímá určenou funkci pomocí této instance jako argumentu a určený další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijímá určenou funkci pomocí této instance jako argumentu a určený další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/radical/#imathelement) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/radical/#str) | Určuje matematický kořen daného řádu ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Přijímá horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Přijímá horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Přijímá spodní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Přijímá spodní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijímá integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Přijímá integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Přijímá integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijímá integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Přijímá integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/group/#) | Umístí tento prvek do skupiny pomocí dolní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků seskupení, jako je dolní složená závorka nebo jiný |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/to_border_box/#) | Umístí tento prvek do ohraničené krabice |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do ohraničené krabice |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/to_math_array/#) | Vloží do vertikálního pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/accent/#char) | Nastaví diakritiku (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/overbar/#) | Nastaví čáru nad tímto prvkem |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/underbar/#) | Nastaví čáru pod tímto prvkem |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/to_box/#) | Umístí tento prvek do neviditelné krabice (logické seskupení) <br/>            která se používá k seskupení komponent rovnice nebo jiného výskytu matematického textu.<br/>            Zabalenný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, <br/>            sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathbox/get_children/#) | Získá podřízené prvky |

### Viz také
* třída [`MathBox`](/slides/python-net/cs/aspose.slides.mathtext/mathbox)
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)