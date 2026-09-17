---
title: MathBorderBox class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox classe

Dessine une bordure rectangulaire ou autre autour de l'IMathElement.

**Héritage:**[`MathBorderBox`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathBorderBox expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Crée un élément MathBorderBox avec une bordure rectangulaire |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Crée un élément MathBorderBox |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`base`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/base/) | Argument de base |
| [`hide_top`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/hide_top/) | Masquer le bord supérieur (false par défaut) - spécifie l'état masqué ou affiché du bord supérieur de la boîte de bordure. |
| [`hide_bottom`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Masquer le bord inférieur (false par défaut) - spécifie l'état masqué ou affiché du bord inférieur de la boîte de bordure. |
| [`hide_left`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/hide_left/) | Masquer le bord gauche (false par défaut) - spécifie l'état masqué ou affiché du bord gauche de la boîte de bordure. |
| [`hide_right`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/hide_right/) | Masquer le bord droit (false par défaut) - spécifie l'état masqué ou affiché du bord droit de la boîte de bordure. |
| [`strikethrough_horizontal`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Barrer horizontalement (false par défaut) - spécifie l'état masqué ou affiché d'une ligne horizontale barrée. |
| [`strikethrough_vertical`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Barrer verticalement (false par défaut) - spécifie l'état masqué ou affiché d'une ligne verticale barrée. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Barrer du coin inférieur gauche au coin supérieur droit (false par défaut).<br/>            Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin inférieur gauche au coin supérieur droit de la boîte de bordure. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Barrer du coin supérieur gauche au coin inférieur droit (false par défaut).<br/>            Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin supérieur gauche au coin inférieur droit de la boîte de bordure. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Combine un élément mathématique et forme un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/join/#str) | Combine un texte mathématique et forme un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/enclose/#) | Entoure un élément mathématique de parenthèses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Entoure un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d’autres caractères comme encadrement |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Prend une fonction d’un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/function/#str) | Prend une fonction d’un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Prend la limite supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Prend la limite supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Prend la limite inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Prend la limite inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prend l’intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Prend l’intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Prend l’intégrale sans limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prend l’intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Prend l’intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/group/#) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de groupement tel qu’une accolade inférieure ou autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Place cet élément dans une boîte de bordure |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte de bordure |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Place dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/accent/#char) | Définit un signe diacritique (un caractère au-dessus de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/overbar/#) | Place une barre au-dessus de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/underbar/#) | Place une barre au-dessous de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d’une équation ou d’une autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d’émulateur d’opérateur avec ou sans point d’alignement, <br/>            servir de point de rupture de ligne, ou être groupé afin d’interdire les retours à la ligne à l’intérieur. |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox/get_children/#) | Obtient les éléments enfants |


### Voir aussi
* classe [`MathBorderBox`](/slides/python-net/fr/aspose.slides.mathtext/mathborderbox)
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)