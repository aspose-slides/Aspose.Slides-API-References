---
title: IGeometryShape
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente la classe parente de toutes les formes géométriques.
type: docs
url: /fr/com.aspose.slides/igeometryshape/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Représente la classe parente de toutes les formes géométriques.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Renvoie une copie du chemin de la forme géométrique. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Met à jour la géométrie de la forme à partir de l'objet [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Met à jour la géométrie de la forme à partir d'un tableau de [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Renvoie l'objet de style de la forme. |
| [getShapeType()](#getShapeType--) | Renvoie ou définit le type de préréglage de la géométrie. |
| [setShapeType(int value)](#setShapeType-int-) | Renvoie ou définit le type de préréglage de la géométrie. |
| [getAdjustments()](#getAdjustments--) | Renvoie une collection des valeurs d'ajustement de la forme. |
| [createShapeElements()](#createShapeElements--) | Crée et renvoie un tableau des éléments de la forme. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

Renvoie une copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme.

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

**Retour :**
com.aspose.slides.IGeometryPath[] - Tableau de [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

Met à jour la géométrie de la forme à partir de l'objet [IGeometryPath](../../com.aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Modifie le type de la forme (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) en [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Chemin de géométrie |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Met à jour la géométrie de la forme à partir d'un tableau de [IGeometryPath](../../com.aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Modifie le type de la forme (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) en [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Tableau des chemins de géométrie |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

Renvoie l'objet de style de la forme. Lecture seule [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Retour :**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

Renvoie ou définit le type de préréglage de la géométrie. Remarque : lors de la modification de la valeur, toutes les valeurs d'ajustement sont réinitialisées à leurs valeurs par défaut. Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Retour :**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

Renvoie ou définit le type de préréglage de la géométrie. Remarque : lors de la modification de la valeur, toutes les valeurs d'ajustement sont réinitialisées à leurs valeurs par défaut. Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

Renvoie une collection des valeurs d'ajustement de la forme. Lecture seule [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Retour :**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

Crée et renvoie un tableau des éléments de la forme.

**Retour :**
com.aspose.slides.IShapeElement[] - Tableau de [IShapeElement](../../com.aspose.slides/ishapeelement)