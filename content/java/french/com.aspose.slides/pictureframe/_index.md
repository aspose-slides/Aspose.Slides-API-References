---
title: PictureFrame
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un cadre contenant une image.
type: docs
url: /fr/com.aspose.slides/pictureframe/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Représente un cadre contenant une image.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Ajoute une trame audio à la diapositive avec une position et une taille spécifiées.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Ajoute une image aux ressources de la présentation.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Définit l'image pour la trame audio.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Enregistre la présentation modifiée sur le disque
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Renvoie les verrous de la forme. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Renvoie l'objet PictureFillFormat d'un cadre d'image. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Renvoie ou définit l'échelle de hauteur (relative à la taille originale de l'image) du cadre d'image. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Renvoie ou définit l'échelle de hauteur (relative à la taille originale de l'image) du cadre d'image. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Renvoie ou définit l'échelle de largeur (relative à la taille originale de l'image) du cadre d'image. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Renvoie ou définit l'échelle de largeur (relative à la taille originale de l'image) du cadre d'image. |
| [isCameo()](#isCameo--) | Détermine si le PictureFrame est un objet Cameo ou non. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


Renvoie les verrous de la forme. Lecture seule [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Renvoie:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Renvoie ou définit le type AutoShape pour un PictureFrame. Tous les éléments du jeu [ShapeType](../../com.aspose.slides/shapetype) sont autorisés, à l'exception de toutes les sortes de lignes :

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

Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Renvoie:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Renvoie ou définit le type AutoShape pour un PictureFrame. Tous les éléments du jeu [ShapeType](../../com.aspose.slides/shapetype) sont autorisés, à l'exception de toutes les sortes de lignes :

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

Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


Renvoie l'objet PictureFillFormat d'un cadre d'image. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Renvoie:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


Renvoie ou définit l'échelle de hauteur (relative à la taille originale de l'image) du cadre d'image. La valeur 1,0 correspond à 100 %. Lecture/écriture float .

**Renvoie:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


Renvoie ou définit l'échelle de hauteur (relative à la taille originale de l'image) du cadre d'image. La valeur 1,0 correspond à 100 %. Lecture/écriture float .

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


Renvoie ou définit l'échelle de largeur (relative à la taille originale de l'image) du cadre d'image. La valeur 1,0 correspond à 100 %. Lecture/écriture float .

**Renvoie:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


Renvoie ou définit l'échelle de largeur (relative à la taille originale de l'image) du cadre d'image. La valeur 1,0 correspond à 100 %. Lecture/écriture float .

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


Détermine si le PictureFrame est un objet Cameo ou non. Lecture seule booléen.

**Renvoie:**
boolean