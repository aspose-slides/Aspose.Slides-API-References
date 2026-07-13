---
title: PictureFrame
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een frame met een afbeelding voor.
type: docs
url: /nl/com.aspose.slides/pictureframe/
---
**Erfenis:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alle geïmplementeerde interfaces:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)  
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Stelt een frame met een afbeelding voor.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Voegt een audioframe toe aan de dia met een opgegeven positie en grootte.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Voegt een afbeelding toe aan de presentatiemiddelen.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Stelt de afbeelding in voor het audioframe.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Slaat de gewijzigde presentatie op schijf
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Retourneert de vergrendelingen van de vorm. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Retourneert het PictureFillFormat-object voor een picture-frame. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Retourneert of stelt de schaal van de hoogte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Retourneert of stelt de schaal van de hoogte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Retourneert of stelt de schaal van de breedte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Retourneert of stelt de schaal van de breedte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. |
| [isCameo()](#isCameo--) | Bepaalt of het PictureFrame een Cameo-object is of niet. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


Retourneert de vergrendelingen van de vorm. Alleen-lezen [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Retour:**  
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Retourneert of stelt het AutoShape-type in voor een PictureFrame. Er zijn toegestane alle items van de set [ShapeType](../../com.aspose.slides/shapetype), behalve alle soorten lijnen:

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

Lezen/Schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Retour:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Retourneert of stelt het AutoShape-type in voor een PictureFrame. Er zijn toegestane alle items van de set [ShapeType](../../com.aspose.slides/shapetype), behalve alle soorten lijnen:

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

Lezen/Schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


Retourneert het PictureFillFormat-object voor een picture-frame. Alleen-lezen [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Retour:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


Retourneert of stelt de schaal van de hoogte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. Waarde 1.0 komt overeen met 100 %. Lezen/Schrijven float .

**Retour:**  
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


Retourneert of stelt de schaal van de hoogte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. Waarde 1.0 komt overeen met 100 %. Lezen/Schrijven float .

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


Retourneert of stelt de schaal van de breedte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. Waarde 1.0 komt overeen met 100 %. Lezen/Schrijven float .

**Retour:**  
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


Retourneert of stelt de schaal van de breedte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. Waarde 1.0 komt overeen met 100 %. Lezen/Schrijven float .

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


Bepaalt of het PictureFrame een Cameo-object is of niet. Alleen-lezen boolean.

**Retour:**  
boolean