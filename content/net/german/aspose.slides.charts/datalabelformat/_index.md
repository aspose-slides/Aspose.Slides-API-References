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
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur lesbar [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Gibt das Diagramm zurück. Nur lesbar [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Stellt das Format des Datenlabels dar. Nur lesbar [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Lese-/Schreib-Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lese-/Schreib-String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Stellt die Position des Datenlabels dar. Lese-/Schreib [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Setzt oder gibt ein Variant zurück, das den Separator darstellt, der für die Datenlabels in einem Diagramm verwendet wird. Lese-/Schreib-String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Stellt das Anzeigeverhalten des angegebenen Diagramms für die Datenlabelblasengröße dar. Wahr zeigt den Blasengrößenwert an. Falsch zum Ausblenden. Lese-/Schreib-Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Stellt das Anzeigeverhalten des angegebenen Diagramms für den Kategorienamen des Datenlabels dar. Wahr, um den Kategorienamen für die Datenlabels im Diagramm anzuzeigen. Falsch zum Ausblenden. Lese-/Schreib-Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Bestimmt, ob das angegebene Diagrammsdatenlabel als Datenhinweis oder als Datenlabel angezeigt wird. Wenn das übergeordnete Objekt dieser DataLabelFormat-Instanz eine DataLabelCollection von Datenlabels ist, wird mit dieser Eigenschaft der Standardwert für die ShowLabelAsDataCallout-Eigenschaft für die neuen Datenlabels in der DataLabelCollection festgelegt. Das Setzen dieses Wertes setzt auch den Wert für die ShowLabelAsDataCallout-Eigenschaft aller Datenlabels in der DataLabelCollection (d.h. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" bewirkt, dass alle DataLabels[i].ShowLabelAsDataCallout gleich val sind). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Stellt das Anzeigeverhalten des Zellwerts des Datenlabels im angegebenen Diagramm dar. Wahr zeigt den Zellwert an. Falsch zum Ausblenden. Lese-/Schreib-Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Stellt das Anzeigeverhalten der Führungsleitungen des Datenlabels im angegebenen Diagramm dar. Wahr zeigt die Führungsleitungen an. Falsch zum Ausblenden. Lese-/Schreib-Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Stellt das Anzeigeverhalten des Legenden-Schlüssels des Datenlabels im angegebenen Diagramm dar. Wahr, wenn der Legenden-Schlüssel des Datenlabels sichtbar ist. Lese-/Schreib-Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Stellt das Anzeigeverhalten des Prozentwertes des Datenlabels im angegebenen Diagramm dar. Wahr zeigt den Prozentwert an. Falsch zum Ausblenden. Lese-/Schreib-Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Gibt einen Boolean zurück oder setzt ihn, um das Anzeigeverhalten des Seriennamens für die Datenlabels im Diagramm anzuzeigen. Wahr, um den Seriennamen anzuzeigen. Falsch zum Ausblenden. Lese-/Schreib-Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Stellt das Anzeigeverhalten des Wertes des Datenlabels im angegebenen Diagramm dar. Wahr zeigt den Wert an. Falsch zum Ausblenden. Lese-/Schreib-Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Gibt das Textformat des Diagramms zurück. Nur lesbar [`IChartTextFormat`](../icharttextformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Siehe auch

* Klasse [PVIObject](../../aspose.slides/pviobject)
* Schnittstelle [IDataLabelFormat](../idatalabelformat)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->