---
title: IMotionEffect
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar beteendet för en rörelseeffekt.
type: docs
url: /sv/com.aspose.slides/imotioneffect/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Representerar rörelseeffektens beteende.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFrom()](#getFrom--) | Anger en x/y-koordinat att starta animationen från (i procent). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Anger en x/y-koordinat att starta animationen från (i procent). |
| [getTo()](#getTo--) | Anger målplatsen för en animationsrörelseeffekt (i procent). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Anger målplatsen för en animationsrörelseeffekt (i procent). |
| [getBy()](#getBy--) | Beskriver det relativa offsetvärdet för animationen (i procent). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Beskriver det relativa offsetvärdet för animationen (i procent). |
| [getRotationCenter()](#getRotationCenter--) | Beskriver rotationscentrum som används för att rotera en rörelsespår med X vinkel. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Beskriver rotationscentrum som används för att rotera en rörelsespår med X vinkel. |
| [getOrigin()](#getOrigin--) | Anger vad ursprunget för rörelsespåret är relativt till, till exempel bildens layout eller föräldern. |
| [setOrigin(int value)](#setOrigin-int-) | Anger vad ursprunget för rörelsespåret är relativt till, till exempel bildens layout eller föräldern. |
| [getPath()](#getPath--) | Anger sökvägsprimitive följt av koordinater för animationsrörelsen. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Anger sökvägsprimitive följt av koordinater för animationsrörelsen. |
| [getPathEditMode()](#getPathEditMode--) | Anger hur rörelsespåret rör sig när formen flyttas. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Anger hur rörelsespåret rör sig när formen flyttas. |
| [getAngle()](#getAngle--) | Beskriver den relativa vinkeln för rörelsespåret. |
| [setAngle(float value)](#setAngle-float-) | Beskriver den relativa vinkeln för rörelsespåret. |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Anger en x/y-koordinat att starta animationen från (i procent). Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Anger en x/y-koordinat att starta animationen från (i procent). Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Anger målplatsen för en animationsrörelseeffekt (i procent). Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Anger målplatsen för en animationsrörelseeffekt (i procent). Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Beskriver det relativa offsetvärdet för animationen (i procent). Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Beskriver det relativa offsetvärdet för animationen (i procent). Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Beskriver rotationscentrum som används för att rotera en rörelsespår med X vinkel. Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Beskriver rotationscentrum som används för att rotera en rörelsespår med X vinkel. Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Anger vad ursprunget för rörelsespåret är relativt till, till exempel bildens layout eller föräldern. Läs/skriv [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Returnerar:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Anger vad ursprunget för rörelsespåret är relativt till, till exempel bildens layout eller föräldern. Läs/skriv [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Anger sökvägsprimitive följt av koordinater för animationsrörelsen. Läs/skriv [IMotionPath](../../com.aspose.slides/imotionpath).

**Returnerar:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Anger sökvägsprimitive följt av koordinater för animationsrörelsen. Läs/skriv [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Anger hur rörelsespåret rör sig när formen flyttas. Läs/skriv [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Returnerar:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Anger hur rörelsespåret rör sig när formen flyttas. Läs/skriv [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Beskriver den relativa vinkeln för rörelsespåret. Läs/skriv float.

**Returnerar:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Beskriver den relativa vinkeln för rörelsespåret. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |