---
title: IPictureFillFormat
second_title: Referência da API Aspose.Slides para Java
description: Representa um estilo de preenchimento de imagem.
type: docs
url: /pt/com.aspose.slides/ipicturefillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Representa um estilo de preenchimento de imagem.
## Métodos

| Método | Descrição |
| --- | --- |
| [getDpi()](#getDpi--) | Retorna ou define o dpi que é usado para preencher uma imagem. |
| [setDpi(int value)](#setDpi-int-) | Retorna ou define o dpi que é usado para preencher uma imagem. |
| [getPictureFillMode()](#getPictureFillMode--) | Retorna ou define o modo de preenchimento da imagem. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Retorna ou define o modo de preenchimento da imagem. |
| [getPicture()](#getPicture--) | Retorna a imagem. |
| [getCropLeft()](#getCropLeft--) | Retorna ou define o número de porcentagens da largura real da imagem que são recortadas à esquerda da imagem. |
| [setCropLeft(float value)](#setCropLeft-float-) | Retorna ou define o número de porcentagens da largura real da imagem que são recortadas à esquerda da imagem. |
| [getCropTop()](#getCropTop--) | Retorna ou define o número de porcentagens da altura real da imagem que são recortadas no topo da imagem. |
| [setCropTop(float value)](#setCropTop-float-) | Retorna ou define o número de porcentagens da altura real da imagem que são recortadas no topo da imagem. |
| [getCropRight()](#getCropRight--) | Retorna ou define o número de porcentagens da largura real da imagem que são recortadas à direita da imagem. |
| [setCropRight(float value)](#setCropRight-float-) | Retorna ou define o número de porcentagens da largura real da imagem que são recortadas à direita da imagem. |
| [getCropBottom()](#getCropBottom--) | Retorna ou define o número de porcentagens da altura real da imagem que são recortadas na parte inferior da imagem. |
| [setCropBottom(float value)](#setCropBottom-float-) | Retorna ou define o número de porcentagens da altura real da imagem que são recortadas na parte inferior da imagem. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Retorna ou define a borda esquerda do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Retorna ou define a borda esquerda do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Retorna ou define a borda superior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Retorna ou define a borda superior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Retorna ou define a borda direita do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Retorna ou define a borda direita do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Retorna ou define a borda inferior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Retorna ou define a borda inferior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Excluir áreas recortadas da imagem de preenchimento. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. |
| [getTileOffsetX()](#getTileOffsetX--) | Retorna ou define o deslocamento horizontal da textura a partir da origem da forma em pontos. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Retorna ou define o deslocamento horizontal da textura a partir da origem da forma em pontos. |
| [getTileOffsetY()](#getTileOffsetY--) | Retorna ou define o deslocamento vertical da textura a partir da origem da forma em pontos. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Retorna ou define o deslocamento vertical da textura a partir da origem da forma em pontos. |
| [getTileScaleX()](#getTileScaleX--) | Retorna ou define a escala horizontal para o preenchimento da textura como uma porcentagem. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Retorna ou define a escala horizontal para o preenchimento da textura como uma porcentagem. |
| [getTileScaleY()](#getTileScaleY--) | Retorna ou define a escala vertical para o preenchimento da textura como uma porcentagem. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Retorna ou define a escala vertical para o preenchimento da textura como uma porcentagem. |
| [getTileAlignment()](#getTileAlignment--) | Retorna ou define como a textura está alinhada dentro da forma. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Retorna ou define como a textura está alinhada dentro da forma. |
| [getTileFlip()](#getTileFlip--) | Inverte o bloco de textura em torno de seu eixo horizontal, vertical ou ambos. |
| [setTileFlip(int value)](#setTileFlip-int-) | Inverte o bloco de textura em torno de seu eixo horizontal, vertical ou ambos. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Retorna ou define o dpi que é usado para preencher uma imagem. Leitura/gravação int.

**Retorna:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Retorna ou define o dpi que é usado para preencher uma imagem. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Retorna ou define o modo de preenchimento da imagem. Leitura/gravação [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Retorna:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Retorna ou define o modo de preenchimento da imagem. Leitura/gravação [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Retorna a imagem. Somente leitura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Retorna:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Retorna ou define o número de porcentagens da largura real da imagem que são recortadas à esquerda da imagem. Leitura/gravação float.

**Retorna:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Retorna ou define o número de porcentagens da largura real da imagem que são recortadas à esquerda da imagem. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Retorna ou define o número de porcentagens da altura real da imagem que são recortadas no topo da imagem. Leitura/gravação float.

**Retorna:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Retorna ou define o número de porcentagens da altura real da imagem que são recortadas no topo da imagem. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Retorna ou define o número de porcentagens da largura real da imagem que são recortadas à direita da imagem. Leitura/gravação float.

**Retorna:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Retorna ou define o número de porcentagens da largura real da imagem que são recortadas à direita da imagem. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Retorna ou define o número de porcentagens da altura real da imagem que são recortadas na parte inferior da imagem. Leitura/gravação float.

**Retorna:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Retorna ou define o número de porcentagens da altura real da imagem que são recortadas na parte inferior da imagem. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Retorna ou define a borda esquerda do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalente. Leitura/gravação float.

**Retorna:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Retorna ou define a borda esquerda do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalente. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Retorna ou define a borda superior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalente. Leitura/gravação float.

**Retorna:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Retorna ou define a borda superior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalente. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Retorna ou define a borda direita do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalente. Leitura/gravação float.

**Retorna:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Retorna ou define a borda direita do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalente. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Retorna ou define a borda inferior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalente. Leitura/gravação float.

**Retorna:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Retorna ou define a borda inferior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalente. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Excluir áreas recortadas da imagem de preenchimento.

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

Este método converte arquivos metafile WMF/EMF em imagem PNG raster enquanto recorta.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
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
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Se true, o método removerá as áreas recortadas da imagem, potencialmente reduzindo ainda mais seu tamanho. |
| resolution | int | A resolução alvo para compressão, especificada como um valor da enumeração [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

Este método altera o tamanho e a resolução da imagem de forma semelhante ao recurso "Picture Format -> Compress Pictures" do PowerPoint. |

**Retorna:**
boolean - Um boolean indicando se a imagem foi comprimida com sucesso. Retorna true se a imagem foi redimensionada ou recortada, caso contrário false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> O exemplo a seguir demonstra como usar o ```
> CompressImage
> ```
 método para reduzir o tamanho de uma imagem em uma apresentação definindo uma resolução alvo e removendo áreas recortadas:
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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
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
### setTileScaleX(float value) {#setTileOffsetX-float-}
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
**Parâmetros:**
| Parâmetro | Tipo | Descrição |
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
O padrão é [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Retorna:**
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

O padrão é [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |