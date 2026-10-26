---
title: ChartSeriesGroup
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
weight: 1460
url: /de/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup Klasse

Stellt eine Gruppe von Reihen dar.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Gibt an, wie die Bubble-Größenwerte im Bubble-Diagramm dargestellt werden. Lese/Schreib [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Gibt den Skalierungsfaktor für das Bubble-Diagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). Lese/Schreib Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Schreibgeschützt [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 Prozent der Plot-Flächengröße liegen). Lese/Schreib Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Liest oder setzt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese/Schreib UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Liest oder setzt den Abstand, angegeben als Prozentsatz der Markierungsbreite, zwischen den Datenreihen in einem 3D-Diagramm. Lese/Schreib UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Gibt den Abstand zwischen Balken- oder Spaltengruppen als Prozentsatz der Balken- bzw. Spaltenbreite an. Lese/Schreib UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True, wenn das Diagramm Serienlinien hat. Wird bei gestapelten Balken- und OfPie-Diagrammen angewendet. Lese/Schreib Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Gibt das HiLowLines-Format an. HiLowLines werden zusammen mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jeder Datenmarker in der Reihe eine andere Farbe hat. Lese/Schreib Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Liest das Element am angegebenen Index. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: Maximaler Abstand (Balken sind vollständig getrennt). - 0 %: Balken nebeneinander ohne Überlappung oder Abstand. - 100 %: Maximale Überlappung (Balken überlappen einander vollständig). Diese Eigenschaft ist Lese/Schreib SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Lese/Schreib [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit einem benutzerdefinierten Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms gezeichnet werden sollen. Schreibgeschützt [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Lese/Schreib Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Gibt an, ob die Reihen dieser Gruppe auf einer sekundären Achse dargestellt werden. Schreibgeschützt Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 Prozent liegen). Lese/Schreib UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Gibt eine Sammlung von Reihen zurück. Schreibgeschützt [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Gibt den Typ dieser Reihen-gruppe zurück. Schreibgeschützt [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Stellt Zugriff auf Auf-/Ab-Balken von Linien- oder Kurs-Diagrammen bereit. Schreibgeschützt [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen für die ChartSeriesGroupCollection Klasse und das CombinableSeriesTypesGroup-Enum.  
2) Eine Gruppe von Reihen enthält einige Reihen-Eigenschaften, die für jede Reihe in der Gruppe gemeinsam sind („Series-Group-Properties“). „Series-Group-Properties“ in der ChartSeriesGroup Klasse sind Lese/Schreib. Jede dieser „Series-Group-Properties“ kann in der ChartSeries Klasse eine schreibgeschützte Projektion haben.

### Siehe auch

* Schnittstelle [IChartSeriesGroup](../ichartseriesgroup)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->