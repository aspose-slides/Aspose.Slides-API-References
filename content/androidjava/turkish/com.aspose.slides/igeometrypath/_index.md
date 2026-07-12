---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /tr/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

GeometryShape'ın geometri yolunu temsil eder
## Yöntemler

| Method | Description |
| --- | --- |
| [getPathData()](#getPathData--) | GeometryShape'ın geometri yolunu yol segmentleri dizisi olarak döndürür. |
| [removeAt(int index)](#removeAt-int-) | Geometri yolunun belirtilen indeksindeki segmenti kaldırır. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Çizgiyi yolun sonuna ekler |
| [lineTo(float x, float y)](#lineTo-float-float-) | Çizgiyi yolun sonuna ekler |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Çizgiyi yolun belirtilen konumuna ekler |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Çizgiyi yolun belirtilen konumuna ekler |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Kübik Bezier eğrisini yolun sonuna ekler |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Kübik Bezier eğrisini yolun sonuna ekler |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Kübik Bezier eğrisini yolun belirtilen konumuna ekler |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Kübik Bezier eğrisini yolun belirtilen konumuna ekler |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Karesel Bezier eğrisini yolun sonuna ekler |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Karesel Bezier eğrisini yolun sonuna ekler |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Karesel Bezier eğrisini yolun belirtilen konumuna ekler |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Karesel Bezier eğrisini yolun belirtilen konumuna ekler |
| [closeFigure()](#closeFigure--) | Bu yolun mevcut figürünü kapatır |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Sonraki nokta konumunu ayarlar. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Sonraki nokta konumunu ayarlar. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Belirtilen yayını yola ekler. |
| [getFillMode()](#getFillMode--) | Dolgu modunu ayarlar |
| [setFillMode(byte value)](#setFillMode-byte-) | Dolgu modunu ayarlar |
| [getStroke()](#getStroke--) | Çizgi görünümünü ayarlar |
| [setStroke(boolean value)](#setStroke-boolean-) | Çizgi görünümünü ayarlar |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

GeometryShape'ın geometri yolunu yol segmentleri dizisi olarak döndürür.

**Döndürür:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Geometri yolunun belirtilen indeksindeki segmenti kaldırır.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken geometri yolunun indeksi. |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

Çizgiyi yolun sonuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| point | android.graphics.PointF | Çizginin bitiş noktası |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Çizgiyi yolun sonuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| x | float | X koordinatı |
| y | float | Y koordinatı |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

Çizgiyi yolun belirtilen konumuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| point | android.graphics.PointF | Bitiş noktası |
| index | long | PathData içindeki segmentin indeksi |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Çizgiyi yolun belirtilen konumuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| x | float | Noktanın X koordinatı |
| y | float | Noktanın Y koordinatı |
| index | long | PathData içindeki segmentin indeksi |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Kübik Bezier eğrisini yolun sonuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| point1 | android.graphics.PointF | İlk yön noktası |
| point2 | android.graphics.PointF | İkinci yön noktası |
| point3 | android.graphics.PointF | Bitiş noktası |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Kübik Bezier eğrisini yolun sonuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| x1 | float | İlk yön noktasının X koordinatı |
| y1 | float | İlk yön noktasının Y koordinatı |
| x2 | float | İkinci yön noktasının X koordinatı |
| y2 | float | İkinci yön noktasının Y koordinatı |
| x3 | float | Bitiş noktasının X koordinatı |
| y3 | float | Bitiş noktasının Y koordinatı |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Kübik Bezier eğrisini yolun belirtilen konumuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| point1 | android.graphics.PointF | İlk yön noktası |
| point2 | android.graphics.PointF | İkinci yön noktası |
| point3 | android.graphics.PointF | Bitiş noktası |
| index | long | PathData içindeki segmentin indeksi |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Kübik Bezier eğrisini yolun belirtilen konumuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
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
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

Karesel Bezier eğrisini yolun sonuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| point1 | android.graphics.PointF | Yön noktası |
| point2 | android.graphics.PointF | Bitiş noktası |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Karesel Bezier eğrisini yolun sonuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| x1 | float | Yön noktasının X koordinatı |
| y1 | float | Yön noktasının Y koordinatı |
| x2 | float | Bitiş noktasının X koordinatı |
| y2 | float | Bitiş noktasının Y koordinatı |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Karesel Bezier eğrisini yolun belirtilen konumuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| point1 | android.graphics.PointF | Yön noktası |
| point2 | android.graphics.PointF | Bitiş noktası |
| index | long | PathData içindeki segmentin indeksi |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Karesel Bezier eğrisini yolun belirtilen konumuna ekler

**Parametreler:**
| Parametre | Type | Açıklama |
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

Bu yolun mevcut figürünü kapatır
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

Sonraki nokta konumunu ayarlar.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| point | android.graphics.PointF | Nokta konumu |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Sonraki nokta konumunu ayarlar.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| x | float | Noktanın X koordinatı |
| y | float | Noktanın Y koordinatı |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Belirtilen yayını yola ekler.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| width | float | Dikdörtgenin genişliği |
| heigth | float | Dikdörtgenin yüksekliği |
| startAngle | float | Başlangıç açısı. |
| sweepAngle | float | Tarama açısı. |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

Dolgu modunu ayarlar

**Döndürür:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

Dolgu modunu ayarlar

**Parametreler:**
| Parametre | Type | Açıklama |
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
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | boolean |  |