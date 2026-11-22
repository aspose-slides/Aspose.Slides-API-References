---
title: ChartSeriesGroup class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup Klasse

Stellt eine Gruppe von Serien dar.

Der ChartSeriesGroup-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`type`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/type/) | Gibt einen Typ dieser Seriengruppe zurück.<br/>            Nur lesbar [`CombinableSeriesTypesGroup`](/slides/python-net/de/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Gibt an, ob die Serien dieser Gruppe auf einer sekundären Achse dargestellt werden.<br/>            Nur lesbar **bool**. |
| [`series`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/series/) | Gibt eine Sammlung von Serien zurück.<br/>            Nur lesbar [`IChartSeriesReadonlyCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Stellt Zugriff auf Auf-/Ab-Balken von Line- oder Stock-Chart bereit.<br/>            Nur lesbar [`IUpDownBarsManager`](/slides/python-net/de/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/gap_width/) | Liest oder setzt den Abstand zwischen Balken- oder Spalten-Clustern als Prozentsatz der Balken- oder Spaltenbreite.<br/>            Der Wert muss zwischen 0 und 500 liegen.<br/>            Lese/Schreib **int**. |
| [`gap_depth`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/gap_depth/) | Liest oder setzt den Abstand zwischen Datenreihen in einem 3D-Diagramm als Prozentsatz der Markierungsbreite.<br/>            Der Wert muss zwischen 0 und 500 liegen.<br/>            Lese/Schreib **int**. |
| [`first_slice_angle`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Liest oder setzt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments,<br/>            in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad).<br/>            Lese/Schreib **int**. |
| [`doughnut_hole_size`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 Prozent der Größe des Darstellungsbereichs liegen).<br/>            Lese/Schreib **int**. |
| [`overlap`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/overlap/) | Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %).<br/>             - -100 %: Maximale Abstand (Balken sind vollständig getrennt).<br/>             - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.<br/>             - 100 %: Maximale Überlappung (Balken überlappen vollständig).<br/>             Diese Eigenschaft ist Lese/Schreib **int**. |
| [`second_pie_size`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder<br/>            eines Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann<br/>            zwischen 5 und 200 Prozent liegen).<br/>            Lese/Schreib **int**. |
| [`bubble_size_representation`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden.<br/>            Lese/Schreib [`BubbleSizeRepresentationType`](/slides/python-net/de/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte<br/>            im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen.<br/>            Wird zusammen mit der Eigenschaft PieSplitBy verwendet.<br/>            Lese/Schreib **float**. |
| [`pie_split_by`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken<br/>            eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen.<br/>            Lese/Schreib [`PieSplitType`](/slides/python-net/de/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat.<br/>            Lese/Schreib **bool**. |
| [`has_series_lines`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Wahr, wenn das Diagramm Serienlinien hat. Wird auf gestapelte Balken- und OfPie-Diagramme angewendet.<br/>            Lese/Schreib **bool**. |
| [`hi_low_lines_format`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Gibt das Format von HiLowLines an.<br/>            HiLowLines wird bei den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet. |
| [`bubble_size_scale`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen).<br/>            Lese/Schreib **int**. |
| [`pie_split_custom_points`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefiniertem Split.<br/>            Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- oder<br/>            Bar-of-Pie-Diagramms gezeichnet werden sollen.<br/>            Nur lesbar [`PieSplitCustomPointCollection`](/slides/python-net/de/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/chart/) | Gibt das übergeordnete Diagramm zurück.<br/>            Nur lesbar [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Ruft das Element am angegebenen Index ab.

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen für die Klasse ChartSeriesGroupCollection und das Enum CombinableSeriesTypesGroup.  
2) Die Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind („series group properties“).  
„Series group properties“ in der Klasse ChartSeriesGroup ist Lese/Schreib.  
Jede „series group properties“ kann in der Klasse ChartSeries eine Nur-lesbar-Projection haben.

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)