---
title: MotionEffect
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje chování efektu pohybu.
type: docs
url: /cs/com.aspose.slides/motioneffect/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Reprezentuje chování efektu pohybu.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getFrom()](#getFrom--) | Určuje souřadnici x/y, odkud má animace začít (v procentech). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Určuje souřadnici x/y, odkud má animace začít (v procentech). |
| [getTo()](#getTo--) | Určuje cílovou polohu pro efekt pohybu animace (v procentech). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Určuje cílovou polohu pro efekt pohybu animace (v procentech). |
| [getBy()](#getBy--) | Popisuje relativní hodnotu posunu pro animaci (v procentech). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Popisuje relativní hodnotu posunu pro animaci (v procentech). |
| [getRotationCenter()](#getRotationCenter--) | Popisuje střed otáčení používaný k otáčení pohybové cesty o úhel X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Popisuje střed otáčení používaný k otáčení pohybové cesty o úhel X. |
| [getOrigin()](#getOrigin--) | Určuje, k čemu je relativní počátek pohybové cesty, např. k rozvržení snímku nebo k nadřazenému objektu. |
| [setOrigin(int value)](#setOrigin-int-) | Určuje, k čemu je relativní počátek pohybové cesty, např. k rozvržení snímku nebo k nadřazenému objektu. |
| [getPath()](#getPath--) | Určuje primitivní část cesty následovanou souřadnicemi pro animaci pohybu. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Určuje primitivní část cesty následovanou souřadnicemi pro animaci pohybu. |
| [getPathEditMode()](#getPathEditMode--) | Určuje, jak se pohybová cesta mění, když se objekt přesune. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Určuje, jak se pohybová cesta mění, když se objekt přesune. |
| [getAngle()](#getAngle--) | Popisuje relativní úhel pohybové cesty. |
| [setAngle(float value)](#setAngle-float-) | Popisuje relativní úhel pohybové cesty. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final Point2D.Float getFrom()
```


Určuje souřadnici x/y, odkud má animace začít (v procentech). Čtení/zápis java.awt.geom.Point2D.Float.

**Návratová hodnota:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```


Určuje souřadnici x/y, odkud má animace začít (v procentech). Čtení/zápis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```


Určuje cílovou polohu pro efekt pohybu animace (v procentech). Čtení/zápis java.awt.geom.Point2D.Float.

**Návratová hodnota:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```


Určuje cílovou polohu pro efekt pohybu animace (v procentech). Čtení/zápis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```


Popisuje relativní hodnotu posunu pro animaci (v procentech). Čtení/zápis java.awt.geom.Point2D.Float.

**Návratová hodnota:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```


Popisuje relativní hodnotu posunu pro animaci (v procentech). Čtení/zápis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```


Popisuje střed otáčení používaný k otáčení pohybové cesty o úhel X. Čtení/zápis java.awt.geom.Point2D.Float.

**Návratová hodnota:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```


Popisuje střed otáčení používaný k otáčení pohybové cesty o úhel X. Čtení/zápis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


Určuje, k čemu je relativní počátek pohybové cesty, např. k rozvržení snímku nebo k nadřazenému objektu. Čtení/zápis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Návratová hodnota:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


Určuje, k čemu je relativní počátek pohybové cesty, např. k rozvržení snímku nebo k nadřazenému objektu. Čtení/zápis [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


Určuje primitivní část cesty následovanou souřadnicemi pro animaci pohybu. Čtení/zápis [IMotionPath](../../com.aspose.slides/imotionpath).

**Návratová hodnota:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


Určuje primitivní část cesty následovanou souřadnicemi pro animaci pohybu. Čtení/zápis [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


Určuje, jak se pohybová cesta mění, když se objekt přesune. Čtení/zápis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Návratová hodnota:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


Určuje, jak se pohybová cesta mění, když se objekt přesune. Čtení/zápis [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


Popisuje relativní úhel pohybové cesty. Čtení/zápis float.

**Návratová hodnota:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


Popisuje relativní úhel pohybové cesty. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |