---
title: IPictureFillFormat
second_title: Aspose.Slides för .NET API-referens
description: Representerar en bildfyllnadsstil.
type: docs
weight: 6630
url: /sv/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interface

Representerar en bildfyllnadsstil.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Properties

| Namn | Beskrivning |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Tillåter att hämta bas-IFillParamSource-gränssnittet. Läs-endast [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Returnerar eller anger antalet procent av den verkliga bildhöjden som beskärs från bildens nederkant. Läs/skriv Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Returnerar eller anger antalet procent av den verkliga bildbredden som beskärs från bildens vänstra kant. Läs/skriv Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Returnerar eller anger antalet procent av den verkliga bildbredden som beskärs från bildens högra kant. Läs/skriv Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Returnerar eller anger antalet procent av den verkliga bildhöjden som beskärs från bildens överkant. Läs/skriv Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Returnerar eller anger dpi som används för att fylla en bild. Läs/skriv Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Returnerar bilden. Läs-endast [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Returnerar eller anger bildens fyllningsläge. Läs/skriv [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Returnerar eller anger nedre kanten av fyllningsrektangeln som definieras av en procentuell offset från rektangelns nedre kant. En positiv procent anger ett inskjut, medan en negativ procent anger ett utskjut. Läs/skriv Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Returnerar eller anger vänstra kanten av fyllningsrektangeln som definieras av en procentuell offset från rektangelns vänstra kant. En positiv procent anger ett inskjut, medan en negativ procent anger ett utskjut. Läs/skriv Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Returnerar eller anger högra kanten av fyllningsrektangeln som definieras av en procentuell offset från rektangelns högra kant. En positiv procent anger ett inskjut, medan en negativ procent anger ett utskjut. Läs/skriv Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Returnerar eller anger övre kanten av fyllningsrektangeln som definieras av en procentuell offset från rektangelns övre kant. En positiv procent anger ett inskjut, medan en negativ procent anger ett utskjut. Läs/skriv Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Returnerar eller anger hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Läs/skriv [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Vänder texturbrickan horisontellt, vertikalt eller båda axlarna. Läs/skriv [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Returnerar eller anger horisontell offset för texturen från formens origo i punkter. Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster. Läs/skriv Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Returnerar eller anger vertikal offset för texturen från formens origo i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Läs/skriv Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Returnerar eller anger horisontell skala för texturfyllning som procent. Läs/skriv Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Returnerar eller anger vertikal skala för texturfyllning som procent. Läs/skriv Single. |

## Methods

| Namn | Beskrivning |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angivna upplösning. Eventuellt raderas även beskurna områden. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angivna upplösning. Eventuellt raderas även beskurna områden. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Radera beskurna områden av fyllningsbilden. |

### See Also

* gränssnitt [IFillParamSource](../ifillparamsource)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->