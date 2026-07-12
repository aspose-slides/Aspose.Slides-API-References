---
title: ShapeElement
second_title: Aspose.Slides for Android için Java API Referansı
description: Aynı ana hat ve dolgu özelliklerine sahip şeklin bir parçasını temsil eder.
type: docs
url: /tr/com.aspose.slides/shapeelement/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Aynı ana hat ve dolgu özelliklerine sahip şeklin bir parçasını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getParentShape()](#getParentShape--) | Elementin oluşturulduğu Shape_PPT'yi döndürür. |
| [getPathPoints()](#getPathPoints--) | Elemanın yolunun geometrisini tanımlayan nokta dizisini alır. |
| [getPathTypes()](#getPathTypes--) | Elemanın yolundaki her noktanın tipini belirten bayt değerleri dizisini alır. |
| [getFillSource()](#getFillSource--) | Bir elemanı nasıl dolduracağınız hakkında bilgi döndürür. |
| [getStrokeSource()](#getStrokeSource--) | Bir elemanı nasıl çizeceğiniz hakkında bilgi döndürür. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Elementin oluşturulduğu Shape_PPT'yi döndürür. Salt-okunur [Shape](../../com.aspose.slides/shape).

**Döndürür:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Elemanın yolunun geometrisini tanımlayan nokta dizisini alır.

**Döndürür:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Elemanın yolundaki her noktanın tipini belirten bayt değerleri dizisini alır.

**0** Noktanın bir şeklin başlangıcı olduğunu gösterir.

**1** Noktanın bir çizginin iki uç noktasından biri olduğunu gösterir.

**3** Noktanın kübik Bezier spline'ının uç noktası ya da kontrol noktası olduğunu gösterir.

**7** Nokta tipini belirten üç düşük sıra biti dışındaki tüm bitleri maskeleyerek gösterir.

**16** İlgili segmentin kesikli olduğunu belirler.

**32** Noktanın bir işaretçi olduğunu belirtir.

**128** Noktanın kapalı bir alt yol (şekil) içindeki son nokta olduğunu belirtir.

**129** Hem bir çizgi segmentinin uç noktası hem de kapalı bir alt yolun son noktası olan bir veri noktasını gösterir.

**Döndürür:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Bir elemanı nasıl dolduracağınız hakkında bilgi döndürür. Salt-okunur [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Döndürür:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Bir elemanı nasıl çizeceğiniz hakkında bilgi döndürür. Salt-okunur [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Döndürür:**
byte