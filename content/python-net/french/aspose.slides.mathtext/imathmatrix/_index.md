---
title: IMathMatrix class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix classe

Spécifie l'objet Matrix, composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes.  
Il est important de noter que les matrices n'ont pas de délimiteurs intégrés.  
Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur (IMathDelimiter).  
Des arguments null peuvent être utilisés pour créer des espaces dans les matrices.

Le type IMathMatrix expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/row_count/) | Nombre de lignes dans la matrice |
| [`column_count`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/column_count/) | Nombre de colonnes dans la matrice |
| [`hide_placeholders`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Masquer les espaces réservés pour les éléments vides de la matrice<br/>            Valeur par défaut : false |
| [`base_justification`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/base_justification/) | Spécifie l'alignement vertical par rapport au texte environnant.<br/>            Les valeurs possibles sont top, bottom, et center.<br/>            Valeur par défaut : Center |
| [`min_column_width`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/min_column_width/) | Largeur minimale de colonne en twips (1/20e de point)<br/>            L'espacement d'écart (également appelé « Column Gap » ou « Gap Width ») est ajouté à <br/>            la MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice<br/>            (distance entre les mêmes bords de colonnes différentes).<br/>            Valeur par défaut : 0. |
| [`column_gap_rule`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Le type d'espacement horizontal entre les colonnes d'une matrice ; <br/>            Les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips).<br/>            Valeur par défaut : SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/column_gap/) | La valeur de l'espacement horizontal entre les colonnes d'une matrice ;<br/>            Si ColumnGapRule est définie à 3 ("Exactly"), l'unité est interprétée comme des twips (1/20e de point)<br/>            Si ColumnGapRule est définie à 4 ("Multiple"), l'unité est interprétée comme le nombre d'incréments de 0,5 em.<br/>            Dans les autres cas, ignoré.<br/>            Valeur par défaut : 0 |
| [`row_gap_rule`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Le type d'espacement vertical entre les lignes d'une matrice ; <br/>            Les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips).<br/>            Valeur par défaut : SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/row_gap/) | La valeur de l'espacement vertical entre les lignes d'une matrice ;<br/>            Si RowGapRule est définie à 3 ("Exactly"), l'unité est interprétée comme des twips (1/20e de point)<br/>            Si RowGapRule est définie à 4 ("Multiple"), l'unité est interprétée comme des demi-lignes.<br/>            Valeur par défaut : 0 |

## Méthodes

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Obtient l'alignement horizontal de la colonne spécifiée |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Définit l'alignement horizontal de la colonne spécifiée |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Définit l'alignement horizontal des colonnes spécifiées |
| [`insert_row_before(self, row_index)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Insère une nouvelle ligne avant celle spécifiée<br/>            Initialement, tous les éléments de la nouvelle ligne sont None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Insère une nouvelle ligne après celle spécifiée<br/>            Initialement, tous les éléments de la nouvelle ligne sont None. |
| [`delete_row(self, row_index)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Supprime la ligne spécifiée |
| [`insert_column_before(self, column_index)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Insère une nouvelle colonne avant celle spécifiée<br/>            Initialement, tous les éléments de la nouvelle colonne sont None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Insère une nouvelle colonne après celle spécifiée<br/>            Initialement, tous les éléments de la nouvelle colonne sont None. |
| [`delete_column(self, column_index)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Supprime la colonne spécifiée |
| [`get_children(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/fr/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Voir aussi
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)