---
title: IGeometryShape
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt die übergeordnete Klasse für alle geometrischen Formen dar.
type: docs
url: /de/com.aspose.slides/igeometryshape/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Stellt die Basisklasse für alle geometrischen Formen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Gibt eine Kopie des Pfads der geometrischen Form zurück. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Aktualisiert die Geometrie der Form aus dem [IGeometryPath](../../com.aspose.slides/igeometrypath)-Objekt. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Aktualisiert die Geometrie der Form aus einem Array von [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Gibt das Stil-Objekt der Form zurück. |
| [getShapeType()](#getShapeType--) | Gibt den voreingestellten Geometrietyp zurück oder setzt ihn. |
| [setShapeType(int value)](#setShapeType-int-) | Gibt den voreingestellten Geometrietyp zurück oder setzt ihn. |
| [getAdjustments()](#getAdjustments--) | Gibt eine Sammlung von Anpassungswerten der Form zurück. |
| [createShapeElements()](#createShapeElements--) | Erstellt und gibt ein Array von Form-Elementen zurück. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

Gibt eine Kopie des Pfads der geometrischen Form zurück. Koordinaten sind relativ zur linken oberen Ecke der Form.

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

**Rückgabewert:**
com.aspose.slides.IGeometryPath[] - Array von [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

Aktualisiert die Geometrie der Form aus dem [IGeometryPath](../../com.aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) zu [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometrie-Pfad |
### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Aktualisiert die Geometrie der Form aus einem Array von [IGeometryPath](../../com.aspose.slides/igeometrypath). Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) zu [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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
public abstract IShapeStyle getShapeStyle()
```

Gibt das Stil-Objekt der Form zurück. Nur-Lese [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Rückgabewert:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

Gibt den voreingestellten Geometrietyp zurück oder setzt ihn. Hinweis: Bei einer Wertänderung werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lesen/Schreiben [ShapeType](../../com.aspose.slides/shapetype).

**Rückgabewert:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

Gibt den voreingestellten Geometrietyp zurück oder setzt ihn. Hinweis: Bei einer Wertänderung werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt. Lesen/Schreiben [ShapeType](../../com.aspose.slides/shapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

Gibt eine Sammlung von Anpassungswerten der Form zurück. Nur-Lese [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Rückgabewert:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

Erstellt und gibt ein Array von Form-Elementen zurück.

**Rückgabewert:**
com.aspose.slides.IShapeElement[] - Array von [IShapeElement](../../com.aspose.slides/ishapeelement)