---
title: IChartSeriesGroup
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
weight: 1950
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
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Ermöglicht das Abrufen der Basis-IChartComponent-Schnittstelle. Nur lesbar [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Gibt an, wie die Bubble-Größenwerte im Bubble-Diagramm dargestellt werden. Lesen/Schreiben [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Gibt den Skalierungsfaktor für das Bubble-Diagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). Lesen/Schreiben Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Größe des Plot-Bereichs liegen). Lesen/Schreiben Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Liest oder setzt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lesen/Schreiben UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Gibt die Distanz zurück oder setzt sie, als Prozentsatz der Marker-Breite, zwischen den Datenreihen in einem 3D-Diagramm. Lesen/Schreiben UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Gibt den Abstand zwischen Balken- oder Spalten-Clustern als Prozentsatz der Balken- oder Spaltenbreite an. Lesen/Schreiben UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Wahr, wenn das Diagramm Reihenlinien hat. Wird auf gestapelte Balken- und OfPie-Diagramme angewendet. Lesen/Schreiben Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Gibt das HiLowLines-Format an. HiLowLines werden mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jeder Datenmarker in der Reihe eine andere Farbe hat. Lesen/Schreiben Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Ruft das Element am angegebenen Index ab. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: maximaler Abstand (Balken sind vollständig getrennt). - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100 %: maximale Überlappung (Balken überlappen vollständig). Diese Eigenschaft ist Lesen/Schreiben SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Lesen/Schreiben [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierte Split-Information für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefiniertem Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms gezeichnet werden sollen. Nur lesbar [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Lesen/Schreiben Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Gibt an, ob die Reihen dieser Gruppe auf einer sekundären Achse gezeichnet werden. Nur lesbar Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). Lesen/Schreiben UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Gibt eine schreibgeschützte Auflistung von Diagramm-Serien zurück. Nur lesbar [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Gibt den Typ dieser Seriengruppe zurück. Nur lesbar [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Stellt Zugriff auf Auf-/Ab-Balken von Linien- oder Kurs-Diagrammen bereit. Nur lesbar [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Bemerkungen

1) Siehe Zusammenfassung und Bemerkungen zur Klasse ChartSeriesGroupCollection und zum Enum CombinableSeriesTypesGroup. 2) Eine Gruppe von Reihen enthält einige Reihen-Eigenschaften, die für jede Reihe in der Gruppe gemeinsam sind („series group properties“). „Series group properties“ in der Klasse ChartSeriesGroup ist lesen/schreiben. Jede der „series group properties“ kann in der Klasse ChartSeries eine schreibgeschützte Projektion haben.

### Siehe Auch

* Schnittstelle [IChartComponent](../ichartcomponent)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->