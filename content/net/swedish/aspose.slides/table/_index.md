---
title: Table
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en tabell på en bild.
type: docs
weight: 10860
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
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln för den alternativa texten som är associerad med en form. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en form renderas i svart-vita visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Returnerar samlingen av kolumner. Läs-endast [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Läs-endast Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Läs-endast [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form. Obs: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Läs-endast [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Returnerar ett TableFormat.FillFormat-objekt som innehåller fyllningsformatet för tabellen. Läs-endast [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Bestämmer om den första kolumnen i en tabell ska ritas med en speciell formatering. Läs/skriv Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Bestämmer om den första raden i en tabell ska ritas med en speciell formatering. Läs/skriv Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger formens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returnerar formens lås. Läs-endast [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger formens höjd i punkt. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestämmer om formen är dold. Läs/skriv Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Bestämmer om jämna rader ska ritas med en annan formatering. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänk-hanteraren. Läs-endast [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-över. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet ”Mark as decorative”. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestämmer om formen är grupperad. Läs-endast Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestämmer om formen är TextHolder_PPT. Läs-endast Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Returnerar cellen på de angivna kolumn- och radindexen. Läs-endast [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Bestämmer om den sista kolumnen i en tabell ska ritas med en speciell formatering. Läs/skriv Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Bestämmer om den sista raden i en tabell ska ritas med en speciell formatering. Läs/skriv Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformat-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har linje-egenskaper. Läs-endast [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tom sträng om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en bild-specifik unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen var som helst i dokumentet. Läs-endast UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras null. Läs-endast [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Läs-endast [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den föräldrapresentation som en bild tillhör. Läs-endast [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa egenskaperna för formens ram. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Bestämmer om tabellen har läsriktning från höger till vänster. Läs-skriv Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antal grader som den angivna formen roteras runt z-axeln. Ett positivt värde betyder medurs rotation; ett negativt värde betyder moturs rotation. Läs/skriv Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Returnerar samlingen av rader. Läs-endast [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returnerar formens lås. Läs-endast [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 egenskaper) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den föräldrabild som en form tillhör. Läs-endast [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Hämtar eller anger inbyggd tabellstil. Läs/skriv [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Returnerar TableFormat-objektet som innehåller format-egenskaper för denna tabell. Läs-endast [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effekt-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Läs-endast [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentations-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel. Läs-endast UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Bestämmer om jämna kolumner ska ritas med en annan formatering. Läs/skriv Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger formens bredd i punkt. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre-vänstra hörn i punkt. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre-vänstra hörn i punkt. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar formens position i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Läs-endast Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från). Null returneras om den aktuella formen inte ärvs. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar formens miniatyrbild. Standard är ShapeThumbnailBounds.Shape för miniatyrbildens gränser. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyrbild. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Slår samman intilliggande celler. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna form inte är en platshållare. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Sätter definierade styckeformat-egenskaper på alla tabellcellers stycken. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Sätter definierade portionsformat-egenskaper på alla tabellcellers portioner. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Sätter definierade textramsformat-egenskaper på alla tabellcellers textramar. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar innehållet i Formen som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar innehållet i Formen som en SVG-fil. |

### Se även

* klass [GraphicalObject](../graphicalobject)
* gränssnitt [ITable](../itable)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->