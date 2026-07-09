---
title: ZoomFrame
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een Slide Zoom-object in een dia voor.
type: docs
weight: 11840
url: /nl/aspose.slides/zoomframe/
---
## ZoomFrame klasse

Stelt een Slide Zoom-object in een dia voor.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Geeft de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Geeft de titel van de alternatieve tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt gerenderd in zwart-wit weergavemodus. Lezen/schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Geeft het aantal verbindingspunten op de vorm terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Geeft de aangepaste gegevens van de vorm terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een vorm worden toegepast. Opmerking: kan null teruggeven voor bepaalde typen vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Geeft het FillFormat-object terug dat opvullingseigenschappen voor een vorm bevat. Opmerking: kan null teruggeven voor bepaalde typen vormen die geen opvullingseigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Geeft de eigenschappen van het vormframe terug of stelt ze in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Geeft de hoogte van de vorm terug of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muisklik terug of stelt deze in. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Geeft de hyperlink-beheerder terug. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muis-over terug of stelt deze in. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Geeft het afbeeldingstype van een zoom-object terug of stelt dit in. Lezen/schrijven [`ZoomImageType`](../zoomimagetype). Standaardwaarde: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Geeft de optie 'Mark as decorative' terug of stelt deze in. Lezen/schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Geeft het LineFormat-object terug dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null teruggeven voor bepaalde typen vormen die geen lijneigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Geeft de naam van een vorm terug of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Geeft een diavoor-specifieke unieke identifier terug die gedurende de levensduur van de vorm constant blijft en PowerPoint of interop-code in staat stelt de vorm vanaf elke locatie in het document betrouwbaar te refereren. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Retourneert anders null. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Geeft de tijdelijke aanduiding van een vorm terug. Retourneert null als de vorm geen tijdelijke aanduiding heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Geeft de bovenliggende presentatie van een dia terug. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Geeft de ruwe eigenschappen van het vormframe terug of stelt ze in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Geeft het navigatiegedrag in de diavoorstelling terug of stelt het in. Lezen/schrijven Boolean. Standaardwaarde: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Geeft het aantal graden dat de opgegeven vorm rond de z-as draait terug of stelt dit in. Een positieve waarde geeft een rotatie met de wijzerzin aan; een negatieve waarde een tegen-wijzerzin. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 eigenschappen) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Geeft de waarde terug of stelt deze in die aangeeft of de Zoom de achtergrond van de bestemmingsdia gebruikt. Lezen/schrijven Boolean. Standaardwaarde: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Geeft de bovenliggende dia van een vorm terug. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | Geeft het dia-object terug of stelt het in waarnaar het Slide Zoom-object linkt. Lezen/schrijven [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null teruggeven voor bepaalde typen vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Geeft de duur van de overgang tussen Zoom en dia terug of stelt deze in. Lezen/schrijven Single. Standaardwaarde: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Geeft een interne, presentatie-specifieke identifier terug die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatically kan worden hertoegewezen, mag hij niet worden gezien als een permanente unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Geeft de breedte van de vorm terug of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Geeft de x-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Geeft de y-coördinaat van de linkerbovenhoek van de vorm terug of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Geeft de afbeelding voor het zoom-object terug of stelt deze in. Lezen/schrijven [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Geeft de positie van een vorm in de z-volgorde terug. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm vooraan in de z-volgorde. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Geeft een basis-placeholder-vorm terug (vorm van de lay-out en/of master-dia waarvan de huidige vorm is geërfd). Een null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetImage](../../aspose.slides/shape/getimage)() | Geeft een miniatuur van de vorm terug. ShapeThumbnailBounds.Shape wordt standaard gebruikt voor miniatuur-afmetingen. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Geeft een miniatuur van de vorm terug. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Geeft de visuele afmetingen van de vorm terug, berekend vanuit de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de vorm op als SVG-bestand. |

### Zie ook

* klasse [ZoomObject](../zoomobject)
* interface [IZoomFrame](../izoomframe)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->