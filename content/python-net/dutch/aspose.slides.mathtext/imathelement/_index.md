---
title: IMathElement class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/imathelement/
---
## IMathElement klasse

Basisinterface van elk wiskundig element: 
            fraction, mathmatical text, function, expression with multiple elements etc

The IMathElement type exposes the following members:

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/divide/#imathelement) | Maakt een breuk met deze teller en de gespecificeerde noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/divide/#str) | Maakt een breuk met deze teller en de gespecificeerde noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en de gespecificeerde noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en de gespecificeerde noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/enclose/#) | Enkelt een wiskundig element in haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/enclose/#char-char) | Enkelt dit element in opgegeven tekens, zoals haakjes of andere tekens, als omkadering |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/as_argument_of_function/#imathelement) | Neemt de gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/as_argument_of_function/#str) | Neemt de gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsofoneargument) | Neemt de gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt de gespecificeerde functie waarbij deze instantie als argument wordt gebruikt en een extra gespecificeerd argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt de gespecificeerde functie waarbij deze instantie als argument wordt gebruikt en een extra gespecificeerd argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_subscript/#imathelement) | Maakt een subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_subscript/#str) | Maakt een subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_superscript/#imathelement) | Maakt een superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_superscript/#str) | Maakt een superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript aan de linkerkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript aan de linkerkant |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad van het gespecificeerde argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad van het gespecificeerde argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_upper_limit/#imathelement) | Neemt bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_upper_limit/#str) | Neemt bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_lower_limit/#imathelement) | Neemt ondergrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/set_lower_limit/#str) | Neemt ondergrens |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes) | Neemt de integraal zonder grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/group/#) | Plaats dit element in een groep met een onderste accolade |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaats dit element in een groep met een gegroepeerd teken, zoals een onderste accolade of een ander teken |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/to_border_box/#) | Plaats dit element in een randvak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaats dit element in een randvak |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/get_children/#) | Haal kindelementen op |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/to_math_array/#) | Plaats in een verticale array |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/overbar/#) | Plaats een balk boven dit element |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/underbar/#) | Plaats een balk onder dit element |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/imathelement/to_box/#) | Plaats dit element in een niet-visuele doos (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen.<br/>            Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regeleinde-punt, of worden gegroepeerd zodat er geen regeleinden binnen toegestaan zijn. |

### Zie ook
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)