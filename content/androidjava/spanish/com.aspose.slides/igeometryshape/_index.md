---
title: IGeometryShape
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa la clase base para todas las formas geométricas.
type: docs
url: /es/com.aspose.slides/igeometryshape/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape)
```
public interface IGeometryShape extends IShape
```

Representa la clase base para todas las formas geométricas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Devuelve una copia de la ruta de la forma geométrica. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Actualiza la geometría de la forma a partir del objeto [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Actualiza la geometría de la forma a partir de una matriz de [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Devuelve el objeto de estilo de la forma. |
| [getShapeType()](#getShapeType--) | Devuelve o establece el tipo predefinido de la geometría. |
| [setShapeType(int value)](#setShapeType-int-) | Devuelve o establece el tipo predefinido de la geometría. |
| [getAdjustments()](#getAdjustments--) | Devuelve una colección de valores de ajuste de la forma. |
| [createShapeElements()](#createShapeElements--) | Crea y devuelve una matriz de los elementos de la forma. |
### getGeometryPaths() {#getGeometryPaths--}
```
public abstract IGeometryPath[] getGeometryPaths()
```

Devuelve una copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma.

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


**Devuelve:**
com.aspose.slides.IGeometryPath[] - Matriz de [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public abstract void setGeometryPath(IGeometryPath geometryPath)
```

Actualiza la geometría de la forma a partir del objeto [IGeometryPath](../../com.aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) a [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Ruta de la geometría |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public abstract void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Actualiza la geometría de la forma a partir de una matriz de [IGeometryPath](../../com.aspose.slides/igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) a [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Matriz de rutas de geometría |

### getShapeStyle() {#getShapeStyle--}
```
public abstract IShapeStyle getShapeStyle()
```

Devuelve el objeto de estilo de la forma. Solo lectura [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Devuelve:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public abstract int getShapeType()
```

Devuelve o establece el tipo predefinido de la geometría. Nota: al cambiar el valor todos los valores de ajuste se restablecerán a sus valores predeterminados. Lectura/escritura [ShapeType](../../com.aspose.slides/shapetype).

**Devuelve:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public abstract void setShapeType(int value)
```

Devuelve o establece el tipo predefinido de la geometría. Nota: al cambiar el valor todos los valores de ajuste se restablecerán a sus valores predeterminados. Lectura/escritura [ShapeType](../../com.aspose.slides/shapetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public abstract IAdjustValueCollection getAdjustments()
```

Devuelve una colección de valores de ajuste de la forma. Solo lectura [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Devuelve:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public abstract IShapeElement[] createShapeElements()
```

Crea y devuelve una matriz de los elementos de la forma.

**Devuelve:**
com.aspose.slides.IShapeElement[] - Matriz de [IShapeElement](../../com.aspose.slides/ishapeelement)