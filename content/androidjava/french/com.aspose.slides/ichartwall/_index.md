---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Représente les parois sur les graphiques 3D.
type: docs
url: /fr/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

Représente les parois sur les graphiques 3D.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getThickness()](#getThickness--) | Returns or sets the walls thickness as a percentage of the largest dimension of the plot volume. |
| [setThickness(int value)](#setThickness-int-) | Returns or sets the walls thickness as a percentage of the largest dimension of the plot volume. |
| [getFormat()](#getFormat--) | Returns the wall fill, line, effect, 3d styles. |
| [getPictureType()](#getPictureType--) | Return or sets the picture type. |
| [setPictureType(int value)](#setPictureType-int-) | Return or sets the picture type. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

Renvoie ou définit l'épaisseur des parois en pourcentage de la plus grande dimension du volume du tracé. Lecture/écriture int.

**Retour:**  
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

Renvoie ou définit l'épaisseur des parois en pourcentage de la plus grande dimension du volume du tracé. Lecture/écriture int.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Renvoie le remplissage, la ligne, l'effet et les styles 3D de la paroi. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Retour:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

Renvoie ou définit le type d'image. Lecture/écriture [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Retour:**  
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

Renvoie ou définit le type d'image. Lecture/écriture [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |