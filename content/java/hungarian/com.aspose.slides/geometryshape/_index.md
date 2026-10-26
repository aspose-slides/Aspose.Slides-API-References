---
title: GeometryShape
second_title: Aspose.Slides Java API referenciája
description: Az összes geometriai alakzat szülőosztályát képviseli.
type: docs
url: /hu/com.aspose.slides/geometryshape/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Minden megvalósított interfész:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

A szülőosztályt képviseli minden geometriai alakzathoz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Visszaadja a geometriai alakzat útvonalának másolatát. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Frissíti az alakzat geometriáját a [IGeometryPath](../../com.aspose.slides/igeometrypath) objektumból. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Frissíti az alakzat geometriáját a [IGeometryPath](../../com.aspose.slides/igeometrypath) tömbből. |
| [getShapeStyle()](#getShapeStyle--) | Visszaadja az alakzat stílusobjektumát. |
| [getShapeType()](#getShapeType--) | Visszaadja vagy beállítja a geometriai előre beállított típust. |
| [setShapeType(int value)](#setShapeType-int-) | Visszaadja vagy beállítja a geometriai előre beállított típust. |
| [getAdjustments()](#getAdjustments--) | Visszaad egy gyűjteményt az alakzat beállítási értékeiről. |
| [createShapeElements()](#createShapeElements--) | Létrehozza és visszaadja az alakzat elemeinek tömbjét. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```


Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához viszonyítva vannak.

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

**Visszatérési érték:**
com.aspose.slides.IGeometryPath[] - Tömb a(z) [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```


Frissíti az alakzat geometriáját a [IGeometryPath](../../com.aspose.slides/igeometrypath) objektumból. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. A alakzat típusát (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) a [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) értékre változtatja.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometriai útvonal |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```


Frissíti az alakzat geometriáját a [IGeometryPath](../../com.aspose.slides/igeometrypath) tömbből. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. A alakzat típusát (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) a [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) értékre változtatja.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Geometriai útvonalak tömbje |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```


Visszaadja az alakzat stílusobjektumát. Csak olvasható [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Visszatérési érték:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Visszaadja vagy beállítja a geometriai előre beállított típust. Megjegyzés: az érték módosításakor minden beállítási érték visszaáll az alapértelmezett értékére. Olvasható/írható [ShapeType](../../com.aspose.slides/shapetype).

**Visszatérési érték:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Visszaadja vagy beállítja a geometriai előre beállított típust. Megjegyzés: az érték módosításakor minden beállítási érték visszaáll az alapértelmezett értékére. Olvasható/írható [ShapeType](../../com.aspose.slides/shapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```


Visszaad egy gyűjteményt az alakzat beállítási értékeiről. Csak olvasható [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Visszatérési érték:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```


Létrehozza és visszaadja az alakzat elemeinek tömbjét.

**Visszatérési érték:**
com.aspose.slides.IShapeElement[] - Tömb a(z) [ShapeElement](../../com.aspose.slides/shapeelement)