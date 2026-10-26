---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Représente la taille et l'orientation d'une diapositive.
type: docs
url: /fr/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Représente la taille et l'orientation d'une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSize()](#getSize--) | Obtient les dimensions de la diapositive en points. |
| [getType()](#getType--) | Obtient le type de taille de la diapositive. |
| [getOrientation()](#getOrientation--) | Obtient ou définit l'orientation de la diapositive. |
| [setOrientation(int value)](#setOrientation-int-) | Obtient ou définit l'orientation de la diapositive. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Définit la taille de la diapositive par type et met à l'échelle le contenu existant. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Définit explicitement les dimensions de la diapositive et met à l'échelle le contenu existant. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Obtient les dimensions de la diapositive en points.

--------------------

Attribuer une nouvelle valeur réinitialise la #getType.getType propriété à [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) et définit la #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

**Renvoie:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


Obtient le type de taille de la diapositive.

--------------------

Attribuer une valeur autre que [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajuste le #getSize.getSize selon les dimensions prédéfinies, tout en conservant la #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) actuelle.

**Renvoie:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Obtient ou définit l'orientation de la diapositive.

--------------------

Modifier cette valeur échange la largeur et la hauteur de la diapositive.

**Renvoie:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Obtient ou définit l'orientation de la diapositive.

--------------------

Modifier cette valeur échange la largeur et la hauteur de la diapositive.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Définit la taille de la diapositive par type et met à l'échelle le contenu existant.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type de taille de diapositive prédéfini à appliquer. |
| scaleType | int | Le mode de mise à l'échelle du contenu à utiliser.

--------------------

Attribuer une valeur autre que [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajuste le #getSize.getSize en fonction du type sélectionné, tout en préservant la #getOrientation.getOrientation/#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Définit explicitement les dimensions de la diapositive et met à l'échelle le contenu existant.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | float | La nouvelle largeur de la diapositive, en points. |
| height | float | La nouvelle hauteur de la diapositive, en points. |
| scaleType | int | Le mode de mise à l'échelle du contenu à utiliser.

--------------------

Cela réinitialise la #getType.getType propriété à [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) et définit la #{#getOrientation.getOrientation/#setOrientation(int).setOrientation(int). |