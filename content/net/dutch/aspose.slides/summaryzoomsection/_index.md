---
title: SummaryZoomSection
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een Summary Zoom Section-object voor in een Summary Zoom-frame.
type: docs
weight: 10800
url: /nl/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection klasse

Stelt een Summary Zoom Section-object voor in een Summary Zoom-frame.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Geeft de alternatieve tekst terug of stelt deze in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Geeft de titel van de alternatieve tekst terug of stelt deze in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Geeft het aantal aansluitpunten van de vorm terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Geeft de aangepaste gegevens van de vorm terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Geeft de tekstbeschrijving van het Summary Zoom Section-object terug. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een vorm worden toegepast. Opmerking: kan null teruggeven voor bepaalde soorten vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Geeft het FillFormat-object terug dat vulopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null teruggeven voor bepaalde soorten vormen die geen vul-eigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Geeft de eigenschappen van het vormframe terug of stelt deze in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt de hoogte van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Geeft de hyperlink terug die is gedefinieerd voor muisklik, of stelt deze in. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Geeft de hyperlinkbeheerder terug. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Geeft de hyperlink terug die is gedefinieerd voor muis-over, of stelt deze in. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Haalt het afbeeldingstype van een zoomobject op of stelt dit in. Lezen/schrijven [`ZoomImageType`](../zoomimagetype). Standaardwaarde: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt de optie ‘Markeer als decoratief’ op of stelt deze in. Lezen/schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Geeft het LineFormat-object terug dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null teruggeven voor bepaalde soorten vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Geeft de naam van een vorm terug of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Geeft een unieke identifier scoped aan de dia terug die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Geeft de placeholder voor een vorm terug. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Geeft de bovenliggende presentatie van een dia terug. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Geeft de ruwe eigenschappen van het vormframe terug of stelt deze in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Haalt het navigatiegedrag in diavoorstelling op of stelt dit in. Lezen/schrijven Boolean. Standaardwaarde: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Geeft het aantal graden terug of stelt dit in waarmee de opgegeven vorm rond de z-as wordt geroteerd. Een positieve waarde duidt op rechtsomdraai; een negatieve waarde duidt op linksomdraai. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Haalt de waarde op die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken. Lezen/schrijven Boolean. Standaardwaarde: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Geeft de bovenliggende dia van een vorm terug. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Haalt het sectie-object op waarnaar het Section Zoom-object linkt, of stelt dit in. Lezen/schrijven [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null teruggeven voor bepaalde soorten vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Geeft de teksttitel van het Summary Zoom Section-object terug. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Haalt de duur van de overgang tussen Zoom en dia op of stelt deze in. Lezen/schrijven Single. Standaardwaarde: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Geeft een interne, presentatie-scoped identifier terug die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag hij niet worden behandeld als een permanente unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt de breedte van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Haalt de afbeelding voor zoomobject op of stelt deze in. Lezen/schrijven [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Geeft de positie van een vorm in de z-volgorde terug. Shapes[0] retourneert de vorm achteraan in de z-volgorde, en Shapes[Shapes.Count - 1] de vorm vooraan. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen bestaat en stelt placeholder-eigenschappen in op een opgegeven placeholder. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Geeft een basis placeholder-vorm terug (vorm van de lay-out en/of masterdia waarvan de huidige vorm is geërfd). Null wordt geretourneerd als de huidige vorm niet is geërfd. |
| [GetImage](../../aspose.slides/shape/getimage)() | Geeft een miniatuur van de vorm terug. ShapeThumbnailBounds.Shape miniatuur-afgrenzingstype wordt standaard gebruikt. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Geeft een miniatuur van de vorm terug. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele afmetingen van de vorm op, berekend op basis van de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de vorm op als SVG-bestand. |

### Zie ook

* klasse [SectionZoomFrame](../sectionzoomframe)
* interface [ISummaryZoomSection](../isummaryzoomsection)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->