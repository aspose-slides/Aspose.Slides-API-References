---
title: IGeometryShape
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar föräldraklassen för alla geometriska former.
type: docs
url: /sv/com.aspose.slides/igeometryshape/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Representerar föräldraklassen för alla geometriska former.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Returnerar en kopia av geometrisk formens sökväg. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Uppdaterar formens geometri från [IGeometryPath](../../com.aspose.slides/igeometrypath)-objektet. |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Uppdaterar formens geometri från en matris av [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Returnerar formens stilobjekt. |
| [getShapeType()](#getShapeType--) | Returnerar eller anger geometrins förinställda typ. |
| [setShapeType(int value)](#setShapeType-int-) | Returnerar eller anger geometrins förinställda typ. |
| [getAdjustments()](#getAdjustments--) | Returnerar en samling av formens justeringsvärden. |
| [createShapeElements()](#createShapeElements--) | Skapar och returnerar en matris av formens element. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

Returnerar en kopia av geometrisk formens sökväg. Koordinaterna är relativa till formens vänstra övre hörn.

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

**Returnerar:**
com.aspose.slides.IGeometryPath[] - Array av [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

Uppdaterar formens geometri från [IGeometryPath](../../com.aspose.slides/igeometrypath)-objektet. Koordinaterna måste vara relativa till formens vänstra övre hörn. Ändrar formens typ (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) till [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Geometrisk sökväg |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Uppdaterar formens geometri från en matris av [IGeometryPath](../../com.aspose.slides/igeometrypath). Koordinaterna måste vara relativa till formens vänstra övre hörn. Ändrar formens typ (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) till [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array av geometriska sökvägar |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

Returnerar formens stilobjekt. Skrivskyddad [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Returnerar:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

Returnerar eller anger geometrins förinställda typ. Obs: vid värdeändring återställs alla justeringsvärden till sina standardvärden. Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Returnerar:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

Returnerar eller anger geometrins förinställda typ. Obs: vid värdeändring återställs alla justeringsvärden till sina standardvärden. Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

Returnerar en samling av formens justeringsvärden. Skrivskyddad [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Returnerar:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

Skapar och returnerar en matris av formens element.

**Returnerar:**
com.aspose.slides.IShapeElement[] - Array av [IShapeElement](../../com.aspose.slides/ishapeelement)