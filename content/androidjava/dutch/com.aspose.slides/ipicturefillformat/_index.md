---
title: IPictureFillFormat
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een afbeeldingvullingsstijl voor.
type: docs
url: /nl/com.aspose.slides/ipicturefillformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Stelt een afbeeldingvullingstijl voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDpi()](#getDpi--) | Retourneert of stelt de dpi in die wordt gebruikt om een afbeelding te vullen. |
| [setDpi(int value)](#setDpi-int-) | Retourneert of stelt de dpi in die wordt gebruikt om een afbeelding te vullen. |
| [getPictureFillMode()](#getPictureFillMode--) | Retourneert of stelt de picture fill-modus in. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Retourneert of stelt de picture fill-modus in. |
| [getPicture()](#getPicture--) | Retourneert de afbeelding. |
| [getCropLeft()](#getCropLeft--) | Retourneert of stelt het percentage van de werkelijke afbeeldingbreedte in dat aan de linkerkant van de afbeelding wordt bijgesneden. |
| [setCropLeft(float value)](#setCropLeft-float-) | Retourneert of stelt het percentage van de werkelijke afbeeldingbreedte in dat aan de linkerkant van de afbeelding wordt bijgesneden. |
| [getCropTop()](#getCropTop--) | Retourneert of stelt het percentage van de werkelijke afbeeldinghoogte in dat aan de bovenkant van de afbeelding wordt bijgesneden. |
| [setCropTop(float value)](#setCropTop-float-) | Retourneert of stelt het percentage van de werkelijke afbeeldinghoogte in dat aan de bovenkant van de afbeelding wordt bijgesneden. |
| [getCropRight()](#getCropRight--) | Retourneert of stelt het percentage van de werkelijke afbeeldingbreedte in dat aan de rechterkant van de afbeelding wordt bijgesneden. |
| [setCropRight(float value)](#setCropRight-float-) | Retourneert of stelt het percentage van de werkelijke afbeeldingbreedte in dat aan de rechterkant van de afbeelding wordt bijgesneden. |
| [getCropBottom()](#getCropBottom--) | Retourneert of stelt het percentage van de werkelijke afbeeldinghoogte in dat aan de onderkant van de afbeelding wordt bijgesneden. |
| [setCropBottom(float value)](#setCropBottom-float-) | Retourneert of stelt het percentage van de werkelijke afbeeldinghoogte in dat aan de onderkant van de afbeelding wordt bijgesneden. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Retourneert of stelt de linkerrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de linkerrand van de shape-begrenzingskader. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Retourneert of stelt de linkerrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de linkerrand van de shape-begrenzingskader. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Retourneert of stelt de bovengrens van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de bovengrens van de shape-begrenzingskader. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Retourneert of stelt de bovengrens van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de bovengrens van de shape-begrenzingskader. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Retourneert of stelt de rechterrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de rechterrand van de shape-begrenzingskader. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Retourneert of stelt de rechterrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de rechterrand van de shape-begrenzingskader. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Retourneert of stelt de onderrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de onderrand van de shape-begrenzingskader. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Retourneert of stelt de onderrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de onderrand van de shape-begrenzingskader. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Verwijder bijgesneden gebieden van de vulafbeelding. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de shape-grootte en gespecificeerde resolutie. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de shape-grootte en gespecificeerde resolutie. |
| [getTileOffsetX()](#getTileOffsetX--) | Retourneert of stelt de horizontale offset van de textuur ten opzichte van de oorsprong van de shape in punten in. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Retourneert of stelt de horizontale offset van de textuur ten opzichte van de oorsprong van de shape in punten in. |
| [getTileOffsetY()](#getTileOffsetY--) | Retourneert of stelt de verticale offset van de textuur ten opzichte van de oorsprong van de shape in punten in. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Retourneert of stelt de verticale offset van de textuur ten opzichte van de oorsprong van de shape in punten in. |
| [getTileScaleX()](#getTileScaleX--) | Retourneert of stelt de horizontale schaal voor de textuurvulling in als een percentage. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Retourneert of stelt de horizontale schaal voor de textuurvulling in als een percentage. |
| [getTileScaleY()](#getTileScaleY--) | Retourneert of stelt de verticale schaal voor de textuurvulling in als een percentage. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Retourneert of stelt de verticale schaal voor de textuurvulling in als een percentage. |
| [getTileAlignment()](#getTileAlignment--) | Retourneert of stelt in hoe de textuur wordt uitgelijnd binnen de shape. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Retourneert of stelt in hoe de textuur wordt uitgelijnd binnen de shape. |
| [getTileFlip()](#getTileFlip--) | Keert de textuurtile om rond zijn horizontale, verticale of beide assen. |
| [setTileFlip(int value)](#setTileFlip-int-) | Keert de textuurtile om rond zijn horizontale, verticale of beide assen. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Retourneert of stelt de dpi in die wordt gebruikt om een afbeelding te vullen. Lezen/schrijven int.

**Retourneert:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Retourneert of stelt de dpi in die wordt gebruikt om een afbeelding te vullen. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Retourneert of stelt de picture fill-modus in. Lezen/schrijven [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Retourneert:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Retourneert of stelt de picture fill-modus in. Lezen/schrijven [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Retourneert de afbeelding. Alleen-lezen [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retourneert:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Retourneert of stelt het percentage van de werkelijke afbeeldingbreedte in dat aan de linkerkant van de afbeelding wordt bijgesneden. Lezen/schrijven float.

**Retourneert:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Retourneert of stelt het percentage van de werkelijke afbeeldingbreedte in dat aan de linkerkant van de afbeelding wordt bijgesneden. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Retourneert of stelt het percentage van de werkelijke afbeeldinghoogte in dat aan de bovenkant van de afbeelding wordt bijgesneden. Lezen/schrijven float.

**Retourneert:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Retourneert of stelt het percentage van de werkelijke afbeeldinghoogte in dat aan de bovenkant van de afbeelding wordt bijgesneden. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Retourneert of stelt het percentage van de werkelijke afbeeldingbreedte in dat aan de rechterkant van de afbeelding wordt bijgesneden. Lezen/schrijven float.

**Retourneert:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Retourneert of stelt het percentage van de werkelijke afbeeldingbreedte in dat aan de rechterkant van de afbeelding wordt bijgesneden. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Retourneert of stelt het percentage van de werkelijke afbeeldinghoogte in dat aan de onderkant van de afbeelding wordt bijgesneden. Lezen/schrijven float.

**Retourneert:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Retourneert of stelt het percentage van de werkelijke afbeeldinghoogte in dat aan de onderkant van de afbeelding wordt bijgesneden. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Retourneert of stelt de linkerrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de linkerrand van de shape-begrenzingskader. Een positief percentage geeft een inspringing aan, een negatief percentage een uitspringing. Lezen/schrijven float.

**Retourneert:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Retourneert of stelt de linkerrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de linkerrand van de shape-begrenzingskader. Een positief percentage geeft een inspringing aan, een negatief percentage een uitspringing. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Retourneert of stelt de bovengrens van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de bovengrens van de shape-begrenzingskader. Een positief percentage geeft een inspringing aan, een negatief percentage een uitspringing. Lezen/schrijven float.

**Retourneert:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Retourneert of stelt de bovengrens van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de bovengrens van de shape-begrenzingskader. Een positief percentage geeft een inspringing aan, een negatief percentage een uitspringing. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Retourneert of stelt de rechterrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de rechterrand van de shape-begrenzingskader. Een positief percentage geeft een inspringing aan, een negatief percentage een uitspringing. Lezen/schrijven float.

**Retourneert:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Retourneert of stelt de rechterrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de rechterrand van de shape-begrenzingskader. Een positief percentage geeft een inspringing aan, een negatief percentage een uitspringing. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Retourneert of stelt de onderrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de onderrand van de shape-begrenzingskader. Een positief percentage geeft een inspringing aan, een negatief percentage een uitspringing. Lezen/schrijven float.

**Retourneert:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Retourneert of stelt de onderrand van de vulrechthoek in die wordt gedefinieerd door een percentage-offset vanaf de onderrand van de shape-begrenzingskader. Een positief percentage geeft een inspringing aan, een negatief percentage een uitspringing. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Verwijder bijgesneden gebieden van de vulafbeelding.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Haalt de PictureFrame op
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Verwijdert bijgesneden gebieden van de PictureFrame-afbeelding
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Bijgesneden afbeelding of origineel als bijsnijden niet nodig is.

--------------------

Deze methode converteert WMF/EMF-metabestanden naar raster-PNG-afbeeldingen terwijl deze bijsnijdt.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Comprimeert de afbeelding door de grootte te verkleinen op basis van de shape-grootte en gespecificeerde resolutie. Optioneel verwijdert het ook bijgesneden gebieden.

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
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> Het volgende voorbeeld toont hoe de ```
> CompressImage
> ```
 methode gebruikt kan worden om de grootte van een afbeelding in een presentatie te verkleinen door een doelresolutie in te stellen en bijgesneden gebieden te verwijderen:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
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
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### getTileOffsetX() {#getTileOffsetX--}
```
public abstract float getTileOffsetX()
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

**Retourneert:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public abstract void setTileOffsetX(float value)
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
public abstract float getTileOffsetY()
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

**Retourneert:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public abstract void setTileOffsetY(float value)
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
public abstract float getTileScaleX()
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
public abstract void setTileScaleX(float value)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public abstract float getTileScaleY()
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
public abstract void setTileScaleY(float value)
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
public abstract byte getTileAlignment()
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
public abstract void setTileAlignment(byte value)
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
public abstract int getTileFlip()
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
public abstract void setTileFlip(int value)
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