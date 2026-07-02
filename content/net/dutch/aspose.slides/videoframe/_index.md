---
title: VideoFrame
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een video-fragment op een dia voor.
type: docs
weight: 11720
url: /nl/aspose.slides/videoframe/
---
## VideoFrame klasse

Stelt een video-fragment op een dia voor.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Geeft een collectie van aanpassingswaarden van de vorm terug. Alleen-lezen [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Geeft de alternatief-tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Geeft de titel van de alternatief-tekst die aan een vorm is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in de zwart-wit modus. Lezen/Schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Haalt de collectie van gesloten ondertitels op die aan het video-frame zijn gekoppeld. Deze eigenschap is alleen-lezen en geeft een [`ICaptionsCollection`](../icaptionscollection) terug met alle ondertiteltracks. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Geeft het aantal verbindingspunten op de vorm terug. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Geeft de aangepaste gegevens van de vorm terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Geeft het EffectFormat-object terug dat pixel-effecten bevat die op een vorm zijn toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Geeft het ingebedde video-object terug of stelt het in. Lezen/Schrijven [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Geeft het FillFormat-object terug dat opvul-opmaak eigenschappen bevat voor een vorm. Opmerking: kan null retourneren voor bepaalde vormen die geen opvul-eigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Geeft de eigenschappen van het vorm-frame terug of stelt ze in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Bepaalt of een video in volledig-schermmodus wordt weergegeven. Lezen/Schrijven Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt de hoogte van de vorm op of stelt deze in, gemeten in points. Lezen/Schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/Schrijven Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Bepaalt of een VideoFrame verborgen is. Lezen/Schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muisklik terug of stelt deze in. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Geeft de hyperlink-manager terug. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Geeft de hyperlink die is gedefinieerd voor muis-over terug of stelt deze in. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Bepaalt of het PictureFrame een Cameo-object is of niet. Alleen-lezen Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt de optie 'Mark as decorative' op of stelt deze in. Lezen/Schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Geeft het LineFormat-object terug dat lijn-opmaak eigenschappen bevat voor een vorm. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Geeft de naam van een videobestand dat aan een VideoFrame is gekoppeld terug of stelt deze in. Lezen/Schrijven String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Geeft de naam van een vorm terug of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/Schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Geeft een dia-gebonden unieke identifier terug die gedurende de levensduur van de vorm constant blijft en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elke plaats in het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Geeft het bovenliggende GroupShape-object terug als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Geeft het PictureFillFormat-object voor een picture-frame terug. Alleen-lezen [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Geeft de placeholder voor een vorm terug. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Bepaalt of een video wordt geloopt. Lezen/Schrijven Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Geeft de afspeelmodus van de video terug of stelt deze in. Lezen/Schrijven [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Geeft de bovenliggende presentatie van een dia terug. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Geeft de ruwe vorm-frame-eigenschappen terug of stelt deze in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Geeft de schaal van de hoogte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture-frame terug of stelt deze in. Waarde 1,0 komt overeen met 100 %. Lezen/Schrijven Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Geeft de schaal van de breedte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture-frame terug of stelt deze in. Waarde 1,0 komt overeen met 100 %. Lezen/Schrijven Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Bepaalt of een video automatisch naar het begin wordt teruggespoeld zodra de film klaar is met afspelen. Lezen/Schrijven Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Geeft het aantal graden terug of stelt deze in waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde geeft een draai met de klok mee aan; een negatieve waarde een draai tegen de klok in. Lezen/Schrijven Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Geeft de vergrendelingen van de vorm terug. Alleen-lezen [`IPictureFrameLock`](../ipictureframelock). (2 eigenschappen) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Geeft het stijlobject van de vorm terug. Alleen-lezen [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Geeft het AutoShape-type voor een PictureFrame terug of stelt dit in. Alle items van de set [`ShapeType`](../shapetype) zijn toegestaan, behalve alle soorten lijnen: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Geeft de bovenliggende dia van een vorm terug. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Geeft het ThreeDFormat-object terug dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Trim einde [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Trim begin [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Geeft een interne, presentatie-gebonden identifier terug die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herzien, mag hij niet worden behandeld als een blijvende unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Geeft het audiovolume terug of stelt dit in. Lezen/Schrijven [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt de breedte van de vorm op of stelt deze in, gemeten in points. Lezen/Schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in points. Lezen/Schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in points. Lezen/Schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Geeft de positie van een vorm in de z-volgorde terug. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] de vorm voorin de z-volgorde. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Maakt een array van de elementen van een vorm aan en retourneert deze. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basis-placeholder-vorm (vorm van de lay-out en/of masterslide waar de huidige vorm van is geërfd). Null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retourneert een kopie van het pad van de geometrische vorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de vorm. ShapeThumbnailBounds.Shape wordt standaard gebruikt voor de miniatuuraanduiding. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Werkt de geometrie van de vorm bij vanuit een [`IGeometryPath`](../igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm ([`ShapeType`](../geometryshape/shapetype)) naar Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Werkt de geometrie van de vorm bij vanuit een array van [`IGeometryPath`](../igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm ([`ShapeType`](../geometryshape/shapetype)) naar Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van Shape op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van Shape op als SVG-bestand. |

### Zie ook

* klasse [PictureFrame](../pictureframe)
* interface [IVideoFrame](../ivideoframe)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->