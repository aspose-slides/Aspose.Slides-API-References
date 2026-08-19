---
title: GeometryShape
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje rodičovskou třídu pro všechny geometrické tvary.
type: docs
url: /cs/com.aspose.slides/geometryshape/
---
**Dědičnost:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Všechny implementované rozhraní:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)  
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Reprezentuje rodičovskou třídu pro všechny geometrické tvary.
## Metody

| Metoda | Popis |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Vrací kopii cesty geometrického tvaru. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Aktualizuje geometrii tvaru z objektu [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Aktualizuje geometrii tvaru z pole [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Vrací objekt stylu tvaru. |
| [getShapeType()](#getShapeType--) | Vrací nebo nastavuje předdefinovaný typ geometrie. |
| [setShapeType(int value)](#setShapeType-int-) | Vrací nebo nastavuje předdefinovaný typ geometrie. |
| [getAdjustments()](#getAdjustments--) | Vrací kolekci hodnot úprav tvaru. |
| [createShapeElements()](#createShapeElements--) | Vytvoří a vrátí pole prvků tvaru. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru.

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

**Vrací:**  
com.aspose.slides.IGeometryPath[] - Array of [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

Aktualizuje geometrii tvaru z objektu [IGeometryPath](../../com.aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) na [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parametry:**  
| Parametr | Typ | Popis |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometrická cesta |
### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Aktualizuje geometrii tvaru z pole [IGeometryPath](../../com.aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) na [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parametry:**  
| Parametr | Typ | Popis |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Pole geometrických cest |
### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

Vrací objekt stylu tvaru. Pouze pro čtení [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Vrací:**  
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Vrací nebo nastavuje předdefinovaný typ geometrie. Poznámka: při změně hodnoty se všechny hodnoty úprav vrátí na výchozí hodnoty. Čtení/zápis [ShapeType](../../com.aspose.slides/shapetype).

**Vrací:**  
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Vrací nebo nastavuje předdefinovaný typ geometrie. Poznámka: při změně hodnoty se všechny hodnoty úprav vrátí na výchozí hodnoty. Čtení/zápis [ShapeType](../../com.aspose.slides/shapetype).

**Parametry:**  
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

Vrací kolekci hodnot úprav tvaru. Pouze pro čtení [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Vrací:**  
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

Vytvoří a vrátí pole prvků tvaru.

**Vrací:**  
com.aspose.slides.IShapeElement[] - Array of [ShapeElement](../../com.aspose.slides/shapeelement)