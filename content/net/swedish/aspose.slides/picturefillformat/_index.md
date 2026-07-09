---
title: PictureFillFormat
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en bildfyllnadsstil.
type: docs
weight: 9390
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
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Tillåter att hämta bas-IPresentationComponent-gränssnittet. Endast läsning [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Returnerar eller anger antalet procent av bildens faktiska höjd som beskärs bort från bildens nederkant. Läs/skriv Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Returnerar eller anger antalet procent av bildens faktiska bredd som beskärs bort från bildens vänstra sida. Läs/skriv Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Returnerar eller anger antalet procent av bildens faktiska bredd som beskärs bort från bildens högra sida. Läs/skriv Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Returnerar eller anger antalet procent av bildens faktiska höjd som beskärs bort från bildens överkant. Läs/skriv Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Returnerar eller anger dpi som används för att fylla en bild. Läs/skriv Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Returnerar bilden. Endast läsning [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Returnerar eller anger bildens fyllnadsläge. Läs/skriv [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Returnerar eller anger den nedre kanten av fyllningsrektangeln som definieras av ett procentuellt avstånd från figurens omgivningsramens nedre kant. En positiv procentsats anger en inskjutning, medan en negativ procentsats anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Returnerar eller anger den vänstra kanten av fyllningsrektangeln som definieras av ett procentuellt avstånd från figurens omgivningsramens vänstra kant. En positiv procentsats anger en inskjutning, medan en negativ procentsats anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Returnerar eller anger den högra kanten av fyllningsrektangeln som definieras av ett procentuellt avstånd från figurens omgivningsramens högra kant. En positiv procentsats anger en inskjutning, medan en negativ procentsats anger en utskjutning. Läs/skriv Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Returnerar eller anger den övre kanten av fyllningsrektangeln som definieras av ett procentuellt avstånd från figurens omgivningsramens övre kant. En positiv procentsats anger en inskjutning, medan en negativ procentsats anger en utskjutning. Läs/skriv Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Returnerar eller anger hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Läs/skriv [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Vänder texturtilelet horisontellt, vertikalt eller båda axlarna. Läs/skriv [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Returnerar eller anger den horisontella förskjutningen av texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster. Läs/skriv Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Returnerar eller anger den vertikala förskjutningen av texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Läs/skriv Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Returnerar eller anger den horisontella skalan för texturfyllnaden som en procentandel. Läs/skriv Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Returnerar eller anger den vertikala skalan för texturfyllnaden som en procentandel. Läs/skriv Single. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Ta bort beskurna områden av den fyllda bilden. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Jämför med angivet objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returnerar hash-kod. |

### Se även

* klass [PVIObject](../pviobject)
* gränssnitt [IPictureFillFormat](../ipicturefillformat)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->