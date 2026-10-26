---
title: IPictureFillFormat
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa un estilo de relleno de imagen.
type: docs
url: /es/com.aspose.slides/ipicturefillformat/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Representa un estilo de relleno de imagen.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDpi()](#getDpi--) | Devuelve o establece el dpi que se usa para rellenar una imagen. |
| [setDpi(int value)](#setDpi-int-) | Devuelve o establece el dpi que se usa para rellenar una imagen. |
| [getPictureFillMode()](#getPictureFillMode--) | Devuelve o establece el modo de relleno de imagen. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Devuelve o establece el modo de relleno de imagen. |
| [getPicture()](#getPicture--) | Devuelve la Picture. |
| [getCropLeft()](#getCropLeft--) | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la Picture. |
| [setCropLeft(float value)](#setCropLeft-float-) | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la Picture. |
| [getCropTop()](#getCropTop--) | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la Picture. |
| [setCropTop(float value)](#setCropTop-float-) | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la Picture. |
| [getCropRight()](#getCropRight--) | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la Picture. |
| [setCropRight(float value)](#setCropRight-float-) | Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la Picture. |
| [getCropBottom()](#getCropBottom--) | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la Picture. |
| [setCropBottom(float value)](#setCropBottom-float-) | Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la Picture. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Elimina áreas recortadas del Picture de relleno. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. |
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
| [getTileFlip()](#getTileFlip--) | Invierte la tesela de textura alrededor de su eje horizontal, vertical o ambos. |
| [setTileFlip(int value)](#setTileFlip-int-) | Invierte la tesela de textura alrededor de su eje horizontal, vertical o ambos. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Devuelve o establece el dpi que se usa para rellenar una imagen. Lectura/escritura int.

**Devuelve:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Devuelve o establece el dpi que se usa para rellenar una imagen. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Devuelve o establece el modo de relleno de imagen. Lectura/escritura [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Devuelve:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Devuelve o establece el modo de relleno de imagen. Lectura/escritura [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Devuelve la Picture. Solo lectura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Devuelve:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la Picture. Lectura/escritura float.

**Devuelve:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la Picture. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la Picture. Lectura/escritura float.

**Devuelve:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la Picture. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la Picture. Lectura/escritura float.

**Devuelve:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Devuelve o establece el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la Picture. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la Picture. Lectura/escritura float.

**Devuelve:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Devuelve o establece el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la Picture. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una extensión. Lectura/escritura float.

**Devuelve:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Devuelve o establece el borde izquierdo del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde izquierdo del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una extensión. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una extensión. Lectura/escritura float.

**Devuelve:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Devuelve o establece el borde superior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde superior del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una extensión. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una extensión. Lectura/escritura float.

**Devuelve:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Devuelve o establece el borde derecho del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde derecho del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una extensión. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una extensión. Lectura/escritura float.

**Devuelve:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Devuelve o establece el borde inferior del rectángulo de relleno que se define mediante un desplazamiento porcentual desde el borde inferior del cuadro delimitador de la forma. Un porcentaje positivo indica una inserción, mientras que un porcentaje negativo indica una extensión. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Elimina áreas recortadas del Picture de relleno.

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
> ```

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen recortada o imagen original si el recorte no es necesario.

--------------------

Este método convierte archivos metafile WMF/EMF a imágenes PNG raster mientras recorta.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Comprime la imagen reduciendo su tamaño según el tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

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
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
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
**Devuelve:**
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

El valor predeterminado es [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |