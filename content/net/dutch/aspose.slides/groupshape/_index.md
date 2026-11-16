---
title: GroupShape
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een groep vormen op een dia voor.
type: docs
weight: 5110
url: /nl/aspose.slides/groupshape/
---
## GroupShape klasse

Stelt een groep vormen op een dia voor.

```csharp
public class GroupShape : Shape, IGroupShape
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | Stelt u in staat de basis IShape interface te verkrijgen. Alleen-lezen [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/Schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Geeft het aantal verbindingspunten op de vorm terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Geeft de aangepaste gegevens van de vorm terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Geeft het EffectFormat object dat pixel-effecten op een vorm bevat terug. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Geeft het FillFormat object dat opvulopmaak-eigenschappen voor een vorm bevat terug. Opmerking: kan null retourneren voor bepaalde vormen die geen opvuleigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Geeft de eigenschappen van het vormframe terug of stelt deze in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Levert of stelt de hoogte van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/Schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muisklik terug of stelt deze in. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Geeft de hyperlink-manager terug. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muis-over terug of stelt deze in. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Levert of stelt de optie ‘Mark as decorative’ in. Lezen/Schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | Geeft het LineFormat object dat lijnopmaak-eigenschappen voor een vorm bevat terug. Opmerking: retourneert null voor GroupShape-objecten omdat zij geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Geeft de naam van een vorm terug of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/Schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Geeft een dia-gebonden unieke identifier die gedurende de levensduur van de vorm constant blijft en PowerPoint of interop-code in staat stelt de vorm vanaf elke locatie in het document betrouwbaar te refereren. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders null. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Geeft de placeholder voor een vorm terug. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Geeft de bovenliggende presentatie van een dia terug. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Geeft de ruwe eigenschappen van het vormframe terug of stelt deze in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Geeft het aantal graden terug waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt op klokwijs draaien; een negatieve waarde duidt op tegen de klok in draaien. Lezen/Schrijven Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGroupShapeLock`](../igroupshapelock). (2 properties) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | Geeft de collectie van vormen binnen de groep terug. Alleen-lezen [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Geeft de bovenliggende dia van een vorm terug. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Geeft het ThreeDFormat object dat 3D-effecteigenschappen voor een vorm bevat terug. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Geeft een interne, presentatie-gebonden identifier die bestemd is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden gewijzigd, mag deze niet worden behandeld als een blijvende unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Levert of stelt de breedte van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Levert of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Levert of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Geeft de positie van een vorm in de z-volgorde terug. Shapes[0] geeft de vorm aan de achterkant van de z-volgorde, en Shapes[Shapes.Count - 1] geeft de vorm aan de voorkant van de z-volgorde. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe indien er geen bestaat en stelt de placeholder-eigenschappen in op een opgegeven. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Geeft een basis placeholder-vorm terug (vorm van de lay-out en/of master-dia waar de huidige vorm van is geërfd). Een null wordt geretourneerd als de huidige vorm niet is geërfd. |
| [GetImage](../../aspose.slides/shape/getimage)() | Geeft een miniatuur van de vorm terug. ShapeThumbnailBounds.Shape-miniatuur-afmetingen-type wordt standaard gebruikt. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Geeft een miniatuur van de vorm terug. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Levert de visuele grenzen van de vorm op basis van de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de vorm op als SVG-bestand. |

### Zie ook

* klasse [Shape](../shape)
* interface [IGroupShape](../igroupshape)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->