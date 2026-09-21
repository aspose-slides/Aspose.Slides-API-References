---
title: MathLimit class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathlimit/
---
## MathLimit klasse

Specificeert het Limit-object, bestaande uit tekst op de basislijn en verkleinde tekst direct erboven of eronder.

**Overerving:**[`MathLimit`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathLimit-type biedt de volgende leden:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | Initialiseert een nieuwe instantie van de MathLimit-klasse. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Initialiseert een nieuwe instantie van de MathLimit-klasse met een onderlimiet |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`base`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/base/) | Basisargument |
| [`limit`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/limit/) | Limietargument |
| [`upper_limit`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/upper_limit/) | Specificeert een boven- of onderlimiet |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/divide/#str) | Maakt een breuk met deze teller en de opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/enclose/#) | Omvat een wiskundig element in haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/enclose/#char-char) | Omvat een wiskundig element in opgegeven tekens, zoals haakjes of andere tekens als kader |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Neemt opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Neemt opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Neemt opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Maakt subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Maakt subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Maakt superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Maakt superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript links |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Neemt bovenlimiet |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Neemt bovenlimiet |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Neemt onderlimiet |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Neemt onderlimiet |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Neemt de integraal zonder limieten |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/group/#) | Plaatst dit element in een groep met een onderste accolade |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaatst dit element in een groep met een groepeerteken, zoals een onderste accolade of een ander teken |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/to_border_box/#) | Plaatst dit element in een randvak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaatst dit element in een randvak |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/to_math_array/#) | Plaatst in een verticale reeks |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/overbar/#) | Stelt een balk boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/underbar/#) | Stelt een balk onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/to_box/#) | Plaatst dit element in een niet-visuele doos (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een ingekapseld object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regeleinde-punt, of zo gegroepeerd worden dat geen regeleinden binnen zijn toegestaan. |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit/get_children/#) | Haalt kindelementen op |

### Zie ook
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* klasse [`MathLimit`](/slides/python-net/nl/aspose.slides.mathtext/mathlimit)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)