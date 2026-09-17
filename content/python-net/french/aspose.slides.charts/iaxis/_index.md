---
title: IAxis class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/iaxis/
---
## IAxis classe

Encapsulates the object that represents a chart's axis.

The IAxis type exposes the following members:

## Propriétés

| Propriété | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/fr/aspose.slides.charts/iaxis/axis_between_categories/) | Représente si l'axe de valeurs croise l'axe de catégories entre les catégories.<br/>            Cette propriété s'applique uniquement aux axes de catégories, et ne s'applique pas aux graphiques 3D.<br/>            Lecture/écriture **bool**. |
| [`cross_at`](/slides/python-net/fr/aspose.slides.charts/iaxis/cross_at/) | Représente le point sur l'axe où l'axe perpendiculaire le croise.<br/>            Lecture/écriture **float**. |
| [`display_unit`](/slides/python-net/fr/aspose.slides.charts/iaxis/display_unit/) | Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeurs.<br/>            Lecture/écriture [`DisplayUnitType`](/slides/python-net/fr/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/fr/aspose.slides.charts/iaxis/actual_max_value/) | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_min_value`](/slides/python-net/fr/aspose.slides.charts/iaxis/actual_min_value/) | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_major_unit`](/slides/python-net/fr/aspose.slides.charts/iaxis/actual_major_unit/) | Spécifie l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_minor_unit`](/slides/python-net/fr/aspose.slides.charts/iaxis/actual_minor_unit/) | Spécifie l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_major_unit_scale`](/slides/python-net/fr/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Spécifie l'échelle de l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`actual_minor_unit_scale`](/slides/python-net/fr/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Spécifie l'échelle de l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [`is_automatic_max_value`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_automatic_max_value/) | Indique si la valeur maximale est assignée automatiquement.<br/>             Lecture/écriture **bool**. |
| [`max_value`](/slides/python-net/fr/aspose.slides.charts/iaxis/max_value/) | Représente la valeur maximale sur l'axe de valeurs.<br/>             Lecture/écriture **float**. |
| [`minor_unit`](/slides/python-net/fr/aspose.slides.charts/iaxis/minor_unit/) | Représente les unités mineures pour l'axe de date ou de valeur.<br/>             Lecture/écriture **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Indique si l'unité mineure de l'axe est assignée automatiquement.<br/>             Lecture/écriture **bool**. |
| [`major_unit`](/slides/python-net/fr/aspose.slides.charts/iaxis/major_unit/) | Représente les unités majeures pour l'axe de date ou de valeur.<br/>             Lecture/écriture **float**. |
| [`is_automatic_major_unit`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Indique si l'unité majeure de l'axe est assignée automatiquement.<br/>            Lecture/écriture **bool**. |
| [`is_automatic_min_value`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_automatic_min_value/) | Indique si la valeur minimale est assignée automatiquement.<br/>             Lecture/écriture **bool**. |
| [`min_value`](/slides/python-net/fr/aspose.slides.charts/iaxis/min_value/) | Représente la valeur minimale sur l'axe de valeurs.<br/>             Lecture/écriture **float**. |
| [`is_logarithmic`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_logarithmic/) | Représente si le type d'échelle de l'axe de valeurs est logarithmique ou non.<br/>             Lecture/écriture **bool**. |
| [`log_base`](/slides/python-net/fr/aspose.slides.charts/iaxis/log_base/) | Représente la base logarithmique. La valeur par défaut est 10.<br/>             Lecture/écriture **float**. |
| [`is_plot_order_reversed`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Représente si MS PowerPoint trace les points de données du dernier au premier.<br/>             Lecture/écriture **bool**. |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_visible/) | Représente si l'axe est visible.<br/>             Lecture/écriture **bool**. |
| [`major_tick_mark`](/slides/python-net/fr/aspose.slides.charts/iaxis/major_tick_mark/) | Représente le type de repère majeur pour l'axe spécifié.<br/>             Lecture/écriture [`TickMarkType`](/slides/python-net/fr/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/fr/aspose.slides.charts/iaxis/minor_tick_mark/) | Représente le type de repère mineur pour l'axe spécifié.<br/>             Lecture/écriture [`TickMarkType`](/slides/python-net/fr/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/fr/aspose.slides.charts/iaxis/tick_label_position/) | Représente la position des libellés de repères sur l'axe spécifié.<br/>             Lecture/écriture [`TickLabelPositionType`](/slides/python-net/fr/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/fr/aspose.slides.charts/iaxis/major_unit_scale/) | Représente l'échelle de l'unité majeure pour l'axe de date.<br/>             Lecture/écriture [`TimeUnitType`](/slides/python-net/fr/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/fr/aspose.slides.charts/iaxis/minor_unit_scale/) | Représente l'échelle de l'unité majeure pour l'axe de date.<br/>             Lecture/écriture [`TimeUnitType`](/slides/python-net/fr/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/fr/aspose.slides.charts/iaxis/base_unit_scale/) | Spécifie la plus petite unité de temps représentée sur l'axe de date.<br/>            Lecture/écriture [`TimeUnitType`](/slides/python-net/fr/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/fr/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Représente le format des lignes de grille mineures sur un axe de graphique.<br/>             Lecture seule [`IChartLinesFormat`](/slides/python-net/fr/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/fr/aspose.slides.charts/iaxis/major_grid_lines_format/) | Représente le format des lignes de grille majeures sur un axe de graphique.<br/>             Lecture seule [`IChartLinesFormat`](/slides/python-net/fr/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/fr/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Indique si les lignes de grille mineures sont affichées.<br/>             Lecture seule **bool**. |
| [`show_major_grid_lines`](/slides/python-net/fr/aspose.slides.charts/iaxis/show_major_grid_lines/) | Indique si les lignes de grille majeures sont affichées.<br/>             Lecture seule **bool**. |
| [`format`](/slides/python-net/fr/aspose.slides.charts/iaxis/format/) | Représente le format de l'axe.<br/>             Lecture seule [`IAxisFormat`](/slides/python-net/fr/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/fr/aspose.slides.charts/iaxis/title/) | Obtient le titre de l'axe.<br/>             Lecture seule [`IChartTitle`](/slides/python-net/fr/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/fr/aspose.slides.charts/iaxis/cross_type/) | Représente le CrossType sur l'axe spécifié où l'autre axe le croise.<br/>             Lecture/écriture [`CrossesType`](/slides/python-net/fr/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/fr/aspose.slides.charts/iaxis/position/) | Représente la position de l'axe.<br/>             Lecture/écriture [`AxisPositionType`](/slides/python-net/fr/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/fr/aspose.slides.charts/iaxis/has_title/) | Détermine si un axe possède un titre visible.<br/>            Lecture/écriture **bool**. |
| [`number_format`](/slides/python-net/fr/aspose.slides.charts/iaxis/number_format/) | Représente la chaîne de format pour les libellés d'axe.<br/>            Lecture/écriture **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Indique si le format est lié aux données sources.<br/>            Lecture/écriture **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/fr/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Représente l'angle de rotation des libellés de repères<br/>            Lecture/écriture **float**. |
| [`tick_label_spacing`](/slides/python-net/fr/aspose.slides.charts/iaxis/tick_label_spacing/) | Spécifie le nombre de libellés de repères à ignorer entre les libellés dessinés.<br/>            Lecture/écriture **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Spécifie la valeur d'espacement automatique des libellés de repères. Si false : utilisez la propriété TickLabelSpacing.<br/>            Lecture/écriture **bool**. |
| [`tick_marks_spacing`](/slides/python-net/fr/aspose.slides.charts/iaxis/tick_marks_spacing/) | Spécifie le nombre de repères à sauter avant que le suivant soit <br/>            dessiné. Applicable aux axes de catégorie ou de série.<br/>            Lecture/écriture **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Spécifie la valeur d'espacement automatique des repères. Si false : utilisez la propriété TickMarksSpacing.<br/>            Lecture/écriture **bool**. |
| [`label_offset`](/slides/python-net/fr/aspose.slides.charts/iaxis/label_offset/) | Spécifie la distance des libellés par rapport à l'axe. Applicable aux axes de catégorie ou de date. La valeur doit être comprise entre 0% et 1000%.<br/>            Lecture/écriture **int**. |
| [`category_axis_type`](/slides/python-net/fr/aspose.slides.charts/iaxis/category_axis_type/) | Spécifie le type de l'axe de catégorie.<br/>            Lecture/écriture [`IAxis.category_axis_type`](/slides/python-net/fr/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/fr/aspose.slides.charts/iaxis/aggregation_type/) | Représente le type d'agrégation de l'axe de catégorie (binning). Applicable à la catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [`bin_width`](/slides/python-net/fr/aspose.slides.charts/iaxis/bin_width/) | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth.<br/>            Applicable aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [`number_of_bins`](/slides/python-net/fr/aspose.slides.charts/iaxis/number_of_bins/) | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins.<br/>            Applicable aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [`is_overflow_bin`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_overflow_bin/) | Spécifie si le bin de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de dépassement. |
| [`is_automatic_overflow_bin`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Spécifie la valeur automatique du bin de dépassement. Si false : utilisez la propriété OverflowBin. |
| [`overflow_bin`](/slides/python-net/fr/aspose.slides.charts/iaxis/overflow_bin/) | Spécifie la valeur personnalisée du bin de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin est vraie. |
| [`is_underflow_bin`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_underflow_bin/) | Spécifie si le bin de sous-flux est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-flux. |
| [`is_automatic_underflow_bin`](/slides/python-net/fr/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Spécifie la valeur automatique du bin de sous-flux. Si false : utilisez la propriété UnderflowBin. |
| [`underflow_bin`](/slides/python-net/fr/aspose.slides.charts/iaxis/underflow_bin/) | Spécifie la valeur personnalisée du bin de sous-flux. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin est vraie. |
| [`text_format`](/slides/python-net/fr/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/iaxis/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/fr/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement en fonction des données de l'axe. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)