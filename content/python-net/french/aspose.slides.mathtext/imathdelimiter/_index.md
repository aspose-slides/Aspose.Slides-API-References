---
title: IMathDelimiter class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/imathdelimiter/
---
## IMathDelimiter classe

Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que les parenthèses, les accolades, les crochets et les barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (𝑥2) ; [𝑥2|𝑦2]

Le type IMathDelimiter expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/arguments/) | Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs |
| [`beginning_character`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/beginning_character/) | Le caractère de début du délimiteur spécifie le caractère de délimiteur de début, ou d'ouverture.<br/>            Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades.<br/>            Valeur par défaut : '('. |
| [`separator_character`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/separator_character/) | Le caractère séparateur du délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur.<br/>            Valeur par défaut : '\|'. |
| [`ending_character`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/ending_character/) | Le caractère de fin du délimiteur spécifie le caractère de délimiteur de fin, ou de fermeture.<br/>            Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades.<br/>            Valeur par défaut : ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/grow_to_match_operand_height/) | Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Lorsque vrai, les délimiteurs croissent verticalement pour correspondre à la hauteur de leur opérande.<br/>            La valeur par défaut est true |
| [`delimiter_shape`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/delimiter_shape/) | Spécifie la forme des délimiteurs dans l'objet délimiteur.<br/>            Lorsque la valeur est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique<br/>            et peuvent encore être ajustés pour correspondre à la hauteur totale de leur contenu.<br/>            Lorsque la valeur est MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu. |

## Méthodes

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`delimit(self, separator_character)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/delimit/#char) | Délimite les arguments en utilisant le caractère délimiteur spécifié |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathdelimiter/to_box/#) |  |

### Voir aussi
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)