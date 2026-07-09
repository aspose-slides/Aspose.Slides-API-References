---
title: IPictureFillFormat
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un style de remplissage d'image.
type: docs
url: /fr/com.aspose.slides/ipicturefillformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Représente un style de remplissage d'image.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDpi()](#getDpi--) | Renvoie ou définit le DPI utilisé pour remplir une image. |
| [setDpi(int value)](#setDpi-int-) | Renvoie ou définit le DPI utilisé pour remplir une image. |
| [getPictureFillMode()](#getPictureFillMode--) | Renvoie ou définit le mode de remplissage d'image. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Renvoie ou définit le mode de remplissage d'image. |
| [getPicture()](#getPicture--) | Renvoie l'image. |
| [getCropLeft()](#getCropLeft--) | Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est recadré du côté gauche de l'image. |
| [setCropLeft(float value)](#setCropLeft-float-) | Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est recadré du côté gauche de l'image. |
| [getCropTop()](#getCropTop--) | Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est recadré du haut de l'image. |
| [setCropTop(float value)](#setCropTop-float-) | Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est recadré du haut de l'image. |
| [getCropRight()](#getCropRight--) | Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est recadré du côté droit de l'image. |
| [setCropRight(float value)](#setCropRight-float-) | Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est recadré du côté droit de l'image. |
| [getCropBottom()](#getCropBottom--) | Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est recadré du bas de l'image. |
| [setCropBottom(float value)](#setCropBottom-float-) | Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est recadré du bas de l'image. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Supprime les zones recadrées de l'image de remplissage. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. |
| [getTileOffsetX()](#getTileOffsetX--) | Renvoie ou définit le décalage horizontal de la texture depuis l'origine de la forme en points. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Renvoie ou définit le décalage horizontal de la texture depuis l'origine de la forme en points. |
| [getTileOffsetY()](#getTileOffsetY--) | Renvoie ou définit le décalage vertical de la texture depuis l'origine de la forme en points. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Renvoie ou définit le décalage vertical de la texture depuis l'origine de la forme en points. |
| [getTileScaleX()](#getTileScaleX--) | Renvoie ou définit l'échelle horizontale du remplissage de texture en pourcentage. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Renvoie ou définit l'échelle horizontale du remplissage de texture en pourcentage. |
| [getTileScaleY()](#getTileScaleY--) | Renvoie ou définit l'échelle verticale du remplissage de texture en pourcentage. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Renvoie ou définit l'échelle verticale du remplissage de texture en pourcentage. |
| [getTileAlignment()](#getTileAlignment--) | Renvoie ou définit comment la texture est alignée dans la forme. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Renvoie ou définit comment la texture est alignée dans la forme. |
| [getTileFlip()](#getTileFlip--) | Retourne la tuile de texture autour de son axe horizontal, vertical ou des deux. |
| [setTileFlip(int value)](#setTileFlip-int-) | Retourne la tuile de texture autour de son axe horizontal, vertical ou des deux. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Renvoie ou définit le DPI utilisé pour remplir une image. Lecture/écriture int.

**Renvoie :**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Renvoie ou définit le DPI utilisé pour remplir une image. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Renvoie ou définit le mode de remplissage d'image. Lecture/écriture [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Renvoie :**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Renvoie ou définit le mode de remplissage d'image. Lecture/écriture [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Renvoie l'image. Lecture seule [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Renvoie :**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est recadré du côté gauche de l'image. Lecture/écriture float.

**Renvoie :**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est recadré du côté gauche de l'image. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est recadré du haut de l'image. Lecture/écriture float.

**Renvoie :**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est recadré du haut de l'image. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est recadré du côté droit de l'image. Lecture/écriture float.

**Renvoie :**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Renvoie ou définit le pourcentage de la largeur réelle de l'image qui est recadré du côté droit de l'image. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est recadré du bas de l'image. Lecture/écriture float.

**Renvoie :**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Renvoie ou définit le pourcentage de la hauteur réelle de l'image qui est recadré du bas de l'image. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. Un pourcentage positif indique un retrait, un pourcentage négatif indique une extension. Lecture/écriture float.

**Renvoie :**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Renvoie ou définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. Un pourcentage positif indique un retrait, un pourcentage négatif indique une extension. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, un pourcentage négatif indique une extension. Lecture/écriture float.

**Renvoie :**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Renvoie ou définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, un pourcentage négatif indique une extension. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. Un pourcentage positif indique un retrait, un pourcentage négatif indique une extension. Lecture/écriture float.

**Renvoie :**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Renvoie ou définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. Un pourcentage positif indique un retrait, un pourcentage négatif indique une extension. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, un pourcentage négatif indique une extension. Lecture/écriture float.

**Renvoie :**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Renvoie ou définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, un pourcentage négatif indique une extension. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Supprime les zones recadrées de l'image de remplissage.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Deletes cropped areas of the PictureFrame image
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Cropped image or origin image if cropping is not necessary.

--------------------

This method converts WMF/EMF metafiles to raster PNG image while cropping.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```
Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compresse l'image avec une résolution cible de 150 DPI (résolution Web) et supprime les zones recadrées
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
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```
 
Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` method to reduce the size of an image in a presentation by setting a target resolution and removing cropped areas:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Obtient le PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compresse l'image avec une résolution cible de 150 DPI (résolution Web) et supprime les zones recadrées
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // résolution Web
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit le décalage horizontal de la texture à 20 points
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit le décalage horizontal de la texture à 20 points
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit le décalage vertical de la texture à -50 points
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit le décalage vertical de la texture à -50 points
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit l'échelle horizontale de la texture à 120 pour cent
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit l'échelle horizontale de la texture à 120 pour cent
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit l'échelle verticale de la texture à 120 pour cent
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit l'échelle verticale de la texture à 120 pour cent
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit l'alignement du carrelage en bas à droite
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Définit l'alignement du carrelage en bas à droite
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>      }
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
>      // Obtient le format de remplissage d'image de la forme
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Définit le mode de remplissage d'image sur Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Retourne la tuile de texture autour de son axe vertical.
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

Retourne la tuile de texture autour de son axe horizontal, vertical ou des deux. Lecture/écriture [TileFlip](../../com.aspose.slides/tileflip).

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

La valeur par défaut est [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |