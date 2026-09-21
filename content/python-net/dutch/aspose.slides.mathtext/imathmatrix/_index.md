---
title: IMathMatrix class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix klasse

Specificeert het Matrix-object, bestaande uit kindelementen die zijn gerangschikt in één of meer rijen en kolommen.  
Het is belangrijk op te merken dat matrices geen ingebouwde scheidingstekens hebben.  
Om de matrix tussen haakjes te plaatsen, moet u het scheidingstekenobject (IMathDelimiter) gebruiken.  
Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren.

Het IMathMatrix-type biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`row_count`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/row_count/) | Aantal rijen in de matrix |
| [`column_count`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/column_count/) | Aantal kolommen in de matrix |
| [`hide_placeholders`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Verberg de tijdelijke aanduidingen voor lege matrixelementen<br/>            Standaard: false |
| [`base_justification`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/base_justification/) | Bepaalt de verticale uitlijning ten opzichte van de omringende tekst. <br/>            Mogelijke waarden zijn top, bottom en center.<br/>            Standaard: Center |
| [`min_column_width`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/min_column_width/) | Minimale kolombreedte in twips (1/20e van een punt)<br/>            De tussenruimte (ook wel “Column Gap” of “Gap Width” genoemd) wordt toegevoegd aan <br/>            de MinColumnWidth om de totale Matrix-kolomafstand te bepalen<br/>            (afstand tussen dezelfde randen van verschillende kolommen).<br/>            Standaard: 0. |
| [`column_gap_rule`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Het type horizontale tussenruimte tussen kolommen van een matrix; <br/>            Horizontale eenheden kunnen ems of points zijn (opgeslagen als twips).<br/>            Standaard: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/column_gap/) | De waarde van de horizontale tussenruimte tussen kolommen van een matrix;<br/>            Als de ColumnGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20e van een punt)<br/>            Als de ColumnGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als 0,5-em-stappen.<br/>            In andere gevallen genegeerd.<br/>            Standaard: 0 |
| [`row_gap_rule`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Het type verticale tussenruimte tussen rijen van een matrix; <br/>            Vertikale eenheden kunnen lines of points zijn (opgeslagen als twips).<br/>            Standaard: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/row_gap/) | De waarde van de verticale tussenruimte tussen rijen van een matrix;<br/>            Als de RowGapRule is ingesteld op 3 (“Exactly”), dan wordt de eenheid geïnterpreteerd als twips (1/20e van een punt)<br/>            Als de RowGapRule is ingesteld op 4 (“Multiple”), dan wordt de eenheid geïnterpreteerd als halve lines.<br/>            Standaard: 0 |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Haal de horizontale uitlijning van de opgegeven kolom op |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Stel de horizontale uitlijning van de opgegeven kolom in |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Stel de horizontale uitlijning van de opgegeven kolommen in |
| [`insert_row_before(self, row_index)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Voeg een nieuwe rij in vóór de opgegeven rij<br/>            Aanvankelijk zijn alle elementen in de nieuwe rij None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Voeg een nieuwe rij in na de opgegeven rij<br/>            Aanvankelijk zijn alle elementen in de nieuwe rij None. |
| [`delete_row(self, row_index)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Verwijdert de opgegeven rij |
| [`insert_column_before(self, column_index)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Voeg een nieuwe kolom in vóór de opgegeven kolom<br/>            Aanvankelijk zijn alle elementen in de nieuwe kolom None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Voeg een nieuwe kolom in na de opgegeven kolom<br/>            Aanvankelijk zijn alle elementen in de nieuwe kolom None. |
| [`delete_column(self, column_index)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Verwijdert de opgegeven kolom |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Zie ook
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)