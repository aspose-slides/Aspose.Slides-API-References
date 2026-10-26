---
title: PictureFrame
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa un marco con una imagen dentro.
type: docs
url: /es/com.aspose.slides/pictureframe/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Todas las interfaces implementadas:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Representa un marco con una imagen dentro.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Añade un marco de audio a la diapositiva con una posición y tamaño especificados.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Añade una imagen a los recursos de la presentación.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Establece la imagen para el marco de audio.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Guarda la presentación modificada en disco
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Devuelve los bloqueos de shape. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Devuelve el objeto PictureFillFormat para un marco de imagen. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. |
| [isCameo()](#isCameo--) | Determina si el PictureFrame es un objeto Cameo o no. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


Devuelve los bloqueos de shape. Solo lectura [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Devuelve:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Devuelve o establece el tipo AutoShape para un PictureFrame. Son permitidos todos los elementos del conjunto [ShapeType](../../com.aspose.slides/shapetype), excepto todo tipo de líneas:

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

Lectura/escritura [ShapeType](../../com.aspose.slides/shapetype).

**Devuelve:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Devuelve o establece el tipo AutoShape para un PictureFrame. Son permitidos todos los elementos del conjunto [ShapeType](../../com.aspose.slides/shapetype), excepto todo tipo de líneas:

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

Lectura/escritura [ShapeType](../../com.aspose.slides/shapetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


Devuelve el objeto PictureFillFormat para un marco de imagen. Solo lectura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Devuelve:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Lectura/escritura  float .

**Devuelve:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Lectura/escritura  float .

**Devuelve:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Lectura/escritura  float .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


Determina si el PictureFrame es un objeto Cameo o no. Solo lectura boolean.

**Devuelve:**
boolean