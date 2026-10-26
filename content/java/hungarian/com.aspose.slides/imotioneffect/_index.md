---
title: IMotionEffect
second_title: Aspose.Slides Java API hivatkozás
description: A mozgási effektus viselkedését reprezentálja.
type: docs
url: /hu/com.aspose.slides/imotioneffect/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

A mozgás effektus viselkedését reprezentálja.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getFrom()](#getFrom--) | Meghatároz egy x/y koordinátát, ahonnan a animáció kezdődik (százalékban). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Meghatároz egy x/y koordinátát, ahonnan a animáció kezdődik (százalékban). |
| [getTo()](#getTo--) | Meghatározza a célhelyet egy animációs mozgáshoz (százalékban). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Meghatározza a célhelyet egy animációs mozgáshoz (százalékban). |
| [getBy()](#getBy--) | Leírja az animáció relatív eltolási értékét (százalékban). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Leírja az animáció relatív eltolási értékét (százalékban). |
| [getRotationCenter()](#getRotationCenter--) | Leírja a forgatás középpontját, amelyet egy X szöggel való útvonalforgatáshoz használnak. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Leírja a forgatás középpontját, amelyet egy X szöggel való útvonalforgatáshoz használnak. |
| [getOrigin()](#getOrigin--) | Meghatározza, hogy a mozgási útvonal eredete mire vonatkozik, például a dia elrendezésére vagy a szülőre. |
| [setOrigin(int value)](#setOrigin-int-) | Meghatározza, hogy a mozgási útvonal eredete mire vonatkozik, például a dia elrendezésére vagy a szülőre. |
| [getPath()](#getPath--) | Meghatározza az animációs mozgáshoz használt útvonal primitívet, amelyet koordináták követnek. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Meghatározza az animációs mozgáshoz használt útvonal primitívet, amelyet koordináták követnek. |
| [getPathEditMode()](#getPathEditMode--) | Meghatározza, hogyan mozog az útvonal, amikor az alakzat mozog. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Meghatározza, hogyan mozog az útvonal, amikor az alakzat mozog. |
| [getAngle()](#getAngle--) | Leírja a mozgási útvonal relatív szögét. |
| [setAngle(float value)](#setAngle-float-) | Leírja a mozgási útvonal relatív szögét. |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Meghatároz egy x/y koordinátát, ahonnan az animáció kezdődik (százalékban). Olvasás/írás java.awt.geom.Point2D.Float.

**Visszatérési érték:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Meghatároz egy x/y koordinátát, ahonnan az animáció kezdődik (százalékban). Olvasás/írás java.awt.geom.Point2D.Float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Meghatározza a célhelyet egy animációs mozgáshoz (százalékban). Olvasás/írás java.awt.geom.Point2D.Float.

**Visszatérési érték:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Meghatározza a célhelyet egy animációs mozgáshoz (százalékban). Olvasás/írás java.awt.geom.Point2D.Float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Leírja az animáció relatív eltolási értékét (százalékban). Olvasás/írás java.awt.geom.Point2D.Float.

**Visszatérési érték:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Leírja az animáció relatív eltolási értékét (százalékban). Olvasás/írás java.awt.geom.Point2D.Float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Leírja a forgatás középpontját, amelyet egy X szöggel való útvonalforgatáshoz használnak. Olvasás/írás java.awt.geom.Point2D.Float.

**Visszatérési érték:**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Leírja a forgatás középpontját, amelyet egy X szöggel való útvonalforgatáshoz használnak. Olvasás/írás java.awt.geom.Point2D.Float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Meghatározza, hogy a mozgási útvonal eredete mire vonatkozik, például a dia elrendezésére vagy a szülőre. Olvasás/írás [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Visszatérési érték:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Meghatározza, hogy a mozgási útvonal eredete mire vonatkozik, például a dia elrendezésére vagy a szülőre. Olvasás/írás [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Meghatározza az animációs mozgáshoz használt útvonal primitívet, amelyet koordináták követnek. Olvasás/írás [IMotionPath](../../com.aspose.slides/imotionpath).

**Visszatérési érték:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Meghatározza az animációs mozgáshoz használt útvonal primitívet, amelyet koordináták követnek. Olvasás/írás [IMotionPath](../../com.aspose.slides/imotionpath).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Meghatározza, hogyan mozog az útvonal, amikor az alakzat mozog. Olvasás/írás [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Visszatérési érték:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Meghatározza, hogyan mozog az útvonal, amikor az alakzat mozog. Olvasás/írás [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Leírja a mozgási útvonal relatív szögét. Olvasás/írás float.

**Visszatérési érték:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Leírja a mozgási útvonal relatív szögét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |