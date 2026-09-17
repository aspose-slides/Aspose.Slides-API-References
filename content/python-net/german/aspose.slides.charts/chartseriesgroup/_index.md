---
title: ChartSeriesGroup class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup Klasse

Stellt eine Gruppe von Reihen dar.

Der Typ ChartSeriesGroup stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`type`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/type/) | Gibt den Typ dieser Seriengruppe zurück.<br/>            Nur-Lesen [`CombinableSeriesTypesGroup`](/slides/python-net/de/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Zeigt an, ob die Reihen dieser Gruppe auf einer sekundären Achse dargestellt werden.<br/>            Nur-Lesen **bool**. |
| [`series`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/series/) | Gibt eine Sammlung von Reihen zurück.<br/>            Nur-Lesen [`IChartSeriesReadonlyCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Stellt Zugriff auf Auf/Ab-Balken von Linien- oder Aktien-Diagrammen bereit.<br/>            Nur-Lesen [`IUpDownBarsManager`](/slides/python-net/de/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/gap_width/) | Gibt den Abstand zwischen Balken- oder Säulen-Cluster an, als Prozentsatz der Balken- oder Säulenbreite.<br/>            Lese/Schreiben **int**. |
| [`gap_depth`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/gap_depth/) | Gibt die Distanz zurück oder legt sie fest, als Prozentsatz der Markierungsbreite, zwischen den Datenreihen in einem 3D-Diagramm.<br/>            Lese/Schreiben **int**. |
| [`first_slice_angle`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Liefert oder legt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments fest, <br/>            in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad).<br/>            Lese/Schreiben **int**. |
| [`doughnut_hole_size`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 Prozent <br/>            der Größe des Zeichenbereichs liegen).<br/>            Lese/Schreiben **int**. |
| [`overlap`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/overlap/) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %).<br/>             - -100 %: Maximale Abstände (Balken sind vollständig getrennt).<br/>             - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.<br/>             - 100 %: Maximale Überlappung (Balken überlappen vollständig).<br/>             Diese Eigenschaft ist Lese/Schreiben **int**. |
| [`second_pie_size`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Gibt die Größe des zweiten Kuchens oder Balkens eines Kreis-im-Kreis-Diagramms oder <br/>            eines Balken-im-Kreis-Diagramms an, als Prozentsatz der Größe des ersten Kuchens (kann <br/>            zwischen 5 und 200 Prozent liegen).<br/>            Lese/Schreiben **int**. |
| [`bubble_size_representation`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Gibt an, wie die Bubble-Größenwerte im Blasendiagramm dargestellt werden.<br/>            Lese/Schreiben [`BubbleSizeRepresentationType`](/slides/python-net/de/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte <br/>            im zweiten Kuchen oder Balken eines Kreis-im-Kreis- oder Balken-im-Kreis-Diagramms liegen. <br/>            Wird zusammen mit der Eigenschaft PieSplitBy verwendet.<br/>            Lese/Schreiben **float**. |
| [`pie_split_by`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken <br/>            eines Kreis-im-Kreis- oder Balken-im-Kreis-Diagramms liegen.<br/>            Lese/Schreiben [`PieSplitType`](/slides/python-net/de/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Gibt an, dass jeder Datenmarker in der Reihe eine andere Farbe hat.<br/>            Lese/Schreiben **bool**. |
| [`has_series_lines`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Wahr, wenn das Diagramm Reihenlinien hat. Wird auf gruppierte Balken- und OfPie-Diagramme angewendet.<br/>            Lese/Schreiben **bool**. |
| [`hi_low_lines_format`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Gibt das HiLowLines-Format an. <br/>            HiLowLines werden zusammen mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet. |
| [`bubble_size_scale`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann <br/>            zwischen 0 und 300 Prozent der Standardgröße liegen).<br/>            Lese/Schreiben **int**. |
| [`pie_split_custom_points`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Die benutzerdefinierte Aufteilungsinformation für ein Kreis-im-Kreis- oder Balken-im-Kreis-Diagramm mit benutzerdefinierter Aufteilung.<br/>            Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Kreis-im-Kreis- oder <br/>            Balken-im-Kreis-Diagramms gezeichnet werden sollen.<br/>            Nur-Lesen [`PieSplitCustomPointCollection`](/slides/python-net/de/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/chart/) | Gibt das übergeordnete Diagramm zurück.<br/>            Nur-Lesen [`IChart`](/slides/python-net/de/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Gibt das Element am angegebenen Index zurück.

## Indexer

| Name | Beschreibung |
| :- | :- |
| [`[index]`](/slides/python-net/de/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen für die Klasse ChartSeriesGroupCollection und das Enum CombinableSeriesTypesGroup.
            2) Eine Gruppe von Reihen enthält einige Reihen-Eigenschaften, die für 
            jede Reihe in der Gruppe gemeinsam sind („series group properties“).
            „Series group properties“ in der Klasse ChartSeriesGroup ist Lese/Schreiben.
            Jede der „series group properties“ kann in der Klasse ChartSeries eine nur-Lese-Projektions-Version haben.

### Siehe Auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)