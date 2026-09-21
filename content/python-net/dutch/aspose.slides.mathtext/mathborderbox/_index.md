---
title: MathBorderBox class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox klasse

Tekent een rechthoekige of andere rand rond de IMathElement.

**Inheritance:**[`MathBorderBox`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathBorderBox-type heeft de volgende leden:

## Constructors

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Maakt een MathBorderBox-element met een rechthoekige rand |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Maakt een MathBorderBox-element |

## Properties

| Property | Beschrijving |
| :- | :- |
| [`base`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/base/) | Basisargument |
| [`hide_top`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/hide_top/) | Hide Top Edge (default is false) - specificeert de verborgen of getoonde status van de bovenrand van de rand-box. |
| [`hide_bottom`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Hide Bottom Edge (default is false) - specificeert de verborgen of getoonde status van de onderrand van de rand-box. |
| [`hide_left`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/hide_left/) | Hide Left Edge (default is false) - specificeert de verborgen of getoonde status van de linkerrand van de rand-box. |
| [`hide_right`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/hide_right/) | Hide Right Edge (default is false) - specificeert de verborgen of getoonde status van de rechterrand van de rand-box. |
| [`strikethrough_horizontal`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Strikethrough Horizontal (default is false) - specificeert de verborgen of getoonde status van een horizontale doorhalingslijn. |
| [`strikethrough_vertical`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Strikethrough Vertical (default is false) - specificeert de verborgen of getoonde status van een verticale doorhalingslijn. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Strikethrough Bottom-Left to Top-Right (default is false).<br/>            Specificeert de verborgen of getoonde status van een diagonale doorhalingslijn van de hoek links-onder naar de hoek rechts-boven van de rand-box. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Strikethrough Top-Left to Bottom-Right (default is false).<br/>            Specificeert de verborgen of getoonde status van een diagonale doorhalingslijn van de hoek links-boven naar de hoek rechts-onder van de rand-box. |

## Methods

| Method | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Verbindt een wiskundig element en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/join/#str) | Verbindt een wiskundige tekst en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/divide/#str) | Maakt een breuk met deze teller en de opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/enclose/#) | Plaatst een wiskundig element tussen haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Plaatst een wiskundig element tussen opgegeven tekens, zoals haakjes of andere tekens als omschrijving |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een extra argument wordt gespecificeerd |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een extra argument wordt gespecificeerd |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Maakt een subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Maakt een subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Maakt een superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Maakt een superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript rechts van het element |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript rechts van het element |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript links van het element |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript links van het element |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad uit het gespecificeerde argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad uit het gespecificeerde argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Neemt een bovenlimiet |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Neemt een bovenlimiet |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Neemt een onderlimiet |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Neemt een onderlimiet |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Neemt de integraal zonder limieten |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/group/#) | Plaatst dit element in een groep met een onderste krulhaak |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaatst dit element in een groep met een groepeer-teken, zoals een onderste krulhaak of een ander teken |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Plaatst dit element in een rand-box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaatst dit element in een rand-box |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Zet in een verticale rij |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/overbar/#) | Plaatst een balk boven dit element |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/underbar/#) | Plaatst een balk onder dit element |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/to_box/#) | Plaatst dit element in een niet-visuele box (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een box-object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regeleinde-punt, of worden gegroepeerd zodat geen regeleinden binnen de box plaatsvinden. |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox/get_children/#) | Haal kind-elementen op |

### See Also
* class [`MathBorderBox`](/slides/python-net/nl/aspose.slides.mathtext/mathborderbox)
* class [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)