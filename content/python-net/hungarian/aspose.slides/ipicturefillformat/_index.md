---
title: IPictureFillFormat class
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat osztály

Kép kitöltési stílust képvisel.

Az IPictureFillFormat típus a következő tagokat tartalmazza:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/hu/aspose.slides/ipicturefillformat/dpi/) | Returns or sets the dpi which is used to fill a picture.<br/>            Olvasás/írás **int**. |
| [`picture_fill_mode`](/slides/python-net/hu/aspose.slides/ipicturefillformat/picture_fill_mode/) | Returns or sets the picture fill mode.<br/>            Olvasás/írás [`PictureFillMode`](/slides/python-net/hu/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/hu/aspose.slides/ipicturefillformat/picture/) | Returns the picture.<br/>            Csak olvasható [`ISlidesPicture`](/slides/python-net/hu/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/hu/aspose.slides/ipicturefillformat/crop_left/) | Returns or sets the number of percents of real image width that are cropped off<br/>            the left of the picture. <br/>            Olvasás/írás **float**. |
| [`crop_top`](/slides/python-net/hu/aspose.slides/ipicturefillformat/crop_top/) | Returns or sets the number of percents of real image height that are cropped off<br/>            the top of the picture. <br/>            Olvasás/írás **float**. |
| [`crop_right`](/slides/python-net/hu/aspose.slides/ipicturefillformat/crop_right/) | Returns or sets the number of percents of real image width that are cropped off<br/>            the right of the picture. <br/>            Olvasás/írás **float**. |
| [`crop_bottom`](/slides/python-net/hu/aspose.slides/ipicturefillformat/crop_bottom/) | Returns or sets the number of percents of real image height that are cropped off<br/>            the bottom of the picture. <br/>            Olvasás/írás **float**. |
| [`stretch_offset_left`](/slides/python-net/hu/aspose.slides/ipicturefillformat/stretch_offset_left/) | Returns or sets left edge of the fill rectangle that is defined by a percentage offset <br/>            from the left edge of the shape's bounding box. <br/>            A positive percentage specifies an inset, while a negative percentage specifies an outset.<br/>            Olvasás/írás **float**. |
| [`stretch_offset_top`](/slides/python-net/hu/aspose.slides/ipicturefillformat/stretch_offset_top/) | Returns or sets top edge of the fill rectangle that is defined by a percentage offset <br/>            from the top edge of the shape's bounding box. <br/>            A positive percentage specifies an inset, while a negative percentage specifies an outset.<br/>            Olvasás/írás **float**. |
| [`stretch_offset_right`](/slides/python-net/hu/aspose.slides/ipicturefillformat/stretch_offset_right/) | Returns or sets right edge of the fill rectangle that is defined by a percentage offset <br/>            from the right edge of the shape's bounding box. <br/>            A positive percentage specifies an inset, while a negative percentage specifies an outset.<br/>            Olvasás/írás **float**. |
| [`stretch_offset_bottom`](/slides/python-net/hu/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset <br/>            from the bottom edge of the shape's bounding box. <br/>            A positive percentage specifies an inset, while a negative percentage specifies an outset.<br/>            Olvasás/írás **float**. |
| [`tile_offset_x`](/slides/python-net/hu/aspose.slides/ipicturefillformat/tile_offset_x/) | Returns or sets the horizontal offset of the texture from the shape's origin in points.<br/>             A positive value moves the texture to the right, while a negative value moves it to the left.<br/>             Olvasás/írás **float**. |
| [`tile_offset_y`](/slides/python-net/hu/aspose.slides/ipicturefillformat/tile_offset_y/) | Returns or sets the vertical offset of the texture from the shape's origin in points.<br/>             A positive value moves the texture down, while a negative value moves it up.<br/>             Olvasás/írás **float**. |
| [`tile_scale_x`](/slides/python-net/hu/aspose.slides/ipicturefillformat/tile_scale_x/) | Returns or sets the horizontal scale for the texture fill as a percentage.<br/>             Olvasás/írás **float**. |
| [`tile_scale_y`](/slides/python-net/hu/aspose.slides/ipicturefillformat/tile_scale_y/) | Returns or sets the vertical scale for the texture fill as a percentage.<br/>             Olvasás/írás **float**. |
| [`tile_alignment`](/slides/python-net/hu/aspose.slides/ipicturefillformat/tile_alignment/) | Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape.<br/>             Olvasás/írás [`RectangleAlignment`](/slides/python-net/hu/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/hu/aspose.slides/ipicturefillformat/tile_flip/) | Flips the texture tile around its horizontal, vertical or both axis.<br/>             Olvasás/írás [`TileFlip`](/slides/python-net/hu/aspose.slides/tileflip). |

## Metódusok

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/hu/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/hu/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/hu/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Delete cropped areas of the fill Picture. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)