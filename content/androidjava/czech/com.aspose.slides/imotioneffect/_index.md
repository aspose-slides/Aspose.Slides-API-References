---
title: IMotionEffect
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje chování efektu pohybu.
type: docs
url: /cs/com.aspose.slides/imotioneffect/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Reprezentuje chování efektu pohybu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFrom()](#getFrom--) | Specifikuje souřadnici x/y, odkud animace začíná (v procentech). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Specifikuje souřadnici x/y, odkud animace začíná (v procentech). |
| [getTo()](#getTo--) | Specifikuje cílovou polohu pro efekt pohybové animace (v procentech). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Specifikuje cílovou polohu pro efekt pohybové animace (v procentech). |
| [getBy()](#getBy--) | Popisuje relativní hodnotu offsetu pro animaci (v procentech). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Popisuje relativní hodnotu offsetu pro animaci (v procentech). |
| [getRotationCenter()](#getRotationCenter--) | Popisuje střed rotace používaný k otáčení pohybové cesty o úhel X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Popisuje střed rotace používaný k otáčení pohybové cesty o úhel X. |
| [getOrigin()](#getOrigin--) | Určuje, vůči čemu je původ pohybové cesty, např. rozvržení snímku nebo rodič. |
| [setOrigin(int value)](#setOrigin-int-) | Určuje, vůči čemu je původ pohybové cesty, např. rozvržení snímku nebo rodič. |
| [getPath()](#getPath--) | Určuje primitivní část cesty následovanou souřadnicemi pro pohyb animace. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Určuje primitivní část cesty následovanou souřadnicemi pro pohyb animace. |
| [getPathEditMode()](#getPathEditMode--) | Určuje, jak se pohybová cesta mění při přesunu tvaru. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Určuje, jak se pohybová cesta mění při přesunu tvaru. |
| [getAngle()](#getAngle--) | Popisuje relativní úhel pohybové cesty. |
| [setAngle(float value)](#setAngle-float-) | Popisuje relativní úhel pohybové cesty. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```


Specifikuje souřadnici x/y, odkud animace začíná (v procentech). Číst/Zapisovat android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```


Specifikuje souřadnici x/y, odkud animace začíná (v procentech). Číst/Zapisovat android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```


Specifikuje cílovou polohu pro efekt pohybové animace (v procentech). Číst/Zapisovat android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```


Specifikuje cílovou polohu pro efekt pohybové animace (v procentech). Číst/Zapisovat android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```


Popisuje relativní hodnotu offsetu pro animaci (v procentech). Číst/Zapisovat android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```


Popisuje relativní hodnotu offsetu pro animaci (v procentech). Číst/Zapisovat android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```


Popisuje střed rotace používaný k otáčení pohybové cesty o úhel X. Číst/Zapisovat android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```


Popisuje střed rotace používaný k otáčení pohybové cesty o úhel X. Číst/Zapisovat android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```


Určuje, co je původ pohybové cesty relativní k (např. rozvržení snímku nebo rodič). Číst/Zapisovat [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Vrací:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```


Určuje, co je původ pohybové cesty relativní k (např. rozvržení snímku nebo rodič). Číst/Zapisovat [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```


Určuje primitivní část cesty následovanou souřadnicemi pro pohyb animace. Číst/Zapisovat [IMotionPath](../../com.aspose.slides/imotionpath).

**Vrací:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```


Určuje primitivní část cesty následovanou souřadnicemi pro pohyb animace. Číst/Zapisovat [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```


Určuje, jak se pohybová cesta mění při přesunu tvaru. Číst/Zapisovat [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Vrací:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```


Určuje, jak se pohybová cesta mění při přesunu tvaru. Číst/Zapisovat [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```


Popisuje relativní úhel pohybové cesty. Číst/Zapisovat float.

**Vrací:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```


Popisuje relativní úhel pohybové cesty. Číst/Zapisovat float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |