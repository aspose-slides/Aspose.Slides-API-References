---
title: IChartSeriesGroup
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
weight: 1870
url: /de/aspose.slides.charts/ichartseriesgroup/
---

## IChartSeriesGroup-Schnittstelle

Stellt eine Gruppe von Serien dar.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IChartComponent-Schnittstelle. Nur lesbar [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Gibt an, wie die Blasengröße auf dem Blasendiagramm dargestellt wird. Lese-/Schreibzugriff [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). Lese-/Schreibzugriff Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Donutdiagramm an (kann zwischen 10 und 90 Prozent der Größe des Zeichenbereichs liegen). Lese-/Schreibzugriff Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Ruft den Winkel der ersten Scheibe eines Kreis- oder Donutdiagramms in Grad ab oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese-/Schreibzugriff UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Gibt den Abstand als Prozentsatz der Markerbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt ihn fest. Lese-/Schreibzugriff UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Gibt den Abstand zwischen Balken- oder Säulengruppen als Prozentsatz der Balken- oder Säulenbreite an. Lese-/Schreibzugriff UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True, wenn das Diagramm Serielinien hat. Gilt für gestapelte Balken- und OfPie-Diagramme. Lese-/Schreibzugriff Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Gibt das HiLowLines-Format an. HiLowLines werden bei HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose-Diagrammtypen verwendet. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lese-/Schreibzugriff Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Ruft das Element am angegebenen Index ab. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Gibt an, wie viel sich Balken und Säulen in 2D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: Maximaler Abstand (Balken sind vollständig getrennt). - 0 %: Balken liegen nebeneinander ohne Überlappung oder Abstand. - 100 %: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft hat Lese-/Schreibzugriff SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen- oder Balken in einem Pie-of-Pie- oder Bar-of-Pie-Diagramm enthalten sind. Lese-/Schreibzugriff [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierten Splitinformationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit einem benutzerdefinierten Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken in einem Pie-of-Pie- oder Bar-of-Pie-Diagramm gezeichnet werden sollen. Nur lesbar [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet werden soll, um zu bestimmen, welche Datenpunkte in dem zweiten Kuchen oder Balken in einem Pie-of-Pie- oder Bar-of-Pie-Diagramm enthalten sind. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lese-/Schreibzugriff Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Gibt an, ob die Serien dieser Gruppe auf der sekundären Achse geplottet werden. Nur lesbar Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 Prozent liegen). Lese-/Schreibzugriff UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Gibt eine schreibgeschützte Sammlung von Diagrammserien zurück. Nur lesbar [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Gibt den Typ dieser Seriengruppe zurück. Nur lesbar [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Ermöglicht den Zugriff auf die Auf-/Ab-Balken des Linien- oder Aktiendiagramms. Nur lesbar [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen für die Klasse ChartSeriesGroupCollection und das Enum CombinableSeriesTypesGroup. 2) Die Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Seriengruppeneigenschaften“). „Seriengruppeneigenschaften“ in der Klasse ChartSeriesGroup sind Lese-/Schreibzugriff. Jede der „Seriengruppeneigenschaften“ kann in der Klasse ChartSeries eine schreibgeschützte Projektion haben.

### Siehe auch

* Schnittstelle [IChartComponent](../ichartcomponent)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->