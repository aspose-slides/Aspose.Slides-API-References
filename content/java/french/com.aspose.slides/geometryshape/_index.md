---
title: GeometryShape
second_title: Référence API Aspose.Slides pour Java
description: Représente la classe parent de toutes les formes géométriques.
type: docs
url: /fr/com.aspose.slides/geometryshape/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Représente la classe parent de toutes les formes géométriques.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Retourne une copie du chemin de la forme géométrique. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Met à jour la géométrie de la forme à partir de l'objet [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Met à jour la géométrie de la forme à partir d'un tableau de [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Retourne l'objet style de la forme. |
| [getShapeType()](#getShapeType--) | Retourne ou définit le type de préréglage géométrique. |
| [setShapeType(int value)](#setShapeType-int-) | Retourne ou définit le type de préréglage géométrique. |
| [getAdjustments()](#getAdjustments--) | Retourne une collection des valeurs d'ajustement de la forme. |
| [createShapeElements()](#createShapeElements--) | Crée et retourne un tableau des éléments de la forme. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```


Retourne une copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
com.aspose.slides.IGeometryPath[] - Tableau de [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```


Met à jour la géométrie de la forme à partir de l'objet [IGeometryPath](../../com.aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) en [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      GeometryPath geometryPath0 = new GeometryPath();
>      geometryPath0.moveTo(0, 0);
>      geometryPath0.lineTo(shape.getWidth(), 0);
>      geometryPath0.lineTo(shape.getWidth(), shape.getHeight()/3);
>      geometryPath0.lineTo(0, shape.getHeight() / 3);
>      geometryPath0.closeFigure();
>      GeometryPath geometryPath1 = new GeometryPath();
>      geometryPath1.moveTo(0, shape.getHeight()/3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight() / 3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight());
>      geometryPath1.lineTo(0, shape.getHeight());
>      geometryPath1.closeFigure();
>      shape.setGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Chemin géométrique |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```


Met à jour la géométrie de la forme à partir d'un tableau de [IGeometryPath](../../com.aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) en [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape)pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Tableau de chemins géométriques |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```


Retourne l'objet style de la forme. Lecture seule [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Retourne :**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Retourne ou définit le type de préréglage géométrique. Remarque : lors du changement de valeur, toutes les valeurs d'ajustement seront réinitialisées à leurs valeurs par défaut. Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Retourne :**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Retourne ou définit le type de préréglage géométrique. Remarque : lors du changement de valeur, toutes les valeurs d'ajustement seront réinitialisées à leurs valeurs par défaut. Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```


Retourne une collection des valeurs d'ajustement de la forme. Lecture seule [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Retourne :**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```


Crée et retourne un tableau des éléments de la forme.

**Retourne :**
com.aspose.slides.IShapeElement[] - Tableau de [ShapeElement](../../com.aspose.slides/shapeelement)