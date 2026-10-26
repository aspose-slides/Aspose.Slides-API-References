---
title: IMotionEffect
second_title: Aspose.Slides pro Java API Reference
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
| [getFrom()](#getFrom--) | Určuje souřadnici x/y, ze které animace začíná (v procentech). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Určuje souřadnici x/y, ze které animace začíná (v procentech). |
| [getTo()](#getTo--) | Určuje cílovou polohu pro animační efekt pohybu (v procentech). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Určuje cílovou polohu pro animační efekt pohybu (v procentech). |
| [getBy()](#getBy--) | Popisuje relativní hodnotu offsetu pro animaci (v procentech). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Popisuje relativní hodnotu offsetu pro animaci (v procentech). |
| [getRotationCenter()](#getRotationCenter--) | Popisuje střed rotace používaný k otáčení dráhy pohybu o úhel X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Popisuje střed rotace používaný k otáčení dráhy pohybu o úhel X. |
| [getOrigin()](#getOrigin--) | Určuje, k čemu je původ dráhy pohybu relativní, např. k rozložení snímku nebo k nadřazenému objektu. |
| [setOrigin(int value)](#setOrigin-int-) | Určuje, k čemu je původ dráhy pohybu relativní, např. k rozložení snímku nebo k nadřazenému objektu. |
| [getPath()](#getPath--) | Určuje primitivní část dráhy následovanou souřadnicemi pro animaci pohybu. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Určuje primitivní část dráhy následovanou souřadnicemi pro animaci pohybu. |
| [getPathEditMode()](#getPathEditMode--) | Určuje, jak se dráha pohybu chová, když se tvar přesune. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Určuje, jak se dráha pohybu chová, když se tvar přesune. |
| [getAngle()](#getAngle--) | Popisuje relativní úhel dráhy pohybu. |
| [setAngle(float value)](#setAngle-float-) | Popisuje relativní úhel dráhy pohybu. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Určuje souřadnici x/y, ze které animace začíná (v procentech). Read/write java.awt.geom.Point2D.Float.

**Vrací:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Určuje souřadnici x/y, ze které animace začíná (v procentech). Read/write java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Určuje cílovou polohu pro animační efekt pohybu (v procentech). Read/write java.awt.geom.Point2D.Float.

**Vrací:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Určuje cílovou polohu pro animační efekt pohybu (v procentech). Read/write java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Popisuje relativní hodnotu offsetu pro animaci (v procentech). Read/write java.awt.geom.Point2D.Float.

**Vrací:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Popisuje relativní hodnotu offsetu pro animaci (v procentech). Read/write java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Popisuje střed rotace používaný k otáčení dráhy pohybu o úhel X. Read/write java.awt.geom.Point2D.Float.

**Vrací:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Popisuje střed rotace používaný k otáčení dráhy pohybu o úhel X. Read/write java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Určuje, k čemu je původ dráhy pohybu relativní, např. k rozložení snímku nebo k nadřazenému objektu. Read/write [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Vrací:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Určuje, k čemu je původ dráhy pohybu relativní, např. k rozložení snímku nebo k nadřazenému objektu. Read/write [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Určuje primitivní část dráhy následovanou souřadnicemi pro animaci pohybu. Read/write [IMotionPath](../../com.aspose.slides/imotionpath).

**Vrací:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Určuje primitivní část dráhy následovanou souřadnicemi pro animaci pohybu. Read/write [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Určuje, jak se dráha pohybu chová, když se tvar přesune. Read/write [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Vrací:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Určuje, jak se dráha pohybu chová, když se tvar přesune. Read/write [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Popisuje relativní úhel dráhy pohybu. Read/write float.

**Vrací:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Popisuje relativní úhel dráhy pohybu. Read/write float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |