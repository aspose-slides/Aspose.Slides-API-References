---
title: MathMatrix class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix klasse

Specificeert het Matrix-object, bestaande uit kindelementen die in één of meer rijen en kolommen zijn geplaatst. 
            Het is belangrijk op te merken dat matrices geen ingebouwde delimiters hebben. 
            Om de matrix in haakjes te plaatsen, moet u het delimiter-object (IMathDelimiter) gebruiken. 
            Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.

**Erfenis:**[`MathMatrix`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathMatrix-type geeft de volgende leden weer:

## Constructeurs

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Initialiseert een nieuw exemplaar van de MathMatrix-klasse. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`row_count`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/row_count/) | Aantal rijen in de matrix |
| [`column_count`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/column_count/) | Aantal kolommen in de matrix |
| [`hide_placeholders`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Verberg de tijdelijke aanduidingen voor lege matrixelementen<br/>            Standaard: false |
| [`base_justification`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/base_justification/) | Specificeert de verticale uitlijning ten opzichte van de omringende tekst. <br/>            Mogelijke waarden zijn top, bottom, en center.<br/>            Standaard: Center |
| [`min_column_width`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/min_column_width/) | Minimale kolombreedte in twips (1/20ste van een punt)<br/>            De spatiëring (ook wel “Column Gap” of “Gap Width” genoemd) wordt toegevoegd aan <br/>            de MinColumnWidth om de totale Matrixkolomspatiëring te bepalen<br/>            (afstand tussen dezelfde randen van verschillende kolommen).<br/>            Standaard: 0. |
| [`column_gap_rule`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Het type horizontale spatiëring tussen kolommen van een matrix; <br/>            Horizontale spatiëringseenheden kunnen ems of points zijn (opgeslagen als twips).<br/>            Standaard: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/column_gap/) | De waarde van de horizontale spatiëring tussen kolommen van een matrix;<br/>            Als de ColumnGapRule is ingesteld op 3 ("Exactly"), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt)<br/>            Als de ColumnGapRule is ingesteld op 4 ("Multiple"), dan wordt de eenheid geïnterpreteerd als een aantal van 0,5 em-incrementen.<br/>            In andere gevallen wordt negeerd.<br/>            Standaard: 0 |
| [`row_gap_rule`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Het type verticale spatiëring tussen rijen van een matrix; <br/>            Verticale spatiëringseenheden kunnen lijnen of points zijn (opgeslagen als twips).<br/>            Standaard: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/row_gap/) | De waarde van de verticale spatiëring tussen rijen van een matrix;<br/>            Als de RowGapRule is ingesteld op 3 ("Exactly"), dan wordt de eenheid geïnterpreteerd als twips (1/20ste van een punt)<br/>            Als de RowGapRule is ingesteld op 4 ("Multiple"), dan wordt de eenheid geïnterpreteerd als halve lijnen.<br/>            Standaard: 0 |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Maakt een breuk met deze teller en opgegeven noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/divide/#str) | Maakt een breuk met deze teller en opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/enclose/#) | Omgeeft een wiskundig element met haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Omgeeft een wiskundig element met opgegeven tekens, zoals haakjes of andere tekens als omkadering |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Neemt een functie van een argument waarbij dit exemplaar de functienaam is |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/function/#str) | Neemt een functie van een argument waarbij dit exemplaar de functienaam is |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Neemt gespecificeerde functie waarbij dit exemplaar het argument is |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Neemt gespecificeerde functie waarbij dit exemplaar het argument is |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Neemt gespecificeerde functie waarbij dit exemplaar het argument is |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt gespecificeerde functie waarbij dit exemplaar het argument is en een extra opgegeven argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt gespecificeerde functie waarbij dit exemplaar het argument is en een extra opgegeven argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Maakt subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Maakt subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Maakt superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Maakt superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript aan de linkerkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript aan de linkerkant |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het opgegeven argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad vanuit het opgegeven argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Neemt bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Neemt bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Neemt ondergrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Neemt ondergrens |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Neemt de integraal zonder grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/group/#) | Plaats dit element in een groep met een onderste accolade |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaats dit element in een groep met een groepeerteken, zoals een onderste accolade of een ander teken |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Plaats dit element in een randvak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaats dit element in een randvak |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Plaatst in een verticale reeks |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/overbar/#) | Stelt een balk boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/underbar/#) | Stelt een balk onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/to_box/#) | Plaatst dit element in een niet-visuele doos (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen.<br/>            Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regelafbreekpunt, of worden gegroepeerd zodat geen regelafbrekingen binnenin worden toegestaan. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Haal de horizontale uitlijning van de opgegeven kolom op |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Stel de horizontale uitlijning van de opgegeven kolom in |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Stel de horizontale uitlijning van de opgegeven kolommen in |
| [`insert_row_before(self, row_index)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Voeg een nieuwe rij in vóór de opgegeven rij<br/>            In eerste instantie zijn alle elementen in de nieuwe rij None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Voeg een nieuwe rij in na de opgegeven rij<br/>            In eerste instantie zijn alle elementen in de nieuwe rij None. |
| [`delete_row(self, row_index)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Verwijdert de opgegeven rij |
| [`insert_column_before(self, column_index)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Voeg een nieuwe kolom in vóór de opgegeven kolom<br/>            In eerste instantie zijn alle elementen in de nieuwe kolom None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Voeg een nieuwe kolom in na de opgegeven kolom<br/>            In eerste instantie zijn alle elementen in de nieuwe kolom None. |
| [`delete_column(self, column_index)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Verwijdert de opgegeven kolom |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix/get_children/#) | Haal kindelementen op |

### Zie ook
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* klasse [`MathMatrix`](/slides/python-net/nl/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)