---
title: ShapeElement
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une partie de la forme avec les mêmes propriétés de contour et de remplissage.
type: docs
url: /fr/com.aspose.slides/shapeelement/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Représente une partie de la forme avec les mêmes propriétés de contour et de remplissage.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParentShape()](#getParentShape--) | Renvoie un Shape_PPT pour lequel l'élément a été créé. |
| [getPathPoints()](#getPathPoints--) | Obtient un tableau de points qui définissent la géométrie du chemin de l'élément. |
| [getPathTypes()](#getPathTypes--) | Obtient un tableau de valeurs octet qui spécifient le type de chaque point du chemin de l'élément. |
| [getFillSource()](#getFillSource--) | Renvoie des informations sur la façon de remplir un élément. |
| [getStrokeSource()](#getStrokeSource--) | Renvoie des informations sur la façon de tracer un élément. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Renvoie un Shape_PPT pour lequel l'élément a été créé. Lecture seule [Shape](../../com.aspose.slides/shape).

**Renvoie :**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```


Obtient un tableau de points qui définissent la géométrie du chemin de l'élément.

**Renvoie :**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


Obtient un tableau de valeurs octet qui spécifient le type de chaque point du chemin de l'élément.

**0** Indique que le point est le début d'une figure.

**1** Indique que le point est l'une des deux extrémités d'une ligne.

**3** Indique que le point est une extrémité ou un point de contrôle d'une spline de Bézier cubique.

**7** Masque tous les bits sauf les trois bits de poids faible, qui indiquent le type de point.

**16** Spécifie que le segment correspondant est en pointillé.

**32** Spécifie que le point est un marqueur.

**128** Spécifie que le point est le dernier point d'un sous-chemin fermé (figure).

**129** Indique un point de données qui est à la fois l'extrémité d'un segment de ligne et le dernier point d'un sous-chemin fermé.

**Renvoie :**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


Renvoie des informations sur la façon de remplir un élément. Lecture seule [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Renvoie :**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


Renvoie des informations sur la façon de tracer un élément. Lecture seule [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Renvoie :**
byte