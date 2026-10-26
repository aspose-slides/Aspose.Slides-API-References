---
title: PictureFillFormat
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
url: /de/com.aspose.slides/picturefillformat/
---
**Vererbung:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)  
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Stellt einen Bildfüllstil dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Gibt den DPI zurück oder setzt ihn, der zum Füllen eines Bildes verwendet wird. |
| [setDpi(int value)](#setDpi-int-) | Gibt den DPI zurück oder setzt ihn, der zum Füllen eines Bildes verwendet wird. |
| [getPictureFillMode()](#getPictureFillMode--) | Gibt den Bildfüllmodus zurück oder setzt ihn. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Gibt den Bildfüllmodus zurück oder setzt ihn. |
| [getPicture()](#getPicture--) | Gibt das Bild zurück. |
| [getCropLeft()](#getCropLeft--) | Gibt den Prozentsatz der realen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder setzt ihn. |
| [setCropLeft(float value)](#setCropLeft-float-) | Gibt den Prozentsatz der realen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder setzt ihn. |
| [getCropTop()](#getCropTop--) | Gibt den Prozentsatz der realen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder setzt ihn. |
| [setCropTop(float value)](#setCropTop-float-) | Gibt den Prozentsatz der realen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder setzt ihn. |
| [getCropRight()](#getCropRight--) | Gibt den Prozentsatz der realen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder setzt ihn. |
| [setCropRight(float value)](#setCropRight-float-) | Gibt den Prozentsatz der realen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder setzt ihn. |
| [getCropBottom()](#getCropBottom--) | Gibt den Prozentsatz der realen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder setzt ihn. |
| [setCropBottom(float value)](#setCropBottom-float-) | Gibt den Prozentsatz der realen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder setzt ihn. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Löscht beschnittene Bereiche des gefüllten Bildes. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Gibt die linke Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Gibt die linke Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Gibt die obere Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Gibt die obere Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Gibt die rechte Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Gibt die rechte Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Gibt die untere Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Gibt die untere Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. |
| [getTileOffsetX()](#getTileOffsetX--) | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder setzt ihn. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder setzt ihn. |
| [getTileOffsetY()](#getTileOffsetY--) | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder setzt ihn. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder setzt ihn. |
| [getTileScaleX()](#getTileScaleX--) | Gibt die horizontale Skalierung der Texturfüllung als Prozentsatz zurück oder setzt sie. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Gibt die horizontale Skalierung der Texturfüllung als Prozentsatz zurück oder setzt sie. |
| [getTileScaleY()](#getTileScaleY--) | Gibt die vertikale Skalierung der Texturfüllung als Prozentsatz zurück oder setzt sie. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Gibt die vertikale Skalierung der Texturfüllung als Prozentsatz zurück oder setzt sie. |
| [getTileAlignment()](#getTileAlignment--) | Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist, oder setzt dies. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist, oder setzt dies. |
| [getTileFlip()](#getTileFlip--) | Spiegelt die Textur-Kachel um seine horizontale, vertikale oder beide Achsen. |
| [setTileFlip(int value)](#setTileFlip-int-) | Spiegelt die Textur-Kachel um seine horizontale, vertikale oder beide Achsen. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lese long.

**Rückgabe:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Gibt den DPI zurück oder setzt ihn, der zum Füllen eines Bildes verwendet wird. Lesen/Schreiben int.

**Rückgabe:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Gibt den DPI zurück oder setzt ihn, der zum Füllen eines Bildes verwendet wird. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Gibt den Bildfüllmodus zurück oder setzt ihn. Lesen/Schreiben [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Rückgabe:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Gibt den Bildfüllmodus zurück oder setzt ihn. Lesen/Schreiben [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Gibt das Bild zurück. Nur-Lese [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Rückgabe:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Gibt den Prozentsatz der realen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder setzt ihn. Lesen/Schreiben float.

**Rückgabe:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Gibt den Prozentsatz der realen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder setzt ihn. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Gibt den Prozentsatz der realen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder setzt ihn. Lesen/Schreiben float.

**Rückgabe:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Gibt den Prozentsatz der realen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder setzt ihn. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Gibt den Prozentsatz der realen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder setzt ihn. Lesen/Schreiben float.

**Rückgabe:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Gibt den Prozentsatz der realen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder setzt ihn. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Gibt den Prozentsatz der realen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder setzt ihn. Lesen/Schreiben float.

**Rückgabe:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Gibt den Prozentsatz der realen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder setzt ihn. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Löscht beschnittene Bereiche des gefüllten Bildes.

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Holt das PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Löscht beschnittene Bereiche des PictureFrame-Bildes
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
[IPPImage](../../com.aspose.slides/ippimage) - Beschnittenes Bild oder Ursprungsbild, wenn Beschneiden nicht notwendig ist.

Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild und schneidet dabei zu.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional löscht es auch beschnittene Bereiche.

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` Methode, um die Größe eines Bildes in einer Präsentation zu reduzieren, indem eine Zielauflösung festgelegt und beschnittene Bereiche entfernt werden:
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
> Das folgende Beispiel zeigt, wie die ```
> CompressImage
> ``` Methode verwendet wird, um die Größe eines Bildes in einer Präsentation zu reduzieren, indem eine Zielauflösung festgelegt und beschnittene Bereiche entfernt werden:
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

Gibt die untere Kante des Füllrechtecks zurück oder setzt sie, die durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt eine Einrückung an, während ein negativer Prozentsatz eine Ausstülpung angibt. Read/write  float .

**Parameter:**
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

Weiter



***



***/

The answer…





Sure

This 













Sch





…







...





…

…

...

"





...



 

...




Writable






…





...









…

…

…
















...





"

















…





 





…
















 





...







weiter







...





 





  

We



...









... 

...



…








 






…

…





















....







 









"""

It?















 





 





…





"





.....





 









)







 









 




































 

 

















...





















...





 

.






















 

















...



"









 […]

















 

 





 



















....









 

...























…

























 

...









\"?











		
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
**Returns:
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

---

Standard ist [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |