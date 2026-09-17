---
title: Axis class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/axis/
---
## Axis classe

Encapsule l'objet qui représente l'axe d'un graphique.

Le type Axis expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/axis/chart/) | Renvoie le graphique parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/fr/aspose.slides.charts/axis/axis_between_categories/) | Représente si l'axe de valeur croise l'axe des catégories entre les catégories.<br/>             Cette propriété ne s'applique qu'aux axes de catégories et ne s'applique pas aux graphiques 3D.<br/>             Lecture/écriture **bool**. |
| [`category_axis_type`](/slides/python-net/fr/aspose.slides.charts/axis/category_axis_type/) | Spécifie le type de l'axe de catégorie.<br/>            Lecture/écriture [`CategoryAxisType`](/slides/python-net/fr/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/fr/aspose.slides.charts/axis/cross_at/) | Représente le point sur l'axe où l'axe perpendiculaire le croise.<br/>             Lecture/écriture **float**. |
| [`display_unit`](/slides/python-net/fr/aspose.slides.charts/axis/display_unit/) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeur.<br/>             Lecture/écriture [`DisplayUnitType`](/slides/python-net/fr/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/fr/aspose.slides.charts/axis/actual_max_value/) | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_min_value`](/slides/python-net/fr/aspose.slides.charts/axis/actual_min_value/) | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_major_unit`](/slides/python-net/fr/aspose.slides.charts/axis/actual_major_unit/) | Spécifie l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_minor_unit`](/slides/python-net/fr/aspose.slides.charts/axis/actual_minor_unit/) | Spécifie l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_major_unit_scale`](/slides/python-net/fr/aspose.slides.charts/axis/actual_major_unit_scale/) | Spécifie l'échelle de l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_minor_unit_scale`](/slides/python-net/fr/aspose.slides.charts/axis/actual_minor_unit_scale/) | Spécifie l'échelle de l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`is_automatic_max_value`](/slides/python-net/fr/aspose.slides.charts/axis/is_automatic_max_value/) | Indique si la valeur maximale est assignée automatiquement.<br/>             Lecture/écriture **bool**. |
| [`max_value`](/slides/python-net/fr/aspose.slides.charts/axis/max_value/) | Représente la valeur maximale sur l'axe de valeur.<br/>             Lecture/écriture **float**. |
| [`minor_unit`](/slides/python-net/fr/aspose.slides.charts/axis/minor_unit/) | Représente les unités secondaires pour l'axe de date ou de valeur.<br/>             Lecture/écriture **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/fr/aspose.slides.charts/axis/is_automatic_minor_unit/) | Indique si l'unité secondaire de l'axe est assignée automatiquement.<br/>             Lecture/écriture **bool**. |
| [`major_unit`](/slides/python-net/fr/aspose.slides.charts/axis/major_unit/) | Représente les unités principales pour l'axe de date ou de valeur.<br/>             Lecture/écriture **float**. |
| [`is_automatic_major_unit`](/slides/python-net/fr/aspose.slides.charts/axis/is_automatic_major_unit/) | Indique si l'unité principale de l'axe est assignée automatiquement.<br/>            Lecture/écriture **bool**. |
| [`is_automatic_min_value`](/slides/python-net/fr/aspose.slides.charts/axis/is_automatic_min_value/) | Indique si la valeur minimale est assignée automatiquement.<br/>             Lecture/écriture **bool**. |
| [`min_value`](/slides/python-net/fr/aspose.slides.charts/axis/min_value/) | Représente la valeur minimale sur l'axe de valeur.<br/>             Lecture/écriture **float**. |
| [`is_logarithmic`](/slides/python-net/fr/aspose.slides.charts/axis/is_logarithmic/) | Représente si le type d'échelle de l'axe de valeur est logarithmique ou non.<br/>             Lecture/écriture **bool**. |
| [`log_base`](/slides/python-net/fr/aspose.slides.charts/axis/log_base/) | Représente la base logarithmique. La valeur par défaut est 10.<br/>             Lecture/écriture **float**. |
| [`is_plot_order_reversed`](/slides/python-net/fr/aspose.slides.charts/axis/is_plot_order_reversed/) | Représente si MS PowerPoint trace les points de données du dernier au premier.<br/>             Lecture/écriture **bool**. |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/axis/is_visible/) | Représente si l'axe est visible.<br/>             Lecture/écriture **bool**. |
| [`major_tick_mark`](/slides/python-net/fr/aspose.slides.charts/axis/major_tick_mark/) | Représente le type de marque de graduation principale pour l'axe spécifié.<br/>             Lecture/écriture [`TickMarkType`](/slides/python-net/fr/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/fr/aspose.slides.charts/axis/minor_tick_mark/) | Représente le type de marque de graduation secondaire pour l'axe spécifié.<br/>             Lecture/écriture [`TickMarkType`](/slides/python-net/fr/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/fr/aspose.slides.charts/axis/tick_label_position/) | Représente la position des étiquettes de marques de graduation sur l'axe spécifié.<br/>             Lecture/écriture [`TickLabelPositionType`](/slides/python-net/fr/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/fr/aspose.slides.charts/axis/major_unit_scale/) | Représente l'échelle de l'unité principale pour l'axe de date.<br/>             Lecture/écriture [`TimeUnitType`](/slides/python-net/fr/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/fr/aspose.slides.charts/axis/minor_unit_scale/) | Représente l'échelle de l'unité principale pour l'axe de date.<br/>             Lecture/écriture [`TimeUnitType`](/slides/python-net/fr/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/fr/aspose.slides.charts/axis/base_unit_scale/) | Spécifie la plus petite unité de temps représentée sur l'axe de date.<br/>            Lecture/écriture [`TimeUnitType`](/slides/python-net/fr/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/fr/aspose.slides.charts/axis/minor_grid_lines_format/) | Représente le format des lignes de grille secondaires sur un axe de graphique.<br/>             Lecture seule [`IChartLinesFormat`](/slides/python-net/fr/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/fr/aspose.slides.charts/axis/major_grid_lines_format/) | Représente le format des lignes de grille principales sur un axe de graphique.<br/>             Lecture seule [`IChartLinesFormat`](/slides/python-net/fr/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/fr/aspose.slides.charts/axis/show_minor_grid_lines/) | Pour masquer la ligne de grille secondaire, définissez MinorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill.<br/>            Lecture seule **bool**. |
| [`show_major_grid_lines`](/slides/python-net/fr/aspose.slides.charts/axis/show_major_grid_lines/) | Pour masquer la ligne de grille principale, définissez MajorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill.<br/>            Lecture seule **bool**. |
| [`format`](/slides/python-net/fr/aspose.slides.charts/axis/format/) | Représente le format de l'axe.<br/>             Lecture seule [`IAxisFormat`](/slides/python-net/fr/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/fr/aspose.slides.charts/axis/text_format/) | Représente le format du texte.<br/>             Lecture seule [`IChartTextFormat`](/slides/python-net/fr/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/fr/aspose.slides.charts/axis/title/) | Obtient le titre de l'axe.<br/>             Lecture seule [`IChartTitle`](/slides/python-net/fr/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/fr/aspose.slides.charts/axis/cross_type/) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise.<br/>             Lecture/écriture [`CrossesType`](/slides/python-net/fr/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/fr/aspose.slides.charts/axis/position/) | Représente la position de l'axe.<br/>             Lecture/écriture [`AxisPositionType`](/slides/python-net/fr/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/fr/aspose.slides.charts/axis/has_title/) | Détermine si un axe possède un titre visible.<br/>            Lecture/écriture **bool**. |
| [`number_format`](/slides/python-net/fr/aspose.slides.charts/axis/number_format/) | Représente la chaîne de format pour les étiquettes d'axe.<br/>            Lecture/écriture **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/fr/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Indique si le format est lié aux données source.<br/>            Lecture/écriture **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/fr/aspose.slides.charts/axis/tick_label_rotation_angle/) | Représente l'angle de rotation des étiquettes de graduation.<br/>            Lecture/écriture **float**. |
| [`tick_label_spacing`](/slides/python-net/fr/aspose.slides.charts/axis/tick_label_spacing/) | Spécifie le nombre d'étiquettes de graduation à ignorer entre les étiquettes affichées. Appliqué à l'axe de catégorie ou de série.<br/>            Lecture/écriture **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/fr/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Spécifie la valeur d'espacement automatique des étiquettes de graduation. Si false : utilisez la propriété TickLabelSpacing.<br/>            Lecture/écriture **bool**. |
| [`tick_marks_spacing`](/slides/python-net/fr/aspose.slides.charts/axis/tick_marks_spacing/) | Spécifie le nombre de marques de graduation à ignorer avant que la suivante ne soit <br/>            dessinée. Appliqué à l'axe de catégorie ou de série.<br/>            Lecture/écriture **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/fr/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Spécifie la valeur d'espacement automatique des marques de graduation. Si false : utilisez la propriété TickMarksSpacing.<br/>            Lecture/écriture **bool**. |
| [`label_offset`](/slides/python-net/fr/aspose.slides.charts/axis/label_offset/) | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué à l'axe de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %.<br/>            Lecture/écriture **int**. |
| [`aggregation_type`](/slides/python-net/fr/aspose.slides.charts/axis/aggregation_type/) | Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [`bin_width`](/slides/python-net/fr/aspose.slides.charts/axis/bin_width/) | Spécifie la largeur du bin lorsque la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth.<br/>            Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [`number_of_bins`](/slides/python-net/fr/aspose.slides.charts/axis/number_of_bins/) | Spécifie le nombre de bins lorsque la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins.<br/>            Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/fr/aspose.slides.charts/axis/is_overflow_bin/) | Spécifie si le bin de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de dépassement. |
| [`is_automatic_overflow_bin`](/slides/python-net/fr/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Spécifie la valeur automatique du bin de dépassement. Si false : utilisez la propriété OverflowBin. |
| [`overflow_bin`](/slides/python-net/fr/aspose.slides.charts/axis/overflow_bin/) | Spécifie la valeur personnalisée du bin de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin est vraie. |
| [`is_underflow_bin`](/slides/python-net/fr/aspose.slides.charts/axis/is_underflow_bin/) | Spécifie si le bin de sous-débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-débordement. |
| [`is_automatic_underflow_bin`](/slides/python-net/fr/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Spécifie la valeur automatique du bin de sous-débordement. Si false : utilisez la propriété UnderflowBin. |
| [`underflow_bin`](/slides/python-net/fr/aspose.slides.charts/axis/underflow_bin/) | Spécifie la valeur personnalisée du bin de sous-débordement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin est vraie. |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/axis/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/fr/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement en fonction des données de l'axe. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)