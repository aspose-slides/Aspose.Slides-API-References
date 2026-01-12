---
title: PictureFillFormat
second_title: Aspose.Sildes for .NET API Reference
description: Represents a picture fill style.
type: docs
weight: 9350
url: /aspose.slides/picturefillformat/
---

## PictureFillFormat class

Represents a picture fill style.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Properties

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Allows to get base IPresentationComponent interface. Read-only [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Returns or sets the number of percents of real image height that are cropped off the bottom of the picture. Read/write Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Returns or sets the number of percents of real image width that are cropped off the left of the picture. Read/write Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Returns or sets the number of percents of real image width that are cropped off the right of the picture. Read/write Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Returns or sets the number of percents of real image height that are cropped off the top of the picture. Read/write Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Returns or sets the dpi which is used to fill a picture. Read/write Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Returns the picture. Read-only [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Returns or sets the picture fill mode. Read/write [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Flips the texture tile around its horizontal, vertical or both axis. Read/write [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Returns or sets the horizontal scale for the texture fill as a percentage. Read/write Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Returns or sets the vertical scale for the texture fill as a percentage. Read/write Single. |

## Methods

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Delete cropped areas of the fill Picture. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compares with specified object. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Returns hash code. |

### See Also

* class [PVIObject](../pviobject)
* interface [IPictureFillFormat](../ipicturefillformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
