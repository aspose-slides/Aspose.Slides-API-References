---
title: GeometryPath
second_title: Référence API Aspose.Slides for Java
description: Représente le chemin géométrique de GeometryShape
type: docs
url: /fr/com.aspose.slides/geometrypath/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Représente le chemin géométrique de GeometryShape
## Constructeurs

| Constructor | Description |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Crée une instance de GeometryPath |
## Méthodes

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | Renvoie le chemin géométrique de GeometryShape sous forme d'un tableau de segments de chemin. |
| [removeAt(int index)](#removeAt-int-) | Supprime le segment à l'index spécifié du chemin géométrique. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Ajoute une ligne à la fin du chemin |
| [lineTo(float x, float y)](#lineTo-float-float-) | Ajoute une ligne à la fin du chemin |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Ajoute une ligne à l'emplacement spécifié du chemin |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Ajoute une ligne à l'emplacement spécifié du chemin |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Ajoute une courbe de Bézier cubique à la fin du chemin |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Ajoute une courbe de Bézier cubique à la fin du chemin |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Ajoute une courbe de Bézier quadratique à la fin du chemin |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Ajoute une courbe de Bézier quadratique à la fin du chemin |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin |
| [closeFigure()](#closeFigure--) | Ferme la figure actuelle de ce chemin |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Définit la position du point suivant. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Définit la position du point suivant. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Ajoute l'arc spécifié au chemin. |
| [getFillMode()](#getFillMode--) | Définit le mode de remplissage |
| [setFillMode(byte value)](#setFillMode-byte-) | Définit le mode de remplissage |
| [getStroke()](#getStroke--) | Définit l'apparence du trait |
| [setStroke(boolean value)](#setStroke-boolean-) | Définit l'apparence du trait |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Crée une instance de GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Renvoie le chemin géométrique de GeometryShape sous forme d'un tableau de segments de chemin.

**Renvoie :**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime le segment à l'index spécifié du chemin géométrique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du chemin géométrique qui doit être supprimé. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

Ajoute une ligne à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Point final de la ligne |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Ajoute une ligne à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point final de la ligne |
| y | float | Coordonnée Y du point final de la ligne |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

Ajoute une ligne à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Point final |
| index | long | Indice du segment dans PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Ajoute une ligne à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point |
| y | float | Coordonnée Y du point |
| index | long | Indice du segment dans PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Ajoute une courbe de Bézier cubique à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Premier point de direction |
| point2 | java.awt.geom.Point2D.Float | Deuxième point de direction |
| point3 | java.awt.geom.Point2D.Float | Point final |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Ajoute une courbe de Bézier cubique à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du premier point de direction |
| y1 | float | Coordonnée Y du premier point de direction |
| x2 | float | Coordonnée X du deuxième point de direction |
| y2 | float | Coordonnée Y du deuxième point de direction |
| x3 | float | Coordonnée X du point final |
| y3 | float | Coordonnée Y du point final |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Premier point de direction |
| point2 | java.awt.geom.Point2D.Float | Deuxième point de direction |
| point3 | java.awt.geom.Point2D.Float | Point final |
| index | long | Indice du segment dans PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du premier point de direction |
| y1 | float | Coordonnée Y du premier point de direction |
| x2 | float | Coordonnée X du deuxième point de direction |
| y2 | float | Coordonnée Y du deuxième point de direction |
| x3 | float | Coordonnée X du point final |
| y3 | float | Coordonnée Y du point final |
| index | long | Indice du segment dans PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Ajoute une courbe de Bézier quadratique à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Point de direction |
| point2 | java.awt.geom.Point2D.Float | Point final |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Ajoute une courbe de Bézier quadratique à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du point de direction |
| y1 | float | Coordonnée Y du point de direction |
| x2 | float | Coordonnée X du point final |
| y2 | float | Coordonnée Y du point final |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Point de direction |
| point2 | java.awt.geom.Point2D.Float | Point final |
| index | long | Indice du segment dans PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du point de direction |
| y1 | float | Coordonnée Y du point de direction |
| x2 | float | Coordonnée X du point final |
| y2 | float | Coordonnée Y du point final |
| index | long | Indice du segment dans PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Ferme la figure actuelle de ce chemin

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

Définit la position du point suivant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Position du point |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Définit la position du point suivant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point |
| y | float | Coordonnée Y du point |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Ajoute l'arc spécifié au chemin.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | float | Largeur du rectangle |
| heigth | float | Hauteur du rectangle |
| startAngle | float | Angle de départ. |
| sweepAngle | float | Angle de balayage/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Définit le mode de remplissage

**Renvoie :**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Définit le mode de remplissage

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Définit l'apparence du trait

**Renvoie :**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Définit l'apparence du trait

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |