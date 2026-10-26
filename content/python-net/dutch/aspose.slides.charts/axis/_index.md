---
title: Axis class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/axis/
---
## Axis klasse

Omvat het object dat de as van een diagram vertegenwoordigt.

Het Axis-type geeft de volgende leden weer:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/axis/chart/) | Retourneert het bovenliggende diagram.<br/>            Alleen-lezen [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/nl/aspose.slides.charts/axis/axis_between_categories/) | Geeft aan of de waardenas de categorieas tussen categorieën kruist.<br/>             Deze eigenschap is alleen van toepassing op categorieassen, en is niet van toepassing op 3D-diagrammen.<br/>             Lezen/schrijven **bool**. |
| [`category_axis_type`](/slides/python-net/nl/aspose.slides.charts/axis/category_axis_type/) | Specificeert het type van de categorieas.<br/>            Lezen/schrijven [`CategoryAxisType`](/slides/python-net/nl/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/nl/aspose.slides.charts/axis/cross_at/) | Geeft het punt op de as weer waar de loodrechte as deze kruist.<br/>             Lezen/schrijven **float**. |
| [`display_unit`](/slides/python-net/nl/aspose.slides.charts/axis/display_unit/) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas.<br/>             Lezen/schrijven [`DisplayUnitType`](/slides/python-net/nl/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/nl/aspose.slides.charts/axis/actual_max_value/) | Specificeert de daadwerkelijke maximale waarde op de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen. |
| [`actual_min_value`](/slides/python-net/nl/aspose.slides.charts/axis/actual_min_value/) | Specificeert de daadwerkelijke minimumwaarde op de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen. |
| [`actual_major_unit`](/slides/python-net/nl/aspose.slides.charts/axis/actual_major_unit/) | Specificeert de daadwerkelijke hoofd-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen. |
| [`actual_minor_unit`](/slides/python-net/nl/aspose.slides.charts/axis/actual_minor_unit/) | Specificeert de daadwerkelijke ondereenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen. |
| [`actual_major_unit_scale`](/slides/python-net/nl/aspose.slides.charts/axis/actual_major_unit_scale/) | Specificeert de daadwerkelijke schaal van de hoofd-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen. |
| [`actual_minor_unit_scale`](/slides/python-net/nl/aspose.slides.charts/axis/actual_minor_unit_scale/) | Specificeert de daadwerkelijke schaal van de ondereenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te krijgen. |
| [`is_automatic_max_value`](/slides/python-net/nl/aspose.slides.charts/axis/is_automatic_max_value/) | Geeft aan of de maximale waarde automatisch wordt toegewezen.<br/>             Lezen/schrijven **bool**. |
| [`max_value`](/slides/python-net/nl/aspose.slides.charts/axis/max_value/) | Geeft de maximale waarde op de waardenas weer.<br/>             Lezen/schrijven **float**. |
| [`minor_unit`](/slides/python-net/nl/aspose.slides.charts/axis/minor_unit/) | Geeft de ondereenheden voor de datum- of waardenas weer.<br/>             Lezen/schrijven **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/nl/aspose.slides.charts/axis/is_automatic_minor_unit/) | Geeft aan of de ondereenheid van de as automatisch wordt toegewezen.<br/>             Lezen/schrijven **bool**. |
| [`major_unit`](/slides/python-net/nl/aspose.slides.charts/axis/major_unit/) | Geeft de hoofd-eenheden voor de datum- of waardenas weer.<br/>             Lezen/schrijven **float**. |
| [`is_automatic_major_unit`](/slides/python-net/nl/aspose.slides.charts/axis/is_automatic_major_unit/) | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen.<br/>            Lezen/schrijven **bool**. |
| [`is_automatic_min_value`](/slides/python-net/nl/aspose.slides.charts/axis/is_automatic_min_value/) | Geeft aan of de minimumwaarde automatisch wordt toegewezen.<br/>             Lezen/schrijven **bool**. |
| [`min_value`](/slides/python-net/nl/aspose.slides.charts/axis/min_value/) | Geeft de minimumwaarde op de waardenas weer.<br/>             Lezen/schrijven **float**. |
| [`is_logarithmic`](/slides/python-net/nl/aspose.slides.charts/axis/is_logarithmic/) | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet.<br/>             Lezen/schrijven **bool**. |
| [`log_base`](/slides/python-net/nl/aspose.slides.charts/axis/log_base/) | Geeft de logaritmische basis weer. Standaardwaarde is 10.<br/>             Lezen/schrijven **float**. |
| [`is_plot_order_reversed`](/slides/python-net/nl/aspose.slides.charts/axis/is_plot_order_reversed/) | Geeft aan of MS PowerPoint gegevenspunten van laatst naar eerst plot.<br/>             Lezen/schrijven **bool**. |
| [`is_visible`](/slides/python-net/nl/aspose.slides.charts/axis/is_visible/) | Geeft aan of de as zichtbaar is.<br/>             Lezen/schrijven **bool**. |
| [`major_tick_mark`](/slides/python-net/nl/aspose.slides.charts/axis/major_tick_mark/) | Geeft het type van de hoofd-ticmarkering voor de opgegeven as weer.<br/>             Lezen/schrijven [`TickMarkType`](/slides/python-net/nl/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/nl/aspose.slides.charts/axis/minor_tick_mark/) | Geeft het type van de onder-ticmarkering voor de opgegeven as weer.<br/>             Lezen/schrijven [`TickMarkType`](/slides/python-net/nl/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/nl/aspose.slides.charts/axis/tick_label_position/) | Geeft de positie van tic-labelmarkeringen op de opgegeven as weer.<br/>             Lezen/schrijving [`TickLabelPositionType`](/slides/python-net/nl/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/nl/aspose.slides.charts/axis/major_unit_scale/) | Geeft de schaal van de hoofd-eenheid voor de datumas weer.<br/>             Lezen/schrijven [`TimeUnitType`](/slides/python-net/nl/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/nl/aspose.slides.charts/axis/minor_unit_scale/) | Geeft de schaal van de hoofd-eenheid voor de datumas weer.<br/>             Lezen/schrijven [`TimeUnitType`](/slides/python-net/nl/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/nl/aspose.slides.charts/axis/base_unit_scale/) | Specificeert de kleinste tijdseenheid die op de datumas wordt weergegeven.<br/>            Lezen/schrijven [`TimeUnitType`](/slides/python-net/nl/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/nl/aspose.slides.charts/axis/minor_grid_lines_format/) | Geeft het formaat van de onder-gridlines op een diagramas weer.<br/>             Alleen-lezen [`IChartLinesFormat`](/slides/python-net/nl/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/nl/aspose.slides.charts/axis/major_grid_lines_format/) | Geeft het formaat van de hoofd-gridlines op een diagramas weer.<br/>             Alleen-lezen [`IChartLinesFormat`](/slides/python-net/nl/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/nl/aspose.slides.charts/axis/show_minor_grid_lines/) | Om onder-gridline te verbergen, stel MinorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill.<br/>            Alleen-lezen **bool**. |
| [`show_major_grid_lines`](/slides/python-net/nl/aspose.slides.charts/axis/show_major_grid_lines/) | Om hoofd-gridline te verbergen, stel MajorGridLinesFormat.Line.FillFormat.FillType in op FillType.NoFill.<br/>            Alleen-lezen **bool**. |
| [`format`](/slides/python-net/nl/aspose.slides.charts/axis/format/) | Geeft het formaat van de as weer.<br/>             Alleen-lezen [`IAxisFormat`](/slides/python-net/nl/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/nl/aspose.slides.charts/axis/text_format/) | Geeft het formaat van tekst weer.<br/>             Alleen-lezen [`IChartTextFormat`](/slides/python-net/nl/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/nl/aspose.slides.charts/axis/title/) | Haalt de titel van de as op.<br/>             Alleen-lezen [`IChartTitle`](/slides/python-net/nl/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/nl/aspose.slides.charts/axis/cross_type/) | Geeft het CrossType op de opgegeven as weer waar de andere as kruist.<br/>             Lezen/schrijven [`CrossesType`](/slides/python-net/nl/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/nl/aspose.slides.charts/axis/position/) | Geeft de positie van de as weer.<br/>             Lezen/schrijven [`AxisPositionType`](/slides/python-net/nl/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/nl/aspose.slides.charts/axis/has_title/) | Bepaalt of een as een zichtbare titel heeft.<br/>            Lezen/schrijven **bool**. |
| [`number_format`](/slides/python-net/nl/aspose.slides.charts/axis/number_format/) | Geeft de notatie-reeks voor de as-labels weer.<br/>            Lezen/schrijven **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/nl/aspose.slides.charts/axis/is_number_format_linked_to_source/) | Geeft aan of het formaat gekoppeld is aan brongegevens.<br/>            Lezen/schrijven **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/nl/aspose.slides.charts/axis/tick_label_rotation_angle/) | Geeft de rotatiehoek van tic-labels weer.<br/>            Lezen/schrijven **float**. |
| [`tick_label_spacing`](/slides/python-net/nl/aspose.slides.charts/axis/tick_label_spacing/) | Specificeert hoeveel tic-labels overgeslagen moeten worden tussen getekende labels. Toegepast op categorie- of series-as.<br/>            Lezen/schrijven **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/nl/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | Specificeert de automatische afstand tussen tic-labels. Indien false: gebruik de eigenschap TickLabelSpacing.<br/>            Lezen/schrijven **bool**. |
| [`tick_marks_spacing`](/slides/python-net/nl/aspose.slides.charts/axis/tick_marks_spacing/) | Specificeert hoeveel tic-markeringen overgeslagen moeten worden voordat de volgende getekend wordt. Toegepast op categorie- of series-as.<br/>            Lezen/schrijven **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/nl/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | Specificeert de automatische afstand tussen tic-markeringen. Indien false: gebruik de eigenschap TickMarksSpacing.<br/>            Lezen/schrijven **bool**. |
| [`label_offset`](/slides/python-net/nl/aspose.slides.charts/axis/label_offset/) | Specificeert de afstand van labels tot de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen.<br/>            Lezen/schrijven **int**. |
| [`aggregation_type`](/slides/python-net/nl/aspose.slides.charts/axis/aggregation_type/) | Geeft het aggregatietype van de categorieas weer (binning). Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [`bin_width`](/slides/python-net/nl/aspose.slides.charts/axis/bin_width/) | Specificeert de bin-breedte wanneer de eigenschap AggregationType is ingesteld op AxisAggregationType.ByBinWidth.<br/>            Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [`number_of_bins`](/slides/python-net/nl/aspose.slides.charts/axis/number_of_bins/) | Specificeert het aantal bins wanneer de eigenschap AggregationType is ingesteld op AxisAggregationType.ByNumberOfBins.<br/>            Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [`is_overflow_bin`](/slides/python-net/nl/aspose.slides.charts/axis/is_overflow_bin/) | Specificeert of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-binwaarde aan te passen. |
| [`is_automatic_overflow_bin`](/slides/python-net/nl/aspose.slides.charts/axis/is_automatic_overflow_bin/) | Specificeert de automatische overflow-binwaarde. Indien false: gebruik de eigenschap OverflowBin. |
| [`overflow_bin`](/slides/python-net/nl/aspose.slides.charts/axis/overflow_bin/) | Specificeert een aangepaste overflow-binwaarde. Toegepast wanneer de eigenschap IsAutomaticOverflowBin false is en IsOverflowBin true is. |
| [`is_underflow_bin`](/slides/python-net/nl/aspose.slides.charts/axis/is_underflow_bin/) | Specificeert of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-binwaarde aan te passen. |
| [`is_automatic_underflow_bin`](/slides/python-net/nl/aspose.slides.charts/axis/is_automatic_underflow_bin/) | Specificeert de automatische underflow-binwaarde. Indien false: gebruik de eigenschap UnderflowBin. |
| [`underflow_bin`](/slides/python-net/nl/aspose.slides.charts/axis/underflow_bin/) | Specificeert een aangepaste underflow-binwaarde. Toegepast wanneer de eigenschap IsAutomaticUnderflowBin false is en IsUnderflowBin true is. |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/axis/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/nl/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | Stelt de eigenschap IAxis.CategoryAxisType in met een waarde die automatisch wordt bepaald op basis van as-gegevens. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)