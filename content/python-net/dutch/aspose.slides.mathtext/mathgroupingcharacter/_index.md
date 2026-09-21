---
title: MathGroupingCharacter class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter klasse

Specificeert een groeperingssymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken

**Erfenis:**[`MathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathGroupingCharacter-type exposeert de volgende leden:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse <br/>            met het standaard groeperingssymbool U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`base`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/base/) | Basisargument |
| [`character`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/character/) | Groeperingssymbool<br/>            Standaardwaarde: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/position/) | Positie van het groeperingssymbool.<br/>            Standaard: Bottom |
| [`vertical_justification`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Verticale uitlijning van het groeperingssymbool.<br/>            Bepaalt de uitlijning van het object ten opzichte van de basislijn.<br/>            Bijvoorbeeld, wanneer het groeperingssymbool boven het object staat, <br/>            VerticalJustification van Top betekent dat de bovenkant van het object op de basislijn valt;<br/>            wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de basislijn<br/>            Standaard: Bottom voor Position=Top, en Top voor Position=Bottom |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Maakt een breuk met deze teller en opgegeven noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Maakt een breuk met deze teller en opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Omringt een wiskundig element met haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Omringt een wiskundig element met opgegeven tekens zoals haakjes of andere tekens als omlijsting |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie wordt gebruikt als functienaam |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Neemt een functie van een argument waarbij deze instantie wordt gebruikt als functienaam |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Neemt een opgegeven functie waarbij deze instantie wordt gebruikt als argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Neemt een opgegeven functie waarbij deze instantie wordt gebruikt als argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Neemt een opgegeven functie waarbij deze instantie wordt gebruikt als argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt een opgegeven functie waarbij deze instantie wordt gebruikt als argument en een opgegeven extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt een opgegeven functie waarbij deze instantie wordt gebruikt als argument en een opgegeven extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Maakt subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Maakt subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Maakt superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Maakt superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript links |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Specificeert de wiskundige wortel van de gegeven graad uit het opgegeven argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Specificeert de wiskundige wortel van de gegeven graad uit het opgegeven argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Neemt bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Neemt bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Neemt ondergrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Neemt ondergrens |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Neemt de integraal zonder grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Plaatst dit element in een groep met een onderste krulhaak |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaatst dit element in een groep met een groeperingssymbool zoals een onderste krulhaak of een ander |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Plaatst dit element in een randvak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaatst dit element in een randvak |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Plaatst in een verticale reeks |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Stelt een accentenmarkering in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Plaatst een streep boven dit element |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Plaatst een streep onder dit element |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Plaatst dit element in een niet-visuele box (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere wiskundige tekst te groeperen.<br/>            Een ingekapseld object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regelbreekpunt, of gegroepeerd worden zodat geen regelbreuken binnen worden toegestaan. |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Haalt kindelementen op |

### Zie ook
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* klasse [`MathGroupingCharacter`](/slides/python-net/nl/aspose.slides.mathtext/mathgroupingcharacter)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)