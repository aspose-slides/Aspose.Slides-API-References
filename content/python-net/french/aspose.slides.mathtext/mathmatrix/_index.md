---
title: MathMatrix class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix classe

Spécifie l'objet Matrix, composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes. 
            Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. 
            Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur (IMathDelimiter).
            Les arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.

**Héritage:**[`MathMatrix`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)

Le type MathMatrix expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Initialise une nouvelle instance de la classe MathMatrix. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`row_count`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/row_count/) | Nombre de lignes dans la matrice |
| [`column_count`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/column_count/) | Nombre de colonnes dans la matrice |
| [`hide_placeholders`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Masquer les espaces réservés pour les éléments vides de la matrice<br/>            Valeur par défaut : false |
| [`base_justification`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/base_justification/) | Spécifie la justification verticale par rapport au texte environnant. <br/>            Les valeurs possibles sont top, bottom, et center.<br/>            Valeur par défaut : Center |
| [`min_column_width`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/min_column_width/) | Largeur minimale de colonne en twips (1/20e de point)<br/>            L'espacement d'écart (aussi appelé “Column Gap” ou “Gap Width”) est ajouté au <br/>            MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice<br/>            (distance entre les mêmes bords de colonnes différentes).<br/>            Valeur par défaut : 0. |
| [`column_gap_rule`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Le type d'espacement horizontal entre les colonnes d'une matrice; <br/>            Les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips).<br/>            Valeur par défaut : SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/column_gap/) | La valeur de l'espacement horizontal entre les colonnes d'une matrice;<br/>            Si ColumnGapRule est réglé sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e de point)<br/>            Si ColumnGapRule est réglé sur 4 ("Multiple"), l'unité est interprétée comme nombre d'incréments de 0,5 em.<br/>            Dans les autres cas ignoré.<br/>            Valeur par défaut : 0 |
| [`row_gap_rule`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Le type d'espacement vertical entre les lignes d'une matrice; <br/>            Les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips).<br/>            Valeur par défaut : SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/row_gap/) | La valeur de l'espacement vertical entre les lignes d'une matrice;<br/>            Si RowGapRule est réglé sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e de point)<br/>            Si RowGapRule est réglé sur 4 ("Multiple"), l'unité est interprétée comme demi-lignes.<br/>            Valeur par défaut : 0 |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Réunit un élément mathématique et forme un bloc mathématique |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/join/#str) | Réunit un texte mathématique et forme un bloc mathématique |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/divide/#str) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/enclose/#) | Encadre un élément mathématique entre parenthèses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Encadre un élément mathématique avec les caractères spécifiés tels que des parenthèses ou d’autres caractères comme encadrement |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Prend une fonction d’un argument en utilisant cette instance comme nom de fonction |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/function/#str) | Prend une fonction d’un argument en utilisant cette instance comme nom de fonction |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Prend une fonction spécifiée en utilisant cette instance comme argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Prend une fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Crée un indice |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Crée un indice |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Crée un exposant |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Crée un exposant |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Crée un indice et un exposant à droite |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crée un indice et un exposant à gauche |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Crée un indice et un exposant à gauche |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Spécifie la racine mathématique du degré donné à partir de l’argument spécifié. |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/radical/#str) | Spécifie la racine mathématique du degré donné à partir de l’argument spécifié. |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Prend la borne supérieure |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Prend la borne supérieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Prend la borne inférieure |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Prend la borne inférieure |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crée un opérateur N-aire |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Crée un opérateur N-aire |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Prend l’intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Prend l’intégrale |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Prend l’intégrale sans bornes |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Prend l’intégrale |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Prend l’intégrale |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/group/#) | Place cet élément dans un groupe à l’aide d’une accolade inférieure |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Place cet élément dans un groupe à l’aide d’un caractère de groupement tel qu’une accolade inférieure ou autre |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Place cet élément dans une boîte bordée |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Place cet élément dans une boîte bordée |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Place dans un tableau vertical |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/accent/#char) | Définit une marque d’accent (un caractère au dessus de cet élément) |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/overbar/#) | Définit une barre au-dessus de cet élément |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/underbar/#) | Définit une barre au-dessous de cet élément |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/to_box/#) | Place cet élément dans une boîte non visuelle (groupement logique) <br/>            qui est utilisée pour regrouper les composants d’une équation ou d’une autre instance de texte mathématique.<br/>            Un objet encadré peut (par exemple) servir d’émulateur d’opérateur avec ou sans point d’alignement, <br/>            servir de point de rupture de ligne, ou être groupé de manière à ne pas autoriser de ruptures de ligne à l’intérieur. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Obtient l’alignement horizontal de la colonne spécifiée |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Définit l’alignement horizontal de la colonne spécifiée |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Définit l’alignement horizontal des colonnes spécifiées |
| [`insert_row_before(self, row_index)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Insère une nouvelle ligne avant celle spécifiée<br/>            Initialement, tous les éléments de la nouvelle ligne sont None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Insère une nouvelle ligne après celle spécifiée<br/>            Initialement, tous les éléments de la nouvelle ligne sont None. |
| [`delete_row(self, row_index)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Supprime la ligne spécifiée |
| [`insert_column_before(self, column_index)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Insère une nouvelle colonne avant celle spécifiée<br/>            Initialement, tous les éléments de la nouvelle colonne sont None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Insère une nouvelle colonne après celle spécifiée<br/>            Initialement, tous les éléments de la nouvelle colonne sont None. |
| [`delete_column(self, column_index)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Supprime la colonne spécifiée |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix/get_children/#) | Obtient les éléments enfants |


### Voir aussi
* classe [`MathElementBase`](/slides/python-net/fr/aspose.slides.mathtext/mathelementbase)
* classe [`MathMatrix`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)