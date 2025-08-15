---
title: PictureFillFormat
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/picturefillformat/
---

## PictureFillFormat class

 Represents a picture fill style.
 
### compressImage {#compressImage}

| Name | Description |
| --- | --- |
| compressImage (boolean, int) | Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the function will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | int | The target resolution for compression, specified as a value of the PicturesCompression enum. This function changes the image's size and resolution similar to PowerPoint's "Picture Format -&gt; Compress Pictures" feature. |

 **Returns:**
boolean

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when the resolution is not a valid value. |


---


### compressImage {#compressImage}

| Name | Description |
| --- | --- |
| compressImage (boolean, float) | Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the function will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized. This function changes the image's size and resolution similar to PowerPoint's "Picture Format -&gt; Compress Pictures" feature. |

 **Returns:**
boolean

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when the resolution is not a positive value. |


---


### deletePictureCroppedAreas {#deletePictureCroppedAreas}

| Name | Description |
| --- | --- |
| deletePictureCroppedAreas () | Delete cropped areas of the fill Picture. |

 **Returns:**
[PPImage](../ppimage)


---


### getCropBottom {#getCropBottom}

| Name | Description |
| --- | --- |
| getCropBottom () | Returns or sets the number of percents of real image height that are cropped off the bottom of the picture. Read/write float. |

 **Returns:**
float


---


### getCropLeft {#getCropLeft}

| Name | Description |
| --- | --- |
| getCropLeft () | Returns or sets the number of percents of real image width that are cropped off the left of the picture. Read/write float. |

 **Returns:**
float


---


### getCropRight {#getCropRight}

| Name | Description |
| --- | --- |
| getCropRight () | Returns or sets the number of percents of real image width that are cropped off the right of the picture. Read/write float. |

 **Returns:**
float


---


### getCropTop {#getCropTop}

| Name | Description |
| --- | --- |
| getCropTop () | Returns or sets the number of percents of real image height that are cropped off the top of the picture. Read/write float. |

 **Returns:**
float


---


### getDpi {#getDpi}

| Name | Description |
| --- | --- |
| getDpi () | Returns or sets the dpi which is used to fill a picture. Read/write int. |

 **Returns:**
int


---


### getPicture {#getPicture}

| Name | Description |
| --- | --- |
| getPicture () | Returns the picture. Read-only ISlidesPicture. |

 **Returns:**
[Picture](../picture)


---


### getPictureFillMode {#getPictureFillMode}

| Name | Description |
| --- | --- |
| getPictureFillMode () | Returns or sets the picture fill mode. Read/write PictureFillMode. |

 **Returns:**
int


---


### getStretchOffsetBottom {#getStretchOffsetBottom}

| Name | Description |
| --- | --- |
| getStretchOffsetBottom () | Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write float. |

 **Returns:**
float


---


### getStretchOffsetLeft {#getStretchOffsetLeft}

| Name | Description |
| --- | --- |
| getStretchOffsetLeft () | Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write float. |

 **Returns:**
float


---


### getStretchOffsetRight {#getStretchOffsetRight}

| Name | Description |
| --- | --- |
| getStretchOffsetRight () | Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write float. |

 **Returns:**
float


---


### getStretchOffsetTop {#getStretchOffsetTop}

| Name | Description |
| --- | --- |
| getStretchOffsetTop () | Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write float. |

 **Returns:**
float


---


### getTileAlignment {#getTileAlignment}

| Name | Description |
| --- | --- |
| getTileAlignment () | Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write RectangleAlignment. Default is RectangleAlignment#TopLeft. |

 **Returns:**
byte


---


### getTileFlip {#getTileFlip}

| Name | Description |
| --- | --- |
| getTileFlip () | Flips the texture tile around its horizontal, vertical or both axis. Read/write TileFlip. Default is TileFlip#NoFlip. |

 **Returns:**
int


---


### getTileOffsetX {#getTileOffsetX}

| Name | Description |
| --- | --- |
| getTileOffsetX () | Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write float. |

 **Returns:**
float


---


### getTileOffsetY {#getTileOffsetY}

| Name | Description |
| --- | --- |
| getTileOffsetY () | Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write float. |

 **Returns:**
float


---


### getTileScaleX {#getTileScaleX}

| Name | Description |
| --- | --- |
| getTileScaleX () | Returns or sets the horizontal scale for the texture fill as a percentage. Read/write float. |

 **Returns:**
float


---


### getTileScaleY {#getTileScaleY}

| Name | Description |
| --- | --- |
| getTileScaleY () | Returns or sets the vertical scale for the texture fill as a percentage. Read/write float. |

 **Returns:**
float


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Returns:**
long


---


### setCropBottom {#setCropBottom}

| Name | Description |
| --- | --- |
| setCropBottom (float) | Returns or sets the number of percents of real image height that are cropped off the bottom of the picture. Read/write float. |


---


### setCropLeft {#setCropLeft}

| Name | Description |
| --- | --- |
| setCropLeft (float) | Returns or sets the number of percents of real image width that are cropped off the left of the picture. Read/write float. |


---


### setCropRight {#setCropRight}

| Name | Description |
| --- | --- |
| setCropRight (float) | Returns or sets the number of percents of real image width that are cropped off the right of the picture. Read/write float. |


---


### setCropTop {#setCropTop}

| Name | Description |
| --- | --- |
| setCropTop (float) | Returns or sets the number of percents of real image height that are cropped off the top of the picture. Read/write float. |


---


### setDpi {#setDpi}

| Name | Description |
| --- | --- |
| setDpi (int) | Returns or sets the dpi which is used to fill a picture. Read/write int. |


---


### setPictureFillMode {#setPictureFillMode}

| Name | Description |
| --- | --- |
| setPictureFillMode (int) | Returns or sets the picture fill mode. Read/write PictureFillMode. |


---


### setStretchOffsetBottom {#setStretchOffsetBottom}

| Name | Description |
| --- | --- |
| setStretchOffsetBottom (float) | Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write float. |


---


### setStretchOffsetLeft {#setStretchOffsetLeft}

| Name | Description |
| --- | --- |
| setStretchOffsetLeft (float) | Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write float. |


---


### setStretchOffsetRight {#setStretchOffsetRight}

| Name | Description |
| --- | --- |
| setStretchOffsetRight (float) | Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write float. |


---


### setStretchOffsetTop {#setStretchOffsetTop}

| Name | Description |
| --- | --- |
| setStretchOffsetTop (float) | Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write float. |


---


### setTileAlignment {#setTileAlignment}

| Name | Description |
| --- | --- |
| setTileAlignment (byte) | Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write RectangleAlignment. Default is RectangleAlignment#TopLeft. |


---


### setTileFlip {#setTileFlip}

| Name | Description |
| --- | --- |
| setTileFlip (int) | Flips the texture tile around its horizontal, vertical or both axis. Read/write TileFlip. Default is TileFlip#NoFlip. |


---


### setTileOffsetX {#setTileOffsetX}

| Name | Description |
| --- | --- |
| setTileOffsetX (float) | Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write float. |


---


### setTileOffsetY {#setTileOffsetY}

| Name | Description |
| --- | --- |
| setTileOffsetY (float) | Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write float. |


---


### setTileScaleX {#setTileScaleX}

| Name | Description |
| --- | --- |
| setTileScaleX (float) | Returns or sets the horizontal scale for the texture fill as a percentage. Read/write float. |


---


### setTileScaleY {#setTileScaleY}

| Name | Description |
| --- | --- |
| setTileScaleY (float) | Returns or sets the vertical scale for the texture fill as a percentage. Read/write float. |


---


