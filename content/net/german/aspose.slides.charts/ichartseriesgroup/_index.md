---
title: IChartSeriesGroup
second_title: Aspose.Slides für .NET API Referenz
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IChartComponent-Schnittstelle. Nur-lesend [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. Lese-/Schreibzugriff [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Gibt den Maßstabsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). Lese-/Schreibzugriff Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Ringdiagramm an (kann zwischen 10 und 90 Prozent der Größe des Diagrammbereichs liegen). Lese-/Schreibzugriff Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Ruft den Winkel des ersten Stücks eines Kreis- oder Ringdiagramms in Grad ab oder setzt ihn (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese-/Schreibzugriff UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Gibt den Abstand als Prozentsatz der Markerbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder setzt ihn. Lese-/Schreibzugriff UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Gibt den Abstand zwischen Balken- oder Säulengruppen als Prozentsatz der Balken- oder Säulenbreite an. Lese-/Schreibzugriff UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True, wenn das Diagramm Serienlinien hat. Gilt für gestapelte Balken- und abgestufte Diagramme. Lese-/Schreibzugriff Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Gibt das Format der HiLowLines an. HiLowLines werden bei den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose angewendet. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lese-/Schreibzugriff Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Ruft das Element am angegebenen Index ab. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Gibt an, wie stark Balken und Spalten in 2D-Diagrammen überlappen sollen, als Prozentsatz (von -100% bis 100%). - -100%: Maximale Abstände (Balken sind komplett getrennt). - 0%: Balken sind ohne Überlappung oder Abstand nebeneinander angeordnet. - 100%: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist Lese-/Schreibzugriff SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Gibt an, wie bestimmt werden soll, welche Datenpunkte im zweiten Kreis oder Balken eines Kreis-oder Balkendiagramms sind. Lese-/Schreibzugriff [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierten Split-Informationen für ein Kreis-oder Balkendiagramm mit einem benutzerdefinierten Split. Enthält Datenpunkte, die im zweiten Kreis oder Balken in einem Kreis-oder Balkendiagramm gezeichnet werden sollen. Nur-lesend [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet werden soll, um zu bestimmen, welche Datenpunkte im zweiten Kreis oder Balken auf einem Kreis-oder Balkendiagramm sind. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Lese-/Schreibzugriff Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Gibt an, ob die Serien dieser Gruppe auf der sekundären Achse dargestellt werden. Nur-lesend Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kreises oder Balkens eines Kreis-oder Balkendiagramms als Prozentsatz der Größe des ersten Kreises an (kann zwischen 5 und 200 Prozent liegen). Lese-/Schreibzugriff UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Gibt eine schreibgeschützte Sammlung von Diagrammserien zurück. Nur-lesend [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Gibt den Typ dieser Seriengruppe zurück. Nur-lesend [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Ermöglicht den Zugriff auf die Auf-/Ab-Balken von Linien- oder Aktien-Diagrammen. Nur-lesend [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen zur ChartSeriesGroupCollection-Klasse und zur CombinableSeriesTypesGroup-Enumeration. 2) Eine Gruppe von Serien enthält einige Serien Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind ("Seriengruppeneigenschaften"). "Seriengruppeneigenschaften" in der ChartSeriesGroup-Klasse sind Lese-/Schreibzugriff. Jede der "Seriengruppeneigenschaften" kann eine schreibgeschützte Projektion in der ChartSeries-Klasse haben.

### Siehe Auch

* Schnittstelle [IChartComponent](../ichartcomponent)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->