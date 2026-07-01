---
title: Table
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en tabell på en bild.
type: docs
weight: 10840
url: /sv/aspose.slides/table/
---
## Table klass

Representerar en tabell på en bild.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa text som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln på den alternativa texten som är associerad med en form. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en form ska renderas i svart-vit visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Returnerar samlingen av kolumner. Endast läsning [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Endast läsning Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Endast läsning [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form. Obs: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Endast läsning [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Returnerar ett TableFormat.FillFormat-objekt som innehåller fyllningsformatet för Tabellen. Endast läsning [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Avgör om den första kolumnen i en tabell ska ritas med särskild formatering. Läs/skriv Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Avgör om den första raden i en tabell ska ritas med särskild formatering. Läs/skriv Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger formens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returnerar formens lås. Endast läsning [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger höjden på formen, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Avgör om formen är dold. Läs/skriv Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Avgör om jämna rader ska ritas med en annan formatering. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänkhanteraren. Endast läsning [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för muspekning. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Avgör om formen är grupperad. Endast läsning Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Avgör om formen är TextHolder_PPT. Endast läsning Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Returnerar cellen vid de angivna kolumn- och radindexen. Endast läsning [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Avgör om den sista kolumnen i en tabell ska ritas med särskild formatering. Läs/skriv Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Avgör om den sista raden i en tabell ska ritas med särskild formatering. Läs/skriv Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har linje-egenskaper. Endast läsning [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tom sträng om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en bild-avgränsad unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från vilken plats som helst i dokumentet. Endast läsning UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar överordnat GroupShape-objekt om formen är grupperad. Annars returneras null. Endast läsning [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Endast läsning [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Endast läsning [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger ram-egenskaperna för den råa formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Avgör om tabellen har läsordning från höger till vänster. Läs/skriv Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Returnerar samlingen av rader. Endast läsning [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returnerar formens lås. Endast läsning [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 egenskaper) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en form. Endast läsning [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Hämtar eller anger inbyggd tabellstil. Läs/skriv [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Returnerar TableFormat-objektet som innehåller formaterings-egenskaper för denna tabell. Endast läsning [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Endast läsning [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-avgränsad identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel. Endast läsning UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Avgör om jämna kolumner ska ritas med en annan formatering. Läs/skriv Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger bredden på formen, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre-vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre-vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Endast läsning Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om det inte finns någon och sätter platshållaregenskaperna till en specificerad. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen ärvs från). Null returneras om den aktuella formen inte ärvs. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar formens miniatyr. ShapeThumbnailBounds.Shape används som standard för miniatyrens bounds-typ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyr. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Slår ihop angränsande celler. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Anger att denna form inte är en platshållare. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Sätter definierade styckeformat-egenskaper för alla tabellcellers stycken. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Sätter definierade portionsformat-egenskaper för alla tabellcellers portioner. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Sätter definierade textramformat-egenskaper för alla tabellcellers textram. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar innehållet i Form som SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar innehållet i Form som SVG-fil. |

### Se även

* klass [GraphicalObject](../graphicalobject)
* gränssnitt [ITable](../itable)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->