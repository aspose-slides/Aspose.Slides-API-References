---
title: GeometryPath
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta il percorso geometrico di GeometryShape
type: docs
url: /it/com.aspose.slides/geometrypath/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Rappresenta il percorso geometrico di GeometryShape
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Crea un'istanza di GeometryPath |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPathData()](#getPathData--) | Restituisce il percorso geometrico di GeometryShape come un array di segmenti di percorso. |
| [removeAt(int index)](#removeAt-int-) | Rimuove il segmento all'indice specificato del percorso geometrico. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Aggiunge una linea alla fine del percorso |
| [lineTo(float x, float y)](#lineTo-float-float-) | Aggiunge una linea alla fine del percorso |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Aggiunge una linea al punto specificato del percorso |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Aggiunge una linea al punto specificato del percorso |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Aggiunge una curva cubica di Bezier alla fine del percorso |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Aggiunge una curva cubica di Bezier alla fine del percorso |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Aggiunge una curva cubica di Bezier al punto specificato del percorso |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Aggiunge una curva cubica di Bezier al punto specificato del percorso |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Aggiunge una curva quadratica di Bezier alla fine del percorso |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Aggiunge una curva quadratica di Bezier alla fine del percorso |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Aggiunge una curva quadratica di Bezier al punto specificato del percorso |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Aggiunge una curva quadratica di Bezier al punto specificato del percorso |
| [closeFigure()](#closeFigure--) | Chiude la figura corrente di questo percorso |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Imposta la posizione del punto successivo. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Imposta la posizione del punto successivo. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Aggiunge l'arco specificato al percorso. |
| [getFillMode()](#getFillMode--) | Imposta la modalità di riempimento |
| [setFillMode(byte value)](#setFillMode-byte-) | Imposta la modalità di riempimento |
| [getStroke()](#getStroke--) | Imposta l'aspetto del tratto |
| [setStroke(boolean value)](#setStroke-boolean-) | Imposta l'aspetto del tratto |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Crea un'istanza di GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Restituisce il percorso geometrico di GeometryShape come un array di segmenti di percorso.

**Restituisce:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove il segmento all'indice specificato del percorso geometrico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del percorso geometrico che deve essere eliminato. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Aggiunge una linea alla fine del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | android.graphics.PointF | Punto finale della linea |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Aggiunge una linea alla fine del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | Coordinata X del punto finale della linea |
| y | float | Coordinata Y del punto finale della linea |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Aggiunge una linea al punto specificato del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | android.graphics.PointF | Punto finale |
| index | long | Indice del segmento in PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Aggiunge una linea al punto specificato del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | Coordinata X del punto |
| y | float | Coordinata Y del punto |
| index | long | Indice del segmento in PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Aggiunge una curva cubica di Bezier alla fine del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | android.graphics.PointF | Primo punto di direzione |
| point2 | android.graphics.PointF | Secondo punto di direzione |
| point3 | android.graphics.PointF | Punto finale |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Aggiunge una curva cubica di Bezier alla fine del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | float | Coordinata X del primo punto di direzione |
| y1 | float | Coordinata Y del primo punto di direzione |
| x2 | float | Coordinata X del secondo punto di direzione |
| y2 | float | Coordinata Y del secondo punto di direzione |
| x3 | float | Coordinata X del punto finale |
| y3 | float | Coordinata Y del punto finale |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Aggiunge una curva cubica di Bezier al punto specificato del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | android.graphics.PointF | Primo punto di direzione |
| point2 | android.graphics.PointF | Secondo punto di direzione |
| point3 | android.graphics.PointF | Punto finale |
| index | long | Indice del segmento in PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Aggiunge una curva cubica di Bezier al punto specificato del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | float | Coordinata X del primo punto di direzione |
| y1 | float | Coordinata Y del primo punto di direzione |
| x2 | float | Coordinata X del secondo punto di direzione |
| y2 | float | Coordinata Y del secondo punto di direzione |
| x3 | float | Coordinata X del punto finale |
| y3 | float | Coordinata Y del punto finale |
| index | long | Indice del segmento in PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Aggiunge una curva quadratica di Bezier alla fine del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | android.graphics.PointF | Punto di direzione |
| point2 | android.graphics.PointF | Punto finale |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Aggiunge una curva quadratica di Bezier alla fine del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | float | Coordinata X del punto di direzione |
| y1 | float | Coordinata Y del punto di direzione |
| x2 | float | Coordinata X del punto finale |
| y2 | float | Coordinata Y del punto finale |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Aggiunge una curva quadratica di Bezier al punto specificato del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | android.graphics.PointF | Punto di direzione |
| point2 | android.graphics.PointF | Punto finale |
| index | long | Indice del segmento in PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Aggiunge una curva quadratica di Bezier al punto specificato del percorso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | float | Coordinata X del punto di direzione |
| y1 | float | Coordinata Y del punto di direzione |
| x2 | float | Coordinata X del punto finale |
| y2 | float | Coordinata Y del punto finale |
| index | long | Indice del segmento in PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Chiude la figura corrente di questo percorso

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Imposta la posizione del punto successivo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | android.graphics.PointF | Posizione del punto |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Imposta la posizione del punto successivo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | Coordinata X del punto |
| y | float | Coordinata Y del punto |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Aggiunge l'arco specificato al percorso.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | float | Larghezza del rettangolo |
| heigth | float | Altezza del rettangolo |
| startAngle | float | Angolo di partenza. |
| sweepAngle | float | Angolo di sweep. |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Imposta la modalità di riempimento

**Restituisce:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Imposta la modalità di riempimento

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Imposta l'aspetto del tratto

**Restituisce:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Imposta l'aspetto del tratto

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |