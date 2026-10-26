---
title: ShapeElement
second_title: Aspose.Slides para Android mediante la Referencia de API Java
description: Representa una parte de la forma con las mismas propiedades de contorno y relleno.
type: docs
url: /es/com.aspose.slides/shapeelement/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Representa una parte de la forma con las mismas propiedades de contorno y relleno.
## Métodos

| Método | Descripción |
| --- | --- |
| [getParentShape()](#getParentShape--) | Devuelve un Shape_PPT para el cual se creó el elemento. |
| [getPathPoints()](#getPathPoints--) | Obtiene una matriz de puntos que define la geometría de la ruta del elemento. |
| [getPathTypes()](#getPathTypes--) | Obtiene una matriz de valores byte que especifican el tipo de cada punto en la ruta del elemento. |
| [getFillSource()](#getFillSource--) | Devuelve información sobre cómo rellenar un elemento. |
| [getStrokeSource()](#getStrokeSource--) | Devuelve información sobre cómo trazar un elemento. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Devuelve un Shape_PPT para el cual se creó el elemento. Solo lectura [Shape](../../com.aspose.slides/shape).

**Devuelve:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Obtiene una matriz de puntos que define la geometría de la ruta del elemento.

**Devuelve:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Obtiene una matriz de valores byte que especifican el tipo de cada punto en la ruta del elemento.

**0** Indica que el punto es el inicio de una figura.

**1** Indica que el punto es uno de los dos extremos de una línea.

**3** Indica que el punto es un extremo o punto de control de una curva Bézier cúbica.

**7** Enmascara todos los bits excepto los tres bits de menor orden, que indican el tipo de punto.

**16** Especifica que el segmento correspondiente es discontinuo.

**32** Especifica que el punto es un marcador.

**128** Especifica que el punto es el último punto en una subruta cerrada (figura).

**129** Indica un punto de datos que es tanto un extremo de un segmento de línea como el último punto de una subruta cerrada.

**Devuelve:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Devuelve información sobre cómo rellenar un elemento. Solo lectura [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Devuelve:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Devuelve información sobre cómo trazar un elemento. Solo lectura [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Devuelve:**
byte