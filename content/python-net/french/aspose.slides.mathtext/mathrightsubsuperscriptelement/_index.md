---
title: MathRightSubSuperscriptElement class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement classe

Spécifie l'objet Sub-Superscript, qui se compose d'une base 
            et d'un indice et d'un exposant placés à droite de la base.

**Héritage:**[`MathRightSubSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement) → [`BaseScript`](/slides/python-net/fr/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathRightSubSuperscriptElement expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | Initialise une nouvelle instance de la classe MathRightSubSuperscriptElement. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`base`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/base/) | Argument de base |
| [`subscript`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/) | Argument d'indice |
| [`superscript`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/) | Argument d'exposant |
| [`align_scripts`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/align_scripts/) | Spécifie l'alignement de l'indice/l'exposant. <br/>            Lorsque vrai, l'indice et l'exposant sont alignés horizontalement l'un par rapport à l'autre.<br/>            Lorsque faux, ils sont ajustés à la forme de la base.<br/>            La valeur par défaut est false. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#imathelement) | Joint un élément mathématique et forme un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#str) | Joint un texte mathématique et forme un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#) | Encadre un élément mathématique entre parenthèses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#char-char) | Encadre un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#imathelement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#str) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#imathelement) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#str) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#imathelement) | Prend la limite supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#str) | Prend la limite supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#imathelement) | Prend la limite inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#str) | Prend la limite inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Prend l'intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes) | Prend l'intégrale sans limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str) | Prend l'intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade inférieure ou autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#) | Place cet élément dans une boîte à bordure |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte à bordure |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_math_array/#) | Insère dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/accent/#char) | Définit un signe d'accent (un caractère au-dessus de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/overbar/#) | Place une barre au-dessus de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/underbar/#) | Place une barre au-dessous de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/>            servir de point de saut de ligne, ou être groupé de façon à ne pas autoriser les sauts de ligne à l'intérieur. |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_children/#) | Obtient les éléments enfants |

### Voir aussi
* classe [`BaseScript`](/slides/python-net/fr/aspose.slides.mathtext/basescript)
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* classe [`MathRightSubSuperscriptElement`](/slides/python-net/fr/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)