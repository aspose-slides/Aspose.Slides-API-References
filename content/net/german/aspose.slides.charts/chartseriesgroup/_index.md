---
title: ChartSeriesGroup
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
weight: 1470
url: /de/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup Klasse

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Eigenschaften

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. Lese/Schreib [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). Lese/Schreib Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Nur lesen [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Donutdiagramm an (kann zwischen 0 und 90 Prozent der Größe des Plotbereichs liegen). Lese/Schreib Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Liefert oder setzt den Winkel des ersten Kuchen- oder Donutdiagrammsegments in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese/Schreib UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Liefert oder setzt den Abstand zwischen Datenreihen in einem 3D-Diagramm als Prozentsatz der Markierungsbreite. Der Wert muss zwischen 0 und 500 liegen. Lese/Schreib UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Liefert oder setzt den Abstand zwischen Balken- oder Spaltengruppen als Prozentsatz der Balken- oder Spaltenbreite. Der Wert muss zwischen 0 und 500 liegen. Lese/Schreib UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True, wenn das Diagramm Serienlinien hat. Wird auf gestapelte Balken- und OfPie-Diagramme angewendet. Lese/Schreib Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Gibt das HiLowLines-Format an. HiLowLines werden mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lese/Schreib Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Liefert das Element am angegebenen Index. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: Maximaler Abstand (Balken sind völlig getrennt). - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100 %: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist Lese/Schreib SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Gibt an, wie ermittelt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Lese/Schreib [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierte Teilungsinformation für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefinierter Teilung. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms gezeichnet werden sollen. Nur lesen [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Lese/Schreib Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Gibt an, ob die Serien dieser Gruppe auf einer Sekundärachse geplottet werden. Nur lesen Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 Prozent liegen). Lese/Schreib UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Gibt eine Sammlung von Serien zurück. Nur lesen [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Gibt den Typ dieser Seriengruppe zurück. Nur lesen [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Stellt Zugriff auf Auf-/Ab-Balken von Linien- oder Kurs-Diagrammen bereit. Nur lesen [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen für die ChartSeriesGroupCollection Klasse und das CombinableSeriesTypesGroup-Enum. 2) Die Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind („series group properties“). „Series group properties“ in der ChartSeriesGroup Klasse ist Lese/Schreib. Jede der „series group properties“ kann in der ChartSeries Klasse eine Nur-Lese-Projection haben.

### Siehe auch

* Schnittstelle [IChartSeriesGroup](../ichartseriesgroup)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->