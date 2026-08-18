---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /es/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Representa la ruta geométrica de GeometryShape
## Métodos

| Método | Descripción |
| --- | --- |
| [getPathData()](#getPathData--) | Devuelve la ruta geométrica de GeometryShape como una matriz de segmentos de ruta. |
| [removeAt(int index)](#removeAt-int-) | Elimina el segmento en el índice especificado de la ruta geométrica. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Agrega una línea al final de la ruta |
| [lineTo(float x, float y)](#lineTo-float-float-) | Agrega una línea al final de la ruta |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Agrega una línea al lugar especificado de la ruta |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Agrega una línea al lugar especificado de la ruta |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Agrega una curva cúbica de Bézier al final de la ruta |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Agrega una curva cúbica de Bézier al final de la ruta |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Agrega una curva cúbica de Bézier al lugar especificado de la ruta |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Agrega una curva cúbica de Bézier al lugar especificado de la ruta |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Agrega una curva cuadrática de Bézier al final de la ruta |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Agrega una curva cuadrática de Bézier al final de la ruta |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Agrega una curva cuadrática de Bézier al lugar especificado de la ruta |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Agrega una curva cuadrática de Bézier al lugar especificado de la ruta |
| [closeFigure()](#closeFigure--) | Cierra la figura actual de esta ruta |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Establece la posición del siguiente punto. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Establece la posición del siguiente punto. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Añade el arco especificado a la ruta. |
| [getFillMode()](#getFillMode--) | Establece el modo de relleno |
| [setFillMode(byte value)](#setFillMode-byte-) | Establece el modo de relleno |
| [getStroke()](#getStroke--) | Establece la apariencia del trazo |
| [setStroke(boolean value)](#setStroke-boolean-) | Establece la apariencia del trazo |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


Devuelve la ruta geométrica de GeometryShape como una matriz de segmentos de ruta.

**Devuelve:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina el segmento en el índice especificado de la ruta geométrica.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la ruta geométrica que debe eliminarse. |
### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```


Agrega una línea al final de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Punto final de la línea |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Agrega una línea al final de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | Coordenada X del punto final de la línea |
| y | float | Coordenada Y del punto final de la línea |
### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```


Agrega una línea al lugar especificado de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Punto final |
| index | long | Índice del segmento en PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


Agrega una línea al lugar especificado de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | Coordenada X del punto |
| y | float | Coordenada Y del punto |
| index | long | Índice del segmento en PathData |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Agrega una curva cúbica de Bézier al final de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Primer punto de dirección |
| point2 | java.awt.geom.Point2D.Float | Segundo punto de dirección |
| point3 | java.awt.geom.Point2D.Float | Punto final |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Agrega una curva cúbica de Bézier al final de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 | float | Coordenada X del primer punto de dirección |
| y1 | float | Coordenada Y del primer punto de dirección |
| x2 | float | Coordenada X del segundo punto de dirección |
| y2 | float | Coordenada Y del segundo punto de dirección |
| x3 | float | Coordenada X del punto final |
| y3 | float | Coordenada Y del punto final |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Agrega una curva cúbica de Bézier al lugar especificado de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Primer punto de dirección |
| point2 | java.awt.geom.Point2D.Float | Segundo punto de dirección |
| point3 | java.awt.geom.Point2D.Float | Punto final |
| index | long | Índice del segmento en PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Agrega una curva cúbica de Bézier al lugar especificado de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 | float | Coordenada X del primer punto de dirección |
| y1 | float | Coordenada Y del primer punto de dirección |
| x2 | float | Coordenada X del segundo punto de dirección |
| y2 | float | Coordenada Y del segundo punto de dirección |
| x3 | float | Coordenada X del punto final |
| y3 | float | Coordenada Y del punto final |
| index | long | Índice del segmento en PathData |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Agrega una curva cuadrática de Bézier al final de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Punto de dirección |
| point2 | java.awt.geom.Point2D.Float | Punto final |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Agrega una curva cuadrática de Bézier al final de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 | float | Coordenada X del punto de dirección |
| y1 | float | Coordenada Y del punto de dirección |
| x2 | float | Coordenada X del punto final |
| y2 | float | Coordenada Y del punto final |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Agrega una curva cuadrática de Bézier al lugar especificado de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Punto de dirección |
| point2 | java.awt.geom.Point2D.Float | Punto final |
| index | long | Índice del segmento en PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Agrega una curva cuadrática de Bézier al lugar especificado de la ruta

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 | float | Coordenada X del punto de dirección |
| y1 | float | Coordenada Y del punto de dirección |
| x2 | float | Coordenada X del punto final |
| y2 | float | Coordenada Y del punto final |
| index | long | Índice del segmento en PathData |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


Cierra la figura actual de esta ruta
### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```


Establece la posición del siguiente punto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Posición del punto |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Establece la posición del siguiente punto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | Coordenada X del punto |
| y | float | Coordenada Y del punto |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Añade el arco especificado a la ruta.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | float | Ancho del rectángulo |
| heigth | float | Altura del rectángulo |
| startAngle | float | Ángulo de inicio. |
| sweepAngle | float | Ángulo de barrido. |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Establece el modo de relleno

**Devuelve:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Establece el modo de relleno

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Establece la apariencia del trazo

**Devuelve:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Establece la apariencia del trazo

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |