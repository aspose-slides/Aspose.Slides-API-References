---
title: MathBlock class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathblock/
---
## MathBlock klasse

Specificeert een instantie van wiskundige tekst die zich binnen een MathParagraph bevindt en op een eigen regel begint.  
Alle wiskundige zones, inclusief vergelijkingen, expressies, reeksen van vergelijkingen of expressies, en formules worden weergegeven door een math block.

**Erfenis:**[`MathBlock`](/slides/python-net/nl/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het type MathBlock stelt de volgende leden beschikbaar:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/__init__/#) | Initialiseert een nieuw exemplaar van de MathBlock klasse. |
| [`__init__(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Maakt een nieuw wiskundig blok en plaatst het opgegeven element erin |
| [`__init__(self, math_elements)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Properties

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/count/) | Geeft het aantal onderliggende wiskundige elementen dat daadwerkelijk in de collectie zit.<br/>            Alleen-lezen **int**. |
| [`is_read_only`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/is_read_only/) | Retourneert false omdat de collectie van onderliggende elementen kan worden gewijzigd. |

Haalt of stelt een IMathElement in op de opgegeven index.

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/__getitem__/) | De nulgebaseerde index van het item |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/join/#imathelement) | Voegt een wiskundig element samen met dit wiskundige blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/join/#str) | Voegt een wiskundige tekst samen met dit wiskundige blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/divide/#imathelement) | Maakt een breuk met deze teller en de opgegeven noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/divide/#str) | Maakt een breuk met deze teller en de opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en de opgegeven noemer |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/enclose/#char-char) | Omvat de onderliggende elementen van dit blok met opgegeven tekens, zoals haakjes of andere tekens als omlijning |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Omvat de onderliggende elementen van dit blok met opgegeven tekens, zoals haakjes of andere als omlijning<br/>            en scheidt met een scheidingsteken |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/enclose/#) | Omvat een wiskundig element in haakjes |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Maakt subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_subscript/#str) | Maakt subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Maakt superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_superscript/#str) | Maakt superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript aan de linkerkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript aan de linkerkant |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad van het opgegeven argument |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad van het opgegeven argument |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Neemt bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Neemt bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Neemt ondergrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Neemt ondergrens |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Neemt de integraal zonder grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/group/#) | Plaats dit element in een groep met behulp van een accolade onderaan |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaats dit element in een groep met een groepeeringskarakter zoals een accolade onderaan of een ander |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/to_border_box/#) | Plaats dit element in een randvak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaats dit element in een randvak |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/to_math_array/#) | Plaatst onderliggende elementen in een verticale rij |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/overbar/#) | Stelt een balk boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/underbar/#) | Stelt een balk onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/to_box/#) | Plaatst dit element in een niet-visueel vak (logische groepering) <br/>            dat wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regeleinde-punt, of worden gegroepeerd zodat er geen regeleinden binnen mogelijk zijn |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/get_children/#) | Haal onderliggende elementen op |
| [`add(self, item)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/add/#imathelement) | Voegt een wiskundig element toe aan het einde van de collectie |
| [`clear(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/clear/#) | Verwijdert alle elementen uit de collectie |
| [`contains(self, item)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/contains/#imathelement) | Bepaalt of de collectie een specifieke waarde bevat |
| [`copy_to(self, array, array_index)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Kopieert naar opgegeven array |
| [`remove(self, item)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/remove/#imathelement) | Verwijdert het eerste voorkomen van een specifiek object uit de collectie |
| [`index_of(self, item)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Bepaalt de index van een specifiek wiskundig element in de collectie |
| [`insert(self, index, item)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Voegt een MathElement in de collectie in op de opgegeven index |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/remove_at/#int) | Verwijdert het element op de opgegeven index van de collectie |
| [`join_block(self, other)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Voegt een ander wiskundig blok samen met dit blok |
| [`delimit(self, separator_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/delimit/#char) | Scheidt onderliggende elementen met een scheidingsteken (zonder de haken) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/nl/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Slaat de inhoud van deze [`MathBlock`](/slides/python-net/nl/aspose.slides.mathtext/mathblock) op als MathML |

### Zie ook
* klasse [`MathBlock`](/slides/python-net/nl/aspose.slides.mathtext/mathblock)
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)