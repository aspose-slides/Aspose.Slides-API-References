---
title: TextFrameFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Bevat de formatTextFrameFormatting-eigenschappen van TextFrames.
type: docs
weight: 10980
url: /nl/aspose.slides/textframeformat/
---
## TextFrameFormat klasse

Bevat de formatTextFrameFormatting-eigenschappen van TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Initialiseert een nieuw exemplaar van de [`TextFrameFormat`](../textframeformat) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Geeft de verticale ankertekst in een TextFrame terug of stelt deze in. Lezen/Schrijven [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe de basis-interface IPresentationComponent op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Geeft de autofit-modus van de tekst terug of stelt deze in. Lezen/Schrijven [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Als NullableBool.True dan moet de tekst horizontaal in de doos gecentreerd worden. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Geeft het aantal kolommen in het tekstgebied terug of stelt dit in. Deze waarde moet positief zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent een ongedefinieerde waarde. Lezen/Schrijven Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Geeft de ruimte tussen tekstkolommen in het tekstgebied (in points) terug of stelt deze in. Dit geldt alleen wanneer er meer dan 1 kolom aanwezig is. Deze waarde moet positief zijn. Anders wordt de waarde op nul gezet. Lezen/Schrijven Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Geeft of stelt het behouden van vlakke tekst in, zelfs als een 3-D-rotatie-effect is toegepast. Lezen/Schrijven Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Geeft de onderste marge (points) in een TextFrame terug of stelt deze in. Lezen/Schrijven Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Geeft de linkermarge (points) in een TextFrame terug of stelt deze in. Lezen/Schrijven Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Geeft de rechtermarge (points) in een TextFrame terug of stelt deze in. Lezen/Schrijven Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Geeft de bovenmarge (points) in een TextFrame terug of stelt deze in. Lezen/Schrijven Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Specificeert de aangepaste rotatie die op de tekst binnen de omhullende doos wordt toegepast. Indien niet opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Indien wel opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dus de vorm kan een rotatie hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende visuele tekstrotatiewaarde, samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen/Schrijven Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Bepaalt de tekstoriëntatie. De resulterende visuele tekstrotatiewaarde, samengevat uit deze eigenschap en de aangepaste hoek in de eigenschap RotationAngle. Lezen/Schrijven [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat 3-D-effecteigenschappen voor een tekst vertegenwoordigt. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Geeft de tekstomslagvorm terug of stelt deze in. Lezen/Schrijven [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** als tekst is afgebroken bij de marges van TextFrame. Lezen/Schrijven [`NullableBool`](../nullablebool). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Haalt de effectieve formatteringsgegevens van het tekstframe op met de toegepaste overerving. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Geeft een hash-code terug. |

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interface [ITextFrameFormat](../itextframeformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->