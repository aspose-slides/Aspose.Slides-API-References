---
title: MathDelimiter class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter classe

Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que les parenthèses, accolades, crochets et barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (𝑥2) ; [𝑥2|𝑦2]

**Héritage:**[`MathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathDelimiter expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Initialise MathDelimiter avec l'élément spécifié comme argument de base unique |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`arguments`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/arguments/) | Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs |
| [`beginning_character`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Le caractère de début du délimiteur spécifie le caractère délimiteur d'ouverture. <br/> Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades.<br/> La valeur par défaut : '(' |
| [`separator_character`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/separator_character/) | Le caractère séparateur du délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur. <br/> La valeur par défaut : '\|' |
| [`ending_character`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/ending_character/) | Le caractère de fin du délimiteur spécifie le caractère délimiteur de fermeture. <br/> Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades.<br/> La valeur par défaut : ')' |
| [`grow_to_match_operand_height`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Spécifie la croissance des caractères BeginningCharacter, SeparatorCharacter, EndingCharacter<br/> Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de l'opérande.<br/> La valeur par défaut est true |
| [`delimiter_shape`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Spécifie la forme des délimiteurs dans l'objet délimiteur. <br/> Lorsque MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique <br/> et sont ajustés pour correspondre à la hauteur totale de leur contenu.<br/> Lorsque MathDelimiterShape.Match, leur hauteur et forme sont modifiées pour correspondre exactement à leur contenu. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Joint un élément mathématique et crée un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/join/#str) | Joint un texte mathématique et crée un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/enclose/#) | Encapsule un élément mathématique entre parenthèses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Encapsule un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/function/#str) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Prend la limite supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Prend la limite supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Prend la limite inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Prend la limite inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Prend l'intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Prend l'intégrale sans limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Prend l'intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/group/#) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade inférieure ou autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Place cet élément dans une boîte à bordure |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte à bordure |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Place dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/accent/#char) | Définit un signe d'accent (un caractère au-dessus de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/overbar/#) | Définit une barre au-dessus de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/underbar/#) | Définit une barre au-dessous de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/to_box/#) | Place cet élément dans une boîte non visuelle (regroupement logique) <br/> qui est utilisée pour regrouper des composants d'une équation ou d'une autre instance de texte mathématique.<br/> Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/> servir de point de saut de ligne, ou être groupé afin de ne pas autoriser de sauts de ligne à l'intérieur |
| [`delimit(self, separator_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Délimite les arguments en utilisant le caractère délimiteur spécifié |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/get_children/#) | Obtient les éléments enfants |


### Voir aussi
* classe [`MathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter)
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)