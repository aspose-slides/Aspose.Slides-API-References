---
title: IGeometryShape
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta la classe base per tutte le forme geometriche.
type: docs
url: /it/com.aspose.slides/igeometryshape/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Rappresenta la classe base per tutte le forme geometriche.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Restituisce una copia del percorso della forma geometrica. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Aggiorna la geometria della forma dall'oggetto [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Aggiorna la geometria della forma da un array di [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Restituisce l'oggetto stile della forma. |
| [getShapeType()](#getShapeType--) | Restituisce o imposta il tipo predefinito di geometria. |
| [setShapeType(int value)](#setShapeType-int-) | Restituisce o imposta il tipo predefinito di geometria. |
| [getAdjustments()](#getAdjustments--) | Restituisce una collezione di valori di aggiustamento della forma. |
| [createShapeElements()](#createShapeElements--) | Crea e restituisce un array di elementi della forma. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```


Restituisce una copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma.

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


**Restituisce:**
com.aspose.slides.IGeometryPath[] - Array di [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```


Aggiorna la geometria della forma dall'oggetto [IGeometryPath](../../com.aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) in [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Percorso geometrico |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```


Aggiorna la geometria della forma da un array di [IGeometryPath](../../com.aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) in [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Array di percorsi geometrici |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```


Restituisce l'oggetto stile della forma. Sola lettura [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Restituisce:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```


Restituisce o imposta il tipo predefinito di geometria. Nota: al cambiamento del valore tutti i valori di aggiustamento verranno ripristinati ai valori predefiniti. Lettura/Scrittura [ShapeType](../../com.aspose.slides/shapetype).

**Restituisce:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```


Restituisce o imposta il tipo predefinito di geometria. Nota: al cambiamento del valore tutti i valori di aggiustamento verranno ripristinati ai valori predefiniti. Lettura/Scrittura [ShapeType](../../com.aspose.slides/shapetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```


Restituisce una collezione di valori di aggiustamento della forma. Sola lettura [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Restituisce:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```


Crea e restituisce un array di elementi della forma.

**Restituisce:**
com.aspose.slides.IShapeElement[] - Array di [IShapeElement](../../com.aspose.slides/ishapeelement)