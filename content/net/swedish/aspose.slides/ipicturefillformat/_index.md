---
title: IPictureFillFormat
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en bildfyllnadsstil.
type: docs
weight: 6670
url: /sv/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat gränssnitt

Representerar en bildfyllnadsstil.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Egenskaper

| Name | Description |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Tillåter att hämta bas-IFillParamSource-gränssnittet. Skrivskyddad [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Returnerar eller anger antalet procent av bildens faktiska höjd som beskärs bort från bildens botten. Läs/skriv Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Returnerar eller anger antalet procent av bildens faktiska bredd som beskärs bort från bildens vänstra sida. Läs/skriv Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Returnerar eller anger antalet procent av bildens faktiska bredd som beskärs bort från bildens högra sida. Läs/skriv Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Returnerar eller anger antalet procent av bildens faktiska höjd som beskärs bort från bildens övre kant. Läs/skriv Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Returnerar eller anger dpi som används för att fylla en bild. Läs/skriv Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Returnerar bilden. Skrivskyddad [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Returnerar eller anger bildens fyllnadsläge. Läs/skriv [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Returnerar eller anger den nedre kanten på fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns nedre kant i figurens omslutande ruta. En positiv procent anger en inbuktning, medan en negativ procent anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Returnerar eller anger den vänstra kanten på fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns vänstra kant i figurens omslutande ruta. En positiv procent anger en inbuktning, medan en negativ procent anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Returnerar eller anger den högra kanten på fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns högra kant i figurens omslutande ruta. En positiv procent anger en inbuktning, medan en negativ procent anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Returnerar eller anger den övre kanten på fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns övre kant i figurens omslutande ruta. En positiv procent anger en inbuktning, medan en negativ procent anger en utskjutning. Läs/skriv Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Returnerar eller anger hur texturen är justerad inom figuren. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över figuren. Läs/skriv [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Vänder texturn på dess horisontella, vertikala eller båda axlar. Läs/skriv [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Returnerar eller anger den horisontella förskjutningen av texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster. Läs/skriv Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Returnerar eller anger den vertikala förskjutningen av texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Läs/skriv Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Returnerar eller anger den horisontella skalan för texturfyllnad som en procent. Läs/skriv Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Returnerar eller anger den vertikala skalan för texturfyllnad som en procent. Läs/skriv Single. |

## Metoder

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Tar bort beskurna områden av den fyllda bilden. |

### Se även

* gränssnitt [IFillParamSource](../ifillparamsource)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->