---
title: MathBar class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathbar/
---
## MathBar klasse

Specificeert de balkfunctie, bestaande uit een basisargument en een bovenstreep of onderstreep

**Overerving:**[`MathBar`](/slides/python-net/nl/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathBar-type heeft de volgende leden:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Initialiseert MathBar met bovenstreep (Bovenpositie) |
| [`__init__(self, element, position)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Initialiseert MathBar met opgegeven positie |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`base`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/base/) | Basisargument |
| [`position`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/position/) | Positie van de balklijn. <br/>            Standaard: Top |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/divide/#imathelement) | Maakt een breuk met deze teller en gespecificeerde noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/divide/#str) | Maakt een breuk met deze teller en gespecificeerde noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en gespecificeerde noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en gespecificeerde noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/enclose/#) | Omvat een wiskundig element in haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/enclose/#char-char) | Omvat een wiskundig element in opgegeven tekens, zoals haakjes of andere karakters als omkadering |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Maakt een subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_subscript/#str) | Maakt een subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Maakt een superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_superscript/#str) | Maakt een superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript aan de linkerkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript aan de linkerkant |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/radical/#imathelement) | Specificeert de wiskundige wortel van de gegeven graad van het opgegeven argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/radical/#str) | Specificeert de wiskundige wortel van de gegeven graad van het opgegeven argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Neemt een bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Neemt een bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Neemt een ondergrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Neemt een ondergrens |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Neemt de integraal zonder grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/group/#) | Plaats dit element in een groep met een onderste accolade |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaats dit element in een groep met een groeperingskarakter, zoals een onderste accolade of een ander |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/to_border_box/#) | Plaats dit element in een randvak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaats dit element in een randvak |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/to_math_array/#) | Zet in een verticale reeks |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/overbar/#) | Stelt een streep boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/underbar/#) | Stelt een streep onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/to_box/#) | Plaats dit element in een niet-visuele doos (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regeleinde-punt, of worden gegroepeerd zodat regelbreuken binnenin niet worden toegestaan. |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbar/get_children/#) | Haalt kindelementen op |

### Zie ook
* klasse [`MathBar`](/slides/python-net/nl/aspose.slides.mathtext/mathbar)
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)