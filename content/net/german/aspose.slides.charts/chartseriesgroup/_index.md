---
title: ChartSeriesGroup
second_title: Aspose.Slides for .NET API Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
weight: 1380
url: /de/aspose.slides.charts/chartseriesgroup/
---

## ChartSeriesGroup-Klasse

Stellt eine Gruppe von Serien dar.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. Lese-/Schreibzugriff [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). Lese-/Schreibzugriff Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Nur Lesezugriff [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Ringdiagramm an (kann zwischen 0 und 90 Prozent der Größe des Diagrammbereichs liegen). Lese-/Schreibzugriff Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Ruft den Winkel der ersten Schnittfläche eines Kreis- oder Ringdiagramms in Grad ab oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese-/Schreibzugriff UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Gibt die Distanz, als Prozentsatz der Markerbreite, zwischen den Datenreihen in einem 3D-Diagramm zurück oder legt sie fest. Lese-/Schreibzugriff UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Gibt den Abstand zwischen Balken- oder Säulengruppen als Prozentsatz der Breite des Balkens oder der Säule an. Lese-/Schreibzugriff UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True, wenn das Diagramm Serienlinien hat. Gilt für gestapelte Balken- und OfPie-Diagramme. Lese-/Schreibzugriff Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Gibt das HiLowLines-Format an. HiLowLines werden angewendet bei den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lese-/Schreibzugriff Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Ruft das Element am angegebenen Index ab. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Gibt an, wie viel Balken und Säulen in 2D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%). - -100%: Maximale Abstände (Balken sind vollständig getrennt). - 0%: Balken sind nebeneinander ohne Überlappung oder Abstand angeordnet. - 100%: Maximale Überlappung (Balken überdecken sich vollständig). Diese Eigenschaft hat Lese-/Schreibzugriff SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Gibt an, wie ermittelt wird, welche Datenpunkte im zweiten Kreis oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms enthalten sind. Lese-/Schreibzugriff [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefiniertem Split. Enthält Datenpunkte, die im zweiten Kreis oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms gezeichnet werden sollen. Nur Lesezugriff [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet werden soll, um zu bestimmen, welche Datenpunkte im zweiten Kreis oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms enthalten sind. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Lese-/Schreibzugriff Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Gibt an, ob die Serien dieser Gruppe auf der sekundären Achse dargestellt werden. Nur Lesezugriff Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kreises oder Balkens eines Pie-of-Pie- oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kreises an (kann zwischen 5 und 200 Prozent liegen). Lese-/Schreibzugriff UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Gibt eine Sammlung von Serien zurück. Nur Lesezugriff [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Gibt einen Typ dieser Seriengruppe zurück. Nur Lesezugriff [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Ermöglicht den Zugriff auf die Hoch-/Tiefbalken von Linien- oder Aktiendiagrammen. Nur Lesezugriff [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen zur ChartSeriesGroupCollection-Klasse und zur CombinableSeriesTypesGroup-Enum. 2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind ("Seriengruppeneigenschaften"). Die "Seriengruppeneigenschaften" in der ChartSeriesGroup-Klasse haben Lese-/Schreibzugriff. Jede der "Seriengruppeneigenschaften" kann eine schreibgeschützte Projektion in der ChartSeries-Klasse haben.

### Siehe auch

* Schnittstelle [IChartSeriesGroup](../ichartseriesgroup)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->