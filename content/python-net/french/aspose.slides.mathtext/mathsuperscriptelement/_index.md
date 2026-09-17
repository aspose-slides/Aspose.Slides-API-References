---
title: MathSuperscriptElement class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement classe

Spécifie l’objet exposant, qui se compose d’une base 
            et d’un exposant de taille réduite placé au-dessus et à droite

**Héritage:**[`MathSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement) → [`BaseScript`](/slides/python-net/fr/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathSuperscriptElement expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, base_arg, super_script)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/__init__/#imathelement-imathelement) | Initialise une nouvelle instance de la classe MathSuperscriptElement. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`base`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/base/) | Argument de base |
| [`superscript`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/superscript/) | Exposant |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/join/#imathelement) | Rejoint un élément mathématique et crée un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/join/#str) | Rejoint un texte mathématique et crée un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/enclose/#) | Encadre un élément mathématique entre parenthèses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/enclose/#char-char) | Encadre un élément mathématique dans les caractères spécifiés tels que des parenthèses ou d’autres caractères comme encadrement |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/function/#imathelement) | Prend une fonction d’un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/function/#str) | Prend une fonction d’un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#str) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l’argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l’argument spécifié. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#imathelement) | Prend la limite supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#str) | Prend la limite supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#imathelement) | Prend la limite inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#str) | Prend la limite inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prend l’intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Prend l’intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes) | Prend l’intégrale sans limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prend l’intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str) | Prend l’intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/group/#) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de groupement tel qu’une accolade inférieure ou un autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#) | Place cet élément dans une boîte à bordure |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte à bordure |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/to_math_array/#) | Place cet élément dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/accent/#char) | Définit un signe d’accent (un caractère au sommet de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/overbar/#) | Définit une barre au sommet de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/underbar/#) | Définit une barre au bas de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d’une équation ou d’une autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d’émulateur d’opérateur avec ou sans point d’alignement, <br/>            servir de point de saut de ligne, ou être groupé de manière à ne pas permettre de sauts de ligne à l’intérieur. |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement/get_children/#) | Obtient les éléments enfants |

### Voir aussi
* classe [`BaseScript`](/slides/python-net/fr/aspose.slides.mathtext/basescript)
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* classe [`MathSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathsuperscriptelement)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)