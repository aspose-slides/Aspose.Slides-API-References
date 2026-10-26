---
title: TextFrameFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Bevat de formatTextFrameFormatting-eigenschappen van TextFrames.
type: docs
weight: 10960
url: /nl/aspose.slides/textframeformat/
---
## TextFrameFormat klasse

Bevat de formatTextFrameFormatting-eigenschappen van TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Initialiseert een nieuwe instantie van [`TextFrameFormat`](../textframeformat) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Retourneert of stelt verticale ankertekst in een TextFrame in. Lezen/Schrijven [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe de basis IPresentationComponent-interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Retourneert of stelt de autofit-modus van de tekst in. Lezen/Schrijven [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Als NullableBool.True dan moet de tekst horizontaal gecentreerd worden in de doos. Lezen/Schrijven [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Retourneert of stelt het aantal kolommen in het tekstgebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent een ongedefinieerde waarde. Lezen/Schrijven Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Retourneert of stelt de ruimte tussen tekstreeks in het tekstgebied in (in punten). Dit is alleen van toepassing wanneer er meer dan 1 kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lezen/Schrijven Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Haalt op of stelt in dat tekst plat blijft zelfs als een 3-D-rotatie-effect is toegepast. Lezen/Schrijven Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Retourneert of stelt de ondermarge (punten) in een TextFrame in. Lezen/Schrijven Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Retourneert of stelt de linkermarge (punten) in een TextFrame in. Lezen/Schrijven Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Retourneert of stelt de rechtermarge (punten) in een TextFrame in. Lezen/Schrijven Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Retourneert of stelt de bovemarge (punten) in een TextFrame in. Lezen/Schrijven Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Specificeert een aangepaste rotatie die op de tekst binnen de omvattende doos wordt toegepast. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als hij wel is opgegeven, wordt hij onafhankelijk van de vorm toegepast. De vorm kan dus een rotatie hebben naast de tekstrotatie. De resulterende visuele tekstrotatie wordt samengevat vanuit deze eigenschap en de vooraf gedefinieerde verticale type in TextVerticalType. Lezen/Schrijven Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Bepaalt de tekstoriëntatie. De resulterende visuele tekstrotatie wordt samengevat vanuit deze eigenschap en de aangepaste hoek in RotationAngle. Lezen/Schrijven [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Retourneert het ThreeDFormat-object dat de 3-D-effecteigenschappen voor een tekst weergeeft. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Haalt op of stelt de vorm voor tekstomloop in. Lezen/Schrijven [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** als tekst wordt omgeslagen bij de marges van de TextFrame. Lezen/Schrijven [`NullableBool`](../nullablebool). |

## Methodes

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergelijkt met het opgegeven object. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Haalt effectieve tekstframe-opmaakgegevens op met de toegepaste overerving. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourneert hashcode. |

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interface [ITextFrameFormat](../itextframeformat)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->