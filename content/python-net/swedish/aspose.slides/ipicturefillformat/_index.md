---
title: IPictureFillFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat klass

Representerar en bildfyllnadsstil.

IPictureFillFormat-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`dpi`](/slides/python-net/sv/aspose.slides/ipicturefillformat/dpi/) | Returnerar eller anger dpi som används för att fylla en bild.<br/>            Läs/skriv **int**. |
| [`picture_fill_mode`](/slides/python-net/sv/aspose.slides/ipicturefillformat/picture_fill_mode/) | Returnerar eller anger bildfyllnadsläget.<br/>            Läs/skriv [`PictureFillMode`](/slides/python-net/sv/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/sv/aspose.slides/ipicturefillformat/picture/) | Returnerar bilden.<br/>            Endast läs [`ISlidesPicture`](/slides/python-net/sv/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/sv/aspose.slides/ipicturefillformat/crop_left/) | Returnerar eller anger antalet procent av den verkliga bildens bredd som beskärs<br/>            på bildens vänstra sida. <br/>            Läs/skriv **float**. |
| [`crop_top`](/slides/python-net/sv/aspose.slides/ipicturefillformat/crop_top/) | Returnerar eller anger antalet procent av den verkliga bildens höjd som beskärs<br/>            på bildens övre sida. <br/>            Läs/skriv **float**. |
| [`crop_right`](/slides/python-net/sv/aspose.slides/ipicturefillformat/crop_right/) | Returnerar eller anger antalet procent av den verkliga bildens bredd som beskärs<br/>            på bildens högra sida. <br/>            Läs/skriv **float**. |
| [`crop_bottom`](/slides/python-net/sv/aspose.slides/ipicturefillformat/crop_bottom/) | Returnerar eller anger antalet procent av den verkliga bildens höjd som beskärs<br/>            på bildens nedre sida. <br/>            Läs/skriv **float**. |
| [`stretch_offset_left`](/slides/python-net/sv/aspose.slides/ipicturefillformat/stretch_offset_left/) | Returnerar eller anger vänster kant av fyllningsrektangeln som definieras av ett procentuell förskjutning <br/>            från formens vänstra kant av begränsningsrutan. <br/>            En positiv procentsats anger en inskjutning, medan en negativ procentsats anger en utskjutning.<br/>            Läs/skriv **float**. |
| [`stretch_offset_top`](/slides/python-net/sv/aspose.slides/ipicturefillformat/stretch_offset_top/) | Returnerar eller anger övre kant av fyllningsrektangeln som definieras av ett procentuell förskjutning <br/>            från formens övre kant av begränsningsrutan. <br/>            En positiv procentsats anger en inskjutning, medan en negativ procentsats anger en utskjutning.<br/>            Läs/skriv **float**. |
| [`stretch_offset_right`](/slides/python-net/sv/aspose.slides/ipicturefillformat/stretch_offset_right/) | Returnerar eller anger högra kant av fyllningsrektangeln som definieras av ett procentuell förskjutning <br/>            från formens högra kant av begränsningsrutan. <br/>            En positiv procentsats anger en inskjutning, medan en negativ procentsats anger en utskjutning.<br/>            Läs/skriv **float**. |
| [`stretch_offset_bottom`](/slides/python-net/sv/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Returnerar eller anger nedre kant av fyllningsrektangeln som definieras av ett procentuell förskjutning <br/>            från formens nedre kant av begränsningsrutan. <br/>            En positiv procentsats anger en inskjutning, medan en negativ procentsats anger en utskjutning.<br/>            Läs/skriv **float**. |
| [`tile_offset_x`](/slides/python-net/sv/aspose.slides/ipicturefillformat/tile_offset_x/) | Returnerar eller anger den horisontella förskjutningen av texturen från formens ursprung i punkter.<br/>             Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster.<br/>             Läs/skriv **float**. |
| [`tile_offset_y`](/slides/python-net/sv/aspose.slides/ipicturefillformat/tile_offset_y/) | Returnerar eller anger den vertikala förskjutningen av texturen från formens ursprung i punkter.<br/>             Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt.<br/>             Läs/skriv **float**. |
| [`tile_scale_x`](/slides/python-net/sv/aspose.slides/ipicturefillformat/tile_scale_x/) | Returnerar eller anger den horisontella skalan för texturfyllnaden som en procentsats.<br/>             Läs/skriv **float**. |
| [`tile_scale_y`](/slides/python-net/sv/aspose.slides/ipicturefillformat/tile_scale_y/) | Returnerar eller anger den vertikala skalan för texturfyllnaden som en procentsats.<br/>             Läs/skriv **float**. |
| [`tile_alignment`](/slides/python-net/sv/aspose.slides/ipicturefillformat/tile_alignment/) | Returnerar eller anger hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen.<br/>             Läs/skriv [`RectangleAlignment`](/slides/python-net/sv/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/sv/aspose.slides/ipicturefillformat/tile_flip/) | Vänder texturbrickan runt dess horisontella, vertikala eller båda axlar.<br/>             Läs/skriv [`TileFlip`](/slides/python-net/sv/aspose.slides/tileflip). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/sv/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/sv/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt tar den också bort beskurna områden. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/sv/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Tar bort beskurna områden av fyllningsbilden. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)