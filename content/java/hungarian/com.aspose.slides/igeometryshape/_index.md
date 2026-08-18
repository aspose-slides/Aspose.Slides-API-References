---
title: IGeometryShape
second_title: Aspose.Slides Java API Referencia
description: A szülőosztályt képviseli az összes geometriai alakzathoz.
type: docs
url: /hu/com.aspose.slides/igeometryshape/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Az összes geometriai alakzat szülőosztályát reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Visszaadja a geometriai alakzat útvonalának másolatát. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Frissíti az alakzat geometriáját a(z) [IGeometryPath](../../com.aspose.slides/igeometrypath) objektumból. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Frissíti az alakzat geometriáját a(z) [IGeometryPath](../../com.aspose.slides/igeometrypath) tömbből. |
| [getShapeStyle()](#getShapeStyle--) | Visszaadja az alakzat stílusobjektumát. |
| [getShapeType()](#getShapeType--) | Visszaadja vagy beállítja a geometriai előre beállított típust. |
| [setShapeType(int value)](#setShapeType-int-) | Visszaadja vagy beállítja a geometriai előre beállított típust. |
| [getAdjustments()](#getAdjustments--) | Visszaadja az alakzat beállítási értékeinek gyűjteményét. |
| [createShapeElements()](#createShapeElements--) | Létrehozza és visszaadja az alakzat elemeinek tömbjét. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```


Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához képest relatívak.

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

**Visszaadja:**
com.aspose.slides.IGeometryPath[] - Array of [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```


Frissíti az alakzat geometriáját a(z) [IGeometryPath](../../com.aspose.slides/igeometrypath) objektumból. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. Megváltoztatja az alakzat típusát (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) a(z) [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) értékre.

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
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```


Frissíti az alakzat geometriáját a(z) [IGeometryPath](../../com.aspose.slides/igeometrypath) tömbből. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. Megváltoztatja az alakzat típusát (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) a(z) [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom) értékre.

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
public abstract IShapeStyle getShapeStyle()
```


Visszaadja az alakzat stílusobjektumát. Csak olvasható [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Visszaadja:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```


Visszaadja vagy beállítja a geometriai előre beállított típust. Megjegyzés: érték módosításakor az összes beállítási érték visszaáll az alapértelmezett értékekre. Olvasható/írható [ShapeType](../../com.aspose.slides/shapetype).

**Visszaadja:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```


Visszaadja vagy beállítja a geometriai előre beállított típust. Megjegyzés: érték módosításakor az összes beállítási érték visszaáll az alapértelmezett értékekre. Olvasható/írható [ShapeType](../../com.aspose.slides/shapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```


Visszaad egy gyűjteményt az alakzat beállítási értékeiről. Csak olvasható [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Visszaadja:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```


Létrehozza és visszaadja az alakzat elemeinek tömbjét.

**Visszaadja:**
com.aspose.slides.IShapeElement[] - Array of [IShapeElement](../../com.aspose.slides/ishapeelement)