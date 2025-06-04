---
title: DataLabelFormat
second_title: Aspose.Slides für .NET API Referenz
description: Stellt Formatierungsoptionen für DataLabel dar.
type: docs
weight: 1490
url: /de/aspose.slides.charts/datalabelformat/
---

## DataLabelFormat-Klasse

Stellt Formatierungsoptionen für DataLabel dar.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Erlaubt den Zugriff auf die Basisschnittstelle IPresentationComponent. Nur-lesend [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Gibt das Diagramm zurück. Nur-lesend [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Stellt das Format des Datenetiketts dar. Nur-lesend [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Lese-/Schreib-Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Stellt den Format-String für das DataLabels-Objekt dar. Lese-/Schreib-String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Stellt die Position des Datenetiketts dar. Lese-/Schreib [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Setzt oder gibt eine Variant zurück, die den für die Datenetiketten in einem Diagramm verwendeten Separator darstellt. Lese-/Schreib-String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Stellt das Anzeigeverhalten des Bubble-Größenwerts des Datenetiketts eines bestimmten Diagramms dar. True zeigt den Bubble-Größenwert an. False, um ihn auszublenden. Lese-/Schreib-Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Stellt das Anzeigeverhalten des Kategorie-Namens des Datenetiketts eines bestimmten Diagramms dar. True, um den Kategorie-Namen für die Datenetiketten in einem Diagramm anzuzeigen. False, um ihn auszublenden. Lese-/Schreib-Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Bestimmt, ob das Datenetikett eines bestimmten Diagramms als Datenaufruf oder als Datenetikett angezeigt wird. Wenn der übergeordnete Bestandteil dieses DataLabelFormat-Objekts eine DataLabelCollection von Datenetiketten ist, wird dieser Wert für die neuen Datenetiketten in der DataLabelCollection festgelegt oder abgerufen. Das Setzen dieses Wertes setzt ebenfalls den Wert der ShowLabelAsDataCallout-Eigenschaft für alle Datenetiketten in der DataLabelCollection (d.h. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" bewirkt, dass alle DataLabels[i].ShowLabelAsDataCallout gleich val ist). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Stellt das Anzeigeverhalten des Zellenwerts des Datenetiketts eines bestimmten Diagramms dar. True zeigt den Zellenwert an. False, um ihn auszublenden. Lese-/Schreib-Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Stellt das Anzeigeverhalten der Führungslinien des Datenetiketts eines bestimmten Diagramms dar. True zeigt die Führungslinien an. False, um sie auszublenden. Lese-/Schreib-Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Stellt das Anzeigeverhalten des Legenden-Schlüssels des Datenetiketts eines bestimmten Diagramms dar. True, wenn der Legenden-Schlüssel des Datenetiketts sichtbar ist. Lese-/Schreib-Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Stellt das Anzeigeverhalten des Prozentwerts des Datenetiketts eines bestimmten Diagramms dar. True zeigt den Prozentwert an. False, um ihn auszublenden. Lese-/Schreib-Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Gibt einen Boolean zurück oder setzt ihn, um das Anzeigeverhalten des Seriennamens für die Datenetiketten in einem Diagramm anzugeben. True, um den Seriennamen anzuzeigen. False, um ihn auszublenden. Lese-/Schreib-Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Stellt das Anzeigeverhalten des Wertes des Datenetiketts eines bestimmten Diagramms dar. True zeigt den Wert an. False, um ihn auszublenden. Lese-/Schreib-Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Gibt das Textformat des Diagramms zurück. Nur-lesend [`IChartTextFormat`](../icharttextformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Siehe auch

* Klasse [PVIObject](../../aspose.slides/pviobject)
* Schnittstelle [IDataLabelFormat](../idatalabelformat)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->