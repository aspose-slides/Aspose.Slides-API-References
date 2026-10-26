---
title: GeometryShape
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt die Elternklasse für alle geometrischen Formen dar.
type: docs
url: /de/com.aspose.slides/geometryshape/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Stellt die Elternklasse für alle geometrischen Formen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Gibt eine Kopie des Pfads der geometrischen Form zurück. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Aktualisiert die Geometrie der Form aus dem [IGeometryPath](../../com.aspose.slides/igeometrypath)-Objekt. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Aktualisiert die Geometrie der Form aus einem Array von [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Gibt das Style-Objekt der Form zurück. |
| [getShapeType()](#getShapeType--) | Gibt den voreingestellten Geometrietyp zurück oder setzt ihn. |
| [setShapeType(int value)](#setShapeType-int-) | Gibt den voreingestellten Geometrietyp zurück oder setzt ihn. |
| [getAdjustments()](#getAdjustments--) | Gibt eine Sammlung von Anpassungswerten der Form zurück. |
| [createShapeElements()](#createShapeElements--) | Erstellt und gibt ein Array von Shape-Elementen zurück. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

Gibt eine Kopie des Pfads der geometrischen Form zurück. Die Koordinaten sind relativ zur linken oberen Ecke der Form.

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


**Rückgabe:**
com.aspose.slides.IGeometryPath[] - Array von [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

Aktualisiert die Geometrie der Form aus dem [IGeometryPath](../../com.aspose.slides/igeometrypath)-Objekt. Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) zu [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometriepfad |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Aktualisiert die Geometrie der Form aus einem Array von [IGeometryPath](../../com.aspose.slides/igeometrypath). Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) zu [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array von Geometriepfaden |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

Gibt das Style-Objekt der Form zurück. Nur lesbar [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Rückgabe:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Gibt den voreingestellten Geometrietyp zurück oder setzt ihn. Hinweis: Beim Ändern des Werts werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lesen/Schreiben [ShapeType](../../com.aspose.slides/shapetype).

**Rückgabe:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Gibt den voreingestellten Geometrietyp zurück oder setzt ihn. Hinweis: Beim Ändern des Werts werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lesen/Schreiben [ShapeType](../../com.aspose.slides/shapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur lesbar [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Rückgabe:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

Erstellt und gibt ein Array von Shape-Elementen zurück.

**Rückgabe:**
com.aspose.slides.IShapeElement[] - Array von [ShapeElement](../../com.aspose.slides/shapeelement)