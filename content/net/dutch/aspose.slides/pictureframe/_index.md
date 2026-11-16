---
title: PictureFrame
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een frame voor met een afbeelding erin.
type: docs
weight: 9430
url: /nl/aspose.slides/pictureframe/
---
## PictureFrame klasse

Representeert een frame met een afbeelding erin.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retourneert een verzameling van aanpassingswaarden van de shape. Alleen-lezen [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourneert of stelt de alternatieve tekst in die aan een shape is gekoppeld. Lezen/Schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourneert of stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. Lezen/Schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. Lezen/Schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourneert het aantal verbindingspunten op de shape. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourneert de aangepaste gegevens van de shape. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een shape worden toegepast. Opmerking: kan null teruggeven voor bepaalde typen shapes die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourneert het FillFormat-object dat opvulopmaak-eigenschappen voor een shape bevat. Opmerking: kan null teruggeven voor bepaalde typen shapes die geen opvuleigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourneert of stelt de eigenschappen van het shape-frame in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt de hoogte van de shape op of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de shape verborgen is. Lezen/Schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourneert de hyperlinkmanager. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover. Lezen/Schrijven [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Bepaalt of de PictureFrame een Cameo-object is of niet. Alleen-lezen Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt de optie 'Mark as decorative' op of stelt deze in. Lezen/Schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de shape gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de shape TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een shape bevat. Opmerking: kan null teruggeven voor bepaalde typen shapes die geen lijn-eigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourneert of stelt de naam van een shape in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/Schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retourneert een uniek, per slide, identifier die constant blijft gedurende de levensduur van de shape en PowerPoint of interop-code in staat stelt de shape betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourneert het bovenliggende GroupShape-object als de shape gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Retourneert het PictureFillFormat-object voor een picture frame. Alleen-lezen [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Retourneert de vergrendelingen van de shape. Alleen-lezen [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourneert de placeholder voor een shape. Retourneert null als de shape geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourneert de bovenliggende presentatie van een slide. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourneert of stelt de ruwe eigenschappen van het shape-frame in. Lezen/Schrijven [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Retourneert of stelt de schaal van de hoogte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame in. Waarde 1,0 komt overeen met 100 %. Lezen/Schrijven Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Retourneert of stelt de schaal van de breedte (relatief aan de oorspronkelijke afbeeldingsgrootte) van het picture frame in. Waarde 1,0 komt overeen met 100 %. Lezen/Schrijven Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourneert of stelt het aantal graden in waarmee de opgegeven shape rond de z-as wordt gedraaid. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde op rotatie tegen de klok in. Lezen/Schrijven Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Retourneert de vergrendelingen van de shape. Alleen-lezen [`IPictureFrameLock`](../ipictureframelock). (2 eigenschappen) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retourneert het stijlobject van de shape. Alleen-lezen [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Retourneert of stelt het AutoShape-type in voor een PictureFrame. Alle items van de set [`ShapeType`](../shapetype) zijn toegestaan, behalve alle soorten lijnen: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourneert de bovenliggende slide van een shape. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een shape bevat. Opmerking: kan null teruggeven voor bepaalde typen shapes die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retourneert een interne, per presentatie, identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden heringericht, mag deze niet worden behandeld als een persistent unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt de breedte van de shape op of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt de x-coördinaat van de linkerbovenhoek van de shape op of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt de y-coördinaat van de linkerbovenhoek van de shape op of stelt deze in, gemeten in punten. Lezen/Schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourneert de positie van een shape in de z-volgorde. Shapes[0] geeft de shape aan de achterkant van de z-volgorde terug, en Shapes[Shapes.Count - 1] geeft de shape aan de voorkant van de z-volgorde terug. Alleen-lezen Int32. |

## Methoden

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen bestaat en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Maakt een array van shape-elementen aan en retourneert deze. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basis-placeholder-shape (shape van de lay-out en/of masterslide waarvan de huidige shape is ge-erfd). Retourneert null als de huidige shape niet is ge-erfd. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retourneert een kopie van het pad van de geometrische shape. Coördinaten zijn relatief aan de linkerbovenhoek van de shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de shape. Standaard wordt ShapeThumbnailBounds.Shape gebruikt voor het type miniatuurbereik van de shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de shape op, berekend aan de hand van de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze shape geen placeholder is. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Werk de geometrie van de shape bij vanuit het [`IGeometryPath`](../igeometrypath)-object. Coördinaten moeten relatief aan de linkerbovenhoek van de shape zijn. Wijzigt het type van de shape ([`ShapeType`](../geometryshape/shapetype)) naar Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Werk de geometrie van de shape bij vanuit een array van [`IGeometryPath`](../igeometrypath). Coördinaten moeten relatief aan de linkerbovenhoek van de shape zijn. Wijzigt het type van de shape ([`ShapeType`](../geometryshape/shapetype)) naar Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van de Shape op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van de Shape op als SVG-bestand. |

### Voorbeelden

The following examples shows how to change Audio Frame Thumbnail.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Voegt een audioframe toe aan de dia met een opgegeven positie en grootte.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Voegt een afbeelding toe aan de presentatie-bronnen.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Stelt de afbeelding in voor het audioframe.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//Slaat de gewijzigde presentatie op naar schijf
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* klasse [GeometryShape](../geometryshape)
* interface [IPictureFrame](../ipictureframe)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->