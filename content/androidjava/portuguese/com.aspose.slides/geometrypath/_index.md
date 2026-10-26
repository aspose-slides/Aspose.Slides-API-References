---
title: GeometryPath
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o caminho geométrico de GeometryShape
type: docs
url: /pt/com.aspose.slides/geometrypath/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Representa o caminho geométrico de GeometryShape
## Construtores

| Construtor | Descrição |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Cria uma instância de GeometryPath |
## Métodos

| Método | Descrição |
| --- | --- |
| [getPathData()](#getPathData--) | Retorna o caminho geométrico de GeometryShape como um array de segmentos de caminho. |
| [removeAt(int index)](#removeAt-int-) | Remove o segmento no índice especificado do caminho geométrico. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Adiciona linha ao final do caminho |
| [lineTo(float x, float y)](#lineTo-float-float-) | Adiciona linha ao final do caminho |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Adiciona linha ao local especificado do caminho |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Adiciona linha ao local especificado do caminho |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Adiciona curva cúbica de Bézier ao final do caminho |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Adiciona curva cúbica de Bézier ao final do caminho |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Adiciona curva cúbica de Bézier ao local especificado do caminho |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Adiciona curva cúbica de Bézier ao local especificado do caminho |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Adiciona curva quadrática de Bézier ao final do caminho |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Adiciona curva quadrática de Bézier ao final do caminho |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Adiciona curva quadrática de Bézier ao local especificado do caminho |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Adiciona curva quadrática de Bézier ao local especificado do caminho |
| [closeFigure()](#closeFigure--) | Fecha a figura atual deste caminho |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Define a posição do próximo ponto. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Define a posição do próximo ponto. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Anexa o arco especificado ao caminho. |
| [getFillMode()](#getFillMode--) | Define o modo de preenchimento |
| [setFillMode(byte value)](#setFillMode-byte-) | Define o modo de preenchimento |
| [getStroke()](#getStroke--) | Define a aparência do contorno |
| [setStroke(boolean value)](#setStroke-boolean-) | Define a aparência do contorno |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Cria uma instância de GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Retorna o caminho geométrico de GeometryShape como um array de segmentos de caminho.

**Retorna:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o segmento no índice especificado do caminho geométrico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do caminho geométrico que deve ser excluído. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Adiciona linha ao final do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point | android.graphics.PointF | Ponto final da linha |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Adiciona linha ao final do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | Coordenada X do ponto final da linha |
| y | float | Coordenada Y do ponto final da linha |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Adiciona linha ao local especificado do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point | android.graphics.PointF | Ponto final |
| index | long | Índice do segmento em PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Adiciona linha ao local especificado do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | Coordenada X do ponto |
| y | float | Coordenada Y do ponto |
| index | long | Índice do segmento em PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Adiciona curva cúbica de Bézier ao final do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point1 | android.graphics.PointF | Primeiro ponto de direção |
| point2 | android.graphics.PointF | Segundo ponto de direção |
| point3 | android.graphics.PointF | Ponto final |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Adiciona curva cúbica de Bézier ao final do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | float | Coordenada X do primeiro ponto de direção |
| y1 | float | Coordenada Y do primeiro ponto de direção |
| x2 | float | Coordenada X do segundo ponto de direção |
| y2 | float | Coordenada Y do segundo ponto de direção |
| x3 | float | Coordenada X do ponto final |
| y3 | float | Coordenada Y do ponto final |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Adiciona curva cúbica de Bézier ao local especificado do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point1 | android.graphics.PointF | Primeiro ponto de direção |
| point2 | android.graphics.PointF | Segundo ponto de direção |
| point3 | android.graphics.PointF | Ponto final |
| index | long | Índice do segmento em PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Adiciona curva cúbica de Bézier ao local especificado do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | float | Coordenada X do primeiro ponto de direção |
| y1 | float | Coordenada Y do primeiro ponto de direção |
| x2 | float | Coordenada X do segundo ponto de direção |
| y2 | float | Coordenada Y do segundo ponto de direção |
| x3 | float | Coordenada X do ponto final |
| y3 | float | Coordenada Y do ponto final |
| index | long | Índice do segmento em PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Adiciona curva quadrática de Bézier ao final do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point1 | android.graphics.PointF | Ponto de direção |
| point2 | android.graphics.PointF | Ponto final |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Adiciona curva quadrática de Bézier ao final do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | float | Coordenada X do ponto de direção |
| y1 | float | Coordenada Y do ponto de direção |
| x2 | float | Coordenada X do ponto final |
| y2 | float | Coordenada Y do ponto final |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Adiciona curva quadrática de Bézier ao local especificado do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point1 | android.graphics.PointF | Ponto de direção |
| point2 | android.graphics.PointF | Ponto final |
| index | long | Índice do segmento em PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Adiciona curva quadrática de Bézier ao local especificado do caminho

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | float | Coordenada X do ponto de direção |
| y1 | float | Coordenada Y do ponto de direção |
| x2 | float | Coordenada X do ponto final |
| y2 | float | Coordenada Y do ponto final |
| index | long | Índice do segmento em PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Fecha a figura atual deste caminho

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Define a posição do próximo ponto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point | android.graphics.PointF | Posição do ponto |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Define a posição do próximo ponto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | Coordenada X do ponto |
| y | float | Coordenada Y do ponto |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Anexa o arco especificado ao caminho.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | float | Largura do retângulo |
| heigth | float | Altura do retângulo |
| startAngle | float | Ângulo inicial. |
| sweepAngle | float | Ângulo de varredura/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Define o modo de preenchimento

**Retorna:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Define o modo de preenchimento

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Define a aparência do contorno

**Retorna:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Define a aparência do contorno

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |