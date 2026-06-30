---
title: PictureFillFormat
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en bildfyllnadsstil.
type: docs
weight: 9370
url: /sv/aspose.slides/picturefillformat/
---
## PictureFillFormat klass

Representerar en bildfyllnadsstil.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Skrivskyddad [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Returnerar eller anger antalet procent av den verkliga bildhöjden som beskärs bort från bildens botten. Läs/skriv Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Returnerar eller anger antalet procent av den verkliga bildbredden som beskärs bort från bildens vänstra sida. Läs/skriv Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Returnerar eller anger antalet procent av den verkliga bildbredden som beskärs bort från bildens högra sida. Läs/skriv Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Returnerar eller anger antalet procent av den verkliga bildhöjden som beskärs bort från bildens övre kant. Läs/skriv Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Returnerar eller anger dpi som används för att fylla en bild. Läs/skriv Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Returnerar bilden. Skrivskyddad [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Returnerar eller anger bildens fyllnadsläge. Läs/skriv [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Returnerar eller anger den nedre kanten av fyllnadsrektangeln som definieras av en procentuell förskjutning från rektangelns nedre kant i formens begränsningsram. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Returnerar eller anger den vänstra kanten av fyllnadsrektangeln som definieras av en procentuell förskjutning från rektangelns vänstra kant i formens begränsningsram. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Returnerar eller anger den högra kanten av fyllnadsrektangeln som definieras av en procentuell förskjutning från rektangelns högra kant i formens begränsningsram. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Returnerar eller anger den övre kanten av fyllnadsrektangeln som definieras av en procentuell förskjutning från rektangelns övre kant i formens begränsningsram. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Läs/skriv Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Returnerar eller anger hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Läs/skriv [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Vänder texturplattan horisontellt, vertikalt eller båda axlarna. Läs/skriv [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Returnerar eller anger den horisontella förskjutningen av texturen från formens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster. Läs/skriv Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Returnerar eller anger den vertikala förskjutningen av texturen från formens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Läs/skriv Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Returnerar eller anger den horisontella skalan för texturfyllnad som en procentandel. Läs/skriv Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Returnerar eller anger den vertikala skalan för texturfyllnad som en procentandel. Läs/skriv Single. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt raderas även beskurna områden. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt raderas även beskurna områden. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Raderar beskurna områden av fyllnadens bild. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Jämför med angivet objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returnerar hashkod. |

### Se även

* klass [PVIObject](../pviobject)
* gränssnitt [IPictureFillFormat](../ipicturefillformat)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->