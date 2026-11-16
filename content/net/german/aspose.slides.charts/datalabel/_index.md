---
title: DataLabel
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt Serienbeschriftungen dar.
type: docs
weight: 1560
url: /de/aspose.slides.charts/datalabel/
---
## DataLabel Klasse

Stellt Serienbeschriftungen dar.

```csharp
public class DataLabel : IDataLabel
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DataLabel](datalabel)(IChartDataPoint) | Erstellt eine neue Instanz der DataLabel Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Nur-Lesen Single. |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Nur-Lesen Single. |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Gibt die tatsächliche x-Position (Links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Nur-Lesen Single. |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Nur-Lesen Single. |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Unten. Nur-Lesen Single. |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Nur-Lesen [`IChart`](../ichart). |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Gibt das Datenbeschriftungsformat zurück. Nur-Lesen [`IDataLabelFormat`](../idatalabelformat). |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Gibt die Höhe eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. Lese/Schreib Single. |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | Falsch bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und somit alle Show*-Flags (ShowValue, ...) false sind). Nur-Lesen Boolean. |
| [LabelShapeType](../../aspose.slides.charts/datalabel/labelshapetype) { get; set; } | Gibt den Formtyp der Datenbeschriftung zurück oder setzt ihn. Gibt NotDefined zurück, wenn keine Form definiert ist. |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Rechts. Nur-Lesen Single. |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Gibt das Textformat zurück. Nur-Lesen [`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch generierten Text der Datenbeschriftung. Der automatisch generierte Text der Datenbeschriftung bedeutet Text, der von den Eigenschaften ShowSeriesName, ShowValue, ... verwaltet wird und mit der Eigenschaft TextFormatManager.TextFormat formatiert ist. Nur-Lesen [`ITextFrame`](../../aspose.slides/itextframe). |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Gibt die Arbeitsmappendatenzelle zurück oder setzt sie. Wird angewendet, wenn die Eigenschaft IDataLabelFormat.ShowLabelValueFromCell den Wert true hat. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Gibt die Breite eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. Lese/Schreib Single. |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Gibt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite zurück oder setzt sie. Lese/Schreib Single. |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Gibt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe zurück oder setzt sie. Lese/Schreib Single. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach dessen Text. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Gibt den tatsächlichen Beschriftungstext basierend auf den DataLabelFormat-Einstellungen oder dem Wert TextFrameForOverriding.Text zurück. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Macht die Datenbeschriftung unsichtbar, indem alle Show*-Flags (ShowValue, ...) auf den Zustand false gesetzt werden. IsVisible wird danach false sein. |

### Siehe auch

* Schnittstelle [IDataLabel](../idatalabel)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->