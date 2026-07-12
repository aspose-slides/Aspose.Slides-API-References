---
title: PictureFillFormat
second_title: Referência da API Java Aspose.Slides para Android
description: Representa um estilo de preenchimento de imagem.
type: docs
url: /pt/com.aspose.slides/picturefillformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as interfaces implementadas:**
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

Representa um estilo de preenchimento de imagem.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | Obtém ou define o DPI usado para preencher uma imagem. |
| [setDpi(int value)](#setDpi-int-) | Obtém ou define o DPI usado para preencher uma imagem. |
| [getPictureFillMode()](#getPictureFillMode--) | Obtém ou define o modo de preenchimento da imagem. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Obtém ou define o modo de preenchimento da imagem. |
| [getPicture()](#getPicture--) | Obtém a imagem. |
| [getCropLeft()](#getCropLeft--) | Obtém ou define a percentagem da largura real da imagem que é recortada à esquerda da imagem. |
| [setCropLeft(float value)](#setCropLeft-float-) | Obtém ou define a percentagem da largura real da imagem que é recortada à esquerda da imagem. |
| [getCropTop()](#getCropTop--) | Obtém ou define a percentagem da altura real da imagem que é recortada no topo da imagem. |
| [setCropTop(float value)](#setCropTop-float-) | Obtém ou define a percentagem da altura real da imagem que é recortada no topo da imagem. |
| [getCropRight()](#getCropRight--) | Obtém ou define a percentagem da largura real da imagem que é recortada à direita da imagem. |
| [setCropRight(float value)](#setCropRight-float-) | Obtém ou define a percentagem da largura real da imagem que é recortada à direita da imagem. |
| [getCropBottom()](#getCropBottom--) | Obtém ou define a percentagem da altura real da imagem que é recortada na parte inferior da imagem. |
| [setCropBottom(float value)](#setCropBottom-float-) | Obtém ou define a percentagem da altura real da imagem que é recortada na parte inferior da imagem. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Exclui áreas recortadas da imagem de preenchimento. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Obtém ou define a borda esquerda do retângulo de preenchimento definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Obtém ou define a borda esquerda do retângulo de preenchimento definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Obtém ou define a borda superior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Obtém ou define a borda superior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Obtém ou define a borda direita do retângulo de preenchimento definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Obtém ou define a borda direita do retângulo de preenchimento definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Obtém ou define a borda inferior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Obtém ou define a borda inferior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. |
| [getTileOffsetX()](#getTileOffsetX--) | Obtém ou define o deslocamento horizontal da textura a partir da origem da forma em pontos. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Obtém ou define o deslocamento horizontal da textura a partir da origem da forma em pontos. |
| [getTileOffsetY()](#getTileOffsetY--) | Obtém ou define o deslocamento vertical da textura a partir da origem da forma em pontos. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Obtém ou define o deslocamento vertical da textura a partir da origem da forma em pontos. |
| [getTileScaleX()](#getTileScaleX--) | Obtém ou define a escala horizontal para o preenchimento da textura como percentagem. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Obtém ou define a escala horizontal para o preenchimento da textura como percentagem. |
| [getTileScaleY()](#getTileScaleY--) | Obtém ou define a escala vertical para o preenchimento da textura como percentagem. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Obtém ou define a escala vertical para o preenchimento da textura como percentagem. |
| [getTileAlignment()](#getTileAlignment--) | Obtém ou define como a textura é alinhada dentro da forma. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Obtém ou define como a textura é alinhada dentro da forma. |
| [getTileFlip()](#getTileFlip--) | Inverte o ladrilho de textura em torno do eixo horizontal, vertical ou ambos. |
| [setTileFlip(int value)](#setTileFlip-int-) | Inverte o ladrilho de textura em torno do eixo horizontal, vertical ou ambos. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

Obtém ou define o DPI usado para preencher uma imagem. Leitura/gravação int .

**Retorna:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

Obtém ou define o DPI usado para preencher uma imagem. Leitura/gravação int .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

Obtém ou define o modo de preenchimento da imagem. Leitura/gravação [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Retorna:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

Obtém ou define o modo de preenchimento da imagem. Leitura/gravação [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Obtém a imagem. Somente leitura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retorna:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

Obtém ou define a percentagem da largura real da imagem que é recortada à esquerda da imagem. Leitura/gravação float .

**Retorna:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

Obtém ou define a percentagem da largura real da imagem que é recortada à esquerda da imagem. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

Obtém ou define a percentagem da altura real da imagem que é recortada no topo da imagem. Leitura/gravação float .

**Retorna:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

Obtém ou define a percentagem da altura real da imagem que é recortada no topo da imagem. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

Obtém ou define a percentagem da largura real da imagem que é recortada à direita da imagem. Leitura/gravação float .

**Retorna:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

Obtém ou define a percentagem da largura real da imagem que é recortada à direita da imagem. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

Obtém ou define a percentagem da altura real da imagem que é recortada na parte inferior da imagem. Leitura/gravação float .

**Retorna:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

Obtém ou define a percentagem da altura real da imagem que é recortada na parte inferior da imagem. Leitura/gravação float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

Exclui áreas recortadas da imagem de preenchimento.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Obtém o PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Exclui áreas recortadas da imagem do PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem recortada ou imagem original se o recorte não for necessário.

--------------------

Este método converte metafiles WMF/EMF em imagem PNG raster enquanto recorta.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` método para reduzir o tamanho de uma imagem em uma apresentação definindo uma resolução alvo e removendo áreas recortadas:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compacta a imagem com resolução alvo de 150 DPI (resolução Web) e remove áreas recortadas
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

> O exemplo a seguir demonstra como usar o método ```
> CompressImage
> ```
 para reduzir o tamanho de uma imagem em uma apresentação definindo uma resolução alvo e removendo áreas recortadas:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Obtém o PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compacta a imagem com resolução alvo de 150 DPI (resolução Web) e remove áreas recortadas
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Resolução Web
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define o deslocamento horizontal da textura para 20 pontos
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define o deslocamento horizontal da textura para 20 pontos
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define o deslocamento vertical da textura para -50 pontos
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define o deslocamento vertical da textura para -50 pontos
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define a escala horizontal da textura para 120 percentuais
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define a escala horizontal da textura para 120 percentuais
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define a escala vertical da textura para 120 percentuais
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define a escala vertical da textura para 120 percentuais
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define o alinhamento das ladrilhos para a parte inferior direita
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

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Define o alinhamento das ladrilhos para a parte inferior direita
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Inverte o ladrilho de textura em torno do seu eixo vertical.
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
>      // Obtém o formato de preenchimento de imagem da forma
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Define o modo de preenchimento da imagem para Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Inverte o ladrinho de textura em torno do seu eixo vertical.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

O padrão é [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |