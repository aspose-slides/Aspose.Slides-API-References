---
title: MathAccent class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathaccent/
---
## Classe MathAccent

Spécifie la fonction d'accent, composée d'une base et d'un signe diacritique combinant  
Exemple : 𝑎́

**Héritage:**[`MathAccent`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathAccent expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | Crée un accent mathématique appliqué à un élément mathématique spécifié avec la valeur du caractère d'accent par défaut |
| [`__init__(self, element, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | Crée un accent mathématique appliqué à un élément mathématique spécifié |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`base`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/base/) | L'argument auquel l'accent a été appliqué |
| [`character`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/character/) | Caractère d'accent<br/>            La valeur doit être comprise dans l'intervalle (U+0300–U+036F) ou (U+20D0–U+20EF)<br/>            Valeur par défaut : accent circonflexe combinant (U+0302) |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/join/#imathelement) | Joint un élément mathématique et forme un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/join/#str) | Joint un texte mathématique et forme un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/enclose/#) | Encadre un élément mathématique entre parenthèses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/enclose/#char-char) | Encadre un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/function/#imathelement) | Applique une fonction à un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/function/#str) | Applique une fonction à un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | Applique la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | Applique la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | Applique la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Applique la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Applique la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | Applique la borne supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | Applique la borne supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | Applique la borne inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | Applique la borne inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Applique l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | Applique l'intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | Applique l'intégrale sans limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | Applique l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | Applique l'intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/group/#) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade inférieure ou un autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/to_border_box/#) | Place cet élément dans une boîte à bordure |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte à bordure |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/to_math_array/#) | Place dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/accent/#char) | Définit un signe d'accent (un caractère au-dessus de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/overbar/#) | Place une barre au-dessus de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/underbar/#) | Place une barre en bas de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/>            servir de point de rupture de ligne, ou être groupé de façon à ne pas autoriser les sauts de ligne à l'intérieur. |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent/get_children/#) | Obtenir les éléments enfants |


### Voir aussi
* classe [`MathAccent`](/slides/python-net/fr/aspose.slides.mathtext/mathaccent)
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)