---
title: MathPhantom class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathphantom/
---
## MathPhantom classe

Représente un objet mathématique fantôme (<m:phant>) qui affecte la mise en page de son élément enfant sans nécessairement l'afficher. Un fantôme peut masquer son expression de base tout en préservant sa largeur, sa hauteur ou sa profondeur afin d'aligner les formules ou de réserver de l'espace. La visibilité et le comportement géométrique sont contrôlés par des propriétés telles que Show, ZeroWid, ZeroAsc, ZeroDesc et Transp.

**Héritage:**[`MathPhantom`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathPhantom expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Initialise une nouvelle instance de la classe [`MathPhantom`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom) <br/>            en utilisant l'élément mathématique de base spécifié. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`base`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/base/) | Argument de base |
| [`show`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/show/) | Obtient ou définit une valeur indiquant si l'élément de base est affiché. |
| [`zero_width`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/zero_width/) | Obtient ou définit une valeur indiquant si la largeur de l'élément de base <br/>            doit être traitée comme zéro. |
| [`zero_asc`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/zero_asc/) | Obtient ou définit une valeur indiquant si l'ascension (hauteur au-dessus de la ligne de base) <br/>            de l'élément de base doit être traitée comme zéro. |
| [`zero_desc`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/zero_desc/) | Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base)<br/>            de l'élément de base doit être traitée comme zéro. |
| [`transp`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/transp/) | Obtient ou définit une valeur indiquant si le fantôme est transparent <br/>            pour les règles d'espacement basées sur les classes. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/join/#imathelement) | Joint un élément mathématique et forme un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/join/#str) | Joint un texte mathématique et forme un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/enclose/#) | Entoure un élément mathématique de parenthèses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Entoure un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/function/#imathelement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/function/#str) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Prend la limite supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Prend la limite supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Prend la limite inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Prend la limite inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Prend l'intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Prend l'intégrale sans limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Prend l'intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/group/#) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade inférieure ou autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/to_border_box/#) | Place cet élément dans une boîte bordée |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte bordée |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/to_math_array/#) | Met dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/accent/#char) | Définit un signe d'accent (un caractère au sommet de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/overbar/#) | Dessine une barre au sommet de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/underbar/#) | Dessine une barre au bas de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/>            servir de point de rupture de ligne, ou être groupé de manière à ne pas autoriser de sauts de ligne à l'intérieur. |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom/get_children/#) | Obtient les éléments enfants |

### Voir aussi
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* classe [`MathPhantom`](/slides/python-net/fr/aspose.slides.mathtext/mathphantom)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)