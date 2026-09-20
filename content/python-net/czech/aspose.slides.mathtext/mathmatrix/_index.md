---
title: MathMatrix class
second_title: Aspose.Slides pro Python pomocí .NET referenční příručky API
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix třída

Specifikuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích.  
            Je důležité poznamenat, že matice nemají vestavěné oddělovače.  
            Pro umístění matice do závorek byste měli použít objekt oddělovače (IMathDelimiter).  
            Null argumenty mohou být použity k vytvoření mezer v maticích.

**Dědičnost:**[`MathMatrix`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)

Typ MathMatrix vystavuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Inicializuje novou instanci MathMatrix třídy. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`row_count`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/row_count/) | Počet řádků v matici |
| [`column_count`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/column_count/) | Počet sloupců v matici |
| [`hide_placeholders`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Skryje zástupné znaky pro prázdné prvky matice<br/>            Výchozí: false |
| [`base_justification`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/base_justification/) | Určuje vertikální zarovnání vzhledem k okolnímu textu.<br/>            Možné hodnoty jsou top, bottom a center.<br/>            Výchozí: Center |
| [`min_column_width`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/min_column_width/) | Minimální šířka sloupce v twips (1/20 bodu)<br/>            Prostor mezi sloupci (také označovaný jako „Column Gap“ nebo „Gap Width“) se přičítá k<br/>            MinColumnWidth k určení celkového rozestupu sloupců v matici<br/>            (vzdálenost mezi stejnými okraji různých sloupců).<br/>            Výchozí: 0. |
| [`column_gap_rule`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Typ horizontálního odstupu mezi sloupci matice;<br/>            Jednotky horizontálního odstupu mohou být ems nebo body (uložené jako twips).<br/>            Výchozí: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/column_gap/) | Hodnota horizontálního odstupu mezi sloupci matice;<br/>            Pokud je ColumnGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu)<br/>            Pokud je ColumnGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako počet 0,5 em kroků.<br/>            V ostatních případech je ignorována.<br/>            Výchozí: 0 |
| [`row_gap_rule`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Typ vertikálního odstupu mezi řádky matice;<br/>            Jednotky vertikálního odstupu mohou být řádky nebo body (uložené jako twips).<br/>            Výchozí: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/row_gap/) | Hodnota vertikálního odstupu mezi řádky matice;<br/>            Pokud je RowGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu)<br/>            Pokud je RowGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako půlřádky.<br/>            Výchozí: 0 |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Spojí matematický prvek a vytváří matematický blok |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/join/#str) | Spojí matematický text a vytváří matematický blok |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/divide/#str) | Vytvoří zlomek s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Vytvoří zlomek zadaného typu s tímto čitatelem a zadaným jmenovatelem |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/enclose/#) | Opraví matematický prvek do závorek |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Opraví matematický prvek do zadaných znaků, jako jsou závorky nebo jiné znaky jako rámování |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/function/#str) | Přijme funkci argumentu s touto instancí jako názvem funkce |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Přijme zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Přijme zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Přijme zadanou funkci s touto instancí jako argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Přijme zadanou funkci s touto instancí jako argument a zadaný další argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Přijme zadanou funkci s touto instancí jako argument a zadaný další argument |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Vytvoří dolní index |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Vytvoří dolní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Vytvoří horní index |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Vytvoří horní index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Vytvoří dolní a horní index vpravo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Vytvoří dolní a horní index vlevo |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Vytvoří dolní a horní index vlevo |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Specifikuje matematický kořen daného řádu ze zadaného argumentu. |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/radical/#str) | Specifikuje matematický kořen daného řádu ze zadaného argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Přijme horní mez |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Přijme horní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Přijme dolní mez |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Přijme dolní mez |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Vytvoří N-ární operátor |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Vytvoří N-ární operátor |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Přijme integrál |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Přijme integrál bez mezí |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Přijme integrál |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Přijme integrál |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/group/#) | Umístí tento prvek do skupiny pomocí spodní složené závorky |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Umístí tento prvek do skupiny pomocí znaků pro seskupování, jako je spodní složená závorka nebo jiný znak |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Umístí tento prvek do rámečkového pole |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umístí tento prvek do rámečkového pole |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Umístí do vertikálního pole |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/accent/#char) | Nastaví akcent (znak nad tímto prvkem) |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/overbar/#) | Nastaví čáru na vrcholu tohoto prvku |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/underbar/#) | Nastaví čáru na spodku tohoto prvku |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/to_box/#) | Umístí tento prvek do neviditelného boxu (logické seskupení) <br/>            který se používá ke skupování komponent rovnice nebo jiného matematického textu.<br/>            Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez bodu zarovnání,<br/>            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Získá horizontální zarovnání zadaného sloupce |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Nastaví horizontální zarovnání zadaného sloupce |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Nastaví horizontální zarovnání zadaných sloupců |
| [`insert_row_before(self, row_index)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Vloží nový řádek před zadaný řádek<br/>            Počátečně jsou všechny prvky v novém řádku None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Vloží nový řádek za zadaný řádek<br/>            Počátečně jsou všechny prvky v novém řádku None. |
| [`delete_row(self, row_index)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Odstraní zadaný řádek |
| [`insert_column_before(self, column_index)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Vloží nový sloupec před zadaný sloupec<br/>            Počátečně jsou všechny prvky v novém sloupci None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Vloží nový sloupec za zadaný sloupec<br/>            Počátečně jsou všechny prvky v novém sloupci None. |
| [`delete_column(self, column_index)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Odstraní zadaný sloupec |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix/get_children/#) | Získá podřízené prvky |


### See Also
* třída [`MathElementBase`](/slides/python-net/cs/aspose.slides.mathtext/mathelementbase)
* třída [`MathMatrix`](/slides/python-net/cs/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)