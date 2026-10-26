---
title: ShapeFrame
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente les propriétés des cadres de forme.
type: docs
url: /fr/com.aspose.slides/shapeframe/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Représente les propriétés du cadre de forme.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Crée de nouvelles propriétés du cadre de forme. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getX()](#getX--) | Renvoie la coordonnée X du coin supérieur gauche d'un cadre. |
| [getY()](#getY--) | Renvoie la coordonnée Y du coin supérieur gauche d'un cadre. |
| [getWidth()](#getWidth--) | Renvoie la largeur d'un cadre. |
| [getHeight()](#getHeight--) | Renvoie la hauteur d'un cadre. |
| [getRotation()](#getRotation--) | Renvoie le nombre de degrés de rotation d'un cadre autour de l'axe z. |
| [getCenterX()](#getCenterX--) | Renvoie la coordonnée X du centre d'un cadre. |
| [getCenterY()](#getCenterY--) | Renvoie la coordonnée Y du centre d'un cadre. |
| [getFlipH()](#getFlipH--) | Détermine si un cadre est retourné horizontalement. |
| [getFlipV()](#getFlipV--) | Détermine si un cadre est retourné verticalement. |
| [getRectangle()](#getRectangle--) | Renvoie les coordonnées d'un cadre. |
| [deepClone()](#deepClone--) | Clone |
| [cloneT()](#cloneT--) | Clone. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à un objet spécifié. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Renvoie une valeur indiquant si cette instance est égale à un objet spécifié. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Crée de nouvelles propriétés du cadre de forme.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X d'un cadre. |
| y | float | Coordonnée Y d'un cadre. |
| width | float | Largeur d'un cadre. |
| height | float | Hauteur d'un cadre. |
| flipH | byte | Vrai si le cadre est retourné horizontalement. |
| flipV | byte | Vrai si le cadre est retourné verticalement. |
| rotationAngle | float | Nombre de degrés de rotation du cadre. |
### getX() {#getX--}
```
public final float getX()
```

Renvoie la coordonnée X du coin supérieur gauche d'un cadre. Lecture seule float.

**Renvoie :**
float
### getY() {#getY--}
```
public final float getY()
```

Renvoie la coordonnée Y du coin supérieur gauche d'un cadre. Lecture seule float.

**Renvoie :**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Renvoie la largeur d'un cadre. Lecture seule float.

**Renvoie :**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Renvoie la hauteur d'un cadre. Lecture seule float.

**Renvoie :**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Renvoie le nombre de degrés de rotation d'un cadre autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture seule float.

**Renvoie :**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Renvoie la coordonnée X du centre d'un cadre. Lecture seule float.

**Renvoie :**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Renvoie la coordonnée Y du centre d'un cadre. Lecture seule float.

**Renvoie :**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Détermine si un cadre est retourné horizontalement. Lecture seule [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Détermine si un cadre est retourné verticalement. Lecture seule [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Renvoie les coordonnées d'un cadre. Lecture seule android.graphics.RectF.

**Renvoie :**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Clone

**Renvoie :**
java.lang.Object - Cadre de forme cloné.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Clone.

**Renvoie :**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Cadre de forme cloné.
### hashCode() {#hashCode--}
```
public int hashCode()
```

**Renvoie :**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Renvoie une valeur indiquant si cette instance est égale à un objet spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer avec cette instance. |

**Renvoie :**
boolean - **true** si obj est un ShapeFrame qui a la même valeur que cette instance ; sinon, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Renvoie une valeur indiquant si cette instance est égée à un objet spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Le ShapeFRameEx à comparer avec cette instance. |

**Renvoie :**
boolean - **true** si value est un ShapeFrame qui a la même valeur que cette instance ; sinon, **false**.