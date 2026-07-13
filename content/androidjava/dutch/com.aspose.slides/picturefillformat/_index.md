---
title: PictureFillFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een picture fill-stijl.
type: docs
url: /nl/com.aspose.slides/picturefillformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Vertegenwoordigt een picture fill style.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Retourneert of stelt de dpi in die wordt gebruikt om een picture te vullen. |
| [setDpi(int value)](#setDpi-int-) | Retourneert of stelt de dpi in die wordt gebruikt om een picture te vullen. |
| [getPictureFillMode()](#getPictureFillMode--) | Retourneert of stelt de picture fill mode in. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Retourneert of stelt de picture fill mode in. |
| [getPicture()](#getPicture--) | Retourneert de picture. |
| [getCropLeft()](#getCropLeft--) | Retourneert of stelt het aantal procenten van de echte afbeeldingsbreedte in dat links van de picture wordt bijgesneden. |
| [setCropLeft(float value)](#setCropLeft-float-) | Retourneert of stelt het aantal procenten van de echte afbeeldingsbreedte in dat links van de picture wordt bijgesneden. |
| [getCropTop()](#getCropTop--) | Retourneert of stelt het aantal procenten van de echte afbeeldinghoogte in dat bovenkant van de picture wordt bijgesneden. |
| [setCropTop(float value)](#setCropTop-float-) | Retourneert of stelt het aantal procenten van de echte afbeeldinghoogte in dat bovenkant van de picture wordt bijgesneden. |
| [getCropRight()](#getCropRight--) | Retourneert of stelt het aantal procenten van de echte afbeeldingsbreedte in dat rechts van de picture wordt bijgesneden. |
| [setCropRight(float value)](#setCropRight-float-) | Retourneert of stelt het aantal procenten van de echte afbeeldingsbreedte in dat rechts van de picture wordt bijgesneden. |
| [getCropBottom()](#getCropBottom--) | Retourneert of stelt het aantal procenten van de echte afbeeldinghoogte in dat onderkant van de picture wordt bijgesneden. |
| [setCropBottom(float value)](#setCropBottom-float-) | Retourneert of stelt het aantal procenten van de echte afbeeldinghoogte in dat onderkant van de picture wordt bijgesneden. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Verwijdert bijgesneden gebieden van de fill Picture. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de shape-grootte en opgegeven resolutie. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de shape-grootte en opgegeven resolutie. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Retourneert of stelt de linkerrand van het fill-rectangle in dat wordt gedefinieerd door een procentuele offset vanaf de linkerrand van de bounding box van de shape. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Retourneert of stelt de linkerrand van het fill-rectangle in dat wordt gedefinieerd door een procentuele offset vanaf de linkerrand van de bounding box van de shape. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Retourneert of stelt de bovengrens van het fill-rectangle in dat wordt gedefinieerd door een procentuele offset vanaf de bovengrens van de bounding box van de shape. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Retourneert of stelt de bovengrens van het fill-rectangle in dat wordt gedefinieerd door een procentuele offset vanaf de bovengrens van de bounding box van de shape. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Retourneert of stelt de rechterrand van het fill-rectangle in dat wordt gedefinieerd door een procentuele offset vanaf de rechterrand van de bounding box van de shape. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Retourneert of stelt de rechterrand van het fill-rectangle in dat wordt gedefinieerd door een procentuele offset vanaf de rechterrand van de bounding box van de shape. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Retourneert of stelt de onderrand van het fill-rectangle in dat wordt gedefinieerd door een procentuele offset vanaf de onderrand van de bounding box van de shape. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Retourneert of stelt de onderrand van het fill-rectangle in dat wordt gedefinieerd door een procentuele offset vanaf de onderrand van de bounding box van de shape. |
| [getTileOffsetX()](#getTileOffsetX--) | Retourneert of stelt de horizontale offset van de texture ten opzichte van de oorsprong van de shape in points in. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Retourneert of stelt de horizontale offset van de texture ten opzichte van de oorsprong van de shape in points in. |
| [getTileOffsetY()](#getTileOffsetY--) | Retourneert of stelt de verticale offset van de texture ten opzichte van de oorsprong van de shape in points in. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Retourneert of stelt de verticale offset van de texture ten opzichte van de oorsprong van de shape in points in. |
| [getTileScaleX()](#getTileScaleX--) | Retourneert of stelt de horizontale schaal voor de texture fill in als een percentage. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Retourneert of stelt de horizontale schaal voor de texture fill in als een percentage. |
| [getTileScaleY()](#getTileScaleY--) | Retourneert of stelt de verticale schaal voor de texture fill in als een percentage. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Retourneert of stelt de verticale schaal voor de texture fill in als een percentage. |
| [getTileAlignment()](#getTileAlignment--) | Retourneert of stelt in hoe de texture is uitgelijnd binnen de shape. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Retourneert of stelt in hoe de texture is uitgelijnd binnen de shape. |
| [getTileFlip()](#getTileFlip--) | Draait de texture-tile rond zijn horizontale, verticale of beide assen. |
| [setTileFlip(int value)](#setTileFlip-int-) | Draait de texture-tile rond zijn horizontale, verticale of beide assen. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Retourneert of stelt de dpi in die wordt gebruikt om een picture te vullen. Lezen/Schrijven  int .

**Retourneert:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Retourneert of stelt de dpi in die wordt gebruikt om een picture te vullen. Lezen/Schrijven  int .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Retourneert of stelt de picture fill mode in. Lezen/Schrijven [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Retourneert:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Retourneert of stelt de picture fill mode in. Lezen/Schrijven [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Retourneert de picture. Alleen-lezen [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retourneert:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Retourneert of stelt het aantal procenten van de echte afbeeldingsbreedte in dat links van de picture wordt bijgesneden. Lezen/Schrijven  float .

**Retourneert:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Retourneert of stelt het aantal procenten van de echte afbeeldingsbreedte in dat links van de picture wordt bijgesneden. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Retourneert of stelt het aantal procenten van de echte afbeeldinghoogte in dat bovenkant van de picture wordt bijgesneden. Lezen/Schrijven  float .

**Retourneert:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Retourneert of stelt het aantal procenten van de echte afbeeldinghoogte in dat bovenkant van de picture wordt bijgesneden. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Retourneert of stelt het aantal procenten van de echte afbeeldingsbreedte in dat rechts van de picture wordt bijgesneden. Lezen/Schrijven  float .

**Retourneert:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Retourneert of stelt het aantal procenten van de echte afbeeldingsbreedte in dat rechts van de picture wordt bijgesneden. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Retourneert of stelt het aantal procenten van de echte afbeeldinghoogte in dat onderkant van de picture wordt bijgesneden. Lezen/Schrijven  float .

**Retourneert:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Retourneert of stelt het aantal procenten van de echte afbeeldinghoogte in dat onderkant van de picture wordt bijgesneden. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Verwijdert bijgesneden gebieden van de fill Picture.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Haalt het PictureFrame op
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Verwijdert bijgesneden gebieden van de PictureFrame-afbeelding
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Cropped image of origin image if cropping is not necessary.

--------------------

Deze methode zet WMF/EMF-metabestanden om naar een raster PNG-afbeelding terwijl ze worden bijgesneden.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Comprimeert de afbeelding door de grootte te verkleinen op basis van de shape-grootte en opgegeven resolutie. Optioneel worden bijgesneden gebieden ook verwijderd.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` methode om de grootte van een afbeelding in een presentatie te verkleinen door een doelresolutie in te stellen en bijgesneden gebieden te verwijderen:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | int | The target resolution for compression, specified as a value of the [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> Het volgende voorbeeld toont hoe de ```
> CompressImage
> ``` methode te gebruiken om de grootte van een afbeelding in een presentatie te verkleinen door een doelresolutie in te stellen en bijgesneden gebieden te verwijderen:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution)
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A  boolean  indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```


Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public final float getStretchOffsetTop()
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public final void setStretchOffsetTop(float value)
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public final float getStretchOffsetRight()
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public final void setStretchOffsetRight(float value)
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public final float getStretchOffsetBottom()
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ``` 
**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public final float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public final void setTileScaleX(float value)
```

```

> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public final float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
 
**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public final void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public final byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public final void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Standaard is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |