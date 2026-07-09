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

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Geeft of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Geeft of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Staat toe de basis-interface IHyperlinkContainer op te halen. Alleen-lezen [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Staat toe de basis-interface ISlideComponent op te halen. Alleen-lezen [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Geeft het aantal verbindingspunten op de vorm terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Geeft de aangepaste gegevens van de vorm terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een vorm zijn toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Geeft het FillFormat-object terug dat opvul-opmaak eigenschappen voor een vorm bevat. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Geeft of stelt de eigenschappen van het vormframe in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Geeft of stelt de hoogte van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/schrijven Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Geeft of stelt de optie 'Mark as decorative' in. Lezen/schrijven Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bepaalt of de vorm een TextHolder is. Alleen-lezen Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Geeft het LineFormat-object terug dat lijn-opmaak eigenschappen voor een vorm bevat. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Geeft of stelt de naam van een vorm in. Lezen/schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Geeft een uniek identifier binnen de dia die constant blijft gedurende de levensduur van de vorm en waarmee PowerPoint of interop-code de vorm betrouwbaar kan refereren vanuit elke locatie in het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Geeft de tijdelijke aanduiding (placeholder) voor een vorm terug. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Geeft of stelt de ruwe eigenschappen van het vormframe in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Geeft of stelt het aantal graden in waarmee de opgegeven vorm om de z-as is geroteerd. Een positieve waarde duidt op een klokrichting rotatie; een negatieve waarde duidt op een tegenklokrichting rotatie. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat lijn-opmaak eigenschappen voor een vorm bevat. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Geeft een interne, presentatie-specifieke identifier terug die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hersteld, mag hij niet worden behandeld als een permanente unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Geeft of stelt de breedte van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Geeft of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Geeft of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/schrijven Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Geeft de positie van een vorm in de z-volgorde terug. Shapes[0] geeft de vorm aan de achterkant van de z-volgorde terug, en Shapes[Shapes.Count - 1] geeft de vorm aan de voorkant van de z-volgorde terug. Alleen-lezen Int32. |

## Methoden

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Voegt een nieuw placeholder toe als er nog geen is en stelt de placeholder-eigenschappen in op een opgegeven. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Geeft een basis placeholder-vorm terug (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd). Een null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Geeft een miniatuur van de vorm terug. Standaard wordt het type ShapeThumbnailBounds.Shape gebruikt voor de miniatuurbereik. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Geeft een miniatuur van de vorm terug. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Slaat de inhoud van de vorm op als SVG-bestand. |

### Zie ook

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->