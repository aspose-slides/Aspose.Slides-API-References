---
title: DataLabel
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een reeks labels voor.
type: docs
weight: 1560
url: /nl/aspose.slides.charts/datalabel/
---
## DataLabel klasse

Stelt een reeks labels voor.

```csharp
public class DataLabel : IDataLabel
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [DataLabel](datalabel)(IChartDataPoint) | Maakt een nieuw exemplaar van de DataLabel klasse aan. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Specificeert de werkelijke hoogte van het diagramonderdeel. Roep de methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden opvraagt. Alleen-lezen Single. |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Specificeert de werkelijke breedte van het diagramonderdeel. Roep de methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden opvraagt. Alleen-lezen Single. |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Specificeert de werkelijke x-locatie (links) van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram. Roep de methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden opvraagt. Alleen-lezen Single. |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Specificeert de werkelijke bovenkant van het diagramonderdeel ten opzichte van de linkerbovenhoek van het diagram. Roep de methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden opvraagt. Alleen-lezen Single. |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Onderkant. Alleen-lezen Single. |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Geeft het bovenliggende diagram terug. Alleen-lezen [`IChart`](../ichart). |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Geeft het gegevenslabelformaat terug. Alleen-lezen [`IDataLabelFormat`](../idatalabelformat). |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Geeft de hoogte van een titel terug of stelt deze in als een fractie van de hoogte van het diagram. Lezen/schrijven Single. |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | False betekent dat het gegevenslabel niet zichtbaar is (en dus alle Show*-vlaggen (ShowValue, ...) false zijn). Alleen-lezen Boolean. |
| [LabelShapeType](../../aspose.slides.charts/datalabel/labelshapetype) { get; set; } | Haalt het vormtype van het gegevenslabel op of stelt dit in. Geeft NotDefined terug als er geen vorm is gedefinieerd. |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Rechts. Alleen-lezen Single. |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Geeft het tekstopmaak terug. Alleen-lezen [`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Kan een rijk opgemaakt tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekstwaarde de automatisch gegenereerde tekst van het gegevenslabel. Automatisch gegenereerde tekst van het gegevenslabel betekent tekst die wordt beheerd door de eigenschappen ShowSeriesName, ShowValue, ... en wordt opgemaakt met de eigenschap TextFormatManager.TextFormat. Alleen-lezen [`ITextFrame`](../../aspose.slides/itextframe). |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Haalt de werkboekgegevenscel op of stelt deze in. Toegepast als de eigenschap IDataLabelFormat.ShowLabelValueFromCell true is. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Geeft de breedte van een titel terug of stelt deze in als een fractie van de breedte van het diagram. Lezen/schrijven Single. |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Geeft de x-coördinaat van een titel terug of stelt deze in als een fractie van de breedte van het diagram. Lezen/schrijven Single. |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Geeft de y-coördinaat van een titel terug of stelt deze in als een fractie van de hoogte van het diagram. Lezen/schrijven Single. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Initialiseer TextFrameForOverriding met de tekst in parameter "text". Als TextFrameForOverriding al is geïnitialiseerd, verandert dan eenvoudigweg de tekst. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Geeft de werkelijke labeltekst terug op basis van de DataLabelFormat-instellingen of de TextFrameForOverriding.Text-waarde. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Maak het gegevenslabel onzichtbaar door alle Show*-vlaggen (ShowValue, ...) op false te zetten. IsVisible zal daarna false zijn. |

### Zie ook

* interface [IDataLabel](../idatalabel)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->