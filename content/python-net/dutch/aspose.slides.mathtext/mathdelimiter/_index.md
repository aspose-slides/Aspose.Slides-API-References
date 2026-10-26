---
title: MathDelimiter class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter klasse

Specificeert het delimiter-object, bestaande uit opening- en sluitings-tekens (zoals haakjes, accolades, vierkante haken en verticale strepen), en één of meer wiskundige elementen binnen, gescheiden door een gespecificeerd teken.
            Voorbeelden: (𝑥2); [𝑥2|𝑦2]

**Erfenis:**[`MathDelimiter`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathDelimiter-type exposeert de volgende leden:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Initialiseert MathDelimiter met het opgegeven element als enkel basisargument |

## Properties

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/arguments/) | Een of meer wiskundige elementen gescheiden door delimiter-tekens |
| [`beginning_character`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character specificeert het beginnende, of openings, delimiter-teken. <br/>            Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades.<br/>            Standaard: '(' |
| [`separator_character`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character specificeert het teken dat argumenten scheidt in het delimiter-object. <br/>            Standaard: '\|' |
| [`ending_character`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character specificeert het eindende, of sluitings, delimiter-teken. <br/>            Wiskundige delimiters zijn omsluitende tekens zoals haakjes, vierkante haken en accolades.<br/>            Standaard: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Wanneer true, groeien de delimiters verticaal om de operand-hoogte te evenaren.<br/>            De standaardwaarde is true |
| [`delimiter_shape`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Specificeert de vorm van delimiters in het delimiter-object. <br/>            Wanneer MathDelimiterShape.Centered, worden delimiters gecentreerd rond de wiskundige as van de wiskundige tekst <br/>            en worden aangepast om de volledige hoogte van hun inhoud te passen.<br/>            Wanneer MathDelimiterShape.Match, worden hun hoogte en vorm aangepast om precies overeen te komen met hun inhoud. |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Maakt een breuk met deze teller en gespecificeerde noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/divide/#str) | Maakt een breuk met deze teller en gespecificeerde noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het gespecificeerde type met deze teller en gespecificeerde noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Maakt een breuk van het gespecificeerde type met deze teller en gespecificeerde noemer |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Omvat een wiskundig element met gespecificeerde tekens zoals haakjes of andere tekens als omlijsting |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/enclose/#) | Omvat een wiskundig element in haakjes |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Neemt gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Neemt gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Neemt gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt gespecificeerde functie waarbij deze instantie als argument wordt gebruikt en gespecificeerd extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt gespecificeerde functie waarbij deze instantie als argument wordt gebruikt en gespecificeerd extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Maakt subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Maakt subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Maakt superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Maakt superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript aan de linkerkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript aan de linkerkant |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad uit het gespecificeerde argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad uit het gespecificeerde argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Neemt bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Neemt bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Neemt ondergrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Neemt ondergrens |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Neemt de integraal zonder grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/group/#) | Plaatst dit element in een groep met behulp van een onderste accolade |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaatst dit element in een groep met een groepeerteken zoals een onderste accolade of een ander teken |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Plaatst dit element in een rand-box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaatst dit element in een rand-box |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Plaatst in een verticale reeks |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/overbar/#) | Stelt een balk boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/underbar/#) | Stelt een balk onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/to_box/#) | Plaatst dit element in een non-visual box (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een boxed object kan (bijvoorbeeld) dienen als operator-emulator met of zonder uitlijningspunt, <br/>            dienen als regeleinde-punt, of gegroepeerd worden zodat geen regeleinden binnen toegestaan zijn. |
| [`delimit(self, separator_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Delimiteert argumenten met het gespecificeerde delimiter-teken |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter/get_children/#) | Haalt kind-elementen op |

### Zie ook
* class [`MathDelimiter`](/slides/python-net/nl/aspose.slides.mathtext/mathdelimiter)
* class [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)