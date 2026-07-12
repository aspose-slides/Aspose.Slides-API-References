---
title: MotionEffect
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt das Verhalten des Bewegungseffekts dar.
type: docs
url: /de/com.aspose.slides/motioneffect/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Stellt das Verhalten des Bewegungseffekts dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFrom()](#getFrom--) | Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). |
| [getTo()](#getTo--) | Gibt den Zielort für einen Bewegungs-Effekt der Animation an (in Prozent). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Gibt den Zielort für einen Bewegungs-Effekt der Animation an (in Prozent). |
| [getBy()](#getBy--) | Beschreibt den relativen Versatzwert für die Animation (in Prozent). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Beschreibt den relativen Versatzwert für die Animation (in Prozent). |
| [getRotationCenter()](#getRotationCenter--) | Beschreibt das Rotationszentrum, das verwendet wird, um einen Bewegungspfad um X Winkel zu drehen. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Beschreibt das Rotationszentrum, das verwendet wird, um einen Bewegungspfad um X Winkel zu drehen. |
| [getOrigin()](#getOrigin--) | Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. das Folienlayout oder das übergeordnete Element. |
| [setOrigin(int value)](#setOrigin-int-) | Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. das Folienlayout oder das übergeordnete Element. |
| [getPath()](#getPath--) | Gibt die Pfadprimitive gefolgt von Koordinaten für die Animationsbewegung an. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Gibt die Pfadprimitive gefolgt von Koordinaten für die Animationsbewegung an. |
| [getPathEditMode()](#getPathEditMode--) | Gibt an, wie sich der Bewegungspfad bewegt, wenn das Objekt verschoben wird. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Gibt an, wie sich der Bewegungspfad bewegt, wenn das Objekt verschoben wird. |
| [getAngle()](#getAngle--) | Beschreibt den relativen Winkel des Bewegungspfads. |
| [setAngle(float value)](#setAngle-float-) | Beschreibt den relativen Winkel des Bewegungspfads. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final PointF getFrom()
```


Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Rückgabe:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```


Gibt eine x/y-Koordinate an, von der die Animation gestartet wird (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```


Gibt den Zielort für einen Bewegungs-Effekt der Animation an (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Rückgabe:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```


Gibt den Zielort für einen Bewegungs-Effekt der Animation an (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```


Beschreibt den relativen Versatzwert für die Animation (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Rückgabe:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```


Beschreibt den relativen Versatzwert für die Animation (in Prozent). Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```


Beschreibt das Rotationszentrum, das verwendet wird, um einen Bewegungspfad um X Winkel zu drehen. Lesen/Schreiben android.graphics.PointF.

**Rückgabe:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```


Beschreibt das Rotationszentrum, das verwendet wird, um einen Bewegungspfad um X Winkel zu drehen. Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. das Folienlayout oder das übergeordnete Element. Lesen/Schreiben [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Rückgabe:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


Gibt an, worauf sich der Ursprung des Bewegungspfads bezieht, z. B. das Folienlayout oder das übergeordnete Element. Lesen/Schreiben [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


Gibt die Pfadprimitive gefolgt von Koordinaten für die Animationsbewegung an. Lesen/Schreiben [IMotionPath](../../com.aspose.slides/imotionpath).

**Rückgabe:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


Gibt die Pfadprimitive gefolgt von Koordinaten für die Animationsbewegung an. Lesen/Schreiben [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


Gibt an, wie sich der Bewegungspfad bewegt, wenn das Objekt verschoben wird. Lesen/Schreiben [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Rückgabe:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


Gibt an, wie sich der Bewegungspfad bewegt, wenn das Objekt verschoben wird. Lesen/Schreiben [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


Beschreibt den relativen Winkel des Bewegungspfads. Lesen/Schreiben float.

**Rückgabe:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


Beschreibt den relativen Winkel des Bewegungspfads. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |