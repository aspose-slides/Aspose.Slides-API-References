---
title: MathBlock class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathblock/
---
## classe MathBlock

Spécifie une instance de texte mathématique contenue dans un MathParagraph et commençant sur sa propre ligne.
            Toutes les zones mathématiques, y compris les équations, les expressions, les tableaux d'équations ou d'expressions, et les formules sont représentées par un math block.

**Héritage:**[`MathBlock`](/slides/python-net/fr/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathBlock expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/__init__/#) | Initialise une nouvelle instance de la classe MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Crée un nouveau bloc mathématique et y place l'élément spécifié |
| [`__init__(self, math_elements)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`count`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/count/) | Obtient le nombre d'éléments mathématiques enfants réellement contenus dans la collection.<br/>            Lecture seule **int**. |
| [`is_read_only`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/is_read_only/) | Renvoie false car la collection d'éléments enfants peut être modifiée. |

Obtient ou définit IMathElement à l'indice spécifié.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/__getitem__/) | L'indice basé sur zéro de l'élément |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/join/#imathelement) | Joint un élément mathématique avec ce bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/join/#str) | Joint un texte mathématique avec ce bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/enclose/#char-char) | Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme cadre |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Encadre les éléments enfants de ce bloc avec des caractères spécifiés tels que des parenthèses ou d'autres comme cadre<br/>            et délimite avec un caractère séparateur |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/enclose/#) | Encadre un élément mathématique entre parenthèses |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/function/#imathelement) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/function/#str) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Prend la limite supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Prend la limite supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Prend la limite inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Prend la limite inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Prend l'intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Prend l'intégrale sans limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prend l'intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Prend l'intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/group/#) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade inférieure ou un autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/to_border_box/#) | Place cet élément dans une boîte à bordure |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte à bordure |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/to_math_array/#) | Place les éléments enfants dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/accent/#char) | Définit un accent (un caractère au-dessus de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/overbar/#) | Définit une barre au sommet de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/underbar/#) | Définit une barre au bas de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d'une équation ou d'autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, <br/>            servir de point de rupture de ligne, ou être groupé de manière à ne pas autoriser les sauts de ligne à l'intérieur. |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/get_children/#) | Obtient les éléments enfants |
| [`add(self, item)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/add/#imathelement) | Ajoute un élément mathématique à la fin de la collection. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/clear/#) | Supprime tous les éléments de la collection. |
| [`contains(self, item)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/contains/#imathelement) | Détermine si la collection contient une valeur spécifique. |
| [`copy_to(self, array, array_index)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Copie dans le tableau spécifié. |
| [`remove(self, item)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/remove/#imathelement) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [`index_of(self, item)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Détermine l'indice d'un élément mathématique spécifique dans la collection. |
| [`insert(self, index, item)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Insère un MathElement dans la collection à l'indice spécifié. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/remove_at/#int) | Supprime l'élément à l'indice spécifié de la collection. |
| [`join_block(self, other)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Joint un autre bloc mathématique avec celui-ci |
| [`delimit(self, separator_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/delimit/#char) | Délimite les éléments enfants avec le caractère séparateur (sans les crochets) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/fr/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Enregistre le contenu de ce [`MathBlock`](/slides/python-net/fr/aspose.slides.mathtext/mathblock) en tant que MathML |


### Voir aussi
* classe [`MathBlock`](/slides/python-net/fr/aspose.slides.mathtext/mathblock)
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)