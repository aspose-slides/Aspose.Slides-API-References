---
title: ChartSeriesGroup
second_title: Aspose.Slides für .NET API Referenz
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
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 Prozent der Größe des Diagrammbereichs liegen). Lese-/Schreibzugriff Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Ruft den Winkel des ersten Stücks eines Kuchen- oder Donutdiagramms in Grad ab oder setzt ihn (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese-/Schreibzugriff UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Gibt die Entfernung als Prozentsatz der Markerbreite zwischen den Datenreihen in einem 3D-Diagramm zurück oder setzt sie. Lese-/Schreibzugriff UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Gibt den Abstand zwischen Balken- oder Säulengruppen als Prozentsatz der Balken- oder Säulenbreite an. Lese-/Schreibzugriff UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Wahr, wenn das Diagramm Serienlinien hat. Gilt für gestapelte Balken- und OfPie-Diagramme. Lese-/Schreibzugriff Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Gibt das Format der HiLowLines an. HiLowLines werden mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose angewendet. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lese-/Schreibzugriff Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Ruft das Element am angegebenen Index ab. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Gibt an, wie viel Balken und Säulen in 2D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%). - -100%: Maximale Abstände (Balken sind vollständig getrennt). - 0%: Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100%: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist Lese-/Schreibzugriff SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-von-Kuchen- oder Balken-von-Kuchen-Diagramms enthalten sind. Lese-/Schreibzugriff [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierte Split-Information für ein Kuchen-von-Kuchen- oder Balken-von-Kuchen-Diagramm mit einem benutzerdefinierten Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken in einem Kuchen-von-Kuchen- oder Balken-von-Kuchen-Diagramm gezeichnet werden sollen. Nur Lesezugriff [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet werden soll, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-von-Kuchen- oder Balken-von-Kuchen-Diagramms enthalten sind. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lese-/Schreibzugriff Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Gibt an, ob die Serien dieser Gruppe auf der sekundären Achse dargestellt werden. Nur Lesezugriff Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-von-Kuchen-Diagramms oder eines Balken-von-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 Prozent liegen). Lese-/Schreibzugriff UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Gibt eine Sammlung von Serien zurück. Nur Lesezugriff [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Gibt den Typ dieser Seriengruppe zurück. Nur Lesezugriff [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Ermöglicht den Zugriff auf Auf-/Abwärtsbalken von Linien- oder Aktiencharts. Nur Lesezugriff [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Bemerkungen

1) Siehe Zusammenfassung und Bemerkungen zur ChartSeriesGroupCollection-Klasse und zum CombinableSeriesTypesGroup-Enum. 2) Eine Gruppe von Serien enthält einige Serien Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind ("Seriengruppeneigenschaften"). Die "Seriengruppeneigenschaften" in der ChartSeriesGroup-Klasse sind Lese-/Schreibzugriff. Jede der "Seriengruppeneigenschaften" kann eine schreibgeschützte Projektion in der ChartSeries-Klasse haben.

### Siehe auch

* interface [IChartSeriesGroup](../ichartseriesgroup)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->