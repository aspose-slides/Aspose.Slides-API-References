---
title: Hyperlink
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een hyperlink voor.
type: docs
weight: 5140
url: /nl/aspose.slides/hyperlink/
---
## Hyperlink klasse

Stelt een hyperlink voor.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Constructors

| Name | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Maakt een instantie van een hyperlink die naar een specifieke dia verwijst. Opmerking: de gemaakte hyperlink moet worden toegewezen aan een object uit dezelfde presentatie, anders wordt de link opgeslagen als NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Maakt een instantie van een hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Maakt een instantie van een hyperlink met een andere hyperlink als bron, waarbij secundaire eigenschappen worden overschreven. |

## Properties

| Name | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Geeft een hyperlink terug die de show beëindigt. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Geeft een hyperlink terug naar de eerste dia van de presentatie. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Geeft een hyperlink terug naar de laatste dia van de presentatie. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Geeft een hyperlink terug naar de laatst bekeken dia. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Geeft een speciale "play mediafile" hyperlink terug. Wordt gebruikt in AudioFrame en VideoFrame. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Geeft een hyperlink terug naar de volgende dia. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Geeft een speciale "do nothing" hyperlink terug. Alleen-lezen [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Geeft een hyperlink terug naar de vorige dia. Alleen-lezen [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Geeft het type van de actie van Hyperlink terug. Alleen-lezen [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Staat toe de basis IPresentationComponent interface op te halen. Alleen-lezen [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Stelt de bron van hyperlinjkleur voor - ofwel stijlen of deelopmaak. Lezen/Schrijven [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Specificeert de externe URL. Alleen-lezen String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Stelt een hyperlink voor die is ingesteld voor dit gedeelte zonder rekening te houden met de daadwerkelijke inhoud van het gedeelte. PowerPoint gedraagt zich specifiek voor koppelingen en hun overeenkomstige tekst in een gedeelte. Het maakt het mogelijk om tekst voor de hyperlink te creëren in de vorm van een geldige URL, verschillend van het werkelijke adres van de koppeling. In dit geval wordt, wanneer u de koppeling bekijkt in het bewerkingsvenster, de tekst aangepast om overeen te komen met het tekstgedeelte. Deze eigenschap vertegenwoordigt de oorspronkelijke waarde van de hyperlink. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Bepaalt of de hyperlink gemarkeerd moet worden bij klikken. Lezen/Schrijven Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Bepaalt of het doel van de bovenliggende hyperlink toegevoegd moet worden aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. Lezen/Schrijven Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Stelt het afspelende geluid van de hyperlink voor. Lezen/Schrijven [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Bepaalt of het geluid moet worden gestopt bij een hyperlinkklik. Lezen/Schrijven Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Geeft het frame binnen de bovenliggende HTML-frameset terug voor het doel van de bovenliggende hyperlink wanneer deze bestaat. Lezen/Schrijven String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Als de Hyperlink naar een specifieke dia verwijst, wordt deze dia teruggegeven. Alleen-lezen [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Geeft de tekenreeks terug die in een gebruikersinterface kan worden weergegeven als geassocieerd met de bovenliggende hyperlink. Lezen/Schrijven String. |

## Methods

| Name | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Bepaalt of de twee Hyperlink-instanties gelijk zijn. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Bepaalt of de twee Hyperlink-instanties gelijk zijn. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Dient als een hash-functie voor een specifiek type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hash-tabel. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Test twee hyperlinks op gelijkheid. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Test twee hyperlinks op ongelijkheid. |

### Zie ook

* klasse [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->