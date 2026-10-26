---
title: SlideSize
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente la taille et l'orientation d'une diapositive.
type: docs
url: /fr/com.aspose.slides/slidesize/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
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
public final SizeF getSize()
```

Obtient les dimensions de la diapositive en points.

--------------------

Attribuer une nouvelle valeur réinitialise la propriété \#getType.getType à [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) et définit la \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Renvoie :**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```

Obtient le type de taille de la diapositive.

--------------------

Attribuer toute valeur autre que [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajuste \#getSize.getSize selon les dimensions prédéfinies, tout en conservant la \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) actuelle.

**Renvoie :**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

Obtient ou définit l'orientation de la diapositive.

--------------------

Modifier cette valeur échange la largeur et la hauteur de la diapositive.

**Renvoie :**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

Obtient ou définit l'orientation de la diapositive.

--------------------

Modifier cette valeur échange la largeur et la hauteur de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

Définit la taille de la diapositive par type et met à l'échelle le contenu existant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | La taille de diapositive prédéfinie à appliquer. |
| scaleType | int | Le mode de mise à l'échelle du contenu à utiliser.

--------------------

Attribuer toute valeur autre que [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ajuste \#getSize.getSize en fonction du type sélectionné, tout en préservant \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Définit explicitement les dimensions de la diapositive et met à l'échelle le contenu existant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | float | La nouvelle largeur de la diapositive, en points. |
| height | float | La nouvelle hauteur de la diapositive, en points. |
| scaleType | int | Le mode de mise à l'échelle du contenu à utiliser.

--------------------

Cela réinitialise la propriété \#getType.getType à [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) et définit la \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |