---
title: MotionEffect
second_title: Aspose.Slides for Android için Java API Referansı
description: Efektin hareket etkisi davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/motioneffect/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Efektin hareket etkisi davranışını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFrom()](#getFrom--) | Animasyonu başlatmak için x/y koordinatını (yüzde cinsinden) belirtir. |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Animasyonu başlatmak için x/y koordinatını (yüzde cinsinden) belirtir. |
| [getTo()](#getTo--) | Animasyon hareket etkisi için hedef konumu (yüzde cinsinden) belirtir. |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Animasyon hareket etkisi için hedef konumu (yüzde cinsinden) belirtir. |
| [getBy()](#getBy--) | Animasyonun göreceli ofset değerini (yüzde cinsinden) açıklar. |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Animasyonun göreceli ofset değerini (yüzde cinsinden) açıklar. |
| [getRotationCenter()](#getRotationCenter--) | Bir hareket yolunu X açıyla döndürmek için kullanılan dönüş merkezini açıklar. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Bir hareket yolunu X açıyla döndürmek için kullanılan dönüş merkezini açıklar. |
| [getOrigin()](#getOrigin--) | Hareket yolunun orijininin slayt düzeni ya da ebeveyn gibi neye göre olduğunu belirtir. |
| [setOrigin(int value)](#setOrigin-int-) | Hareket yolunun orijininin slayt düzeni ya da ebeveyn gibi neye göre olduğunu belirtir. |
| [getPath()](#getPath--) | Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. |
| [getPathEditMode()](#getPathEditMode--) | Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. |
| [getAngle()](#getAngle--) | Hareket yolunun göreceli açısını açıklar. |
| [setAngle(float value)](#setAngle-float-) | Hareket yolunun göreceli açısını açıklar. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final PointF getFrom()
```


Animasyonu başlatmak için x/y koordinatını (yüzde cinsinden) belirtir. Okunur/Yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```


Animasyonu başlatmak için x/y koordinatını (yüzde cinsinden) belirtir. Okunur/Yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```


Animasyon hareket etkisi için hedef konumu (yüzde cinsinden) belirtir. Okunur/Yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```


Animasyon hareket etkisi için hedef konumu (yüzde cinsinden) belirtir. Okunur/Yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```


Animasyonun göreceli ofset değerini (yüzde cinsinden) açıklar. Okunur/Yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```


Animasyonun göreceli ofset değerini (yüzde cinsinden) açıklar. Okunur/Yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```


Bir hareket yolunu X açıyla döndürmek için kullanılan dönüş merkezini açıklar. Okunur/Yazılır android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```


Bir hareket yolunu X açıyla döndürmek için kullanılan dönüş merkezini açıklar. Okunur/Yazılır android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


Hareket yolunun orijininin slayt düzeni ya da ebeveyn gibi neye göre olduğunu belirtir. Okunur/Yazılır [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Döndürür:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


Hareket yolunun orijininin slayt düzeni ya da ebeveyn gibi neye göre olduğunu belirtir. Okunur/Yazılır [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. Okunur/Yazılır [IMotionPath](../../com.aspose.slides/imotionpath).

**Döndürür:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


Animasyon hareketi için koordinatlarla birlikte yol ilkelini belirtir. Okunur/Yazılır [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. Okunur/Yazılır [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Döndürür:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. Okunur/Yazılır [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


Hareket yolunun göreceli açısını açıklar. Okunur/Yazılır float.

**Döndürür:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


Hareket yolunun göreceli açısını açıklar. Okunur/Yazılır float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |