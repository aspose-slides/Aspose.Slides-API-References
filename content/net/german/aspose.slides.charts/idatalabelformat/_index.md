---
title: IDataLabelFormat
second_title: Aspose.Slides für .NET API Referenz
description: Stellt Formatierungsoptionen für DataLabel dar.
type: docs
weight: 1960
url: /de/aspose.slides.charts/idatalabelformat/
---

## IDataLabelFormat-Schnittstelle

Stellt Formatierungsoptionen für DataLabel dar.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Ermöglicht den Zugriff auf die Basis-IFormattedTextContainer-Schnittstelle. Nur lesbar [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Stellt das Format des Datenetiketts dar. Nur lesbar [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Lese-/Schreibbares Boolean. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreibbarer String. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Stellt die Position des Datenetiketts dar. Lese-/Schreibbarer [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Setzt oder gibt einen Variant zurück, der den für die Datenetiketten in einem Diagramm verwendeten Trenner darstellt. Lese-/Schreibbarer String. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Stellt das Anzeigeverhalten des Wertes für die Blasengröße eines bestimmten Diagramm-Datenetiketts dar. Wahr zeigt den Blasengrößenwert an. Falsch, um zu verbergen. Lese-/Schreibbares Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Stellt das Anzeigeverhalten des Kategorienamens eines bestimmten Diagramm-Datenetiketts dar. Wahr, um den Kategorienamen für die Datenetiketten in einem Diagramm anzuzeigen. Falsch, um zu verbergen. Lese-/Schreibbares Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Bestimmt, ob das Datenetikett des bestimmten Diagramms als Datenhinweis oder als Datenetikett angezeigt wird. Wenn der übergeordnete Container dieses DataLabelFormat-Objekts eine DataLabelCollection von Datenetiketten ist, dann ruft diese Eigenschaft den Standardwert der ShowLabelAsDataCallout-Eigenschaft für die neuen Datenetiketten in der DataLabelCollection ab oder legt ihn fest. Setzen Sie diese Eigenschaft mit einem Wert, wird dieser Wert auch für die ShowLabelAsDataCallout-Eigenschaft aller Datenetiketten in der DataLabelCollection gesetzt (d.h. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" führt dazu, dass alle DataLabels[i].ShowLabelAsDataCallout gleich val sind). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Stellt das Anzeigeverhalten des Zellwertes eines bestimmten Diagramm-Datenetiketts dar. Wahr zeigt den Zellwert an. Falsch, um zu verbergen. Lese-/Schreibbares Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Stellt das Anzeigeverhalten der Führungslinien eines bestimmten Diagramm-Datenetiketts dar. Wahr zeigt die Führungslinien an. Falsch, um zu verbergen. Lese-/Schreibbares Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Stellt das Anzeigeverhalten des Legende-Schlüssels eines bestimmten Diagramm-Datenetiketts dar. Wahr, wenn der Legende-Schlüssel des Datenetiketts sichtbar ist. Lese-/Schreibbares Boolean. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Stellt das Anzeigeverhalten des Prozentwerts eines bestimmten Diagramm-Datenetiketts dar. Wahr zeigt den Prozentwert an. Falsch, um zu verbergen. Lese-/Schreibbares Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Gibt ein Boolean zurück oder legt es fest, um das Anzeigeverhalten des Seriennamens für die Datenetiketten in einem Diagramm anzuzeigen. Wahr, um den Seriennamen anzuzeigen. Falsch, um zu verbergen. Lese-/Schreibbares Boolean. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Stellt das Anzeigeverhalten des Werteprozents eines bestimmten Diagramm-Datenetiketts dar. Wahr zeigt den Prozentwert an. Falsch, um zu verbergen. Lese-/Schreibbares Boolean. |

### Siehe auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->