---
title: MathSubscriptElement class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement classe

Spécifie l'objet indice, qui se compose d'une base 
            et d'un indice de taille réduite placé en dessous et à droite.

**Héritage:**[`MathSubscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement) → [`BaseScript`](/slides/python-net/fr/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathSubscriptElement expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, base_arg, sub_script)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/__init__/#imathelement-imathelement) | Initialise une nouvelle instance de la classe MathSubscriptElement. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`base`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/base/) | Argument de base |
| [`subscript`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/subscript/) | Indice |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/join/#imathelement) | Joint un élément mathématique et crée un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/join/#str) | Joint un texte mathématique et crée un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/enclose/#) | Enveloppe un élément mathématique entre parenthèses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/enclose/#char-char) | Enveloppe un élément mathématique entre les caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/function/#imathelement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/function/#str) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#str) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#imathelement) | Prend la limite supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#str) | Prend la limite supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#imathelement) | Prend la limite inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#str) | Prend la limite inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Prend l'intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes) | Prend l'intégrale sans limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str) | Prend l'intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/group/#) | Place cet élément dans un groupe en utilisant une accolade en bas |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade en bas ou un autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#) | Place cet élément dans une boîte avec bordure |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte avec bordure |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/to_math_array/#) | Place dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/accent/#char) | Définit une marque d'accent (un caractère au-dessus de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/overbar/#) | Dessine une barre au dessus de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/underbar/#) | Dessine une barre en dessous de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/>            servir de point de saut de ligne, ou être groupé de manière à ne pas autoriser les sauts de ligne à l'intérieur. |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement/get_children/#) | Obtient les éléments enfants |


### Voir aussi
* classe [`BaseScript`](/slides/python-net/fr/aspose.slides.mathtext/basescript)
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* classe [`MathSubscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathsubscriptelement)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)