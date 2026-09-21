---
title: MathBox class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.mathtext/mathbox/
---
## MathBox klasse

Specificeert de logische boxing (verpakking) van een wiskundig element.
            For example, a boxed object can serve as an operator emulator with or without an alignment point, 
            serve as a line break point, or be grouped such as not to allow line breaks within.
            For example, the "==" operator should be boxed to prevent line breaks.

**Overerving:**[`MathBox`](/slides/python-net/nl/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)

Het MathBox-type maakt de volgende leden beschikbaar:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Initialiseert MathBox met het opgegeven element als argument |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`base`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/base/) | Basisargument |
| [`operator_emulator`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/operator_emulator/) | Operator Emulator.<br/>            Wanneer true, gedragen de doos en de inhoud zich als één operator en erven de eigenschappen van een operator. <br/>            Dit betekent bijvoorbeeld dat het teken kan dienen als een punt voor een regeleinde en kan worden uitgelijnd met andere operatoren.<br/>            Operator-emulators worden vaak gebruikt wanneer een of meer glyphs combineren tot een operator, zoals '=='.<br/>            Standaardwaarde: false |
| [`no_break`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/no_break/) | Geen onderbreking<br/>            Deze eigenschap specificeert de eigenschap "unbreakable" op de objectdoos. Wanneer true, kunnen er geen regeleinden binnen de doos optreden.<br/>            Dit kan belangrijk zijn voor operator-emulators die uit meer dan één binaire operator bestaan. <br/>            Wanneer dit element niet gespecificeerd is, kunnen er onderbrekingen in de doos optreden.<br/>            Standaard: true |
| [`differential`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/differential/) | Differentiaal<br/>            Wanneer true, gedraagt de doos zich als een differentiaal (bijv. 𝑑𝑥 in een integrand), en ontvangt de juiste <br/>            horizontale spatiëring voor het wiskundige differentiaal.<br/>            Standaard: false |
| [`alignment_point`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/alignment_point/) | Wanneer true, dient deze operator-emulator als uitlijningspunt; dat wil zeggen,<br/>            aangewezen uitlijningspunten in andere vergelijkingen kunnen ermee worden uitgelijnd.<br/>            Standaard: false |
| [`explicit_break`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/explicit_break/) | Expliciete onderbreking geeft aan of er een regeleinde is aan het begin van het Box-object, <br/>            zodat de regel wordt afgebroken aan het begin van het Box-object.<br/>            Specificeert het aantal van de operator op de vorige regel van wiskundige tekst die<br/>            gebruikt moet worden als het uitlijningspunt voor de huidige regel van wiskundige tekst<br/>            mogelijke waarden: 1..255<br/>            Standaard: 0 (geen expliciete onderbreking) |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/join/#imathelement) | Voegt een wiskundig element samen en vormt een wiskundig blok |
| [`join(self, math_text)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/join/#str) | Voegt een wiskundige tekst samen en vormt een wiskundig blok |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/divide/#imathelement) | Creëert een breuk met deze teller en gespecificeerde noemer |
| [`divide(self, denominator)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/divide/#str) | Creëert een breuk met deze teller en gespecificeerde noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Creëert een breuk van het opgegeven type met deze teller en gespecificeerde noemer |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Creëert een breuk van het opgegeven type met deze teller en gespecificeerde noemer |
| [`enclose(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/enclose/#) | Omvat een wiskundig element in haakjes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/enclose/#char-char) | Omvat een wiskundig element in opgegeven tekens, zoals haakjes of andere tekens als omlijsting |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/function/#imathelement) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`function(self, function_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/function/#str) | Neemt een functie van een argument waarbij deze instantie als functienaam wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Neemt een gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Neemt een gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Neemt een gespecificeerde functie waarbij deze instantie als argument wordt gebruikt |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Neemt een gespecificeerde functie waarbij deze instantie als argument wordt gebruikt en een bijkomend argument opgegeven |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Neemt een gespecificeerde functie waarbij deze instantie als argument wordt gebruikt en een bijkomend argument opgegeven |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Creëert subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_subscript/#str) | Creëert subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Creëert superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_superscript/#str) | Creëert superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creëert subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Creëert subscript en superscript aan de rechterkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creëert subscript en superscript aan de linkerkant |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Creëert subscript en superscript aan de linkerkant |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/radical/#imathelement) | Specificeert de wiskundige wortel van de opgegeven graad van het gespecificeerde argument. |
| [`radical(self, degree)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/radical/#str) | Specificeert de wiskundige wortel van de opgegeven graad van het gespecificeerde argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Neemt bovengrens |
| [`set_upper_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Neemt bovengrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Neemt ondergrens |
| [`set_lower_limit(self, limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Neemt ondergrens |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creëert een N-ary-operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Creëert een N-ary-operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Neemt de integraal |
| [`integral(self, integral_type)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Neemt de integraal zonder grenzen |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Neemt de integraal |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Neemt de integraal |
| [`group(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/group/#) | Plaatst dit element in een groep met behulp van een onderste accolade |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Plaatst dit element in een groep met behulp van een groepeerend teken zoals een onderste accolade of een ander teken |
| [`to_border_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/to_border_box/#) | Plaatst dit element in een randvak |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Plaatst dit element in een randvak |
| [`to_math_array(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/to_math_array/#) | Plaatst in een verticale array |
| [`accent(self, accent_character)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/accent/#char) | Stelt een accentteken in (een teken boven dit element) |
| [`overbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/overbar/#) | Stelt een balk boven dit element in |
| [`underbar(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/underbar/#) | Stelt een balk onder dit element in |
| [`to_box(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/to_box/#) | Plaatst dit element in een niet-visuele doos (logische groepering) <br/>            die wordt gebruikt om componenten van een vergelijking of andere instantie van wiskundige tekst te groeperen.<br/>            Een verpakte object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, <br/>            dienen als een regeleinde-punt, of gegroepeerd worden zodat er geen regeleinden binnen toegestaan zijn. |
| [`get_children(self)`](/slides/python-net/nl/aspose.slides.mathtext/mathbox/get_children/#) | Haalt kindelementen op |

### Zie ook
* klasse [`MathBox`](/slides/python-net/nl/aspose.slides.mathtext/mathbox)
* klasse [`MathElementBase`](/slides/python-net/nl/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/nl/aspose.slides.mathtext)
* bibliotheek [`Aspose.Slides`](/slides/python-net)