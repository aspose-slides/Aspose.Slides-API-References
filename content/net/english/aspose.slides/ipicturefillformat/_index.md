---
title: IPictureFillFormat
second_title: Aspose.Sildes for .NET API Reference
description: Represents a picture fill style.
type: docs
weight: 6590
url: /aspose.slides/ipicturefillformat/
---

## IPictureFillFormat interface

Represents a picture fill style.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Properties

| Name | Description |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Allows to get base IFillParamSource interface. Read-only [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Returns or sets the number of percents of real image height that are cropped off the bottom of the picture. Read/write Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Returns or sets the number of percents of real image width that are cropped off the left of the picture. Read/write Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Returns or sets the number of percents of real image width that are cropped off the right of the picture. Read/write Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Returns or sets the number of percents of real image height that are cropped off the top of the picture. Read/write Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Returns or sets the dpi which is used to fill a picture. Read/write Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Returns the picture. Read-only [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Returns or sets the picture fill mode. Read/write [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Flips the texture tile around its horizontal, vertical or both axis. Read/write [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Returns or sets the horizontal scale for the texture fill as a percentage. Read/write Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Returns or sets the vertical scale for the texture fill as a percentage. Read/write Single. |

## Methods

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Delete cropped areas of the fill Picture. |

### See Also

* interface [IFillParamSource](../ifillparamsource)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
