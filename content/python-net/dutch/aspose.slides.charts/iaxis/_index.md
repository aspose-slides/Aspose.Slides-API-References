---
title: IAxis class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/iaxis/
---
## IAxis klasse

Omhult het object dat een as van een diagram voorstelt.

Het IAxis-type stelt de volgende leden beschikbaar:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/nl/aspose.slides.charts/iaxis/axis_between_categories/) | Geeft aan of de waardenas de categorias doorloopt tussen categorieën.<br/>            Deze eigenschap geldt alleen voor categorias, en is niet van toepassing op 3D-diagrammen.<br/>            Lezen/Schrijven **bool**. |
| [`cross_at`](/slides/python-net/nl/aspose.slides.charts/iaxis/cross_at/) | Geeft het punt op de as waar de loodrechte as deze kruist.<br/>            Lezen/Schrijven **float**. |
| [`display_unit`](/slides/python-net/nl/aspose.slides.charts/iaxis/display_unit/) | Specificeert de schaalwaarde van de weergave-eenheden voor de waardenas.<br/>            Lezen/Schrijven [`DisplayUnitType`](/slides/python-net/nl/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/nl/aspose.slides.charts/iaxis/actual_max_value/) | Specificeert de werkelijke maximale waarde op de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [`actual_min_value`](/slides/python-net/nl/aspose.slides.charts/iaxis/actual_min_value/) | Specificeert de werkelijke minimale waarde op de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [`actual_major_unit`](/slides/python-net/nl/aspose.slides.charts/iaxis/actual_major_unit/) | Specificeert de werkelijke hoofd-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [`actual_minor_unit`](/slides/python-net/nl/aspose.slides.charts/iaxis/actual_minor_unit/) | Specificeert de werkelijke subeenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [`actual_major_unit_scale`](/slides/python-net/nl/aspose.slides.charts/iaxis/actual_major_unit_scale/) | Specificeert de werkelijke schaal van de hoofd-eenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [`actual_minor_unit_scale`](/slides/python-net/nl/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | Specificeert de werkelijke schaal van de subeenheid van de as. Roep eerder de methode IChart.ValidateChartLayout() aan om de werkelijke waarde te verkrijgen. |
| [`is_automatic_max_value`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_automatic_max_value/) | Geeft aan of de maximale waarde automatisch wordt toegewezen.<br/>             Lezen/Schrijven **bool**. |
| [`max_value`](/slides/python-net/nl/aspose.slides.charts/iaxis/max_value/) | Geeft de maximale waarde op de waardenas weer.<br/>             Lezen/Schrijven **float**. |
| [`minor_unit`](/slides/python-net/nl/aspose.slides.charts/iaxis/minor_unit/) | Geeft de subeenheden voor de datum- of waardenas weer.<br/>             Lezen/Schrijven **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | Geeft aan of de subeenheid van de as automatisch wordt toegewezen.<br/>             Lezen/Schrijven **bool**. |
| [`major_unit`](/slides/python-net/nl/aspose.slides.charts/iaxis/major_unit/) | Geeft de hoofd-eenheden voor de datum- of waardenas weer.<br/>             Lezen/Schrijven **float**. |
| [`is_automatic_major_unit`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_automatic_major_unit/) | Geeft aan of de hoofd-eenheid van de as automatisch wordt toegewezen.<br/>            Lezen/Schrijven **bool**. |
| [`is_automatic_min_value`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_automatic_min_value/) | Geeft aan of de minimale waarde automatisch wordt toegewezen.<br/>             Lezen/Schrijven **bool**. |
| [`min_value`](/slides/python-net/nl/aspose.slides.charts/iaxis/min_value/) | Geeft de minimale waarde op de waardenas weer.<br/>             Lezen/Schrijven **float**. |
| [`is_logarithmic`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_logarithmic/) | Geeft aan of het schaaltype van de waardenas logaritmisch is of niet.<br/>             Lezen/Schrijven **bool**. |
| [`log_base`](/slides/python-net/nl/aspose.slides.charts/iaxis/log_base/) | Geeft de logaritmische basis weer. Standaardwaarde is 10.<br/>             Lezen/Schrijven **float**. |
| [`is_plot_order_reversed`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_plot_order_reversed/) | Geeft aan of MS PowerPoint gegevenspunten van laatste naar eerste plot.<br/>             Lezen/Schrijven **bool**. |
| [`is_visible`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_visible/) | Geeft aan of de as zichtbaar is.<br/>             Lezen/Schrijven **bool**. |
| [`major_tick_mark`](/slides/python-net/nl/aspose.slides.charts/iaxis/major_tick_mark/) | Geeft het type van de hoofd-tick-markering voor de opgegeven as weer.<br/>             Lezen/Schrijven [`TickMarkType`](/slides/python-net/nl/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/nl/aspose.slides.charts/iaxis/minor_tick_mark/) | Geeft het type van de sub-tick-markering voor de opgegeven as weer.<br/>             Lezen/Schrijven [`TickMarkType`](/slides/python-net/nl/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/nl/aspose.slides.charts/iaxis/tick_label_position/) | Geeft de positie van tick-markeringlabels op de opgegeven as weer.<br/>             Lezen/Schrijven [`TickLabelPositionType`](/slides/python-net/nl/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/nl/aspose.slides.charts/iaxis/major_unit_scale/) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer.<br/>             Lezen/Schrijven [`TimeUnitType`](/slides/python-net/nl/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/nl/aspose.slides.charts/iaxis/minor_unit_scale/) | Geeft de schaal van de hoofd-eenheid voor de datum-as weer.<br/>             Lezen/Schrijven [`TimeUnitType`](/slides/python-net/nl/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/nl/aspose.slides.charts/iaxis/base_unit_scale/) | Specificeert de kleinste tijdseenheid die op de datum-as wordt weergegeven.<br/>            Lezen/Schrijven [`TimeUnitType`](/slides/python-net/nl/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/nl/aspose.slides.charts/iaxis/minor_grid_lines_format/) | Geeft het formaat van de subrasterlijnen op een diagramas weer.<br/>             Alleen-lezen [`IChartLinesFormat`](/slides/python-net/nl/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/nl/aspose.slides.charts/iaxis/major_grid_lines_format/) | Geeft het formaat van de hoofdrasterlijnen op een diagramas weer.<br/>             Alleen-lezen [`IChartLinesFormat`](/slides/python-net/nl/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/nl/aspose.slides.charts/iaxis/show_minor_grid_lines/) | Geeft aan of de subrasterlijnen zichtbaar waren.<br/>             Alleen-lezen **bool**. |
| [`show_major_grid_lines`](/slides/python-net/nl/aspose.slides.charts/iaxis/show_major_grid_lines/) | Geeft aan of de hoofdrasterlijnen zichtbaar waren.<br/>             Alleen-lezen **bool**. |
| [`format`](/slides/python-net/nl/aspose.slides.charts/iaxis/format/) | Geeft het formaat van de as weer.<br/>             Alleen-lezen [`IAxisFormat`](/slides/python-net/nl/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/nl/aspose.slides.charts/iaxis/title/) | Haalt de titel van de as op.<br/>             Alleen-lezen [`IChartTitle`](/slides/python-net/nl/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/nl/aspose.slides.charts/iaxis/cross_type/) | Geeft het CrossType op de opgegeven as weer waar de andere as kruist.<br/>             Lezen/Schrijven [`CrossesType`](/slides/python-net/nl/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/nl/aspose.slides.charts/iaxis/position/) | Geeft de positie van de as weer.<br/>             Lezen/Schrijven [`AxisPositionType`](/slides/python-net/nl/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/nl/aspose.slides.charts/iaxis/has_title/) | Bepaalt of een as een zichtbare titel heeft.<br/>            Lezen/Schrijven **bool**. |
| [`number_format`](/slides/python-net/nl/aspose.slides.charts/iaxis/number_format/) | Geeft de opmaakreeks voor de As-labels weer.<br/>            Lezen/Schrijven **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | Geeft aan of de opmaak gekoppeld is aan brongegevens.<br/>            Lezen/Schrijven **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/nl/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | Geeft de rotatiehoek van tick-labels weer<br/>            Lezen/Schrijven **float**. |
| [`tick_label_spacing`](/slides/python-net/nl/aspose.slides.charts/iaxis/tick_label_spacing/) | Specificeert hoeveel tick-labels overgeslagen moeten worden tussen getekende labels.<br/>            Lezen/Schrijven **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | Specificeert de automatische spacing-waarde voor tick-labels. Indien false: gebruik de TickLabelSpacing-eigenschap.<br/>            Lezen/Schrijven **bool**. |
| [`tick_marks_spacing`](/slides/python-net/nl/aspose.slides.charts/iaxis/tick_marks_spacing/) | Specificeert hoeveel tick-markeringen moeten worden overgeslagen voordat de volgende wordt<br/>            getekend. Toegepast op categorie- of serie-as.<br/>            Lezen/Schrijven **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | Specificeert de automatische spacing-waarde voor tick-markeringen. Indien false: gebruik de TickMarksSpacing-eigenschap.<br/>            Lezen/Schrijven **bool**. |
| [`label_offset`](/slides/python-net/nl/aspose.slides.charts/iaxis/label_offset/) | Specificeert de afstand van labels van de as. Toegepast op categorie- of datum-as. Waarde moet tussen 0% en 1000% liggen.<br/>            Lezen/Schrijven **int**. |
| [`category_axis_type`](/slides/python-net/nl/aspose.slides.charts/iaxis/category_axis_type/) | Specificeert het type van de categorie-as.<br/>            Lezen/Schrijven [`IAxis.category_axis_type`](/slides/python-net/nl/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/nl/aspose.slides.charts/iaxis/aggregation_type/) | Geeft het aggregatietype van de categorie-as weer (binnnen). Toegepast op categorie. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [`bin_width`](/slides/python-net/nl/aspose.slides.charts/iaxis/bin_width/) | Specificeert de bin-breedte wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByBinWidth.<br/>            Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [`number_of_bins`](/slides/python-net/nl/aspose.slides.charts/iaxis/number_of_bins/) | Specificeert het aantal bins wanneer de AggregationType-eigenschap is ingesteld op AxisAggregationType.ByNumberOfBins.<br/>            Toegepast op categorie-assen. Alleen gebruikt met Histogram- of HistogramPareto-series. |
| [`is_overflow_bin`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_overflow_bin/) | Specificeert of een overflow-bin wordt toegepast. Gebruik IsAutomaticOverflowBin en OverflowBin om de overflow-bin-waarde aan te passen. |
| [`is_automatic_overflow_bin`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | Specificeert de automatische overflow-bin-waarde. Indien false: gebruik de OverflowBin-eigenschap. |
| [`overflow_bin`](/slides/python-net/nl/aspose.slides.charts/iaxis/overflow_bin/) | Specificeert een aangepaste overflow-bin-waarde. Toegepast wanneer IsAutomaticOverflowBin op false staat en IsOverflowBin true is. |
| [`is_underflow_bin`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_underflow_bin/) | Specificeert of een underflow-bin wordt toegepast. Gebruik IsAutomaticUnderflowBin en UnderflowBin om de underflow-bin-waarde aan te passen. |
| [`is_automatic_underflow_bin`](/slides/python-net/nl/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | Specificeert de automatische onderflow-bin-waarde. Indien false: gebruik de UnderflowBin-eigenschap. |
| [`underflow_bin`](/slides/python-net/nl/aspose.slides.charts/iaxis/underflow_bin/) | Specificeert een aangepaste underflow-bin-waarde. Toegepast wanneer IsAutomaticUnderflowBin op false staat en IsUnderflowBin true is. |
| [`text_format`](/slides/python-net/nl/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/nl/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides.charts/iaxis/presentation/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/nl/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | Stelt de IAxis.CategoryAxisType-eigenschap in met een waarde die automatisch wordt bepaald op basis van asgegevens. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)