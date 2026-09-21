---
title: MathNaryOperator class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator klasse

Specificeert een N-aire wiskundig object, zoals Som en Integraal.
            Het bestaat uit een operator, een basis (of operand), en optionele boven- en onderlimieten. 
            Voorbeelden van N-aire operatoren zijn: Som, Vereniging, Doorsnede, Integraal

**Erfenis:**[`MathNaryOperator`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het type MathNaryOperator exposeert de volgende leden:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Initializes a new instance of the MathNaryOperator class. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Initializes a new instance of the MathNaryOperator class. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Initializes a new instance of the MathNaryOperator class. |

## Eigenschappen

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/base/) | Basisargument |
| [`subscript`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/subscript/) | Specificeert een subscriptargument dat bijvoorbeeld, in het geval van een integraal, de onderlimiet instelt |
| [`superscript`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/superscript/) | Specificeert een superscriptargument dat bijvoorbeeld, in het geval van een integraal, de bovengrens instelt |
| [`operator`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/operator/) | N-aire operator teken<br/>            Bijvoorbeeld: '∑', '∫' |
| [`limit_location`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/limit_location/) | De locatie van limieten (subscript en superscript) |
| [`grow_to_match_operand_height`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Operator teken groeit verticaal om de hoogte van zijn operand te evenaren |
| [`hide_subscript`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Verberg subscript |
| [`hide_superscript`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Verberg superscript |

## Methodes

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Maakt een breuk met deze teller en opgegeven noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Maakt een breuk met deze teller en opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Omsluit een wiskundig element in haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Omsluit een wiskundig element in opgegeven tekens zoals haakjes of andere karakters als omlijning |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en opgegeven extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en opgegeven extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Creëert subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Creëert subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Creëert superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Creëert superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creëert subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Creëert subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creëert subscript en superscript aan de linkerkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Creëert subscript en superscript aan de linkerkant |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Specificeert de wiskundige wortel van de gegeven graad uit het opgegeven argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Specificeert de wiskundige wortel van de gegeven graad uit het opgegeven argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Neemt bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Neemt bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Neemt onderlimiet |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Neemt onderlimiet |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creëert een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Creëert een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Neemt de integraal zonder limieten |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/group/#) | Plaatst dit element in een groep met behulp van een onderste accolade |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaatst dit element in een groep met een groepeerkarakter zoals een onderste accolade of een ander |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Plaatst dit element in een randvak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaatst dit element in een randvak |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Plaatst in een verticale array |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Stelt een accent teken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Stelt een balk boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Stelt een balk onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Plaatst dit element in een niet-visuele box (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een ingekaderd object kan (bijvoorbeeld) dienen als een operatoremulator met of zonder een uitlijningspunt, <br/>            dienen als een regeleinde, of gegroepeerd worden zodat er geen regeleinden binnen toegestaan zijn. |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Haalt kindelementen op |


### Zie ook
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* klasse [`MathNaryOperator`](/slides/python-net/nl/aspose.slides.mathtext/mathnaryoperator)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)