---
title: MotionEffect
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar beteendet för rörelseeffekten.
type: docs
url: /sv/com.aspose.slides/motioneffect/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Representerar rörelseeffektens beteende.

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFrom()](#getFrom--) | Anger en x/y-koordinat för att starta animationen från (i procent). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Anger en x/y-koordinat för att starta animationen från (i procent). |
| [getTo()](#getTo--) | Anger målplatsen för en rörelseeffekt (i procent). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Anger målplatsen för en rörelseeffekt (i procent). |
| [getBy()](#getBy--) | Beskriver det relativa förskjutningsvärdet för animationen (i procent). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Beskriver det relativa förskjutningsvärdet för animationen (i procent). |
| [getRotationCenter()](#getRotationCenter--) | Beskriver rotationscentrum som används för att rotera en rörelsebana med X vinkel. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Beskriver rotationscentrum som används för att rotera en rörelsebana med X vinkel. |
| [getOrigin()](#getOrigin--) | Anger vad ursprunget för rörelsebana är relativt till exempel layouten på bilden eller föräldern. |
| [setOrigin(int value)](#setOrigin-int-) | Anger vad ursprunget för rörelsebana är relativt till exempel layouten på bilden eller föräldern. |
| [getPath()](#getPath--) | Anger banprimitive följd av koordinater för animationsrörelsen. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Anger banprimitive följd av koordinater för animationsrörelsen. |
| [getPathEditMode()](#getPathEditMode--) | Anger hur rörelsebana rör sig när formen flyttas. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Anger hur rörelsebana rör sig när formen flyttas. |
| [getAngle()](#getAngle--) | Beskriver den relativa vinkeln för rörelsebana. |
| [setAngle(float value)](#setAngle-float-) | Beskriver den relativa vinkeln för rörelsebana. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

Anger en x/y-koordinat för att starta animationen från (i procent). Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

Anger en x/y-koordinat för att starta animationen från (i procent). Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

Anger målplatsen för en rörelseeffekt (i procent). Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

Anger målplatsen för en rörelseeffekt (i procent). Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

Beskriver det relativa förskjutningsvärdet för animationen (i procent). Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

Beskriver det relativa förskjutningsvärdet för animationen (i procent). Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

Beskriver rotationscentrum som används för att rotera en rörelsebana med X vinkel. Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

Beskriver rotationscentrum som används för att rotera en rörelsebana med X vinkel. Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Anger vad ursprunget för rörelsebana är relativt till exempel layouten på bilden eller föräldern. Läs/skriv [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Returnerar:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Anger vad ursprunget för rörelsebana är relativt till exempel layouten på bilden eller föräldern. Läs/skriv [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

Anger banprimitive följd av koordinater för animationsrörelsen. Läs/skriv [IMotionPath](../../com.aspose.slides/imotionpath).

**Returnerar:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

Anger banprimitive följd av koordinater för animationsrörelsen. Läs/skriv [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

Anger hur rörelsebana rör sig när formen flyttas. Läs/skriv [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Returnerar:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Anger hur rörelsebana rör sig när formen flyttas. Läs/skriv [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Beskriver den relativa vinkeln för rörelsebana. Läs/skriv float.

**Returnerar:**
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Beskriver den relativa vinkeln för rörelsebana. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |