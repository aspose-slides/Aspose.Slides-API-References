---
title: Shape
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en form på en bild.
type: docs
weight: 9810
url: /sv/aspose.slides/shape/
---
## Shape klass

Representerar en form på en bild.

```csharp
public class Shape : IShape
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln på den alternativa texten som är associerad med en form. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en form renderas i svartvita visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningsplatser på formen. Läs-endast Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Läs-endast [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. Obs: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Läs-endast [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformaterings-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har fyllnings-egenskaper. Läs-endast [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger formens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger höjden på formen, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Avgör om formen är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som är definierad för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänks-hanteraren. Läs-endast [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som är definierad för musöver. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Avgör om formen är grupperad. Läs-endast Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Avgör om formen är TextHolder_PPT. Läs-endast Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har linje-egenskaper. Läs-endast [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tom sträng om det behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en bild-avgränsad unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från var som helst i dokumentet. Läs-endast UInt32. Se även [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar föräldern GroupShape-objektet om formen är grupperad. Annars returneras null. Läs-endast [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Läs-endast [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar föräldrapresentationen för en bild. Läs-endast [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa ram-egenskaperna för formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Returnerar formens lås. Läs-endast [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar föräldrabilden för en form. Läs-endast [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Läs-endast [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-avgränsad identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmeras, får det inte behandlas som en beständig unik nyckel. Läs-endast UInt32. Se även [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger bredden på formen, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Läs-endast Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en angiven. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen är ärvd från). Null returneras om den aktuella formen inte är ärvd. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | Returnerar formens miniatyrbild. ShapeThumbnailBounds.Shape används som standard för miniatyrbildens gränsstyp. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyrbild. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar den visuella gränsen för formen beräknad från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna form inte är en platshållare. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Sparar innehållet i Shape som SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Sparar innehållet i Shape som SVG-fil. |

### Se även

* gränssnitt [IShape](../ishape)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->