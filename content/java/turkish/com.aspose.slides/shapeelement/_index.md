---
title: ShapeElement
second_title: Aspose.Slides for Java API Referansı
description: Aynı dış hat ve doldurma özelliklerine sahip bir şeklin bir bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/shapeelement/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Aynı dış hat ve doldurma özelliklerine sahip bir şeklin bir bölümünü temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getParentShape()](#getParentShape--) | Shape_PPT'yi döndürür; bu eleman hangi şekil için oluşturulmuştur. |
| [getPathPoints()](#getPathPoints--) | Elemanın yolunun geometrisini tanımlayan nokta dizisini alır. |
| [getPathTypes()](#getPathTypes--) | Elemanın yolundaki her noktanın türünü belirten bayt değerleri dizisini alır. |
| [getFillSource()](#getFillSource--) | Elemanın nasıl doldurulacağıyla ilgili bilgileri döndürür. |
| [getStrokeSource()](#getStrokeSource--) | Elemanın nasıl çizileceğiyle ilgili bilgileri döndürür. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Shape_PPT'yi döndürür; bu eleman hangi şekil için oluşturulmuştur. Salt okunur [Shape](../../com.aspose.slides/shape).

**Döndürür:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

Elemanın yolunun geometrisini tanımlayan nokta dizisini alır.

**Döndürür:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Elemanın yolundaki her noktanın türünü belirten bayt değerleri dizisini alır.

**0** Noktanın bir şeklin başlangıcı olduğunu belirtir.

**1** Noktanın bir çizginin iki uç noktasından biri olduğunu belirtir.

**3** Noktanın bir kübik Bezier eğrisinin uç noktası veya kontrol noktası olduğunu belirtir.

**7** Üç düşük bit dışındaki tüm bitleri maskelemektedir; bu bitler nokta türünü gösterir.

**16** İlgili segmentin kesikli olduğunu belirtir.

**32** Noktanın bir işaretçi olduğunu belirtir.

**128** Noktanın kapalı bir alt yolun (şeklin) son noktasını belirttiğini belirtir.

**129** Hem bir çizgi segmentinin uç noktası hem de kapalı bir alt yolun son noktası olan bir veri noktasını belirtir.

**Döndürür:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Elemanın nasıl doldurulacağıyla ilgili bilgileri döndürür. Salt okunur [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Döndürür:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Elemanın nasıl çizileceğiyle ilgili bilgileri döndürür. Salt okunur [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Döndürür:**
byte