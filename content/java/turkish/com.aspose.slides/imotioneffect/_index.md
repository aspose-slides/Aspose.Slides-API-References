---
title: IMotionEffect
second_title: Aspose.Slides için Java API Referansı
description: Etkinin hareket efekti davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/imotioneffect/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Bir efektin hareket etkisi davranışını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFrom()](#getFrom--) | Animasyonu başlatmak için x/y koordinatını (yüzde olarak) belirtir. |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Animasyonu başlatmak için x/y koordinatını (yüzde olarak) belirtir. |
| [getTo()](#getTo--) | Animasyon hareket etkisi için hedef konumu (yüzde olarak) belirtir. |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Animasyon hareket etkisi için hedef konumu (yüzde olarak) belirtir. |
| [getBy()](#getBy--) | Animasyon için göreli ofset değerini (yüzde olarak) tanımlar. |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Animasyon için göreli ofset değerini (yüzde olarak) tanımlar. |
| [getRotationCenter()](#getRotationCenter--) | X açıyla bir hareket yolunu döndürmek için kullanılan dönüş merkezini tanımlar. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | X açıyla bir hareket yolunu döndürmek için kullanılan dönüş merkezini tanımlar. |
| [getOrigin()](#getOrigin--) | Hareket yolunun orijininin slayt düzeni ya da üst öğe gibi neye göre olduğunu belirtir. |
| [setOrigin(int value)](#setOrigin-int-) | Hareket yolunun orijininin slayt düzeni ya da üst öğe gibi neye göre olduğunu belirtir. |
| [getPath()](#getPath--) | Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. |
| [getPathEditMode()](#getPathEditMode--) | Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. |
| [getAngle()](#getAngle--) | Hareket yolunun göreli açısını tanımlar. |
| [setAngle(float value)](#setAngle-float-) | Hareket yolunun göreli açısını tanımlar. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Animasyonu başlatmak için x/y koordinatını (yüzde olarak) belirtir. Okuma/yazma java.awt.geom.Point2D.Float.

**Döndürür:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Animasyonu başlatmak için x/y koordinatını (yüzde olarak) belirtir. Okuma/yazma java.awt.geom.Point2D.Float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Animasyon hareket etkisi için hedef konumu (yüzde olarak) belirtir. Okuma/yazma java.awt.geom.Point2D.Float.

**Döndürür:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Animasyon hareket etkisi için hedef konumu (yüzde olarak) belirtir. Okuma/yazma java.awt.geom.Point2D.Float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Animasyon için göreli ofset değerini (yüzde olarak) tanımlar. Okuma/yazma java.awt.geom.Point2D.Float.

**Döndürür:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Animasyon için göreli ofset değerini (yüzde olarak) tanımlar. Okuma/yazma java.awt.geom.Point2D.Float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

X açıyla bir hareket yolunu döndürmek için kullanılan dönüş merkezini tanımlar. Okuma/yazma java.awt.geom.Point2D.Float.

**Döndürür:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

X açıyla bir hareket yolunu döndürmek için kullanılan dönüş merkezini tanımlar. Okuma/yazma java.awt.geom.Point2D.Float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Hareket yolunun orijininin slayt düzeni ya da üst öğe gibi neye göre olduğunu belirtir. Okuma/yazma [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Döndürür:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Hareket yolunun orijininin slayt düzeni ya da üst öğe gibi neye göre olduğunu belirtir. Okuma/yazma [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. Okuma/yazma [IMotionPath](../../com.aspose.slides/imotionpath).

**Döndürür:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. Okuma/yazma [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. Okuma/yazma [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Döndürür:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. Okuma/yazma [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Hareket yolunun göreli açısını tanımlar. Okuma/yazma float.

**Döndürür:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Hareket yolunun göreli açısını tanımlar. Okuma/yazma float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |