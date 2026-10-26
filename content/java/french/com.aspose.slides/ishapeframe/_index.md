---
title: IShapeFrame
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés des cadres de forme.
type: docs
url: /fr/com.aspose.slides/ishapeframe/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Représente les propriétés du cadre de forme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getX()](#getX--) | Renvoie la coordonnée X du coin supérieur gauche d'un cadre. |
| [getY()](#getY--) | Renvoie la coordonnée Y du coin supérieur gauche d'un cadre. |
| [getWidth()](#getWidth--) | Renvoie la largeur d'un cadre. |
| [getHeight()](#getHeight--) | Renvoie la hauteur d'un cadre. |
| [getRotation()](#getRotation--) | Renvoie le nombre de degrés d'une rotation du cadre autour de l'axe z. |
| [getCenterX()](#getCenterX--) | Renvoie la coordonnée X du centre d'un cadre. |
| [getCenterY()](#getCenterY--) | Renvoie la coordonnée Y du centre d'un cadre. |
| [getFlipH()](#getFlipH--) | Détermine si un cadre est retourné horizontalement. |
| [getFlipV()](#getFlipV--) | Détermine si un cadre est retourné verticalement. |
| [getRectangle()](#getRectangle--) | Renvoie les coordonnées d'un cadre. |
### getX() {#getX--}
```
public abstract float getX()
```


Renvoie la coordonnée X du coin supérieur gauche d'un cadre. float en lecture seule.

**Renvoie :**
float
### getY() {#getY--}
```
public abstract float getY()
```


Renvoie la coordonnée Y du coin supérieur gauche d'un cadre. float en lecture seule.

**Renvoie :**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Renvoie la largeur d'un cadre. float en lecture seule.

**Renvoie :**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Renvoie la hauteur d'un cadre. float en lecture seule.

**Renvoie :**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Renvoie le nombre de degrés d'une rotation du cadre autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse. float en lecture seule.

**Renvoie :**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


Renvoie la coordonnée X du centre d'un cadre. float en lecture seule.

**Renvoie :**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


Renvoie la coordonnée Y du centre d'un cadre. float en lecture seule.

**Renvoie :**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


Détermine si un cadre est retourné horizontalement. [NullableBool](../../com.aspose.slides/nullablebool) en lecture seule.

**Renvoie :**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


Détermine si un cadre est retourné verticalement. [NullableBool](../../com.aspose.slides/nullablebool) en lecture seule.

**Renvoie :**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```


Renvoie les coordonnées d'un cadre. java.awt.geom.Rectangle2D.Float en lecture seule.

**Renvoie :**
java.awt.geom.Rectangle2D.Float