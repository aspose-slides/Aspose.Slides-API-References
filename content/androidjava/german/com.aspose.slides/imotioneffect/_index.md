---
title: IMotionEffect
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt das Verhalten von Bewegungseffekten des Effekts dar.
type: docs
url: /de/com.aspose.slides/imotioneffect/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Stellt das Verhalten von Bewegungseffekten des Effekts dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFrom()](#getFrom--) | Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). |
| [getTo()](#getTo--) | Gibt den Zielort für einen Animationsbewegungseffekt an (in Prozent). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Gibt den Zielort für einen Animationsbewegungseffekt an (in Prozent). |
| [getBy()](#getBy--) | Beschreibt den relativen Versatzwert für die Animation (in Prozent). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Beschreibt den relativen Versatzwert für die Animation (in Prozent). |
| [getRotationCenter()](#getRotationCenter--) | Beschreibt das Rotationszentrum, das zum Drehen eines Bewegungspfads um X Winkel verwendet wird. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Beschreibt das Rotationszentrum, das zum Drehen eines Bewegungspfads um X Winkel verwendet wird. |
| [getOrigin()](#getOrigin--) | Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. auf das Folienlayout oder das übergeordnete Element. |
| [setOrigin(int value)](#setOrigin-int-) | Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. auf das Folienlayout oder das übergeordnete Element. |
| [getPath()](#getPath--) | Gibt das Pfadprimitive an, gefolgt von Koordinaten für die Animationsbewegung. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Gibt das Pfadprimitive an, gefolgt von Koordinaten für die Animationsbewegung. |
| [getPathEditMode()](#getPathEditMode--) | Gibt an, wie sich der Bewegungspfad bewegt, wenn die Form verschoben wird. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Gibt an, wie sich der Bewegungspfad bewegt, wenn die Form verschoben wird. |
| [getAngle()](#getAngle--) | Beschreibt den relativen Winkel des Bewegungspfads. |
| [setAngle(float value)](#setAngle-float-) | Beschreibt den relativen Winkel des Bewegungspfads. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Rückgabewert:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Gibt den Zielort für einen Animationsbewegungseffekt an (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Rückgabewert:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Gibt den Zielort für einen Animationsbewegungseffekt an (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Beschreibt den relativen Versatzwert für die Animation (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Rückgabewert:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Beschreibt den relativen Versatzwert für die Animation (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Beschreibt das Rotationszentrum, das zum Drehen eines Bewegungspfads um X Winkel verwendet wird. Lesen/Schreiben android.graphics.PointF.

**Rückgabewert:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Beschreibt das Rotationszentrum, das zum Drehen eines Bewegungspfads um X Winkel verwendet wird. Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. auf das Folienlayout oder das übergeordnete Element. Lesen/Schreiben [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Rückgabewert:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. auf das Folienlayout oder das übergeordnete Element. Lesen/Schreiben [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Gibt das Pfadprimitive an, gefolgt von Koordinaten für die Animationsbewegung. Lesen/Schreiben [IMotionPath](../../com.aspose.slides/imotionpath).

**Rückgabewert:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Gibt das Pfadprimitive an, gefolgt von Koordinaten für die Animationsbewegung. Lesen/Schreiben [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Gibt an, wie sich der Bewegungspfad bewegt, wenn die Form verschoben wird. Lesen/Schreiben [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Rückgabewert:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Gibt an, wie sich der Bewegungspfad bewegt, wenn die Form verschoben wird. Lesen/Schreiben [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Beschreibt den relativen Winkel des Bewegungspfads. Lesen/Schreiben float.

**Rückgabewert:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Beschreibt den relativen Winkel des Bewegungspfads. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |