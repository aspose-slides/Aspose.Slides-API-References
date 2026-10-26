---
title: PictureFillFormat class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/picturefillformat/
---
## PictureFillFormat klass

Representerar en bildfyllnadsstil.

**Arv:**[`PictureFillFormat`](/slides/python-net/sv/aspose.slides/picturefillformat) → [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)

Typen PictureFillFormat exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`dpi`](/slides/python-net/sv/aspose.slides/picturefillformat/dpi/) | Returnerar eller anger dpi som används för att fylla en bild.<br/>            Läs/skriv **int**. |
| [`picture_fill_mode`](/slides/python-net/sv/aspose.slides/picturefillformat/picture_fill_mode/) | Returnerar eller anger bildfyllnadsläget.<br/>            Läs/skriv [`PictureFillMode`](/slides/python-net/sv/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/sv/aspose.slides/picturefillformat/picture/) | Returnerar bilden.<br/>            Endast läs [`ISlidesPicture`](/slides/python-net/sv/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/sv/aspose.slides/picturefillformat/crop_left/) | Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs bort<br/>            vänster om bilden. <br/>            Läs/skriv **float**. |
| [`crop_top`](/slides/python-net/sv/aspose.slides/picturefillformat/crop_top/) | Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs bort<br/>            toppen av bilden. <br/>            Läs/skriv **float**. |
| [`crop_right`](/slides/python-net/sv/aspose.slides/picturefillformat/crop_right/) | Returnerar eller anger antalet procent av den faktiska bildbredden som beskärs bort<br/>            höger om bilden. <br/>            Läs/skriv **float**. |
| [`crop_bottom`](/slides/python-net/sv/aspose.slides/picturefillformat/crop_bottom/) | Returnerar eller anger antalet procent av den faktiska bildhöjden som beskärs bort<br/>            botten av bilden. <br/>            Läs/skriv **float**. |
| [`stretch_offset_left`](/slides/python-net/sv/aspose.slides/picturefillformat/stretch_offset_left/) | Returnerar eller anger vänster kant av fyllningsrektangeln som definieras av en procentuell förskjutning <br/>            från vänstra kanten av figurens omslutningsram. <br/>            En positiv procent anger en infogning, medan en negativ procent anger en utstickning.<br/>            Läs/skriv **float**. |
| [`stretch_offset_top`](/slides/python-net/sv/aspose.slides/picturefillformat/stretch_offset_top/) | Returnerar eller anger överkant av fyllningsrektangeln som definieras av en procentuell förskjutning <br/>            från överkanten av figurens omslutningsram. <br/>            En positiv procent anger en infogning, medan en negativ procent anger en utstickning.<br/>            Läs/skriv **float**. |
| [`stretch_offset_right`](/slides/python-net/sv/aspose.slides/picturefillformat/stretch_offset_right/) | Returnerar eller anger höger kant av fyllningsrektangeln som definieras av en procentuell förskjutning <br/>            från högra kanten av figurens omslutningsram. <br/>            En positiv procent anger en infogning, medan en negativ procent anger en utstickning.<br/>            Läs/skriv **float**. |
| [`stretch_offset_bottom`](/slides/python-net/sv/aspose.slides/picturefillformat/stretch_offset_bottom/) | Returnerar eller anger nedre kant av fyllningsrektangeln som definieras av en procentuell förskjutning <br/>            från nederkanten av figurens omslutningsram. <br/>            En positiv procent anger en infogning, medan en negativ procent anger en utstickning.<br/>            Läs/skriv **float**. |
| [`tile_offset_x`](/slides/python-net/sv/aspose.slides/picturefillformat/tile_offset_x/) | Returnerar eller anger den horisontella förskjutningen av texturen från figurens ursprung i punkter.<br/>             Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster.<br/>             Läs/skriv **float**. |
| [`tile_offset_y`](/slides/python-net/sv/aspose.slides/picturefillformat/tile_offset_y/) | Returnerar eller anger den vertikala förskjutningen av texturen från figurens ursprung i punkter.<br/>             Ett positivt värde flyttar texturen neråt, medan ett negativt värde flyttar den uppåt.<br/>             Läs/skriv **float**. |
| [`tile_scale_x`](/slides/python-net/sv/aspose.slides/picturefillformat/tile_scale_x/) | Returnerar eller anger den horisontella skalan för texturfyllnad som en procentandel.<br/>             Läs/skriv **float**. |
| [`tile_scale_y`](/slides/python-net/sv/aspose.slides/picturefillformat/tile_scale_y/) | Returnerar eller anger den vertikala skalan för texturfyllnad som en procentandel.<br/>             Läs/skriv **float**. |
| [`tile_alignment`](/slides/python-net/sv/aspose.slides/picturefillformat/tile_alignment/) | Returnerar eller anger hur texturen är justerad inom figuren. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över figuren.<br/>             Läs/skriv [`RectangleAlignment`](/slides/python-net/sv/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/sv/aspose.slides/picturefillformat/tile_flip/) | Vänder texturplattan kring dess horisontella, vertikala eller båda axlar.<br/>             Läs/skriv [`TileFlip`](/slides/python-net/sv/aspose.slides/tileflip). |
| [`slide`](/slides/python-net/sv/aspose.slides/picturefillformat/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/picturefillformat/presentation/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/sv/aspose.slides/picturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Eventuellt raderas även beskurna områden. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/sv/aspose.slides/picturefillformat/compress_image/#bool-float) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Eventuellt raderas även beskurna områden. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/sv/aspose.slides/picturefillformat/delete_picture_cropped_areas/#) | Radera beskurna områden av fyllningsbilden. |

### Se även
* klass [`PictureFillFormat`](/slides/python-net/sv/aspose.slides/picturefillformat)
* klass [`PVIObject`](/slides/python-net/sv/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)