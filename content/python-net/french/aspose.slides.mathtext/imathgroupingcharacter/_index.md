---
title: IMathGroupingCharacter class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/imathgroupingcharacter/
---
## IMathGroupingCharacter classe

Spécifie un symbole de regroupement au-dessus ou au-dessous d’une expression, généralement pour mettre en évidence la relation entre les éléments

Le type IMathGroupingCharacter expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`base`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/base/) | Argument de base |
| [`character`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/character/) | Caractère de regroupement<br/>            Valeur par défaut: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/position/) | Position du caractère de regroupement.<br/>            Valeur par défaut: Bottom |
| [`vertical_justification`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/vertical_justification/) | Justification verticale du caractère de groupe.<br/>            Spécifie l'alignement de l'objet par rapport à la ligne de base.<br/>            Par exemple, lorsque le caractère de groupe se trouve au-dessus de l'objet, <br/>            VerticalJustification of Top signifie que le haut de l'objet se trouve sur la ligne de base;<br/>            lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet se trouve sur la ligne de base<br/>            Valeur par défaut: Bottom pour Position=Top, et Top pour Position=Bottom |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathgroupingcharacter/to_box/#) |  |

### Voir aussi
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)