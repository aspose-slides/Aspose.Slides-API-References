---
title: IPictureFillFormat class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat Klasse

Stellt einen Bildfüllstil dar.

Der Typ IPictureFillFormat stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/de/aspose.slides/ipicturefillformat/dpi/) | Gibt die DPI zurück oder legt sie fest, die zum Ausfüllen eines Bildes verwendet wird.<br/>            Lesen/Schreiben **int**. |
| [`picture_fill_mode`](/slides/python-net/de/aspose.slides/ipicturefillformat/picture_fill_mode/) | Gibt den Bildfüllmodus zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`PictureFillMode`](/slides/python-net/de/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/de/aspose.slides/ipicturefillformat/picture/) | Gibt das Bild zurück.<br/>            Nur-Lesen [`ISlidesPicture`](/slides/python-net/de/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/de/aspose.slides/ipicturefillformat/crop_left/) | Gibt den Prozentsatz der realen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`crop_top`](/slides/python-net/de/aspose.slides/ipicturefillformat/crop_top/) | Gibt den Prozentsatz der realen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`crop_right`](/slides/python-net/de/aspose.slides/ipicturefillformat/crop_right/) | Gibt den Prozentsatz der realen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`crop_bottom`](/slides/python-net/de/aspose.slides/ipicturefillformat/crop_bottom/) | Gibt den Prozentsatz der realen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`stretch_offset_left`](/slides/python-net/de/aspose.slides/ipicturefillformat/stretch_offset_left/) | Gibt die linke Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist.<br/>            Ein positiver Prozentsatz gibt eine Einprägung an, ein negativer Prozentsatz einen Auskragungswert.<br/>            Lesen/Schreiben **float**. |
| [`stretch_offset_top`](/slides/python-net/de/aspose.slides/ipicturefillformat/stretch_offset_top/) | Gibt die obere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist.<br/>            Ein positiver Prozentsatz gibt eine Einprägung an, ein negativer Prozentsatz einen Auskragungswert.<br/>            Lesen/Schreiben **float**. |
| [`stretch_offset_right`](/slides/python-net/de/aspose.slides/ipicturefillformat/stretch_offset_right/) | Gibt die rechte Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist.<br/>            Ein positiver Prozentsatz gibt eine Einprägung an, ein negativer Prozentsatz einen Auskragungswert.<br/>            Lesen/Schreiben **float**. |
| [`stretch_offset_bottom`](/slides/python-net/de/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Gibt die untere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist.<br/>            Ein positiver Prozentsatz gibt eine Einprägung an, ein negativer Prozentsatz einen Auskragungswert.<br/>            Lesen/Schreiben **float**. |
| [`tile_offset_x`](/slides/python-net/de/aspose.slides/ipicturefillformat/tile_offset_x/) | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest.<br/>            Ein positiver Wert verschiebt die Textur nach rechts, ein negativer Wert nach links.<br/>            Lesen/Schreiben **float**. |
| [`tile_offset_y`](/slides/python-net/de/aspose.slides/ipicturefillformat/tile_offset_y/) | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest.<br/>            Ein positiver Wert verschiebt die Textur nach unten, ein negativer Wert nach oben.<br/>            Lesen/Schreiben **float**. |
| [`tile_scale_x`](/slides/python-net/de/aspose.slides/ipicturefillformat/tile_scale_x/) | Gibt den horizontalen Maßstab für die Texturfüllung als Prozentsatz zurück oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`tile_scale_y`](/slides/python-net/de/aspose.slides/ipicturefillformat/tile_scale_y/) | Gibt den vertikalen Maßstab für die Texturfüllung als Prozentsatz zurück oder legt ihn fest.<br/>            Lesen/Schreiben **float**. |
| [`tile_alignment`](/slides/python-net/de/aspose.slides/ipicturefillformat/tile_alignment/) | Gibt zurück oder legt fest, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung bestimmt den Startpunkt des Texturmusters und wie es über die Form wiederholt wird.<br/>            Lesen/Schreiben [`RectangleAlignment`](/slides/python-net/de/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/de/aspose.slides/ipicturefillformat/tile_flip/) | Dreht die Texturfliese um ihre horizontale, vertikale oder beide Achsen.<br/>            Lesen/Schreiben [`TileFlip`](/slides/python-net/de/aspose.slides/tileflip). |

## Methoden

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/de/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden dabei auch beschnittene Bereiche gelöscht. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/de/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden dabei auch beschnittene Bereiche gelöscht. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/de/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Löscht beschnittene Bereiche des Füllbildes. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)