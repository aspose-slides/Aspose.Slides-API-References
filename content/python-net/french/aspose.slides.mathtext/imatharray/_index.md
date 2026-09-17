---
title: IMathArray class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/imatharray/
---
## IMathArray classe

Spécifie un tableau vertical d'équations ou de tout objet mathématique

Le type IMathArray expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`arguments`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/arguments/) | Ensemble des éléments du tableau |
| [`base_justification`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/base_justification/) | Spécifie l'alignement du tableau par rapport au texte environnant<br/>            Le texte en dehors du tableau peut être aligné avec le bas, le haut ou le centre d'un objet tableau.<br/>            Valeur par défaut : Center |
| [`maximum_distribution`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/maximum_distribution/) | Distribution maximale<br/>            Lorsque vrai, le tableau est espacé à la largeur maximale de l'élément contenant (page, colonne, cellule, etc.). |
| [`object_distribution`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/object_distribution/) | Distribution d'objet<br/>            Lorsque vrai, le contenu du tableau est espacé à la largeur maximale de l'objet tableau. |
| [`row_spacing_rule`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/row_spacing_rule/) | Le type d'espacement vertical entre les éléments du tableau |
| [`row_spacing`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/row_spacing/) | Espacement entre les lignes d'un tableau<br/>            Il n'est utilisé que lorsque RowSpacingRule est réglé sur 3 Exactly, auquel cas l'unité de mesure est les points <br/>            ou Multiple, auquel cas l'unité de mesure est les demi-lignes.<br/>            Valeur par défaut : 0 |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/imatharray/to_box/#) |  |

### Voir aussi
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)