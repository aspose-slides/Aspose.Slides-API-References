---
title: IShape
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en form på en bild.
type: docs
weight: 6950
url: /sv/aspose.slides/ishape/
---
## IShape-gränssnitt

Representerar en form på en bild.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är kopplad till en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln för den alternativa texten som är kopplad till en form. Läs/skriv String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Tillåter att hämta basgränssnittet IHyperlinkContainer. Endast läs [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Tillåter att hämta basgränssnittet ISlideComponent. Endast läs [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Egenskapen specificerar hur en form ska renderas i svartvit visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Endast läs Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Returnerar formens anpassade data. Endast läs [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. Endast läs [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformatinställningar för en form. Endast läs [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Returnerar eller anger ramens egenskaper för formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Hämtar eller anger formens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Bestämmer om formen är dold. Läs/skriv Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Bestämmer om formen är grupperad. Endast läs Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Bestämmer om formen är TextHolder. Endast läs Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformateringsinställningar för en form. Endast läs [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Returnerar eller anger namnet på en form. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Returnerar en bildspecifik unik identifierare som förblir konstant under formens livslängd och låter PowerPoint eller interop-kod referera till formen på ett pålitligt sätt från någon plats i dokumentet. Endast läs UInt32. Se även [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Returnerar förälder-GroupShape-objektet om formen är grupperad. Annars returneras null. Endast läs [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Returnerar platshållaren för en form. Endast läs [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Returnerar eller anger de råa ramens egenskaper för formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Returnerar formens lås. Endast läs [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller linjeformateringsinställningar för en form. Endast läs [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Returnerar en intern, presentationsspecifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel. Endast läs UInt32. Se även [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Hämtar eller anger formens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Endast läs Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en angiven. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudsidan som den aktuella formen ärvts från). null returneras om den aktuella formen inte är ärvd. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Returnerar formens miniatyrbild. ShapeThumbnailBounds.Shape används som standard för miniatyrbildens gränstyp. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyrbild. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Anger att denna form inte är en platshållare. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Sparar innehållet i Shape som SVG-fil. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Sparar innehållet i Shape som SVG-fil. |

### Se även

* gränssnitt [IHyperlinkContainer](../ihyperlinkcontainer)
* gränssnitt [ISlideComponent](../islidecomponent)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->