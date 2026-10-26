---
title: MathPhantom class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathphantom/
---
## MathPhantom klasse

Stelt een fantoom wiskundig object (<m:phant>) voor dat de lay-out van zijn onderliggende element beïnvloedt zonder het noodzakelijkerwijs weer te geven. Een fantoom kan zijn basisexpressie verbergen terwijl het zijn breedte, hoogte of diepte behoudt om formules uit te lijnen of ruimte te reserveren. Zichtbaarheid en geometrisch gedrag worden geregeld door eigenschappen zoals Show, ZeroWid, ZeroAsc, ZeroDesc en Transp.

**Erfenis:**[`MathPhantom`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathPhantom-type bevat de volgende leden:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Initialiseert een nieuw exemplaar van de [`MathPhantom`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom) klasse <br/>            met het opgegeven basismath-element. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`base`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/base/) | Basisargument |
| [`show`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/show/) | Krijgt of stelt een waarde in die aangeeft of het basiselement wordt weergegeven. |
| [`zero_width`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/zero_width/) | Krijgt of stelt een waarde in die aangeeft of de breedte van het basiselement <br/>            als nul moet worden beschouwd. |
| [`zero_asc`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/zero_asc/) | Krijgt of stelt een waarde in die aangeeft of de stijging (hoogte boven de basislijn) <br/>            van het basiselement als nul moet worden beschouwd. |
| [`zero_desc`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/zero_desc/) | Krijgt of stelt een waarde in die aangeeft of de daling (diepte onder de basislijn)<br/>            van het basiselement als nul moet worden beschouwd. |
| [`transp`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/transp/) | Krijgt of stelt een waarde in die aangeeft of het fantoom transparant is <br/>            voor klasse-gebaseerde spatiëringsregels. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Maakt een breuk met deze teller en een opgegeven noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/divide/#str) | Maakt een breuk met deze teller en een opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Maakt een breuk van het opgegeven type met deze teller en opgegeven noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/enclose/#) | Omvat een wiskundig element met haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Omvat een wiskundig element met opgegeven tekens zoals haakjes of andere tekens als omlijsting |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt een opgegeven functie waarbij deze instantie als argument wordt gebruikt en een opgegeven extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Maakt subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Maakt subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Maakt superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Maakt superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Maakt subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Maakt subscript en superscript aan de linkerkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Maakt subscript en superscript aan de linkerkant |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad uit het opgegeven argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Neemt bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Neemt bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Neemt ondergrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Neemt ondergrens |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Maakt een N-aire operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Maakt een N-aire operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Neemt de integraal zonder grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/group/#) | Plaatst dit element in een groep met een onderste accolade |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaatst dit element in een groep met een groeperingsteken zoals een onderste accolade of een ander teken |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/to_border_box/#) | Plaatst dit element in een rand-box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaatst dit element in een rand-box |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/to_math_array/#) | Zet in een verticale reeks |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/overbar/#) | Stelt een streep boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/underbar/#) | Stelt een streep onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/to_box/#) | Plaatst dit element in een niet-visuele box (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een ingekaderd object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder uitlijningspunt, <br/>            dienen als een regeleinde-punt, of gegroepeerd worden zodat geen regeleinden binnen toegestaan zijn. |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom/get_children/#) | Haalt onderliggende elementen op |

### Zie ook
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* klasse [`MathPhantom`](/slides/python-net/nl/aspose.slides.mathtext/mathphantom)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)