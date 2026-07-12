---
title: MotionEffect
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A hatás mozgási effektus viselkedését ábrázolja.
type: docs
url: /hu/com.aspose.slides/motioneffect/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Minden megvalósított interfész:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Képviseli a mozgási effekt viselkedését.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFrom()](#getFrom--) | Megad egy x/y koordinátát, ahonnan a animáció indul (százalékban). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Megad egy x/y koordinátát, ahonnan a animáció indul (százalékban). |
| [getTo()](#getTo--) | Megadja a célhelyet egy animációs mozgási effekt számára (százalékban). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Megadja a célhelyet egy animációs mozgási effekt számára (százalékban). |
| [getBy()](#getBy--) | Leírja az animáció relatív eltolásértékét (százalékban). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Leírja az animáció relatív eltolásértékét (százalékban). |
| [getRotationCenter()](#getRotationCenter--) | Leírja a forgás középpontját, amelyet egy mozgási út X szöggel való elforgatásához használnak. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Leírja a forgás középpontját, amelyet egy mozgási út X szöggel való elforgatásához használnak. |
| [getOrigin()](#getOrigin--) | Megadja, hogy a mozgási út kiindulópontja mire vonatkozik, például a dia elrendezésére vagy a szülőre. |
| [setOrigin(int value)](#setOrigin-int-) | Megadja, hogy a mozgási út kiindulópontja mire vonatkozik, például a dia elrendezésére vagy a szülőre. |
| [getPath()](#getPath--) | Megadja az út primitívjét, amelyet koordináták követnek az animációs mozgáshoz. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Megadja az út primitívjét, amelyet koordináták követnek az animációs mozgáshoz. |
| [getPathEditMode()](#getPathEditMode--) | Megadja, hogyan mozog a mozgási út, amikor az alakzat mozog. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Megadja, hogyan mozog a mozgási út, amikor az alakzat mozog. |
| [getAngle()](#getAngle--) | Leírja a mozgási út relatív szögét. |
| [setAngle(float value)](#setAngle-float-) | Leírja a mozgási út relatív szögét. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

Megad egy x/y koordinátát, ahonnan a animáció indul (százalékban). Olvasás/írás android.graphics.PointF.

**Visszatérési érték:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

Megad egy x/y koordinátát, ahonnan a animáció indul (százalékban). Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

Megadja a célhelyet egy animációs mozgási effekt számára (százalékban). Olvasás/írás android.graphics.PointF.

**Visszatérési érték:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

Megadja a célhelyet egy animációs mozgási effekt számára (százalékban). Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

Leírja az animáció relatív eltolásértékét (százalékban). Olvasás/írás android.graphics.PointF.

**Visszatérési érték:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

Leírja az animáció relatív eltolásértékét (százalékban). Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

Leírja a forgás középpontját, amelyet egy mozgási út X szöggel való elforgatásához használnak. Olvasás/írás android.graphics.PointF.

**Visszatérési érték:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

Leírja a forgás középpontját, amelyet egy mozgási út X szöggel való elforgatásához használnak. Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Megadja, hogy a mozgási út kiindulópontja mire vonatkozik, például a dia elrendezésére vagy a szülőre. Olvasás/írás [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Visszatérési érték:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Megadja, hogy a mozgási út kiindulópontja mire vonatkozik, például a dia elrendezésére vagy a szülőre. Olvasás/írás [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

Megadja az út primitívjét, amelyet koordináták követnek az animációs mozgáshoz. Olvasás/írás [IMotionPath](../../com.aspose.slides/imotionpath).

**Visszatérési érték:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

Megadja az út primitívjét, amelyet koordináták követnek az animációs mozgáshoz. Olvasás/írás [IMotionPath](../../com.aspose.slides/imotionpath).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

Megadja, hogyan mozog a mozgási út, amikor az alakzat mozog. Olvasás/írás [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Visszatérési érték:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Megadja, hogyan mozog a mozgási út, amikor az alakzat mozog. Olvasás/írás [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Leírja a mozgási út relatív szögét. Olvasás/írás float.

**Visszatérési érték:**
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Leírja a mozgási út relatív szögét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |