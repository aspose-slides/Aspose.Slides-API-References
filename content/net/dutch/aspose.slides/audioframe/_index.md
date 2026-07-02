---
title: AudioFrame
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een audiofragment op een dia voor.
type: docs
weight: 870
url: /nl/aspose.slides/audioframe/
---
## AudioFrame klasse

Stelt een audiofragment op een dia voor.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retourneert een collectie van aanpassingswaarden van de vorm. Alleen-lezen [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Retourneert of stelt een laatste track-index in Lezen/Schrijven Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Retourneert of stelt een laatste track-tijd in. Lezen/Schrijven Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Retourneert of stelt een starttrack-index in. Lezen/Schrijven Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Retourneert of stelt een starttrack-tijd in. Lezen/Schrijven Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/Schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Haalt de collectie van ondertitels op die aan het audioframe zijn gekoppeld. Deze eigenschap is alleen-lezen en retourneert een [`ICaptionsCollection`](../icaptionscollection) met alle ondertitelsporen. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourneert het aantal aansluitpunten op de vorm. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourneert het EffectFormat-object dat pixel-effecten op een vorm bevat. Opmerking: kan null retourneren voor bepaalde types vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Bepaalt of een geluid is ingesloten in een presentatie. Alleen-lezen Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Retourneert of stelt het ingesloten audio-object in. Lezen/Schrijven [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Lezen/Schrijven Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Specificeert de tijdsduur voor de eindfade-out van de media in milliseconden. Lezen/Schrijven Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourneert het FillFormat-object dat opvulopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde types vormen die geen opvuleigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourneert of stelt de eigenschappen van het vormframe in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt op of stelt de hoogte van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/Schrijven Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Bepaalt of een AudioFrame verborgen is. Lezen/Schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourneert de hyperlink-beheerder. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Bepaalt of het PictureFrame een Cameo-object is of niet. Alleen-lezen Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt op of stelt de optie 'Mark as decorative' in. Lezen/Schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde types vormen die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Retourneert of stelt de naam van een audiobestand in dat gekoppeld is aan een AudioFrame. Lezen/Schrijven String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourneert of stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/Schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retourneert een dia-specifieke unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders null. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Retourneert het PictureFillFormat-object voor een afbeeldingframe. Alleen-lezen [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Bepaalt of audio wordt afgespeeld over de dia's heen. Lezen/Schrijven Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Bepaalt of audio in een lus wordt afgespeeld. Lezen/Schrijven Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Retourneert of stelt de audio-afspeelmodus in. Lezen/Schrijven [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourneert of stelt de ruwe eigenschappen van het vormframe in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Retourneert of stelt de schaal van de hoogte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het afbeeldingframe in. Waarde 1.0 komt overeen met 100 %. Lezen/Schrijven Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Retourneert of stelt de schaal van de breedte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het afbeeldingframe in. Waarde 1.0 komt overeen met 100 %. Lezen/Schrijven Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Bepaalt of audio automatisch wordt teruggespoeld naar het begin na het afspelen. Lezen/Schrijven Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt op een klokwijzerige rotatie; een negatieve waarde duidt op een tegen-klokwijzerige rotatie. Lezen/Schrijven Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IPictureFrameLock`](../ipictureframelock). (2 eigenschappen) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retourneert het stijlobject van de vorm. Alleen-lezen [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Retourneert of stelt het AutoShape-type in voor een PictureFrame. Er zijn alle items van de set [`ShapeType`](../shapetype) toegestaan, behalve alle soorten lijnen: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde types vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Specificeert de tijdsduur die van het einde van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lezen/Schrijven Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Specificeert de tijdsduur die van het begin van de media moet worden verwijderd tijdens het afspelen, in milliseconden. Lezen/Schrijven Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retourneert een interne, presentatie-specifieke identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde kan worden hertoegewezen door de gebruiker of programmatisch, mag deze niet worden behandeld als een persistent unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Retourneert of stelt het audio-volume in. Lezen/Schrijven [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Retourneert of stelt het audio-volume in procenten. Lezen/Schrijven Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt op of stelt de breedte van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Lezen/Schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm vooraan de z-volgorde. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Maakt een array van elementen van de vorm aan en retourneert deze. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basis-placeholder-vorm (vorm van de lay-out en/of masterdia waar de huidige vorm van is geërfd). Null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retourneert een kopie van het pad van de geometrievorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de vorm. Het type ShapeThumbnailBounds.Shape wordt standaard gebruikt voor miniatuur-grenzen. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de vorm op berekend vanuit de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Werkt de geometrie van de vorm bij vanuit [`IGeometryPath`](../igeometrypath) object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm ([`ShapeType`](../geometryshape/shapetype)) naar Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Werkt de geometrie van de vorm bij vanuit een array van [`IGeometryPath`](../igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm ([`ShapeType`](../geometryshape/shapetype)) naar Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de vorm op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de vorm op als SVG-bestand. |

### Voorbeelden

De volgende voorbeelden tonen hoe je audio-afspeelopties kunt wijzigen.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Haalt de AudioFrame-vorm op
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Stelt de afspeelmodus in op afspelen bij klikken
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Stelt het volume in op Laag
    audioFrame.Volume = AudioVolumeMode.Low;
    // Stelt het audio in om over dia's heen af te spelen
    audioFrame.PlayAcrossSlides = true;
    // Schakelt de lus voor de audio uit
    audioFrame.PlayLoopMode = false;
    // Verbergt de AudioFrame tijdens de diavoorstelling
    audioFrame.HideAtShowing = true;
    // Spoelt de audio terug naar het begin na afspelen
    audioFrame.RewindAudio = true;
    // Slaat het PowerPoint-bestand op schijf
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* klasse [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->