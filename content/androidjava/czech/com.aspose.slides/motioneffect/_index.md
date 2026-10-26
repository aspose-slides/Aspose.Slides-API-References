---
title: MotionEffect
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje chování efektu pohybu.
type: docs
url: /cs/com.aspose.slides/motioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**All Implemented Interfaces:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Represent motion effect behavior of effect.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getFrom()](#getFrom--) | Určuje souřadnici x/y, ze které se animace spustí (v procentech). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Určuje souřadnici x/y, ze které se animace spustí (v procentech). |
| [getTo()](#getTo--) | Určuje cílovou polohu pro efekt pohybu animace (v procentech). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Určuje cílovou polohu pro efekt pohybu animace (v procentech). |
| [getBy()](#getBy--) | Popisuje relativní hodnotu posunu pro animaci (v procentech). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Popisuje relativní hodnotu posunu pro animaci (v procentech). |
| [getRotationCenter()](#getRotationCenter--) | Popisuje střed otáčení použité k otočení dráhy pohybu o úhel X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Popisuje střed otáčení použité k otočení dráhy pohybu o úhel X. |
| [getOrigin()](#getOrigin--) | Určuje, k čemu je relativní počátek dráhy pohybu, například k rozložení snímku nebo rodiči. |
| [setOrigin(int value)](#setOrigin-int-) | Určuje, k čemu je relativní počátek dráhy pohybu, například k rozložení snímku nebo rodiči. |
| [getPath()](#getPath--) | Určuje primitivní tvar dráhy následovaný souřadnicemi pro pohyb animace. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Určuje primitivní tvar dráhy následovaný souřadnicemi pro pohyb animace. |
| [getPathEditMode()](#getPathEditMode--) | Určuje, jak se dráha pohybu chová, když je tvar přesunut. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Určuje, jak se dráha pohybu chová, když je tvar přesunut. |
| [getAngle()](#getAngle--) | Popisuje relativní úhel dráhy pohybu. |
| [setAngle(float value)](#setAngle-float-) | Popisuje relativní úhel dráhy pohybu. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final PointF getFrom()
```


Určuje souřadnici x/y, ze které se animace spustí (v procentech). Číst/zapisovat android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```


Určuje souřadnici x/y, ze které se animace spustí (v procentech). Číst/zapisovat android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```


Určuje cílovou polohu pro efekt pohybu animace (v procentech). Číst/zapisovat android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```


Určuje cílovou polohu pro efekt pohybu animace (v procentech). Číst/zapisovat android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```


Popisuje relativní hodnotu posunu pro animaci (v procentech). Číst/zapisovat android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```


Popisuje relativní hodnotu posunu pro animaci (v procentech). Číst/zapisovat android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```


Popisuje střed otáčení použité k otočení dráhy pohybu o úhel X. Číst/zapisovat android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```


Popisuje střed otáčení použité k otočení dráhy pohybu o úhel X. Číst/zapisovat android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


Určuje, k čemu je relativní počátek dráhy pohybu, například k rozložení snímku nebo rodiči. Číst/zapisovat [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Vrací:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


Určuje, k čemu je relativní počátek dráhy pohybu, například k rozložení snímku nebo rodiči. Číst/zapisovat [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


Určuje primitivní tvar dráhy následovaný souřadnicemi pro pohyb animace. Číst/zapisovat [IMotionPath](../../com.aspose.slides/imotionpath).

**Vrací:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


Určuje primitivní tvar dráhy následovaný souřadnicemi pro pohyb animace. Číst/zapisovat [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


Určuje, jak se dráha pohybu chová, když je tvar přesunut. Číst/zapisovat [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Vrací:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


Určuje, jak se dráha pohybu chová, když je tvar přesunut. Číst/zapisovat [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


Popisuje relativní úhel dráhy pohybu. Číst/zapisovat float.

**Vrací:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


Popisuje relativní úhel dráhy pohybu. Číst/zapisovat float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |