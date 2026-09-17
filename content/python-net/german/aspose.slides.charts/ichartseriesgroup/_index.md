---
title: IChartSeriesGroup class
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup Klasse

Stellt eine Gruppe von Serien dar.

Der Typ IChartSeriesGroup stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/type/) | Gibt einen Typ dieser Seriengruppe zurück.<br/>            Nur-Lesen [`CombinableSeriesTypesGroup`](/slides/python-net/de/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Gibt an, ob die Serien dieser Gruppe auf der sekundären Achse geplottet werden.<br/>            Nur-Lesen **bool**. |
| [`series`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/series/) | Gibt eine schreibgeschützte Sammlung von Diagrammserien zurück.<br/>            Nur-Lesen [`IChartSeriesReadonlyCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Stellt Zugriff auf Auf-/Ab-Balken von Linien- oder Aktien-Diagrammen bereit.<br/>            Nur-Lesen [`IUpDownBarsManager`](/slides/python-net/de/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/gap_width/) | Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an.<br/>            Lese/Schreib **int**. |
| [`gap_depth`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Gibt den Abstand als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt ihn fest.<br/>            Lese/Schreib **int**. |
| [`first_slice_angle`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Liest oder setzt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments, <br/>            in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad).<br/>            Lese/Schreib **int**. |
| [`is_color_varied`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat.<br/>            Lese/Schreib **bool**. |
| [`has_series_lines`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | True, wenn das Diagramm Serienlinien hat. Wird bei gestapelten Balken- und OfPie-Diagrammen angewendet.<br/>            Lese/Schreib **bool**. |
| [`overlap`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/overlap/) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %).<br/>             - -100%: Maximaler Abstand (Balken sind vollständig getrennt).<br/>             - 0%: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.<br/>             - 100%: Maximale Überlappung (Balken überlappen sich vollständig).<br/>             Diese Eigenschaft ist Lese/Schreib **int**. |
| [`second_pie_size`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder <br/>            eines Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann <br/>            zwischen 5 und 200 % liegen).<br/>            Lese/Schreib **int**. |
| [`pie_split_position`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte <br/>            sich im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms befinden. <br/>            Wird zusammen mit der PieSplitBy-Eigenschaft verwendet.<br/>            Lese/Schreib **float**. |
| [`pie_split_by`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken <br/>            eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen.<br/>            Lese/Schreib [`PieSplitType`](/slides/python-net/de/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Die benutzerdefinierten Teilungsinformationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefinierter Teilung.<br/>            Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- oder <br/>            Bar-of-Pie-Diagramms gezeichnet werden sollen.<br/>            Nur-Lesen [`IPieSplitCustomPointCollection`](/slides/python-net/de/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 und 90 % der Größe des Plot-Bereichs liegen).<br/>            Lese/Schreib **int**. |
| [`bubble_size_scale`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann <br/>            zwischen 0 und 300 % der Standardgröße liegen).<br/>            Lese/Schreib **int**. |
| [`hi_low_lines_format`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Gibt das HiLowLines-Format an. <br/>            HiLowLines werden mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose angewendet. |
| [`bubble_size_representation`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Gibt an, wie die Bubble-Größenwerte im Blasendiagramm dargestellt werden.<br/>            Lese/Schreib [`BubbleSizeRepresentationType`](/slides/python-net/de/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Gibt das Element am angegebenen Index zurück.

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen für die Klasse ChartSeriesGroupCollection und das Enum CombinableSeriesTypesGroup.  
2) Die Gruppe von Serien enthält einige Serien-Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Series group properties“).  
   „Series group properties“ in der Klasse ChartSeriesGroup ist Lese/Schreib.  
   Jede der „Series group properties“ kann eine Nur-Lese-Projection in der Klasse ChartSeries haben.

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)