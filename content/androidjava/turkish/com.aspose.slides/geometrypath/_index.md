---
title: GeometryPath
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: GeometryShape'ın geometrik yolunu temsil eder
type: docs
url: /tr/com.aspose.slides/geometrypath/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

GeometryShape'ın geometrik yolunu temsil eder
## Kurucular

| Kurucu | Açıklama |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | GeometryPath örneği oluşturur |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape'ın geometrik yolunu yol segmentleri dizisi olarak döndürür. |
| [removeAt(int index)](#removeAt-int-) | Geometrik yoldaki belirtilen indisteki segmenti kaldırır. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Yola sonuna bir çizgi ekler |
| [lineTo(float x, float y)](#lineTo-float-float-) | Yola sonuna bir çizgi ekler |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Yola belirtilen konumuna bir çizgi ekler |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Yola belirtilen konumuna bir çizgi ekler |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Yola sonuna kübik Bezier eğrisi ekler |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Yola sonuna kübik Bezier eğrisi ekler |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Yola belirtilen konumuna kübik Bezier eğrisi ekler |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Yola belirtilen konumuna kübik Bezier eğrisi ekler |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Yola sonuna ikincil Bezier eğrisi ekler |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Yola sonuna ikincil Bezier eğrisi ekler |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Yola belirtilen konumuna ikincil Bezier eğrisi ekler |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Yola belirtilen konumuna ikincil Bezier eğrisi ekler |
| [closeFigure()](#closeFigure--) | Bu yolun geçerli şekilini kapatır |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Sonraki nokta konumunu ayarlar. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Sonraki nokta konumunu ayarlar. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Belirtilen yayı yola ekler. |
| [getFillMode()](#getFillMode--) | Dolgu modunu ayarlar |
| [setFillMode(byte value)](#setFillMode-byte-) | Dolgu modunu ayarlar |
| [getStroke()](#getStroke--) | Çizgi görünümünü ayarlar |
| [setStroke(boolean value)](#setStroke-boolean-) | Çizgi görünümünü ayarlar |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

GeometryPath örneği oluşturur

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

GeometryShape'ın geometrik yolunu yol segmentleri dizisi olarak döndürür.

**Dönüş Değeri:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Geometrik yoldaki belirtilen indisteki segmenti kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken geometrik yol segmentinin indeksi. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Yola sonuna bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | android.graphics.PointF | Çizginin bitiş noktası |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Yola sonuna bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Çizginin bitiş noktasının X koordinatı |
| y | float | Çizginin bitiş noktasının Y koordinatı |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Yola belirtilen konumuna bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | android.graphics.PointF | Bitiş noktası |
| index | long | PathData içindeki segmentin indeksi |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Yola belirtilen konumuna bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Noktanın X koordinatı |
| y | float | Noktanın Y koordinatı |
| index | long | PathData içindeki segmentin indeksi |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Yola sonuna kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | android.graphics.PointF | İlk yön noktası |
| point2 | android.graphics.PointF | İkinci yön noktası |
| point3 | android.graphics.PointF | Bitiş noktası |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Yola sonuna kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | İlk yön noktasının X koordinatı |
| y1 | float | İlk yön noktasının Y koordinatı |
| x2 | float | İkinci yön noktasının X koordinatı |
| y2 | float | İkinci yön noktasının Y koordinatı |
| x3 | float | Bitiş noktasının X koordinatı |
| y3 | float | Bitiş noktasının Y koordinatı |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Yola belirtilen konumuna kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | android.graphics.PointF | İlk yön noktası |
| point2 | android.graphics.PointF | İkinci yön noktası |
| point3 | android.graphics.PointF | Bitiş noktası |
| index | long | PathData içindeki segmentin indeksi |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Yola belirtilen konumuna kübik Bezier eğrisi ekler

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

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Yola sonuna ikincil Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | android.graphics.PointF | Yön noktası |
| point2 | android.graphics.PointF | Bitiş noktası |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Yola sonuna ikincil Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | Yön noktasının X koordinatı |
| y1 | float | Yön noktasının Y koordinatı |
| x2 | float | Bitiş noktasının X koordinatı |
| y2 | float | Bitiş noktasının Y koordinatı |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Yola belirtilen konumuna ikincil Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | android.graphics.PointF | Yön noktası |
| point2 | android.graphics.PointF | Bitiş noktası |
| index | long | PathData içindeki segmentin indeksi |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Yola belirtilen konumuna ikincil Bezier eğrisi ekler

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
public final void closeFigure()
```

Bu yolun geçerli şekilini kapatır

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Sonraki nokta konumunu ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | android.graphics.PointF | Nokta konumu |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Sonraki nokta konumunu ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Noktanın X koordinatı |
| y | float | Noktanın Y koordinatı |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Belirtilen yayı yola ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | float | Dikdörtgenin genişliği |
| heigth | float | Dikdörtgenin yüksekliği |
| startAngle | float | Başlangıç açısı. |
| sweepAngle | float | Süpürme açısı/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Dolgu modunu ayarlar

**Dönüş Değeri:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Dolgu modunu ayarlar

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Çizgi görünümünü ayarlar

**Dönüş Değeri:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Çizgi görünümünü ayarlar

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |