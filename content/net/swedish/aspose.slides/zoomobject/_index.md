---
title: ZoomObject
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett Zoom-objekt i en bild.
type: docs
weight: 11850
url: /sv/aspose.slides/zoomobject/
---
## ZoomObject-klass

Representerar ett Zoom-objekt i en bild.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln på den alternativa texten som är associerad med en form. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en form renderas i svart-vit visningsläge.. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Skrivskyddad Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. Obs: kan returnera null för vissa typer av former som saknar effekt-egenskaper. Skrivskyddad [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformaterings-egenskaper för en form. Obs: kan returnera null för vissa typer av former som saknar fyllnings-egenskaper. Skrivskyddad [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger formens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returnerar formens lås. Skrivskyddad [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger formens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestämmer om formen är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänks-hanteraren. Skrivskyddad [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-över. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Hämtar eller anger bildtypen för ett zoom-objekt. Läs/skriv [`ZoomImageType`](../zoomimagetype). Standardvärde: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestämmer om formen är grupperad. Skrivskyddad Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestämmer om formen är TextHolder_PPT. Skrivskyddad Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en form. Obs: kan returnera null för vissa typer av former som saknar linje-egenskaper. Skrivskyddad [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tom sträng vid behov. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en unik identifierare som är begränsad till bild och förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken del av dokumentet som helst. Skrivskyddad UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar det överordnade GroupShape-objektet om formen är grupperad. Annars returneras null. Skrivskyddad [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Skrivskyddad [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Skrivskyddad [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa ram-egenskaperna för en form. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Hämtar eller anger navigeringsbeteendet i bildspel. Läs/skriv Boolean. Standardvärde: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den specificerade formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returnerar formens lås. Skrivskyddad [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 egenskaper) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Hämtar eller anger värdet som specificerar om Zoom ska använda bakgrunden på målbilden. Läs/skriv Boolean. Standardvärde: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en form. Skrivskyddad [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form. Obs: kan returnera null för vissa typer av former som saknar 3D-egenskaper. Skrivskyddad [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. Läs/skriv Single. Standardvärde: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-begränsad identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte behandlas som en beständig unik nyckel. Skrivskyddad UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger formens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Hämtar eller anger bild för zoom-objektet. Läs/skriv [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en angiven. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen ärvs från). Null returneras om den aktuella formen inte ärvs. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar en miniatyr av formen. ShapeThumbnailBounds.Shape används som standard för miniatyrens gränser. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar en miniatyr av formen. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar de visuella gränserna för formen beräknade utifrån dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Anger att denna form inte är en platshållare. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar innehållet i Form som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar innehållet i Form som en SVG-fil. |

### Se även

* klass [GraphicalObject](../graphicalobject)
* gränssnitt [IZoomObject](../izoomobject)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->