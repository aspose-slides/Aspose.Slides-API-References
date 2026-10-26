---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
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
| [getSize()](#getSize--) | Gets the slide dimensions in points. |
| [getType()](#getType--) | Gets the slide size type. |
| [getOrientation()](#getOrientation--) | Gets or sets the slide orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the slide orientation. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Sets the slide size by type and scales existing content. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Sets the slide dimensions explicitly and scales existing content. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


Obtient les dimensions de la diapositive en points.

--------------------

Attribuer une nouvelle valeur réinitialise la propriété \#getType.getType à [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) et définit la \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Retourne:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```


Obtient le type de taille de la diapositive.

--------------------

Attribuer n'importe quelle valeur autre que [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajuste le \#getSize.getSize selon les dimensions prédéfinies, tout en conservant le \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) actuel.

**Retourne:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Obtient ou définit l'orientation de la diapositive.

--------------------

Modifier cette valeur échange la largeur et la hauteur de la diapositive.

**Retourne:**
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
| type | int | La taille de diapositive prédéfinie à appliquer. |
| scaleType | int | Le mode de mise à l'échelle du contenu à utiliser.

--------------------

Attribuer n'importe quelle valeur autre que [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajuste le \#getSize.getSize en fonction du type sélectionné, tout en préservant le \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |
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

Cela réinitialise la propriété \#getType.getType à [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) et définit le \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |