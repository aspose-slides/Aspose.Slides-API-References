---
title: MathDelimiter class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter classe

Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que les parenthèses, les accolades, les crochets et les barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié.  
Exemples : (𝑥2); [𝑥2|𝑦2]

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
| [`beginning_character`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Le caractère de début du délimiteur indique le caractère délimiteur de début, ou d'ouverture. <br/>            Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades.<br/>            Valeur par défaut : '('. |
| [`separator_character`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/separator_character/) | Le caractère séparateur du délimiteur indique le caractère qui sépare les arguments dans l'objet délimiteur. <br/>            Valeur par défaut : '\|'. |
| [`ending_character`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/ending_character/) | Le caractère de fin du délimiteur indique le caractère délimiteur de fin, ou de fermeture. <br/>            Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades.<br/>            Valeur par défaut : ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Lorsqu'il est vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de leur opérande.<br/>            La valeur par défaut est true |
| [`delimiter_shape`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Spécifie la forme des délimiteurs dans l'objet délimiteur. <br/>            Lorsque MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique <br/>            et sont adaptés pour couvrir toute la hauteur de leur contenu.<br/>            Lorsque MathDelimiterShape.Match, leur hauteur et forme sont modifiées pour correspondre exactement à leur contenu. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Joint un élément mathématique et crée un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/join/#str) | Joint un texte mathématique et crée un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Encadre un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme cadre |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/enclose/#) | Encadre un élément mathématique entre parenthèses |
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
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
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
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade inférieure ou un autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Place cet élément dans une boîte à bordure |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte à bordure |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Place dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/accent/#char) | Définit un signe d'accent (un caractère au-dessus de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/overbar/#) | Dessine une barre au-dessus de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/underbar/#) | Dessine une barre en dessous de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/>            servir de point de retour à la ligne, ou être groupé de façon à ne pas autoriser les retours à la ligne à l'intérieur. |
| [`delimit(self, separator_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Délimite les arguments en utilisant le caractère délimiteur spécifié |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter/get_children/#) | Obtenir les éléments enfants |

### Voir aussi
* classe [`MathDelimiter`](/slides/python-net/fr/aspose.slides.mathtext/mathdelimiter)
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)