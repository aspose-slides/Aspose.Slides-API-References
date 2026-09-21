---
title: IMathBlock class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/imathblock/
---
## IMathBlock klasse

Specificeert een instantie van wiskundige tekst die zich binnen een MathParagraph bevindt en op een eigen regel begint. 
Alle wiskundige zones, inclusief vergelijkingen, uitdrukkingen, reeksen van vergelijkingen of uitdrukkingen, en formules worden weergegeven door een math-block.

Het type IMathBlock biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`count`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/count/) |  |

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/__getitem__/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/enclose/#char-char-char) | Omhult kindelementen van dit blok met opgegeven tekens zoals haakjes of andere als omlijsting<br/>            en scheidt met een scheidingsteken |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/enclose/#char-char) |  |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/divide/#str-mathfractiontypes) |  |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`delimit(self, separator_character)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/delimit/#char) | Scheidt alle kindelementen met een scheidingsteken (zonder de haakjes) |
| [`join_block(self, other)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/join_block/#imathblock) | Voegt een ander wiskundig blok samen met dit blok |
| [`write_as_math_ml(self, stream)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/write_as_math_ml/#iorawiobase) | Slaat de inhoud van deze [`IMathBlock`](/slides/python-net/nl/aspose.slides.mathtext/imathblock) op als MathML |
| [`add(self, item)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/add/#imathelement) |  |
| [`index_of(self, item)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/index_of/#imathelement) |  |
| [`insert(self, index, item)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/insert/#int-imathelement) |  |
| [`clear(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/clear/#) |  |
| [`contains(self, item)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/contains/#imathelement) |  |
| [`remove(self, item)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/remove/#imathelement) |  |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/remove_at/#int) |  |
| [`copy_to(self, array, array_index)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/copy_to/#listimathelement-int) |  |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathblock/to_box/#) |  |

### Zie ook
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)