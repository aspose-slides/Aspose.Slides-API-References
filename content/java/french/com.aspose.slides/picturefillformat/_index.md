---
title: PictureFillFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un style de remplissage d'image.
type: docs
url: /fr/com.aspose.slides/picturefillformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Représente un style de remplissage d'image.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Renvoie ou définit le dpi utilisé pour remplir une image. |
| [setDpi(int value)](#setDpi-int-) | Renvoie ou définit le dpi utilisé pour remplir une image. |
| [getPictureFillMode()](#getPictureFillMode--) | Renvoie ou définit le mode de remplissage d'image. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Renvoie ou définit le mode de remplissage d'image. |
| [getPicture()](#getPicture--) | Renvoie l'image. |
| [getCropLeft()](#getCropLeft--) | Renvoie ou définit le pourcentage de la largeur réelle de l'image recadré à gauche de l'image. |
| [setCropLeft(float value)](#setCropLeft-float-) | Renvoie ou définit le pourcentage de la largeur réelle de l'image recadré à gauche de l'image. |
| [getCropTop()](#getCropTop--) | Renvoie ou définit le pourcentage de la hauteur réelle de l'image recadré en haut de l'image. |
| [setCropTop(float value)](#setCropTop-float-) | Renvoie ou définit le pourcentage de la hauteur réelle de l'image recadré en haut de l'image. |
| [getCropRight()](#getCropRight--) | Renvoie ou définit le pourcentage de la largeur réelle de l'image recadré à droite de l'image. |
| [setCropRight(float value)](#setCropRight-float-) | Renvoie ou définit le pourcentage de la largeur réelle de l'image recadré à droite de l'image. |
| [getCropBottom()](#getCropBottom--) | Renvoie ou définit le pourcentage de la hauteur réelle de l'image recadré en bas de l'image. |
| [setCropBottom(float value)](#setCropBottom-float-) | Renvoie ou définit le pourcentage de la hauteur réelle de l'image recadré en bas de l'image. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Supprime les zones recadrées du remplissage d'image. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord gauche de la boîte englobante de la forme. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord gauche de la boîte englobante de la forme. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord supérieur de la boîte englobante de la forme. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord supérieur de la boîte englobante de la forme. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord droit de la boîte englobante de la forme. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord droit de la boîte englobante de la forme. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord inférieur de la boîte englobante de la forme. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage par rapport au bord inférieur de la boîte englobante de la forme. |
| [getTileOffsetX()](#getTileOffsetX--) | Renvoie ou définit le décalage horizontal de la texture depuis l'origine de la forme en points. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Renvoie ou définit le décalage horizontal de la texture depuis l'origine de la forme en points. |
| [getTileOffsetY()](#getTileOffsetY--) | Renvoie ou définit le décalage vertical de la texture depuis l'origine de la forme en points. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Renvoie ou définit le décalage vertical de la texture depuis l'origine de la forme en points. |
| [getTileScaleX()](#getTileScaleX--) | Renvoie ou définit l'échelle horizontale du remplissage de texture en pourcentage. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Renvoie ou définit l'échelle horizontale du remplissage de texture en pourcentage. |
| [getTileScaleY()](#getTileScaleY--) | Renvoie ou définit l'échelle verticale du remplissage de texture en pourcentage. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Renvoie ou définit l'échelle verticale du remplissage de texture en pourcentage. |
| [getTileAlignment()](#getTileAlignment--) | Renvoie ou définit l'alignement de la texture à l'intérieur de la forme. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Renvoie ou définit l'alignement de la texture à l'intérieur de la forme. |
| [getTileFlip()](#getTileFlip--) | Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. |
| [setTileFlip(int value)](#setTileFlip-int-) | Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Renvoie ou définit le dpi utilisé pour remplir une image. Lecture/écriture int.

**Renvoie :**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Renvoie ou définit le dpi utilisé pour remplir une image. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Renvoie ou définit le mode de remplissage d'image. Lecture/écriture [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Renvoie :**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Renvoie ou définit le mode de remplissage d'image. Lecture/écriture [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Renvoie l'image. Lecture seule [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Renvoie :**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Renvoie ou définit le pourcentage de la largeur réelle de l'image recadré à gauche de l'image. Lecture/écriture float.

**Renvoie :**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Renvoie ou définit le pourcentage de la largeur réelle de l'image recadré à gauche de l'image. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Renvoie ou définit le pourcentage de la hauteur réelle de l'image recadré en haut de l'image. Lecture/écriture float.

**Renvoie :**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Renvoie ou définit le pourcentage de la hauteur réelle de l'image recadré en haut de l'image. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Renvoie ou définit le pourcentage de la largeur réelle de l'image recadré à droite de l'image. Lecture/écriture float.

**Renvoie :**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Renvoie ou définit le pourcentage de la largeur réelle de l'image recadré à droite de l'image. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Renvoie ou définit le pourcentage de la hauteur réelle de l'image recadré en bas de l'image. Lecture/écriture float.

**Renvoie :**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Renvoie ou définit le pourcentage de la hauteur réelle de l'image recadré en bas de l'image. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Supprime les zones recadrées du remplissage d'image.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Obtient le PictureFrame
>      IPictureFrame picFrame = (IPPictureFrame)slide.getShapes().get_Item(0);
>      // Supprime les zones recadrées de l'image du PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**
[IPPImage](../../com.aspose.slides/ippimage) - Image recadrée ou image d'origine si le recadrage n'est pas nécessaire.

--------------------

Cette méthode convertit les métafichiers WMF/EMF en image PNG raster tout en recadrant.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, elle supprime également les zones recadrées.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` méthode pour réduire la taille d'une image dans une présentation en définissant une résolution cible et en supprimant les zones recadrées :
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
> L'exemple suivant montre comment utiliser la ```
> CompressImage
> ``` méthode pour réduire la taille d'une image dans une présentation en définissant une résolution cible et en supprimant les zones recadrées :
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

--------------------

La valeur par défaut est [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |