---
title: IShape
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een vorm op een dia voor.
type: docs
weight: 6950
url: /nl/aspose.slides/ishape/
---
## IShape interface

Stelt een vorm op een dia voor.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Staat toe de basis IHyperlinkContainer interface op te halen. Alleen-lezen [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Staat toe de basis ISlideComponent interface op te halen. Alleen-lezen [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm zijn toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Retourneert het FillFormat-object dat vulopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Retourneert of stelt de eigenschappen van het vormkader in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Retourneert of stelt de hoogte van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/schrijven Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Retourneert of stelt de optie 'Mark as decorative' in. Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bepaalt of de vorm een TextHolder is. Alleen-lezen Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Retourneert of stelt de naam van een vorm in. Lezen/schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Retourneert een unieke identifier binnen de dia die gedurende de levensduur van de vorm constant blijft en PowerPoint of interopcode in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders null. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Retourneert de placeholder voor een vorm. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Retourneert of stelt de ruwe eigenschappen van het vormkader in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm wordt geroteerd rond de z-as. Een positieve waarde duidt op een klokwijzerrotatie; een negatieve waarde duidt op een tegenklokrotatie. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Retourneert het ThreeDFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Retourneert een interne, presentatiegebonden identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde kan worden herkend door de gebruiker of programmatisch, moet hij niet worden behandeld als een permanente unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Retourneert of stelt de breedte van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Retourneert of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Retourneert of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] geeft de vorm aan de achterkant van de z-volgorde terug, en Shapes[Shapes.Count - 1] geeft de vorm aan de voorkant van de z-volgorde terug. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen bestaat en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Retourneert een basisplaceholder-vorm (vorm van de lay-out en/of master-dia waarvan de huidige vorm is geërfd). Een null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Retourneert een miniatuur van de vorm. ShapeThumbnailBounds.Shape miniatuur-grens type wordt standaard gebruikt. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Slaat de inhoud van Shape op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Slaat de inhoud van Shape op als SVG-bestand. |

### Zie ook

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->