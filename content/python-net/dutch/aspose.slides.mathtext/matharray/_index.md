---
title: MathArray class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/matharray/
---
## MathArray klasse

Specificeert een verticale array van vergelijkingen of willekeurige wiskundige objecten

**Inheritance:**[`MathArray`](/slides/python-net/nl/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathArray-type maakt de volgende leden beschikbaar:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/__init__/#imathelement) | Maakt een wiskundige array en plaatst het opgegeven element erin |
| [`__init__(self, elements)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`arguments`](/slides/python-net/nl/aspose.slides.mathtext/matharray/arguments/) | De verzameling items van de array |
| [`base_justification`](/slides/python-net/nl/aspose.slides.mathtext/matharray/base_justification/) | Specificeert de uitlijning van de array ten opzichte van omliggende tekst<br/>            Tekst buiten de array kan uitgelijnd worden met de onderkant, bovenkant of het midden van een array-object.<br/>            Standaardwaarde: Center |
| [`maximum_distribution`](/slides/python-net/nl/aspose.slides.mathtext/matharray/maximum_distribution/) | Maximum distributie<br/>            Wanneer true, wordt de array gespreid tot de maximale breedte van het omvattende element (pagina, kolom, cel, enz.). |
| [`object_distribution`](/slides/python-net/nl/aspose.slides.mathtext/matharray/object_distribution/) | Objectdistributie<br/>            Wanneer true, worden de inhoud van de array gespreid tot de maximale breedte van het array-object. |
| [`row_spacing_rule`](/slides/python-net/nl/aspose.slides.mathtext/matharray/row_spacing_rule/) | Het type verticale spatiëring tussen array-elementen<br/>            Standaard: SingleLineGap |
| [`row_spacing`](/slides/python-net/nl/aspose.slides.mathtext/matharray/row_spacing/) | Spatiëring tussen rijen van een array<br/>            Wordt alleen gebruikt wanneer RowSpacingRule is ingesteld op 3 Exact, in welk geval de meeteenheid punten is <br/>            of Multiple, waarbij de meeteenheid halve regels is.<br/>            Standaard: 0 |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/join/#imathelement) | Voegt een wiskundig element toe en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/join/#str) | Voegt een wiskundige tekst toe en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/divide/#imathelement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/divide/#str) | Maakt een breuk met deze teller en de opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/enclose/#) | Omgeeft een wiskundig element met haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/enclose/#char-char) | Omgeeft een wiskundig element met opgegeven tekens, zoals haakjes of andere tekens als omlijning |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Maakt subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_subscript/#str) | Maakt subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Maakt superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_superscript/#str) | Maakt superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript rechts |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript rechts |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript links |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript links |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Neemt bovenlimiet |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Neemt bovenlimiet |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Neemt onderlimiet |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Neemt onderlimiet |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Neemt de integraal zonder limieten |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/group/#) | Plaatst dit element in een groep met een accolade onderaan |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaatst dit element in een groep met een groepeerteken zoals een accolade onderaan of een ander teken |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/to_border_box/#) | Plaatst dit element in een rand-vak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaatst dit element in een rand-vak |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/to_math_array/#) | Zet in een verticale array |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/overbar/#) | Stelt een balk boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/underbar/#) | Stelt een balk onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/to_box/#) | Plaatst dit element in een niet-visuele doos (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regeleinde-punt, of gegroepeerd worden zodat geen regeleindes binnen toegestaan zijn. |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/matharray/get_children/#) | Haal kindelementen op |

### Zie ook
* klasse [`MathArray`](/slides/python-net/nl/aspose.slides.mathtext/matharray)
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)