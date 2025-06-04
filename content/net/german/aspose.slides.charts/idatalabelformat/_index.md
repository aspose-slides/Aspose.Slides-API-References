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
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Ermöglicht den Zugriff auf die Basisschnittstelle IFormattedTextContainer. Nur-lesend [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Stellt das Format des Datenbeschriftung dar. Nur-lesend [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Lese-/schreibbares Boolean. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/schreibbare Zeichenfolge. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Stellt die Position der Datenbeschriftung dar. Lese-/schreibbar [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Setzt oder gibt einen Variant zurück, der den für die Datenbeschriftungen in einem Diagramm verwendeten Separator darstellt. Lese-/schreibbare Zeichenfolge. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Stellt das Anzeigeverhalten des Bubble-Größenwerts der angegebenen Diagrammdatenbeschriftung dar. True zeigt den Bubble-Größenwert an. False, um ihn auszublenden. Lese-/schreibbares Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Stellt das Anzeigeverhalten des Kategorienamens der angegebenen Diagrammdatenbeschriftung dar. True, um den Kategorienamen für die Datenbeschriftungen in einem Diagramm anzuzeigen. False, um ihn auszublenden. Lese-/schreibbares Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Bestimmt, ob die angegebene Diagrammdatenbeschriftung als Datenaufruf oder als Datenbeschriftung angezeigt wird. Wenn der übergeordnete Partner dieses DataLabelFormat-Objekts eine DataLabelCollection-Sammlung von Datenbeschriftungen ist, wird diese Eigenschaft verwendet, um den Standardwert der ShowLabelAsDataCallout-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection-Sammlung abzurufen oder festzulegen. Das Setzen dieser Eigenschaft mit einem Wert setzt diesen Wert auch für die ShowLabelAsDataCallout-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection-Sammlung fest (d.h. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" bewirkt, dass alle DataLabels[i].ShowLabelAsDataCallout gleich val ist). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Stellt das Anzeigeverhalten des Zellwerts der angegebenen Diagrammdatenbeschriftung dar. True zeigt den Zellwert an. False, um ihn auszublenden. Lese-/schreibbares Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Stellt das Anzeigeverhalten der Führungsleitungen der angegebenen Diagrammdatenbeschriftung dar. True zeigt die Führungsleitungen an. False, um sie auszublenden. Lese-/schreibbares Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Stellt das Anzeigeverhalten des Legendenschlüssels der angegebenen Diagrammdatenbeschriftung dar. True, wenn der Legendenschlüssel der Datenbeschriftung sichtbar ist. Lese-/schreibbares Boolean. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Stellt das Anzeigeverhalten des Prozentwerts der angegebenen Diagrammdatenbeschriftung dar. True zeigt den Prozentwert an. False, um ihn auszublenden. Lese-/schreibbares Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Gibt ein Boolean zurück oder setzt dieses, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. True, um den Seriennamen anzuzeigen. False, um ihn auszublenden. Lese-/schreibbares Boolean. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Stellt das Anzeigeverhalten des Wertes der angegebenen Diagrammdatenbeschriftung dar. True zeigt den Wert an. False, um ihn auszublenden. Lese-/schreibbares Boolean. |

### Siehe Auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->