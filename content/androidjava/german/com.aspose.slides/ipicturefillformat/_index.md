---
title: IPictureFillFormat
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
url: /de/com.aspose.slides/ipicturefillformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Stellt einen Bildfüllstil dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDpi()](#getDpi--) | Gibt den dpi zurück oder legt ihn fest, der zum Füllen eines Bildes verwendet wird. |
| [setDpi(int value)](#setDpi-int-) | Gibt den dpi zurück oder legt ihn fest, der zum Füllen eines Bildes verwendet wird. |
| [getPictureFillMode()](#getPictureFillMode--) | Gibt den Bildfüllmodus zurück oder legt ihn fest. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Gibt den Bildfüllmodus zurück oder legt ihn fest. |
| [getPicture()](#getPicture--) | Gibt das Bild zurück. |
| [getCropLeft()](#getCropLeft--) | Gibt den Prozentsatz der tatsächlichen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder legt ihn fest. |
| [setCropLeft(float value)](#setCropLeft-float-) | Gibt den Prozentsatz der tatsächlichen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder legt ihn fest. |
| [getCropTop()](#getCropTop--) | Gibt den Prozentsatz der tatsächlichen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder legt ihn fest. |
| [setCropTop(float value)](#setCropTop-float-) | Gibt den Prozentsatz der tatsächlichen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder legt ihn fest. |
| [getCropRight()](#getCropRight--) | Gibt den Prozentsatz der tatsächlichen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder legt ihn fest. |
| [setCropRight(float value)](#setCropRight-float-) | Gibt den Prozentsatz der tatsächlichen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder legt ihn fest. |
| [getCropBottom()](#getCropBottom--) | Gibt den Prozentsatz der tatsächlichen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder legt ihn fest. |
| [setCropBottom(float value)](#setCropBottom-float-) | Gibt den Prozentsatz der tatsächlichen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder legt ihn fest. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Gibt die linke Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Gibt die linke Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Gibt die obere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Gibt die obere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Gibt die rechte Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Gibt die rechte Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Gibt die untere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Gibt die untere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Löscht zugeschnittene Bereiche des gefüllten Bildes. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. |
| [getTileOffsetX()](#getTileOffsetX--) | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest. |
| [getTileOffsetY()](#getTileOffsetY--) | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück oder legt ihn fest. |
| [getTileScaleX()](#getTileScaleX--) | Gibt die horizontale Skalierung für die Texturfüllung in Prozent zurück oder legt sie fest. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Gibt die horizontale Skalierung für die Texturfüllung in Prozent zurück oder legt sie fest. |
| [getTileScaleY()](#getTileScaleY--) | Gibt die vertikale Skalierung für die Texturfüllung in Prozent zurück oder legt sie fest. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Gibt die vertikale Skalierung für die Texturfüllung in Prozent zurück oder legt sie fest. |
| [getTileAlignment()](#getTileAlignment--) | Gibt zurück oder legt fest, wie die Textur innerhalb der Form ausgerichtet ist. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Gibt zurück oder legt fest, wie die Textur innerhalb der Form ausgerichtet ist. |
| [getTileFlip()](#getTileFlip--) | Dreht das Textur-Kachelmuster um seine horizontale, vertikale oder beide Achsen. |
| [setTileFlip(int value)](#setTileFlip-int-) | Dreht das Textur-Kachelmuster um seine horizontale, vertikale oder beide Achsen. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Gibt den dpi zurück oder legt ihn fest, der zum Füllen eines Bildes verwendet wird. Lesen/Schreiben int.

**Rückgabe:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Gibt den dpi zurück oder legt ihn fest, der zum Füllen eines Bildes verwendet wird. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Gibt den Bildfüllmodus zurück oder legt ihn fest. Lesen/Schreiben [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Rückgabe:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Gibt den Bildfüllmodus zurück oder legt ihn fest. Lesen/Schreiben [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Gibt das Bild zurück. Nur lesend [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Rückgabe:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Gibt den Prozentsatz der tatsächlichen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder legt ihn fest. Lesen/Schreiben float.

**Rückgabe:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Gibt den Prozentsatz der tatsächlichen Bildbreite zurück, der links vom Bild abgeschnitten wird, oder legt ihn fest. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Gibt den Prozentsatz der tatsächlichen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder legt ihn fest. Lesen/Schreiben float.

**Rückgabe:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Gibt den Prozentsatz der tatsächlichen Bildhöhe zurück, der oben vom Bild abgeschnitten wird, oder legt ihn fest. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Gibt den Prozentsatz der tatsächlichen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder legt ihn fest. Lesen/Schreiben float.

**Rückgabe:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Gibt den Prozentsatz der tatsächlichen Bildbreite zurück, der rechts vom Bild abgeschnitten wird, oder legt ihn fest. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Gibt den Prozentsatz der tatsächlichen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder legt ihn fest. Lesen/Schreiben float.

**Rückgabe:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Gibt den Prozentsatz der tatsächlichen Bildhöhe zurück, der unten vom Bild abgeschnitten wird, oder legt ihn fest. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Gibt die linke Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet einen Einzug, ein negativer Prozentsatz einen Auszug. Lesen/Schreiben float.

**Rückgabe:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Gibt die linke Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet einen Einzug, ein negativer Prozentsatz einen Auszug. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Gibt die obere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet einen Einzug, ein negativer Prozentsatz einen Auszug. Lesen/Schreiben float.

**Rückgabe:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Gibt die obere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet einen Einzug, ein negativer Prozentsatz einen Auszug. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Gibt die rechte Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet einen Einzug, ein negativer Prozentsatz einen Auszug. Lesen/Schreiben float.

**Rückgabe:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Gibt die rechte Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet einen Einzug, ein negativer Prozentsatz einen Auszug. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Gibt die untere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet einen Einzug, ein negativer Prozentsatz einen Auszug. Lesen/Schreiben float.

**Rückgabe:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Gibt die untere Kante des Füllrechtecks zurück oder legt sie fest, die durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet einen Einzug, ein negativer Prozentsatz einen Auszug. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Löscht zugeschnittene Bereiche des gefüllten Bildes.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Holt das PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Löscht zugeschnittene Bereiche des PictureFrame-Bildes
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Rückgabe:**
[IPPImage](../../com.aspose.slides/ippimage) – Zugezischtes Bild oder Originalbild, falls kein Zuschnitt nötig ist.

--------------------

Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild und schneidet es zu.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional löscht es auch zugeschnittene Bereiche.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` Methode zur Reduzierung der Bildgröße in einer Präsentation durch Festlegung einer Zielauflösung und Entfernen zugeschnittener Bereiche:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Bild mit einer Zielauflösung von 150 DPI (Web-Auflösung) komprimieren und zugeschnittene Bereiche entfernen
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
> Das folgende Beispiel zeigt, wie die ```
> CompressImage
> ```
-Methode verwendet wird, um die Bildgröße in einer Präsentation durch Festlegung einer Zielauflösung und Entfernen zugeschnittener Bereiche zu reduzieren:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Holt das PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Bild mit einer Zielauflösung von 150 DPI (Web-Auflösung) komprimieren und zugeschnittene Bereiche entfernen
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web-Auflösung
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Falls true, entfernt die Methode die zugeschnittenen Bildbereiche, wodurch die Größe weiter reduziert werden kann. |
| resolution | float | Die Zielauflösung in DPI. Dieser Wert muss positiv sein und bestimmt, wie das Bild skaliert wird. |

--------------------

Diese Methode ändert die Größe und Auflösung des Bildes ähnlich der PowerPoint-Funktion „Picture Format -> Compress Pictures“.

**Rückgabe:**
boolean – Ein boolescher Wert, der angibt, ob das Bild erfolgreich komprimiert wurde. Gibt true zurück, wenn das Bild skaliert oder zugeschnitten wurde, andernfalls false.
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt den horizontalen Versatz der Textur auf 20 Punkte
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt den horizontalen Versatz der Textur auf 20 Punkte
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt den vertikalen Versatz der Textur auf -50 Punkte
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Rückgabe:**
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt den vertikalen Versatz der Textur auf -50 Punkte
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt die horizontale Skalierung der Textur auf 120 Prozent
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Rückgabe:**
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt die horizontale Skalierung der Textur auf 120 Prozent
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt die vertikale Skalierung der Textur auf 120 Prozent
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt die vertikale Skalierung der Textur auf 120 Prozent
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt die Ausrichtung der Kachel auf rechts unten
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Setzt die Ausrichtung der Kachel auf rechts unten
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Dreht die Texturkachel um ihre vertikale Achse.
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
>      // Holt das picture fill format der Form
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Setzt den Bildfüllmodus auf Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Dreht die Texturkachel um ihre vertikale Achse.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Standardwert ist [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |