---
title: IShape
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een vorm op een dia voor.
type: docs
weight: 6970
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
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Staat toe de basis IHyperlinkContainer interface op te halen. Alleen-lezen [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Staat toe de basis ISlideComponent interface op te halen. Alleen-lezen [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/Schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Geeft het aantal verbindingplaatsen op de vorm terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Geeft de aangepaste gegevens van de vorm terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een vorm zijn toegepast. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Geeft het FillFormat-object terug dat opmaak-eigenschappen voor vulling van een vorm bevat. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Geeft de eigenschappen van het vormframe terug of stelt deze in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Haalt de hoogte van de vorm op of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/Schrijven Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Haalt de optie 'Mark as decorative' op of stelt deze in. Lezen/Schrijven Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bepaalt of de vorm een TextHolder is. Alleen-lezen Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Geeft het LineFormat-object terug dat lijnopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Geeft de naam van een vorm terug of stelt deze in. Lezen/Schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Geeft een dia-specifieke unieke identifier terug die gedurende de levensduur van de vorm constant blijft en PowerPoint of interopcode in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Geeft de placeholder voor een vorm terug. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Geeft de ruwe eigenschappen van het vormframe terug of stelt deze in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Geeft het aantal graden terug of stelt dit in waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt op een klokwijzerrotatie; een negatieve waarde duidt op een tegenklokwijzerrotatie. Lezen/Schrijven Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat lijnopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Geeft een interne, presentatie-specifieke identifier terug die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden beschouwd als een permanente unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Haalt de breedte van de vorm op of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Geeft de positie van een vorm in de z-volgorde terug. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm voorin de z-volgorde. Alleen-lezen Int32. |

## Methoden

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Geeft een basis placeholder-vorm terug (vorm uit de lay-out en/of masterslide waarvan de huidige vorm is geërfd). Een null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Geeft een miniatuur van de vorm terug. ShapeThumbnailBounds.Shape wordt standaard gebruikt als type voor de miniatuurbounds. |
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