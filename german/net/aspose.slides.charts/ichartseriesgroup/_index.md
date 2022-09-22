---
title: IChartSeriesGroup
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
weight: 1830
url: /de/net/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

Stellt eine Gruppe von Serien dar.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Ermöglicht das Abrufen der Basis-IChartComponent-Schnittstelle. Schreibgeschützt[`IChartComponent`](../ichartcomponent) . |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. Lesen/Schreiben[`BubbleSizeRepresentationType`](../bubblesizerepresentationtype) . |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße betragen). Lesen/SchreibenInt32 . |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Gibt die Größe des Lochs in einem Ringdiagramm an (kann zwischen 10 und 90 Prozent der Größe des Diagrammbereichs betragen). Lesen/SchreibenByte . |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Holt oder setzt den Winkel des ersten Torten- oder Ringdiagrammsegments, in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lesen/SchreibenUInt16 . |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Gibt den Abstand zwischen den Datenreihen in einem 3D-Diagramm als Prozentsatz der Markierungsbreite zurück oder legt ihn fest. Lesen/SchreibenUInt16 . |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- oder Spaltenbreite an. Lesen/SchreibenUInt16 . |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Wahr, wenn das Diagramm Reihenlinien hat. Wird auf gestapelte Balken- und OfPie-Diagramme angewendet. Lesen/SchreibenBoolean . |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Gibt das HiLowLines-Format an. HiLowLines angewendet mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Gibt an, dass jede Datenmarkierung in der Reihe eine andere Farbe hat. Lesen/SchreibenBoolean . |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Ruft das Element am angegebenen Index ab. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Gibt an, wie viel Balken und Säulen sich auf 2-D-Diagrammen überlappen sollen (von -100 bis 100). Lesen/SchreibenSByte . |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Gibt an, wie bestimmt wird, welche Datenpunkte sich im zweiten Kreis oder Balken in einem Tortendiagramm oder Balkendiagramm befinden. Lesen/Schreiben[`PieSplitType`](../piesplittype) . |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Die benutzerdefinierten Aufteilungsinformationen für ein Torten- oder Balkendiagramm mit einer benutzerdefinierten Aufteilung. Enthält Datenpunkte, die im zweiten Torten- oder Balken in einem Torten- oder -Balken gezeichnet werden sollen -Kreisdiagramm. Schreibgeschützt[`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection) . |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Gibt einen Wert an, der verwendet werden soll, um zu bestimmen, welche Datenpunkte sich im zweiten Kreis oder Balken in einem Tortendiagramm oder Balkendiagramm befinden. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lesen/SchreibenDouble . |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Gibt an, ob Reihen dieser Gruppe auf der sekundären Achse dargestellt werden. SchreibgeschütztBoolean . |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Gibt die Größe des zweiten Kreises oder Balkens eines Kreisdiagramms oder eines Kreisdiagramms als Prozentsatz der Größe des ersten Kreises an (kann zwischen 5 und 200 Prozent liegen). Lesen SchreibenUInt16 . |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Gibt eine schreibgeschützte Sammlung von Diagrammreihen zurück. Schreibgeschützt[`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection) . |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Gibt einen Typ dieser Seriengruppe zurück. Schreibgeschützt[`CombinableSeriesTypesGroup`](../combinableseriestypesgroup) . |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Zugriff auf Aufwärts-/Abwärtsbalken von Linien- oder Aktiendiagrammen gewähren. Nur Lesen[`IUpDownBarsManager`](../iupdownbarsmanager) . |

### Bemerkungen

1) Siehe Zusammenfassung und Bemerkungen für die ChartSeriesGroupCollection-Klasse und die CombinableSeriesTypesGroup-Aufzählung. 2) Die Reihengruppe enthält einige Reiheneigenschaften, die für jede Reihe in der Gruppe gemeinsam sind ("Reihengruppeneigenschaften"). "Reihengruppeneigenschaften" in der Klasse ChartSeriesGroup ist Lese-/Schreibzugriff. Jede der „Seriengruppeneigenschaften“ kann eine schreibgeschützte Projektion in der ChartSeries-Klasse haben.

### Siehe auch

* interface [IChartComponent](../ichartcomponent)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
