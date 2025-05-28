---
title: DataLabel
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Serie von Beschriftungen dar.
type: docs
weight: 1470
url: /de/aspose.slides.charts/datalabel/
---

## DataLabel-Klasse

Stellt eine Serie von Beschriftungen dar.

```csharp
public class DataLabel : IDataLabel
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DataLabel](datalabel)(IChartDataPoint) | Erstellt eine neue Instanz der DataLabel-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lesen Sie Single. |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lesen Sie Single. |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur oberen linken Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lesen Sie Single. |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Gibt den tatsächlichen oberen Rand des Diagrammelements relativ zur oberen linken Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lesen Sie Single. |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Unten. Nur Lesezugriff Single. |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Nur Lesezugriff [`IChart`](../ichart). |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Gibt das Format der Datenbeschriftung zurück. Nur Lesezugriff [`IDataLabelFormat`](../idatalabelformat). |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Gibt die Höhe eines Titels als Bruchteil der Höhe des Diagramms zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). Nur Lesezugriff Boolean. |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Rechts. Nur Lesezugriff Single. |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Gibt das Textformat zurück. Nur Lesezugriff [`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch generierten Text der Datenbeschriftung. Der automatisch generierte Text der Datenbeschriftung bedeutet Text, der von den Eigenschaften ShowSeriesName, ShowValue, ... verwaltet wird und mit der Eigenschaft TextFormatManager.TextFormat formatiert wird. Nur Lesezugriff [`ITextFrame`](../../aspose.slides/itextframe). |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Ruft die Datenzelle des Arbeitsbuchs ab oder legt sie fest. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell gleich true ist. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Gibt die Breite eines Titels als Bruchteil der Breite des Diagramms zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Gibt die x-Koordinate eines Titels als Bruchteil der Breite des Diagramms zurück oder legt sie fest. Lese-/Schreibzugriff Single. |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Gibt die y-Koordinate eines Titels als Bruchteil der Höhe des Diagramms zurück oder legt sie fest. Lese-/Schreibzugriff Single. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach seinen Text. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Gibt den tatsächlichen Beschriftungstext basierend auf den Einstellungen von DataLabelFormat oder dem Wert von TextFrameForOverriding.Text zurück. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Macht die Datenbeschriftung unsichtbar, indem alle Show*-Flags (ShowValue, ...) auf den Zustand false gesetzt werden. IsVisible wird danach false sein. |

### Siehe auch

* Schnittstelle [IDataLabel](../idatalabel)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->