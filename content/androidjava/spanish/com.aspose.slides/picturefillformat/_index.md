---
title: PictureFillFormat
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un estilo de relleno de imagen.
type: docs
url: /es/com.aspose.slides/picturefillformat/
---
**Herencia:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)  
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Representa un estilo de relleno de imagen.

## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Devuelve o establece el dpi que se usa para rellenar una imagen. |
| [setDpi(int value)](#setDpi-int-) | Devuelve o establece el dpi que se usa para rellenar una imagen. |
| [getPictureFillMode()](#getPictureFillMode--) | Devuelve o establece el modo de relleno de imagen. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Devuelve o establece el modo de relleno de imagen. |
| [getPicture()](#getPicture--) | Devuelve la imagen. |
| [getCropLeft()](#getCropLeft--) | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la imagen. |
| [setCropLeft(float value)](#setCropLeft-float-) | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la imagen. |
| [getCropTop()](#getCropTop--) | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la imagen. |
| [setCropTop(float value)](#setCropTop-float-) | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la imagen. |
| [getCropRight()](#getCropRight--) | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la imagen. |
| [setCropRight(float value)](#setCropRight-float-) | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la imagen. |
| [getCropBottom()](#getCropBottom--) | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la imagen. |
| [setCropBottom(float value)](#setCropBottom-float-) | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la imagen. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Elimina las áreas recortadas del relleno de imagen. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. |
| [getTileOffsetX()](#getTileOffsetX--) | Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos. |
| [getTileOffsetY()](#getTileOffsetY--) | Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. |
| [getTileScaleX()](#getTileScaleX--) | Devuelve o establece la escala horizontal para el relleno de textura como un porcentaje. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Devuelve o establece la escala horizontal para el relleno de textura como un porcentaje. |
| [getTileScaleY()](#getTileScaleY--) | Devuelve o establece la escala vertical para el relleno de textura como un porcentaje. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Devuelve o establece la escala vertical para el relleno de textura como un porcentaje. |
| [getTileAlignment()](#getTileAlignment--) | Devuelve o establece cómo se alinea la textura dentro de la forma. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Devuelve o establece cómo se alinea la textura dentro de la forma. |
| [getTileFlip()](#getTileFlip--) | Voltea la tesela de textura alrededor de su eje horizontal, vertical o ambos. |
| [setTileFlip(int value)](#setTileFlip-int-) | Voltea la tesela de textura alrededor de su eje horizontal, vertical o ambos. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**  
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Devuelve o establece el dpi que se usa para rellenar una imagen. Lectura/escritura  int .

**Devuelve:**  
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Devuelve o establece el dpi que se usa para rellenar una imagen. Lectura/escritura  int .

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Devuelve o establece el modo de relleno de imagen. Lectura/escritura [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Devuelve:**  
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Devuelve o establece el modo de relleno de imagen. Lectura/escritura [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Devuelve la imagen. Solo lectura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Devuelve:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la imagen. Lectura/escritura  float .

**Devuelve:**  
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la imagen. Lectura/escritura  float .

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la imagen. Lectura/escritura  float .

**Devuelve:**  
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la imagen. Lectura/escritura  float .

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la imagen. Lectura/escritura  float .

**Devuelve:**  
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la imagen. Lectura/escritura  float .

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la imagen. Lectura/escritura  float .

**Devuelve:**  
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la imagen. Lectura/escritura  float .

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Elimina las áreas recortadas del relleno de Imagen.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Obtiene el PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Elimina áreas recortadas de la imagen del PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
```

**Devuelve:**  
[IPPImage](../../com.aspose.slides/ippimage) - Imagen recortada o imagen original si el recorte no es necesario.

--------------------

Este método convierte metafiles WMF/EMF a imagen raster PNG mientras recorta.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina áreas recortadas.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` método para reducir el tamaño de una imagen en una presentación estableciendo una resolución objetivo y eliminando áreas recortadas:
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
> El siguiente ejemplo muestra cómo usar el método ```
> CompressImage
> ```
 para reducir el tamaño de una imagen en una presentación estableciendo una resolución objetivo y eliminando áreas recortadas:
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

Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una protrusión. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
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

**Parámetros:**
| Parámetro | Tipo | Descripción |
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
**Devuelve:**
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

El valor predeterminado es [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parámetros:**  
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |