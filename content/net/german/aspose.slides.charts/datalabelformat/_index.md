---
title: DataLabelFormat
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt Formatierungsoptionen für DataLabel bereit.
type: docs
weight: 1570
url: /de/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat Klasse

Stellt Formatierungsoptionen für DataLabel bereit.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur lesbar [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Gibt das Diagramm zurück. Nur lesbar [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Stellt das Format des Datenlabels dar. Nur lesbar [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Lese-/Schreib-Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreib-String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Stellt die Position des Datenlabels dar. Lese-/Schreib [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Legt fest oder gibt eine Variant zurück, die das Trennzeichen für die Datenlabels eines Diagramms darstellt. Lese-/Schreib-String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Stellt das Anzeigeverhalten des Blasengrößenwerts eines angegebenen Diagramms dar. Wahr zeigt den Blasengrößenwert an. Falsch verbirgt ihn. Lese-/Schreib-Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Stellt das Anzeigeverhalten des Kategorienamens eines angegebenen Diagramms dar. Wahr zeigt den Kategorienamen für die Datenlabels an. Falsch verbirgt ihn. Lese-/Schreib-Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Bestimmt, ob das Datenlabel eines angegebenen Diagramms als Datenbeschriftung oder als Datencallout angezeigt wird. Wenn der übergeordnete Container dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenlabels ist, ruft diese Eigenschaft den Standardwert der ShowLabelAsDataCallout-Eigenschaft für die neuen Datenlabels in der DataLabelCollection-Sammlung ab oder legt ihn fest. Das Setzen dieser Eigenschaft auf einen Wert legt diesen Wert auch für die ShowLabelAsDataCallout-Eigenschaft aller Datenlabels in der DataLabelCollection-Sammlung fest (z. B. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" bewirkt, dass für alle DataLabels[i].ShowLabelAsDataCallout der Wert val gilt). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Stellt das Anzeigeverhalten des Zellenwerts eines angegebenen Diagramms dar. Wahr zeigt den Zellenwert an. Falsch verbirgt ihn. Lese-/Schreib-Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Stellt das Anzeigeverhalten der Führungsleitungen eines angegebenen Diagramms dar. Wahr zeigt die Führungsleitungen an. Falsch verbirgt sie. Lese-/Schreib-Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Stellt das Anzeigeverhalten des Legenden-Schlüssels eines Datenlabels eines angegebenen Diagramms dar. Wahr, wenn der Legenden-Schlüssel sichtbar ist. Lese-/Schreib-Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Stellt das Anzeigeverhalten des Prozentwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Prozentwert an. Falsch verbirgt ihn. Lese-/Schreib-Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Gibt einen Boolean zurück oder legt ihn fest, um das Anzeigeverhalten des Seriennamens für die Datenlabels eines Diagramms anzugeben. Wahr zeigt den Seriennamen an. Falsch verbirgt ihn. Lese-/Schreib-Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Stellt das Anzeigeverhalten des Prozentwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Prozentwert an. Falsch verbirgt ihn. Lese-/Schreib-Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Gibt das Diagramm-Textformat zurück. Nur lesbar [`IChartTextFormat`](../icharttextformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Siehe auch

* Klasse [PVIObject](../../aspose.slides/pviobject)
* Schnittstelle [IDataLabelFormat](../idatalabelformat)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->