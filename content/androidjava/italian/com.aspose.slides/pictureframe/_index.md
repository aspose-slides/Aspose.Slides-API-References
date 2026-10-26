---
title: PictureFrame
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: "Rappresenta un fotogramma con un'immagine all'interno."
type: docs
url: /it/com.aspose.slides/pictureframe/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tutte le interfacce implementate:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Rappresenta un fotogramma con un'immagine all'interno.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Aggiunge un fotogramma audio alla diapositiva con una posizione e dimensione specificate.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Aggiunge un'immagine alle risorse della presentazione.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Imposta l'immagine per il fotogramma audio.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Salva la presentazione modificata su disco
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Restituisce i lock della forma. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Restituisce l'oggetto PictureFillFormat per un frame immagine. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Restituisce o imposta la scala dell'altezza (relativa alle dimensioni originali dell'immagine) del frame immagine. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Restituisce o imposta la scala dell'altezza (relativa alle dimensioni originali dell'immagine) del frame immagine. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Restituisce o imposta la scala della larghezza (relativa alle dimensioni originali dell'immagine) del frame immagine. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Restituisce o imposta la scala della larghezza (relativa alle dimensioni originali dell'immagine) del frame immagine. |
| [isCameo()](#isCameo--) | Determina se il PictureFrame è un oggetto Cameo o meno. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


Restituisce i lock della forma. Solo lettura [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Restituisce:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Restituisce o imposta il tipo AutoShape per un PictureFrame. Sono consentiti tutti gli elementi del set [ShapeType](../../com.aspose.slides/shapetype), eccetto tutti i tipi di linee:

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

Lettura/scrittura [ShapeType](../../com.aspose.slides/shapetype).

**Restituisce:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Restituisce o imposta il tipo AutoShape per un PictureFrame. Sono consentiti tutti gli elementi del set [ShapeType](../../com.aspose.slides/shapetype), eccetto tutti i tipi di linee:

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

Lettura/scrittura [ShapeType](../../com.aspose.slides/shapetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


Restituisce l'oggetto PictureFillFormat per un frame immagine. Solo lettura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Restituisce:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


Restituisce o imposta la scala dell'altezza (relativa alle dimensioni originali dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura  float .

**Restituisce:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


Restituisce o imposta la scala dell'altezza (relativa alle dimensioni originali dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


Restituisce o imposta la scala della larghezza (relativa alle dimensioni originali dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura  float .

**Restituisce:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


Restituisce o imposta la scala della larghezza (relativa alle dimensioni originali dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


Determina se il PictureFrame è un oggetto Cameo o meno. Solo lettura boolean.

**Restituisce:**
boolean