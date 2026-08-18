---
title: GeometryPath
second_title: Aspose.Slides for Java API Referansı
description: GeometryShape'in geometri yolunu temsil eder
type: docs
url: /tr/com.aspose.slides/geometrypath/
---
**Kalıtım:**  
java.lang.Object

**Uygulanan Tüm Arayüzler:**  
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)  
```
public final class GeometryPath implements IGeometryPath
```

GeometryShape'in geometri yolunu temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | GeometryPath'in bir örneğini oluşturur |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape'in geometri yolunu yol segmentleri dizisi olarak döndürür. |
| [removeAt(int index)](#removeAt-int-) | Geometri yolunun belirtilen indisindeki segmenti kaldırır. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Yolun sonuna bir çizgi ekler. |
| [lineTo(float x, float y)](#lineTo-float-float-) | Yolun sonuna bir çizgi ekler. |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Yolun belirtilen yerine bir çizgi ekler. |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Yolun belirtilen yerine bir çizgi ekler. |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Yolun sonuna kübik Bezier eğrisi ekler. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Yolun sonuna kübik Bezier eğrisi ekler. |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Yolun belirtilen yerine kübik Bezier eğrisi ekler. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Yolun belirtilen yerine kübik Bezier eğrisi ekler. |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Yolun sonuna ikinci dereceli Bezier eğrisi ekler. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Yolun sonuna ikinci dereceli Bezier eğrisi ekler. |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Yolun belirtilen yerine ikinci dereceli Bezier eğrisi ekler. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Yolun belirtilen yerine ikinci dereceli Bezier eğrisi ekler. |
| [closeFigure()](#closeFigure--) | Bu yolun geçerli figürünü kapatır. |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Sonraki nokta konumunu ayarlar. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Sonraki nokta konumunu ayarlar. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Belirtilen yayı yola ekler. |
| [getFillMode()](#getFillMode--) | Dolgu kipini ayarlar. |
| [setFillMode(byte value)](#setFillMode-byte-) | Dolgu kipini ayarlar. |
| [getStroke()](#getStroke--) | Çizgi görünümünü ayarlar. |
| [setStroke(boolean value)](#setStroke-boolean-) | Çizgi görünümünü ayarlar. |

### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

GeometryPath'in bir örneğini oluşturur

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

GeometryShape'in geometri yolunu yol segmentleri dizisi olarak döndürür.

**Döndürür:**  
com.aspose.slides.IPathSegment[]

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Geometri yolunun belirtilen indisindeki segmenti kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken geometri yolunun indeksi. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

Yolun sonuna bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Çizginin son noktası |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Yolun sonuna bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Çizginin son noktasının X koordinatı |
| y | float | Çizginin son noktasının Y koordinatı |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

Yolun belirtilen yerine bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Son nokta |
| index | long | PathData içindeki segmentin indeksi |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Yolun belirtilen yerine bir çizgi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Noktanın X koordinatı |
| y | float | Noktanın Y koordinatı |
| index | long | PathData içindeki segmentin indeksi |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Yolun sonuna kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | İlk yön noktası |
| point2 | java.awt.geom.Point2D.Float | İkinci yön noktası |
| point3 | java.awt.geom.Point2D.Float | Son nokta |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Yolun sonuna kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | İlk yön noktasının X koordinatı |
| y1 | float | İlk yön noktasının Y koordinatı |
| x2 | float | İkinci yön noktasının X koordinatı |
| y2 | float | İkinci yön noktasının Y koordinatı |
| x3 | float | Son noktanın X koordinatı |
| y3 | float | Son noktanın Y koordinatı |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Yolun belirtilen yerine kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | İlk yön noktası |
| point2 | java.awt.geom.Point2D.Float | İkinci yön noktası |
| point3 | java.awt.geom.Point2D.Float | Son nokta |
| index | long | PathData içindeki segmentin indeksi |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Yolun belirtilen yerine kübik Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | İlk yön noktasının X koordinatı |
| y1 | float | İlk yön noktasının Y koordinatı |
| x2 | float | İkinci yön noktasının X koordinatı |
| y2 | float | İkinci yön noktasının Y koordinatı |
| x3 | float | Son noktanın X koordinatı |
| y3 | float | Son noktanın Y koordinatı |
| index | long | PathData içindeki segmentin indeksi |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Yolun sonuna ikinci dereceli Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Yön noktası |
| point2 | java.awt.geom.Point2D.Float | Son nokta |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Yolun sonuna ikinci dereceli Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | Yön noktasının X koordinatı |
| y1 | float | Yön noktasının Y koordinatı |
| x2 | float | Son noktanın X koordinatı |
| y2 | float | Son noktanın Y koordinatı |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Yolun belirtilen yerine ikinci dereceli Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Yön noktası |
| point2 | java.awt.geom.Point2D.Float | Son nokta |
| index | long | PathData içindeki segmentin indeksi |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Yolun belirtilen yerine ikinci dereceli Bezier eğrisi ekler

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | float | Yön noktasının X koordinatı |
| y1 | float | Yön noktasının Y koordinatı |
| x2 | float | Son noktanın X koordinatı |
| y2 | float | Son noktanın Y koordinatı |
| index | long | PathData içindeki segmentin indeksi |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Bu yolun geçerli figürünü kapatır

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

Sonraki nokta konumunu ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Nokta konumu |

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
| startAngle | float | Başlangıç açısı |
| sweepAngle | float | Tarama açısı |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Dolgu kipini ayarlar

**Döndürür:**  
byte

### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Dolgu kipini ayarlar

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Çizgi görünümünü ayarlar

**Döndürür:**  
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