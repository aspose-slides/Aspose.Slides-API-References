---
title: IMathBox class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/imathbox/
---
## IMathBox klass

Anger den logiska inkapslingen (paketeringen) av ett matematiskt element.
            Till exempel kan ett inkapslat objekt fungera som en operatoremulator med eller utan en justeringspunkt, fungera som en radbrytpunkt eller grupperas så att radbrytningar inte tillåts inom det. Till exempel bör operatorn "==" inkapslas för att förhindra radbrytningar.

IMathBox-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/base/) | Basargument |
| [`operator_emulator`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/operator_emulator/) | Operatoremulator.<br/>            När sant beter sig boxen och dess innehåll som en enda operator och ärver egenskaperna hos en operator. <br/>            Detta innebär till exempel att tecknet kan fungera som en punkt för radbrytning och kan justeras till andra operatorer.<br/>            Operatoremulatorer används ofta när ett eller flera tecken kombineras för att bilda en operator, såsom '=='.<br/>            Standardvärde: false |
| [`no_break`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/no_break/) | Ingen brytning.<br/>            Denna egenskap anger den "obrytbara" egenskapen på objektboxen. När sant kan ingen radbrytning ske inom boxen.<br/>            Detta kan vara viktigt för operatoremulatorer som består av mer än en binär operator. <br/>            När detta element inte anges kan brytningar ske i boxen.<br/>            Standard: true |
| [`differential`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/differential/) | Differential.<br/>            När sant fungerar boxen som en differential (t.ex. 𝑑𝑥 i ett integrand), och får lämplig <br/>            horisontell avstånd för den matematiska differentialen.<br/>            Standard: false |
| [`alignment_point`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/alignment_point/) | När sant fungerar denna operatoremulator som en justeringspunkt; det vill säga, <br/>            utsedda justeringspunkter i andra ekvationer kan justeras med den.<br/>            Standard: false |
| [`explicit_break`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/explicit_break/) | Explicit brytning anger om det finns en radbrytning i början av Box-objektet, <br/>            så att raden bryts i början av box-objektet.<br/>            Anger numret på operatorn i föregående rad av matematisk text som ska<br/>            användas som justeringspunkt för den aktuella raden av matematisk text<br/>            möjliga värden: 1..255<br/>            Standard: 0 (ingen explicit brytning) |

## Metoder

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/to_box/#) |  |

### Se också
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)