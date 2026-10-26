---
title: PictureFrame
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa um quadro com uma imagem dentro.
type: docs
url: /pt/com.aspose.slides/pictureframe/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Representa um quadro com uma imagem dentro.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Adiciona um quadro de áudio ao slide com posição e tamanho especificados.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Adiciona uma imagem aos recursos da apresentação.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Define a imagem para o quadro de áudio.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Salva a apresentação modificada no disco
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Retorna os bloqueios da forma. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Retorna o objeto PictureFillFormat para um quadro de imagem. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. |
| [isCameo()](#isCameo--) | Determina se o PictureFrame é um objeto Cameo ou não. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

Retorna os bloqueios da forma. Somente leitura [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Retorna:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Retorna ou define o tipo AutoShape para um PictureFrame. São permitidos todos os itens do conjunto [ShapeType](../../com.aspose.slides/shapetype), exceto todos os tipos de linhas:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Leitura/gravação [ShapeType](../../com.aspose.slides/shapetype).

**Retorna:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Retorna ou define o tipo AutoShape para um PictureFrame. São permitidos todos os itens do conjunto [ShapeType](../../com.aspose.slides/shapetype), exceto todos os tipos de linhas:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Leitura/gravação [ShapeType](../../com.aspose.slides/shapetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

Retorna o objeto PictureFillFormat para um quadro de imagem. Somente leitura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retorna:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/gravação  float .

**Retorna:**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

Retorna ou define a escala de altura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/gravação  float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/gravação  float .

**Retorna:**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

Retorna ou define a escala de largura (relativa ao tamanho original da imagem) do quadro de imagem. Valor 1.0 corresponde a 100%. Leitura/gravação  float .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

Determina se o PictureFrame é um objeto Cameo ou não. Somente leitura boolean.

**Retorna:**
boolean