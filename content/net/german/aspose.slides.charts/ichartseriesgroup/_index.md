---
title: IChartSeriesGroup
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt eine Gruppe von Reihen dar.
type: docs
weight: 1970
url: /de/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup Schnittstelle

Stellt eine Gruppe von Reihen dar.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Ermöglicht das Abrufen der Basis-IChartComponent-Schnittstelle. Nur-Lesen [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. Lese/Schreib [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). Lese/Schreib Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 und 90 Prozent der Größe des Plotbereichs liegen). Lese/Schreib Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Liest oder setzt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese/Schreib UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Liest oder setzt den Abstand zwischen Datenreihen in einem 3D-Diagramm als Prozentsatz der Markierungsbreite. Der Wert muss zwischen 0 und 500 liegen. Lese/Schreib UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Liest oder setzt den Abstand zwischen Balken- oder Säulengruppen als Prozentsatz der Balken- oder Säulenbreite. Der Wert muss zwischen 0 und 500 liegen. Lese/Schreib UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Wahr, wenn das Diagramm Serienlinien hat. Wird bei gestapelten Balken- und OfPie-Diagrammen angewendet. Lese/Schreib Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Gibt das HiLowLines-Format an. HiLowLines werden mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jeder Datenmarker in der Reihe eine andere Farbe hat. Lese/Schreib Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Liest das Element am angegebenen Index. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: Maximale Abstände (Balken sind vollständig getrennt). - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100 %: Maximale Überlappung (Balken überlappen vollständig). Diese Eigenschaft ist Lese/Schreib SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Lese/Schreib [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierte Teilungsinformation für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefinierter Teilung. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms gezeichnet werden sollen. Nur-Lesen [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lese/Schreib Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Zeigt an, ob die Reihen dieser Gruppe auf einer sekundären Achse dargestellt werden. Nur-Lesen Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 Prozent liegen). Lese/Schreib UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Gibt eine Nur-Lesen-Auflistung von Diagrammreihen zurück. Nur-Lesen [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Gibt den Typ dieser Reihen-Gruppe zurück. Nur-Lesen [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Stellt Zugriff auf Auf-/Ab-Balken eines Linien- oder Kurs-Diagramms bereit. Nur-Lesen [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Bemerkungen

1) Siehe Zusammenfassung und Bemerkungen für die ChartSeriesGroupCollection Klasse und das CombinableSeriesTypesGroup enum. 2) Die Gruppe von Reihen enthält einige Reihen-Eigenschaften, die für jede Reihe in der Gruppe gemeinsam sind („Series group properties“). „Series group properties“ in der ChartSeriesGroup Klasse ist Lese/Schreib. Jede „Series group properties“ kann in der ChartSeries Klasse eine Nur-Lesen-Projection haben.

### Siehe auch

* Schnittstelle [IChartComponent](../ichartcomponent)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->