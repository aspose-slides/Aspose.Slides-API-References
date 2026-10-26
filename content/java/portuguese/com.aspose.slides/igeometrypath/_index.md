---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Representa o caminho geométrico de GeometryShape
type: docs
url: /pt/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Representa o caminho geométrico de GeometryShape
## Métodos

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | Retorna o caminho geométrico de GeometryShape como um array de segmentos de caminho. |
| [removeAt(int index)](#removeAt-int-) | Remove o segmento no índice especificado do caminho geométrico. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Adiciona uma linha ao final do caminho |
| [lineTo(float x, float y)](#lineTo-float-float-) | Adiciona uma linha ao final do caminho |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Adiciona uma linha ao local especificado do caminho |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Adiciona uma linha ao local especificado do caminho |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Adiciona curva cúbica de Bezier ao final do caminho |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Adiciona curva cúbica de Bezier ao final do caminho |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Adiciona curva cúbica de Bezier ao local especificado do caminho |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Adiciona curva cúbica de Bezier ao local especificado do caminho |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Adiciona curva quadrática de Bezier ao final do caminho |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Adiciona curva quadrática de Bezier ao final do caminho |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Adiciona curva quadrática de Bezier ao local especificado do caminho |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Adiciona curva quadrática de Bezier ao local especificado do caminho |
| [closeFigure()](#closeFigure--) | Fecha a figura atual deste caminho |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Define a posição do próximo ponto. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Define a posição do próximo ponto. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Anexa o arco especificado ao caminho. |
| [getFillMode()](#getFillMode--) | Define o modo de preenchimento |
| [setFillMode(byte value)](#setFillMode-byte-) | Define o modo de preenchimento |
| [getStroke()](#getStroke--) | Define a aparência do contorno |
| [setStroke(boolean value)](#setStroke-boolean-) | Define a aparência do contorno |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

Retorna o caminho geométrico de GeometryShape como um array de segmentos de caminho.

**Retorna:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o segmento no índice especificado do caminho geométrico.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice do caminho geométrico que deve ser excluído. |
### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

Adiciona uma linha ao final do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Ponto final da linha |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Adiciona uma linha ao final do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Coordenada X do ponto final da linha |
| y | float | Coordenada Y do ponto final da linha |
### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

Adiciona uma linha ao local especificado do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Ponto final |
| index | long | Índice do segmento em PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Adiciona uma linha ao local especificado do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Coordenada X do ponto |
| y | float | Coordenada Y do ponto |
| index | long | Índice do segmento em PathData |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Adiciona curva cúbica de Bezier ao final do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Primeiro ponto de direção |
| point2 | java.awt.geom.Point2D.Float | Segundo ponto de direção |
| point3 | java.awt.geom.Point2D.Float | Ponto final |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Adiciona curva cúbica de Bezier ao final do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Coordenada X do primeiro ponto de direção |
| y1 | float | Coordenada Y do primeiro ponto de direção |
| x2 | float | Coordenada X do segundo ponto de direção |
| y2 | float | Coordenada Y do segundo ponto de direção |
| x3 | float | Coordenada X do ponto final |
| y3 | float | Coordenada Y do ponto final |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Adiciona curva cúbica de Bezier ao local especificado do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Primeiro ponto de direção |
| point2 | java.awt.geom.Point2D.Float | Segundo ponto de direção |
| point3 | java.awt.geom.Point2D.Float | Ponto final |
| index | long | Índice do segmento em PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Adiciona curva cúbica de Bezier ao local especificado do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Coordenada X do primeiro ponto de direção |
| y1 | float | Coordenada Y do primeiro ponto de direção |
| x2 | float | Coordenada X do segundo ponto de direção |
| y2 | float | Coordenada Y do segundo ponto de direção |
| x3 | float | Coordenada X do ponto final |
| y3 | float | Coordenada Y do ponto final |
| index | long | Índice do segmento em PathData |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Adiciona curva quadrática de Bezier ao final do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Ponto de direção |
| point2 | java.awt.geom.Point2D.Float | Ponto final |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Adiciona curva quadrática de Bezier ao final do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Coordenada X do ponto de direção |
| y1 | float | Coordenada Y do ponto de direção |
| x2 | float | Coordenada X do ponto final |
| y2 | float | Coordenada Y do ponto final |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Adiciona curva quadrática de Bezier ao local especificado do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Ponto de direção |
| point2 | java.awt.geom.Point2D.Float | Ponto final |
| index | long | Índice do segmento em PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Adiciona curva quadrática de Bezier ao local especificado do caminho

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Coordenada X do ponto de direção |
| y1 | float | Coordenada Y do ponto de direção |
| x2 | float | Coordenada X do ponto final |
| y2 | float | Coordenada Y do ponto final |
| index | long | Índice do segmento em PathData |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Fecha a figura atual deste caminho
### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

Define a posição do próximo ponto.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Posição do ponto |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Define a posição do próximo ponto.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Coordenada X do ponto |
| y | float | Coordenada Y do ponto |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Anexa o arco especificado ao caminho.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Largura do retângulo |
| heigth | float | Altura do retângulo |
| startAngle | float | Ângulo inicial. |
| sweepAngle | float | Ângulo de varredura/ |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

Define o modo de preenchimento

**Retorna:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

Define o modo de preenchimento

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

Define a aparência do contorno

**Retorna:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Define a aparência do contorno

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
