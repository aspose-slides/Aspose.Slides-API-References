---
title: IGeometryPath
second_title: Aspose.Slides pour Android via Java API Reference
description: Représente le chemin géométrique de GeometryShape
type: docs
url: /fr/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Représente le chemin géométrique de GeometryShape
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPathData()](#getPathData--) | Renvoie le chemin géométrique de GeometryShape sous forme d'un tableau de segments de chemin. |
| [removeAt(int index)](#removeAt-int-) | Supprime le segment à l'index spécifié du chemin géométrique. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Ajoute une ligne à la fin du chemin |
| [lineTo(float x, float y)](#lineTo-float-float-) | Ajoute une ligne à la fin du chemin |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Ajoute une ligne à l'emplacement spécifié du chemin |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Ajoute une ligne à l'emplacement spécifié du chemin |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Ajoute une courbe cubique de Bézier à la fin du chemin |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Ajoute une courbe cubique de Bézier à la fin du chemin |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Ajoute une courbe cubique de Bézier à l'emplacement spécifié du chemin |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Ajoute une courbe cubique de Bézier à l'emplacement spécifié du chemin |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Ajoute une courbe quadratique de Bézier à la fin du chemin |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Ajoute une courbe quadratique de Bézier à la fin du chemin |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Ajoute une courbe quadratique de Bézier à l'emplacement spécifié du chemin |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Ajoute une courbe quadratique de Bézier à l'emplacement spécifié du chemin |
| [closeFigure()](#closeFigure--) | Ferme la figure actuelle de ce chemin |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Définit la position du point suivant. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Définit la position du point suivant. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Ajoute l'arc spécifié au chemin. |
| [getFillMode()](#getFillMode--) | Définit le mode de remplissage |
| [setFillMode(byte value)](#setFillMode-byte-) | Définit le mode de remplissage |
| [getStroke()](#getStroke--) | Définit l'apparence du trait |
| [setStroke(boolean value)](#setStroke-boolean-) | Définit l'apparence du trait |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


Renvoie le chemin géométrique de GeometryShape sous forme d'un tableau de segments de chemin.

**Renvoie :**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime le segment à l'index spécifié du chemin géométrique.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du segment du chemin qui doit être supprimé. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```


Ajoute une ligne à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | Point final de la ligne |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Ajoute une ligne à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point final de la ligne |
| y | float | Coordonnée Y du point final de la ligne |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```


Ajoute une ligne à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | Point final |
| index | long | Index du segment dans PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


Ajoute une ligne à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point |
| y | float | Coordonnée Y du point |
| index | long | Index du segment dans PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


Ajoute une courbe cubique de Bézier à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | Premier point de direction |
| point2 | android.graphics.PointF | Deuxième point de direction |
| point3 | android.graphics.PointF | Point final |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Ajoute une courbe cubique de Bézier à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du premier point de direction |
| y1 | float | Coordonnée Y du premier point de direction |
| x2 | float | Coordonnée X du deuxième point de direction |
| y2 | float | Coordonnée Y du deuxième point de direction |
| x3 | float | Coordonnée X du point final |
| y3 | float | Coordonnée Y du point final |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


Ajoute une courbe cubique de Bézier à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | Premier point de direction |
| point2 | android.graphics.PointF | Deuxième point de direction |
| point3 | android.graphics.PointF | Point final |
| index | long | Index du segment dans PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Ajoute une courbe cubique de Bézier à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du premier point de direction |
| y1 | float | Coordonnée Y du premier point de direction |
| x2 | float | Coordonnée X du deuxième point de direction |
| y2 | float | Coordonnée Y du deuxième point de direction |
| x3 | float | Coordonnée X du point final |
| y3 | float | Coordonnée Y du point final |
| index | long | Index du segment dans PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```


Ajoute une courbe quadratique de Bézier à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | Point de direction |
| point2 | android.graphics.PointF | Point final |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Ajoute une courbe quadratique de Bézier à la fin du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du point de direction |
| y1 | float | Coordonnée Y du point de direction |
| x2 | float | Coordonnée X du point final |
| y2 | float | Coordonnée Y du point final |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```


Ajoute une courbe quadratique de Bézier à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | Point de direction |
| point2 | android.graphics.PointF | Point final |
| index | long | Index du segment dans PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Ajoute une courbe quadratique de Bézier à l'emplacement spécifié du chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | float | Coordonnée X du point de direction |
| y1 | float | Coordonnée Y du point de direction |
| x2 | float | Coordonnée X du point final |
| y2 | float | Coordonnée Y du point final |
| index | long | Index du segment dans PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


Ferme la figure actuelle de ce chemin

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```


Définit la position du point suivant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | Position du point |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Définit la position du point suivant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | float | Coordonnée X du point |
| y | float | Coordonnée Y du point |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Ajoute l'arc spécifié au chemin.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | float | Largeur du rectangle |
| heigth | float | Hauteur du rectangle |
| startAngle | float | Angle de départ. |
| sweepAngle | float | Angle d'extension/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Définit le mode de remplissage

**Renvoie :**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Définit le mode de remplissage

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Définit l'apparence du trait

**Renvoie :**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Définit l'apparence du trait

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |