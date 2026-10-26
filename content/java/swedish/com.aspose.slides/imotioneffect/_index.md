---
title: IMotionEffect
second_title: Aspose.Slides för Java API-referens
description: Representerar rörelseeffektens beteende.
type: docs
url: /sv/com.aspose.slides/imotioneffect/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Representerar rörelseeffektsbeteendet för effekten.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFrom()](#getFrom--) | Anger en x/y-koordinat för att starta animationen från (i procent). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Anger en x/y-koordinat för att starta animationen från (i procent). |
| [getTo()](#getTo--) | Anger målpositionen för en animationsrörelseeffekt (i procent). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Anger målpositionen för en animationsrörelseeffekt (i procent). |
| [getBy()](#getBy--) | Beskriver det relativa förskjutningsvärdet för animationen (i procent). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Beskriver det relativa förskjutningsvärdet för animationen (i procent). |
| [getRotationCenter()](#getRotationCenter--) | Beskriver rotationscentrum som används för att rotera en rörelsebana med X vinkel. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Beskriver rotationscentrum som används för att rotera en rörelsebana med X vinkel. |
| [getOrigin()](#getOrigin--) | Anger vad ursprunget för rörelsebanan är relativt till, t.ex. bildens layout eller föräldern. |
| [setOrigin(int value)](#setOrigin-int-) | Anger vad ursprunget för rörelsebanan är relativt till, t.ex. bildens layout eller föräldern. |
| [getPath()](#getPath--) | Anger bana-primitive följt av koordinater för animationsrörelsen. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Anger bana-primitive följt av koordinater för animationsrörelsen. |
| [getPathEditMode()](#getPathEditMode--) | Anger hur rörelsebanan rör sig när formen flyttas. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Anger hur rörelsebanan rör sig när formen flyttas. |
| [getAngle()](#getAngle--) | Beskriver den relativa vinkeln för rörelsebanan. |
| [setAngle(float value)](#setAngle-float-) | Beskriver den relativa vinkeln för rörelsebanan. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Anger en x/y-koordinat för att starta animationen från (i procent). Läs/skriv java.awt.geom.Point2D.Float.

**Returnerar:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Anger en x/y-koordinat för att starta animationen från (i procent). Läs/skriv java.awt.geom.Point2D.Float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Anger målpositionen för en animationsrörelseeffekt (i procent). Läs/skriv java.awt.geom.Point2D.Float.

**Returnerar:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Anger målpositionen för en animationsrörelseeffekt (i procent). Läs/skriv java.awt.geom.Point2D.Float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Beskriver det relativa förskjutningsvärdet för animationen (i procent). Läs/skriv java.awt.geom.Point2D.Float.

**Returnerar:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Beskriver det relativa förskjutningsvärdet för animationen (i procent). Läs/skriv java.awt.geom.Point2D.Float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Beskriver rotationscentrum som används för att rotera en rörelsebana med X vinkel. Läs/skriv java.awt.geom.Point2D.Float.

**Returnerar:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Beskriver rotationscentrum som används för att rotera en rörelsebana med X vinkel. Läs/skriv java.awt.geom.Point2D.Float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Anger vad ursprunget för rörelsebanan är relativt till, t.ex. bildens layout eller föräldern. Läs/skriv [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Returnerar:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Anger vad ursprunget för rörelsebanan är relativt till, t.ex. bildens layout eller föräldern. Läs/skriv [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Anger bana-primitive följt av koordinater för animationsrörelsen. Läs/skriv [IMotionPath](../../com.aspose.slides/imotionpath).

**Returnerar:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Anger bana-primitive följt av koordinater för animationsrörelsen. Läs/skriv [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Anger hur rörelsebanan rör sig när formen flyttas. Läs/skriv [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Returnerar:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Anger hur rörelsebanan rör sig när formen flyttas. Läs/skriv [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Beskriver den relativa vinkeln för rörelsebanan. Läs/skriv float.

**Returnerar:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Beskriver den relativa vinkeln för rörelsebanan. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |