---
title: IGeometryShape
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente la classe parent de toutes les formes géométriques.
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
| [getGeometryPaths()](#getGeometryPaths--) | Retourne une copie du chemin de la forme géométrique. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Met à jour la géométrie de la forme à partir de l'objet [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Met à jour la géométrie de la forme à partir d'un tableau de [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Retourne l'objet style de la forme. |
| [getShapeType()](#getShapeType--) | Retourne ou définit le type prédéfini de géométrie. |
| [setShapeType(int value)](#setShapeType-int-) | Retourne ou définit le type prédéfini de géométrie. |
| [getAdjustments()](#getAdjustments--) | Retourne une collection des valeurs d'ajustement de la forme. |
| [createShapeElements()](#createShapeElements--) | Crée et retourne un tableau des éléments de la forme. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
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

**Returns:**
com.aspose.slides.IGeometryPath[] - Array of [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

Updates shape geometry from [IGeometryPath](../../com.aspose.slides/igeometrypath) object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) to [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometry path |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Updates shape geometry from array of [IGeometryPath](../../com.aspose.slides/igeometrypath). Coordinates must be relative to the left top corner of the shape. Changes the type of the shape (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) to [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array geometry paths |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

Returns shape's style object. Read-only [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Returns:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

Returns a collection of shape's adjustment values. Read-only [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Returns:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()


Crée et retourne un tableau des éléments de la forme.

**Retourne :**
com.aspose.slides.IShapeElement[] - Tableau de [IShapeElement](../../com.aspose.slides/ishapeelement)