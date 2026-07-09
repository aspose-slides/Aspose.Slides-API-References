---
title: PictureFrame
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een frame met een afbeelding erin voor.
type: docs
weight: 9410
url: /nl/aspose.slides/pictureframe/
---
## PictureFrame klasse

Stelt een frame met een afbeelding erin voor.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retourneert een collectie aanpassingswaarden van de vorm. Alleen-lezen [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm worden toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourneert het FillFormat-object dat vulopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen vul-eigenschappen hebben. Alleen-lezen [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourneert of stelt de eigenschappen van het vormframe in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Haalt de hoogte van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bepaalt of de vorm verborgen is. Lezen/schrijven Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourneert de hyperlinkbeheerder. Alleen-lezen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover. Lezen/schrijven [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Bepaalt of de PictureFrame een Cameo-object is of niet. Alleen-lezen Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Haalt de optie 'Mark as decorative' op of stelt deze in. Lezen/schrijven Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bepaalt of de vorm gegroepeerd is. Alleen-lezen Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen lijneigenschappen hebben. Alleen-lezen [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourneert of stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/schrijven String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retourneert een uniek identificatienummer binnen de dia die gedurende de levensduur van de vorm constant blijft en waarmee PowerPoint of interopcode de vorm betrouwbaar vanuit elke locatie in het document kan refereren. Alleen-lezen UInt32. Zie ook [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders null. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Retourneert het PictureFillFormat-object voor een fotokader. Alleen-lezen [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourneert of stelt de ruwe eigenschappen van het vormframe in. Lezen/schrijven [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Retourneert of stelt de schaal van de hoogte (relatief ten opzichte van de oorspronkelijke afbeelding) van het fotokader in. Waarde 1.0 komt overeen met 100%. Lezen/schrijven Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Retourneert of stelt de schaal van de breedte (relatief ten opzichte van de oorspronkelijke afbeelding) van het fotokader in. Waarde 1.0 komt overeen met 100%. Lezen/schrijven Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourneert of stelt het aantal graden in waarop de opgegeven vorm rond de z-as is geroteerd. Een positieve waarde geeft rotatie met de klok mee aan; een negatieve waarde geeft rotatie tegen de klok in aan. Lezen/schrijven Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Retourneert de vergrendelingen van de vorm. Alleen-lezen [`IPictureFrameLock`](../ipictureframelock). (2 eigenschappen) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retourneert het stijlobject van de vorm. Alleen-lezen [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Retourneert of stelt het AutoShape-type voor een PictureFrame in. Er zijn alle toegestane items van de set [`ShapeType`](../shapetype), behalve allerlei lijnen: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retourneert een interne, voor de presentatie geldende identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatically kan worden herverdeeld, mag deze niet worden beschouwd als een blijvende unieke sleutel. Alleen-lezen UInt32. Zie ook [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Haalt de breedte van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op of stelt deze in, gemeten in punten. Lezen/schrijven Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achteraan in de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm vooraan in de z-volgorde. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Maakt een array van vorm-elementen aan en retourneert deze. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourneert een basis-placeholder-vorm (vorm van de lay-out en/of de masterslide waarvan de huidige vorm is geërfd). Null wordt geretourneerd als de huidige vorm niet geërfd is. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retourneert een kopie van het pad van de geometrievorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourneert een miniatuur van de vorm. ShapeThumbnailBounds.Shape wordt standaard gebruikt als miniatuur-grens type. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourneert een miniatuur van de vorm. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Haalt de visuele grenzen van de vorm op, berekend op basis van de gerenderde inhoud. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definieert dat deze vorm geen placeholder is. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Werk de vormgeometrie bij vanuit [`IGeometryPath`](../igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm ([`ShapeType`](../geometryshape/shapetype)) naar Aangepast. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Werk de vormgeometrie bij vanuit een array van [`IGeometryPath`](../igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm ([`ShapeType`](../geometryshape/shapetype)) naar Aangepast. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Slaat de inhoud van Shape op als SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Slaat de inhoud van Shape op als SVG-bestand. |

### Voorbeelden

De volgende voorbeelden laten zien hoe je de miniatuur van een Audio Frame wijzigt.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Voegt een audio-frame toe aan de dia met een opgegeven positie en grootte.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Voegt een afbeelding toe aan de presentatieresources.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Stelt de afbeelding in voor het audio-frame.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//Slaat de gewijzigde presentatie op naar schijf
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* klasse [GeometryShape](../geometryshape)
* interface [IPictureFrame](../ipictureframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->