---
title: IMotionEffect
second_title: Aspose.Slides for Android için Java API Referansı
description: Etkinin hareket efekti davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/imotioneffect/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Etkinin hareket efekti davranışını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getFrom()](#getFrom--) | Animasyonu başlatmak için x/y koordinatını (yüzde olarak) belirtir. |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Animasyonu başlatmak için x/y koordinatını (yüzde olarak) belirtir. |
| [getTo()](#getTo--) | Animasyon hareket efekti için hedef konumu (yüzde olarak) belirtir. |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Animasyon hareket efekti için hedef konumu (yüzde olarak) belirtir. |
| [getBy()](#getBy--) | Animasyon için göreceli ofset değerini (yüzde olarak) açıklar. |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Animasyon için göreceli ofset değerini (yüzde olarak) açıklar. |
| [getRotationCenter()](#getRotationCenter--) | Bir hareket yolunu X açıyla döndürmek için kullanılan dönüş merkezini açıklar. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Bir hareket yolunu X açıyla döndürmek için kullanılan dönüş merkezini açıklar. |
| [getOrigin()](#getOrigin--) | Kaydırma düzeni veya üst nesne gibi hareket yolunun kökeninin neye göre olduğunu belirtir. |
| [setOrigin(int value)](#setOrigin-int-) | Kaydırma düzeni veya üst nesne gibi hareket yolunun kökeninin neye göre olduğunu belirtir. |
| [getPath()](#getPath--) | Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. |
| [getPathEditMode()](#getPathEditMode--) | Şekil hareket ettiğinde hareket yolunun nasıl hareket ettiğini belirtir. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Şekil hareket ettiğinde hareket yolunun nasıl hareket ettiğini belirtir. |
| [getAngle()](#getAngle--) | Hareket yolunun göreceli açısını açıklar. |
| [setAngle(float value)](#setAngle-float-) | Hareket yolunun göreceli açısını açıklar. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Animasyonu başlatmak için x/y koordinatını (yüzde olarak) belirtir. Okunur/yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Animasyonu başlatmak için x/y koordinatını (yüzde olarak) belirtir. Okunur/yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Animasyon hareket efekti için hedef konumu (yüzde olarak) belirtir. Okunur/yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Animasyon hareket efekti için hedef konumu (yüzde olarak) belirtir. Okunur/yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Animasyon için göreceli ofset değerini (yüzde olarak) açıklar. Okunur/yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Animasyon için göreceli ofset değerini (yüzde olarak) açıklar. Okunur/yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Bir hareket yolunu X açıyla döndürmek için kullanılan dönüş merkezini açıklar. Okunur/yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Bir hareket yolunu X açıyla döndürmek için kullanılan dönüş merkezini açıklar. Okunur/yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Kaydırma düzeni veya üst nesne gibi hareket yolunun kökeninin neye göre olduğunu belirtir. Okunur/yazılır [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Döndürür:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Kaydırma düzeni veya üst nesne gibi hareket yolunun kökeninin neye göre olduğunu belirtir. Okunur/yazılır [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. Okunur/yazılır [IMotionPath](../../com.aspose.slides/imotionpath).

**Döndürür:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. Okunur/yazılır [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Şekil hareket ettiğinde hareket yolunun nasıl hareket ettiğini belirtir. Okunur/yazılır [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Döndürür:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Şekil hareket ettiğinde hareket yolunun nasıl hareket ettiğini belirtir. Okunur/yazılır [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Hareket yolunun göreceli açısını açıklar. Okunur/yazılır float.

**Döndürür:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Hareket yolunun göreceli açısını açıklar. Okunur/yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |