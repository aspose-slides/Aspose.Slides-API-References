---
title: DataLabelFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt Formatierungsoptionen für DataLabel bereit.
type: docs
weight: 1580
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
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Legt fest oder gibt einen Variant zurück, der das Trennzeichen für die Datenlabels in einem Diagramm darstellt. Lese-/Schreib-String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Stellt das Anzeigeverhalten des Bubble-Größenwerts des Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Bubble-Größenwert an. Falsch blendet ihn aus. Lese-/Schreib-Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Stellt das Anzeigeverhalten des Kategorienamens des Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Kategorienamen für die Datenlabels in einem Diagramm an. Falsch blendet ihn aus. Lese-/Schreib-Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Bestimmt, ob das Datenlabel eines angegebenen Diagramms als Datenbeschriftung (Data Callout) oder als Datenlabel angezeigt wird. Wenn der übergeordnete Container dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenlabels ist, liest oder schreibt diese Eigenschaft den Standardwert der ShowLabelAsDataCallout-Eigenschaft für neue Datenlabels in der DataLabelCollection-Sammlung. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert ebenfalls für die ShowLabelAsDataCallout-Eigenschaft aller Datenlabels in der DataLabelCollection-Sammlung (z. B. \"DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;\" bewirkt, dass alle DataLabels[i].ShowLabelAsDataCallout den Wert val erhalten). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Stellt das Anzeigeverhalten des Zellenwerts des Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Zellenwert an. Falsch blendet ihn aus. Lese-/Schreib-Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Stellt das Anzeigeverhalten der Leader-Linien des Datenlabels eines angegebenen Diagramms dar. Wahr zeigt die Leader-Linien an. Falsch blendet sie aus. Lese-/Schreib-Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Stellt das Anzeigeverhalten des Legenden-Schlüssels des Datenlabels eines angegebenen Diagramms dar. Wahr, wenn der Legenden-Schlüssel des Datenlabels sichtbar ist. Lese-/Schreib-Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Stellt das Anzeigeverhalten des Prozentwerts des Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Prozentwert an. Falsch blendet ihn aus. Lese-/Schreib-Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Gibt einen Boolean zurück oder setzt ihn, um das Anzeigeverhalten des Seriennamens für die Datenlabels in einem Diagramm anzugeben. Wahr zeigt den Seriennamen an. Falsch blendet ihn aus. Lese-/Schreib-Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Stellt das Anzeigeverhalten des Prozentwerts des Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Prozentwert an. Falsch blendet ihn aus. Lese-/Schreib-Boolean. |
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