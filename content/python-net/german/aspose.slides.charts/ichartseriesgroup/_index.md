---
title: IChartSeriesGroup class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup Klasse

Stellt eine Gruppe von Serien dar.

Der Typ IChartSeriesGroup stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`type`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/type/) | Gibt den Typ dieser Seriengruppe zurück.<br/>            Nur lesbar [`CombinableSeriesTypesGroup`](/slides/python-net/de/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Gibt an, ob die Serien dieser Gruppe auf einer sekundären Achse geplottet werden.<br/>            Nur lesbar **bool**. |
| [`series`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/series/) | Gibt eine schreibgeschützte Sammlung von Diagrammserien zurück.<br/>            Nur lesbar [`IChartSeriesReadonlyCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Stellt Zugriff auf Auf-/Ab-Balken von Linien- oder Kurs-Diagrammen bereit.<br/>            Nur lesbar [`IUpDownBarsManager`](/slides/python-net/de/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/gap_width/) | Liest oder schreibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- bzw. Säulenbreite.<br/>            Der Wert muss zwischen 0 und 500 liegen.<br/>            Lesen/Schreiben **int**. |
| [`gap_depth`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Liest oder schreibt den Abstand zwischen Datenserien in einem 3D-Diagramm als Prozentsatz der Markierungsbreite.<br/>            Der Wert muss zwischen 0 und 500 liegen.<br/>            Lesen/Schreiben **int**. |
| [`first_slice_angle`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Liest oder schreibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad).<br/>            Lesen/Schreiben **int**. |
| [`is_color_varied`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat.<br/>            Lesen/Schreiben **bool**. |
| [`has_series_lines`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Wahr, wenn das Diagramm Serienlinien hat. Wird bei gestapelten Balken- und OfPie-Diagrammen angewendet.<br/>            Lesen/Schreiben **bool**. |
| [`overlap`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/overlap/) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %).<br/>             - -100 %: Maximaler Abstand (Balken sind vollständig getrennt).<br/>             - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert.<br/>             - 100 %: Maximale Überlappung (Balken überlappen einander vollständig).<br/>             Diese Eigenschaft ist Lesen/Schreiben **int**. |
| [`second_pie_size`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-von-Kuchen-Diagramms bzw. eines Balken-von-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen).<br/>            Lesen/Schreiben **int**. |
| [`pie_split_position`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Gibt einen Wert an, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-von-Kuchen- oder Balken-von-Kuchen-Diagramms liegen.<br/>            Wird zusammen mit der Eigenschaft PieSplitBy verwendet.<br/>            Lesen/Schreiben **float**. |
| [`pie_split_by`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-von-Kuchen- oder Balken-von-Kuchen-Diagramms liegen.<br/>            Lesen/Schreiben [`PieSplitType`](/slides/python-net/de/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Die benutzerdefinierten Split-Informationen für ein Kuchen-von-Kuchen- oder Balken-von-Kuchen-Diagramm mit benutzerdefiniertem Split.<br/>            Enthält Datenpunkte, die im zweiten Kuchen bzw. Balken gezeichnet werden sollen.<br/>            Nur lesbar [`IPieSplitCustomPointCollection`](/slides/python-net/de/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Größe des Zeichenbereichs liegen).<br/>            Lesen/Schreiben **int**. |
| [`bubble_size_scale`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen).<br/>            Lesen/Schreiben **int**. |
| [`hi_low_lines_format`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Gibt das Format von HiLowLines an.<br/>            HiLowLines werden mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet. |
| [`bubble_size_representation`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden.<br/>            Lesen/Schreiben [`BubbleSizeRepresentationType`](/slides/python-net/de/aspose.slides.charts/bubblesizerepresentationtype). |
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
2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Seriengruppen-Eigenschaften“).  
   „Seriengruppen-Eigenschaften“ in der Klasse ChartSeriesGroup ist Lesen/Schreiben.  
   Jede der „Seriengruppen-Eigenschaften“ kann in der Klasse ChartSeries eine schreibgeschützte Projektion besitzen.

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)