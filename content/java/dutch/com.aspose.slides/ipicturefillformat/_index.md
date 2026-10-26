---
title: IPictureFillFormat
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een afbeeldingsvullingsstijl voor.
type: docs
url: /nl/com.aspose.slides/ipicturefillformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Stelt een afbeeldingsvullingsstijl voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDpi()](#getDpi--) | Geeft de dpi terug of stelt deze in die wordt gebruikt om een afbeelding te vullen. |
| [setDpi(int value)](#setDpi-int-) | Geeft de dpi terug of stelt deze in die wordt gebruikt om een afbeelding te vullen. |
| [getPictureFillMode()](#getPictureFillMode--) | Geeft de afbeeldingsvullingsmodus terug of stelt deze in. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Geeft de afbeeldingsvullingsmodus terug of stelt deze in. |
| [getPicture()](#getPicture--) | Geeft de afbeelding terug. |
| [getCropLeft()](#getCropLeft--) | Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat links van de afbeelding wordt bijgesneden terug of stelt dit in. |
| [setCropLeft(float value)](#setCropLeft-float-) | Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat links van de afbeelding wordt bijgesneden terug of stelt dit in. |
| [getCropTop()](#getCropTop--) | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat boven de afbeelding wordt bijgesneden terug of stelt dit in. |
| [setCropTop(float value)](#setCropTop-float-) | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat boven de afbeelding wordt bijgesneden terug of stelt dit in. |
| [getCropRight()](#getCropRight--) | Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat rechts van de afbeelding wordt bijgesneden terug of stelt dit in. |
| [setCropRight(float value)](#setCropRight-float-) | Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat rechts van de afbeelding wordt bijgesneden terug of stelt dit in. |
| [getCropBottom()](#getCropBottom--) | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat onder de afbeelding wordt bijgesneden terug of stelt dit in. |
| [setCropBottom(float value)](#setCropBottom-float-) | Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat onder de afbeelding wordt bijgesneden terug of stelt dit in. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Geeft de linkerrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de linkerrand van het begrenzingsvak van de vorm. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Geeft de linkerrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de linkerrand van het begrenzingsvak van de vorm. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Geeft de bovengrens van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de bovengrens van het begrenzingsvak van de vorm. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Geeft de bovengrens van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de bovengrens van het begrenzingsvak van de vorm. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Geeft de rechterrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de rechterrand van het begrenzingsvak van de vorm. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Geeft de rechterrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de rechterrand van het begrenzingsvak van de vorm. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Geeft de onderrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de onderrand van het begrenzingsvak van de vorm. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Geeft de onderrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de onderrand van het begrenzingsvak van de vorm. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Verwijder bijgesneden gebieden van de vulafbeelding. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. |
| [getTileOffsetX()](#getTileOffsetX--) | Geeft de horizontale offset van de textuur vanaf de oorsprong van de vorm in punten terug of stelt deze in. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Geeft de horizontale offset van de textuur vanaf de oorsprong van de vorm in punten terug of stelt deze in. |
| [getTileOffsetY()](#getTileOffsetY--) | Geeft de verticale offset van de textuur vanaf de oorsprong van de vorm in punten terug of stelt deze in. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Geeft de verticale offset van de textuur vanaf de oorsprong van de vorm in punten terug of stelt deze in. |
| [getTileScaleX()](#getTileScaleX--) | Geeft de horizontale schaal voor de textuurvulling als percentage terug of stelt deze in. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Geeft de horizontale schaal voor de textuurvulling als percentage terug of stelt deze in. |
| [getTileScaleY()](#getTileScaleY--) | Geeft de verticale schaal voor de textuurvulling als percentage terug of stelt deze in. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Geeft de verticale schaal voor de textuurvulling als percentage terug of stelt deze in. |
| [getTileAlignment()](#getTileAlignment--) | Geeft terug of stelt in hoe de textuur binnen de vorm wordt uitgelijnd. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Geeft terug of stelt in hoe de textuur binnen de vorm wordt uitgelijnd. |
| [getTileFlip()](#getTileFlip--) | Draait de textuurtegel rond zijn horizontale, verticale of beide assen. |
| [setTileFlip(int value)](#setTileFlip-int-) | Draait de textuurtegel rond zijn horizontale, verticale of beide assen. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Geeft de dpi terug of stelt deze in die wordt gebruikt om een afbeelding te vullen. Lezen/schrijven int.

**Retourneert:**
int
### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Geeft de dpi terug of stelt deze in die wordt gebruikt om een afbeelding te vullen. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Geeft de afbeeldingsvullingsmodus terug of stelt deze in. Lezen/schrijven [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Retourneert:**
int
### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Geeft de afbeeldingsvullingsmodus terug of stelt deze in. Lezen/schrijven [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Geeft de afbeelding terug. Alleen-lezen [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retourneert:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat links van de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven float.

**Retourneert:**
float
### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat links van de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat boven de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven float.

**Retourneert:**
float
### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat boven de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat rechts van de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven float.

**Retourneert:**
float
### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Geeft het aantal procenten van de werkelijke afbeeldingsbreedte dat rechts van de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat onder de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven float.

**Retourneert:**
float
### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Geeft het aantal procenten van de werkelijke afbeeldingshoogte dat onder de afbeelding wordt bijgesneden terug of stelt dit in. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Geeft de linkerrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de linkerrand van het begrenzingsvak van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen/schrijven float.

**Retourneert:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Geeft de linkerrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de linkerrand van het begrenzingsvak van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Geeft de bovengrens van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de bovengrens van het begrenzingsvak van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen/schrijven float.

**Retourneert:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Geeft de bovengrens van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de bovengrens van het begrenzingsvak van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Geeft de rechterrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de rechterrand van het begrenzingsvak van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen/schrijven float.

**Retourneert:**
float
### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Geeft de rechterrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de rechterrand van het begrenzingsvak van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Geeft de onderrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de onderrand van het begrenzingsvak van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen/schrijven float.

**Retourneert:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Geeft de onderrand van de vulrechthoek terug of stelt deze in die wordt gedefinieerd door een percentages offset vanaf de onderrand van het begrenzingsvak van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen/schrijven float.

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
>      // Haalt het PictureFrame op
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Verwijdert bijgesneden gebieden van de PictureFrame-afbeelding
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage) - Bijgesneden afbeelding of originele afbeelding als bijsnijden niet nodig is.

--------------------

Deze methode converteert WMF/EMF-metabestanden naar een raster-PNG-afbeelding terwijl ze wordt bijgesneden.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel worden bijgesneden gebieden ook verwijderd.

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
| deleteCroppedAreasOfImage | boolean | Als true, verwijdert de methode de bijgesneden gebieden van de afbeelding, waardoor de grootte mogelijk verder wordt verkleind. |
| resolution | int | De doelresolutie voor compressie, gespecificeerd als een waarde van de [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

Deze methode wijzigt de grootte en resolutie van de afbeelding, vergelijkbaar met de functie “Picture Format -> Compress Pictures” van PowerPoint. |

**Retour:**
boolean - Een boolean die aangeeft of de afbeelding met succes is gecomprimeerd. Retourneert true als de afbeelding is verkleind of bijgesneden, anders false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe de ```
> CompressImage
> ```
-methode wordt gebruikt om de grootte van een afbeelding in een presentatie te verkleinen door een doelresolutie in te stellen en bijgesneden gebieden te verwijderen:
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

We have no explicit comments in the provided code block—only descriptive text. Since the instruction is to translate comments only, and there are no comment markers (`//`, `/* */`, `#`), no translation is needed. However, preserving the block exactly as given is required.

```
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

**Returns:**
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

**Retour:**
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