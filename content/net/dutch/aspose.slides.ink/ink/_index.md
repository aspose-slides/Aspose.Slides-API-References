---
title: Ink
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een inktobject op een dia voor.
type: docs
weight: 7570
url: /nl/aspose.slides.ink/ink/
---
## Ink klasse

```csharp
public class Ink : GraphicalObject, IInk
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Geeft de alternatieve tekst die aan een shape is gekoppeld terug of stelt deze in. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Geeft de titel van de alternatieve tekst die aan een shape is gekoppeld terug of stelt deze in. Lezen/schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus.. Lezen/schrijven [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Geeft het aantal verbindingspunten op de shape terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Geeft de aangepaste gegevens van de shape terug. Alleen-lezen [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een shape zijn toegepast. Opmerking: kan null retourneren voor bepaalde typen shapes die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Geeft het FillFormat-object terug dat opvulopmaak-eigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde typen shapes die geen opvuleigenschappen hebben. Alleen-lezen [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Geeft de eigenschappen van het shapeframe terug of stelt deze in. Lezen/schrijven [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Geeft de vergrendelingen van de shape terug. Alleen-lezen [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Geeft de hoogte van de shape terug of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de shape verborgen is. Lezen/schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muisklik terug of stelt deze in. Lezen/schrijven [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Geeft de hyperlinkmanager terug. Alleen-lezen [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muis-over terug of stelt deze in. Lezen/schrijven [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Geeft de 'Markeer als decoratief' optie terug of stelt deze in. Lezen/schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de shape gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de shape TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Geeft het LineFormat-object terug dat lijnopmaak-eigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde typen shapes die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Geeft de naam van een shape terug of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Geeft een uniek identificatie-nummer binnen de dia terug dat gedurende de levensduur van de shape constant blijft en PowerPoint of interop-code in staat stelt de shape betrouwbaar vanuit elk deel van het document te refereren. Alleen-lezen UInt32. Zie ook [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de shape gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Geeft de placeholder voor een shape terug. Retourneert null als de shape geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Geeft de bovenliggende presentatie van een dia terug. Alleen-lezen [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Geeft de ruwe shapeframe-eigenschappen terug of stelt deze in. Lezen/schrijven [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Geeft het aantal graden terug of stelt dit in waarmee de opgegeven shape rond de z-as is geroteerd. Een positieve waarde duidt rotatie met de klok mee aan; een negatieve waarde duidt rotatie tegen de klok in aan. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Geeft de vergrendelingen van de shape terug. Alleen-lezen [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Geeft de bovenliggende dia van een shape terug. Alleen-lezen [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat 3d-effecteigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde typen shapes die geen 3d-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | Holt alle sporen die zich in het IInk-element [`IInkTrace`](../iinktrace) bevinden. Alleen-lezen. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Geeft een interne, presentatie-gebonden identifier terug die bedoeld is voor gebruik door add-ins of andere code. Aangezien deze waarde door de gebruiker of programmatisch kan worden heringesteld, mag deze niet worden behandeld als een permanente unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Geeft de breedte van de shape terug of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Geeft de x-coördinaat van de linkerbovenhoek van de shape terug of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Geeft de y-coördinaat van de linkerbovenhoek van de shape terug of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Geeft de positie van een shape in de z-volgorde terug. Shapes[0] geeft de shape terug die zich achterin de z-volgorde bevindt, en Shapes[Shapes.Count - 1] geeft de shape terug die zich voorin de z-volgorde bevindt. Alleen-lezen Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | Holt de collectie van aangepaste afbeeldingen die worden gebruikt om visuele effecten voor inkt-penseelstijlen te simuleren. Deze afbeeldingen worden gebruikt bij het renderen van inkt met specifieke [`InkEffectType`](../inkeffecttype)-waarden, zoals Galaxy, Rainbow, enz. Door uw eigen afbeeldingen te leveren, kunt u bepalen hoe elk inkt-effect verschijnt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Geeft een basis placeholder-shape terug (shape van de lay-out en/of masterslide waarvan de huidige shape is geërfd). Een null wordt geretourneerd als de huidige shape niet geërfd is. |
| [GetImage](../../aspose.slides/shape/getimage)() | Geeft een thumbnail van de shape terug. ShapeThumbnailBounds.Shape wordt standaard gebruikt als type voor de thumbnail-bounds. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Geeft een thumbnail van de shape terug. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Holt de visuele grenzen van de shape, berekend vanuit de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze shape geen placeholder is. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de Shape op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de Shape op als SVG-bestand. |

### Zie ook

* klasse [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IInk](../iink)
* namespace [Aspose.Slides.Ink](../../aspose.slides.ink)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->