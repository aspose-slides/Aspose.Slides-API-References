---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /tr/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

GeometryShape'in geometri yolunu temsil eder
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape'in geometri yolunu yol segmentlerinin bir dizisi olarak döndürür. |
| [removeAt(int index)](#removeAt-int-) | Geometri yolunda belirtilen indeksdeki segmenti kaldırır. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Yola sonuna bir çizgi ekler |
| [lineTo(float x, float y)](#lineTo-float-float-) | Yola sonuna bir çizgi ekler |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Yolda belirtilen konuma bir çizgi ekler |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Yolda belirtilen konuma bir çizgi ekler |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Yolun sonuna kübik Bezier eğrisi ekler |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Yolun sonuna kübik Bezier eğrisi ekler |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Yolda belirtilen konuma kübik Bezier eğrisi ekler |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Yolda belirtilen konuma kübik Bezier eğrisi ekler |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Yolun sonuna ikincil Bezier eğrisi ekler |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Yolun sonuna ikincil Bezier eğrisi ekler |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Yolda belirtilen konuma ikincil Bezier eğrisi ekler |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Yolda belirtilen konuma ikincil Bezier eğrisi ekler |
| [closeFigure()](#closeFigure--) | Bu yolun geçerli figürünü kapatır |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Sonraki nokta konumunu ayarlar. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Sonraki nokta konumunu ayarlar. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Belirtilen yayı yola ekler. |
| [getFillMode()](#getFillMode--) | Doldurma modunu ayarlar |
| [setFillMode(byte value)](#setFillMode-byte-) | Doldurma modunu ayarlar |
| [getStroke()](#getStroke--) | Çizgi görünümünü ayarlar |
| [setStroke(boolean value)](#setStroke-boolean-) | Çizgi görünümünü ayarlar |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

GeometryShape'in geometri yolunu yol segmentlerinin bir dizisi olarak döndürür.

**Döndürür:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Geometri yolunda belirtilen indeksteki segmenti kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken geometri yolunun indeksi. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

Yola sonuna bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Çizginin son noktası |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Yola sonuna bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Çizginin son noktasının X koordinatı |
| y | float | Çizginin son noktasının Y koordinatı |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

Yolda belirtilen konuma bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Son nokta |
| index | long | PathData içindeki segmentin indeksi |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Yolda belirtilen konuma bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Noktanın X koordinatı |
| y | float | Noktanın Y koordinatı |
| index | long | PathData içindeki segmentin indeksi |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Yolun sonuna kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | İlk yön noktası |
| point2 | java.awt.geom.Point2D.Float | İkinci yön noktası |
| point3 | java.awt.geom.Point2D.Float | Bitiş noktası |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Yolun sonuna kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | İlk yön noktasının X koordinatı |
| y1 | float | İlk yön noktasının Y koordinatı |
| x2 | float | İkinci yön noktasının X koordinatı |
| y2 | float | İkinci yön noktasının Y koordinatı |
| x3 | float | Bitiş noktasının X koordinatı |
| y3 | float | Bitiş noktasının Y koordinatı |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Yolda belirtilen konuma kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | İlk yön noktası |
| point2 | java.awt.geom.Point2D.Float | İkinci yön noktası |
| point3 | java.awt.geom.Point2D.Float | Bitiş noktası |
| index | long | PathData içindeki segmentin indeksi |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Yolda belirtilen konuma kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | İlk yön noktasının X koordinatı |
| y1 | float | İlk yön noktasının Y koordinatı |
| x2 | float | İkinci yön noktasının X koordinatı |
| y2 | float | İkinci yön noktasının Y koordinatı |
| x3 | float | Bitiş noktasının X koordinatı |
| y3 | float | Bitiş noktasının Y koordinatı |
| index | long | PathData içindeki segmentin indeksi |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Yolun sonuna ikincil Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Yön noktası |
| point2 | java.awt.geom.Point2D.Float | Bitiş noktası |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Yolun sonuna ikincil Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | Yön noktasının X koordinatı |
| y1 | float | Yön noktasının Y koordinatı |
| x2 | float | Bitiş noktasının X koordinatı |
| y2 | float | Bitiş noktasının Y koordinatı |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Yolda belirtilen konuma ikincil Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Yön noktası |
| point2 | java.awt.geom.Point2D.Float | Bitiş noktası |
| index | long | PathData içindeki segmentin indeksi |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Yolda belirtilen konuma ikincil Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | Yön noktasının X koordinatı |
| y1 | float | Yön noktasının Y koordinatı |
| x2 | float | Bitiş noktasının X koordinatı |
| y2 | float | Bitiş noktasının Y koordinatı |
| index | long | PathData içindeki segmentin indeksi |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Bu yolun geçerli figürünü kapatır

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

Sonraki nokta konumunu ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Nokta konumu |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Sonraki nokta konumunu ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Noktanın X koordinatı |
| y | float | Noktanın Y koordinatı |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Belirtilen yayı yola ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | float | Dikdörtgenin genişliği |
| heigth | float | Dikdörtgenin yüksekliği |
| startAngle | float | Başlangıç açısı. |
| sweepAngle | float | Kapsama açısı/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

Doldurma modunu ayarlar

**Döndürür:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

Doldurma modunu ayarlar

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

Çizgi görünümünü ayarlar

**Döndürür:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Çizgi görünümünü ayarlar

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |