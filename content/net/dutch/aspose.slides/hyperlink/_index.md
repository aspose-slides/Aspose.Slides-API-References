---
title: Hyperlink
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een hyperlink voor.
type: docs
weight: 5120
url: /nl/aspose.slides/hyperlink/
---
## Hyperlink klasse

Stelt een hyperlink voor.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Maakt een instantie van een hyperlink die naar een specifieke dia wijst. Opmerking: de gemaakte hyperlink moet worden toegewezen aan een object uit dezelfde presentatie, anders wordt de link opgeslagen als NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Maakt een instantie van een hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Maakt een instantie van een hyperlink met een andere hyperlink als bron, waarbij secundaire eigenschappen worden overschreven. |

## Properties

| Naam | Beschrijving |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Retourneert een hyperlink die de presentatie beëindigt. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Retourneert een hyperlink naar de eerste dia van de presentatie. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Retourneert een hyperlink naar de laatste dia van de presentatie. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Retourneert een hyperlink naar de laatst bekeken dia. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Retourneert een speciale "play mediafile" hyperlink. Wordt gebruikt in AudioFrame en VideoFrame. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Retourneert een hyperlink naar de volgende dia. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Retourneert een speciale "do nothing" hyperlink. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Retourneert een hyperlink naar de vorige dia. Alleen-lezen [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Retourneert het type van de actie van de Hyperlink. Alleen-lezen [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Stelt u in staat de basale IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Stelt de bron van de hyperlinkkleur voor - ofwel stijlen of gedeelte-opmaak. Lezen/Schrijven [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Specificeert de externe URL. Alleen-lezen String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Stelt een hyperlink voor die voor dit gedeelte is ingesteld, ongeacht de feitelijke inhoud van het gedeelte. PowerPoint gedraagt zich specifiek voor links en hun bijbehorende tekst in een gedeelte. Het staat toe om tekst voor de hyperlink te maken in de vorm van een geldige URL, verschillend van het daadwerkelijke adres van de link. In dit geval, wanneer u de link bekijkt in het bewerkingsvenster, wordt deze aangepast om overeen te komen met het tekstdeling. Deze eigenschap vertegenwoordigt de oorspronkelijke waarde van de hyperlink. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Bepaalt of de hyperlink moet worden gemarkeerd bij klikken. Lezen/Schrijven Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. Lezen/Schrijven Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Stelt het afspelende geluid van de hyperlink voor. Lezen/Schrijven [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Bepaalt of het geluid moet worden gestopt bij klikken op de hyperlink. Lezen/Schrijven Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink wanneer deze bestaat. Lezen/Schrijven String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Als de Hyperlink naar een specifieke dia wijst, retourneert deze dia. Alleen-lezen [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Retourneert de tekenreeks die mogelijk wordt weergegeven in een gebruikersinterface als geassocieerd met de bovenliggende hyperlink. Lezen/Schrijven String. |

## Methods

| Naam | Beschrijving |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Bepaalt of de twee Hyperlink-instantieën gelijk zijn. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Bepaalt of de twee Hyperlink-instantieën gelijk zijn. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Dient als een hashfunctie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en gegevensstructuren zoals een hash-tabel. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Test twee hyperlinks op gelijkheid. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Test twee hyperlinks op ongelijkheid. |

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->