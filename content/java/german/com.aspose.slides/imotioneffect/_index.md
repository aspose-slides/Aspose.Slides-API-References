---
title: IMotionEffect
second_title: Aspose.Slides für Java API-Referenz
description: Stellt das Verhalten des Bewegungseffekts dar.
type: docs
url: /de/com.aspose.slides/imotioneffect/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Stellt das Verhalten des Bewegungseffekts dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFrom()](#getFrom--) | Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). |
| [getTo()](#getTo--) | Gibt den Zielort für einen Animationsbewegungseffekt an (in Prozent). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Gibt den Zielort für einen Animationsbewegungseffekt an (in Prozent). |
| [getBy()](#getBy--) | Beschreibt den relativen Versatzwert für die Animation (in Prozent). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Beschreibt den relativen Versatzwert für die Animation (in Prozent). |
| [getRotationCenter()](#getRotationCenter--) | Beschreibt das Rotationszentrum, das verwendet wird, um einen Bewegungspfad um einen X-Winkel zu drehen. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Beschreibt das Rotationszentrum, das verwendet wird, um einen Bewegungspfad um einen X-Winkel zu drehen. |
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
public abstract Point2D.Float getFrom()
```

Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). Lesen/Schreiben java.awt.geom.Point2D.Float.

**Rückgabe:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). Lesen/Schreiben java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Gibt den Zielort für einen Animationsbewegungseffekt an (in Prozent). Lesen/Schreiben java.awt.geom.Point2D.Float.

**Rückgabe:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Gibt den Zielort für einen Animationsbewegungseffekt an (in Prozent). Lesen/Schreiben java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Beschreibt den relativen Versatzwert für die Animation (in Prozent). Lesen/Schreiben java.awt.geom.Point2D.Float.

**Rückgabe:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Beschreibt den relativen Versatzwert für die Animation (in Prozent). Lesen/Schreiben java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Beschreibt das Rotationszentrum, das verwendet wird, um einen Bewegungspfad um einen X-Winkel zu drehen. Lesen/Schreiben java.awt.geom.Point2D.Float.

**Rückgabe:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Beschreibt das Rotationszentrum, das verwendet wird, um einen Bewegungspfad um einen X-Winkel zu drehen. Lesen/Schreiben java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. auf das Folienlayout oder das übergeordnete Element. Lesen/Schreiben [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Rückgabe:**
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

**Rückgabe:**
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

**Rückgabe:**
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

**Rückgabe:**
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