---
title: IMotionEffect
second_title: Aspose.Slides Android-hoz a Java API hivatkozás alapján
description: A hatás mozgási effektusának viselkedését képviseli.
type: docs
url: /hu/com.aspose.slides/imotioneffect/
---
**Összes megvalósított interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

A hatás mozgási effektus viselkedését képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFrom()](#getFrom--) | Megad egy x/y koordinátát, ahonnan a animáció indul (százalékban). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Megad egy x/y koordinátát, ahonnan a animáció indul (százalékban). |
| [getTo()](#getTo--) | Megadja a célhelyet egy animációs mozgási effektushoz (százalékban). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Megadja a célhelyet egy animációs mozgási effektushoz (százalékban). |
| [getBy()](#getBy--) | Leírja a relatív eltolás értékét az animációhoz (százalékban). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Leírja a relatív eltolás értékét az animációhoz (százalékban). |
| [getRotationCenter()](#getRotationCenter--) | Leírja a forgási középpontot, amelyet a mozgási út X szöggel történő forgatásához használnak. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Leírja a forgási középpontot, amelyet a mozgási út X szöggel történő forgatásához használnak. |
| [getOrigin()](#getOrigin--) | Megadja, hogy a mozgási út kiindulópontja mire vonatkozik, például a dia elrendezésére vagy a szülőre. |
| [setOrigin(int value)](#setOrigin-int-) | Megadja, hogy a mozgási út kiindulópontja mire vonatkozik, például a dia elrendezésére vagy a szülőre. |
| [getPath()](#getPath--) | Megadja a út primitív elemet, amelyet koordináták követnek az animációs mozgáshoz. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Megadja a út primitív elemet, amelyet koordináták követnek az animációs mozgáshoz. |
| [getPathEditMode()](#getPathEditMode--) | Megadja, hogyan mozog a mozgási út, amikor az alakzatot áthelyezik. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Megadja, hogyan mozog a mozgási út, amikor az alakzatot áthelyezik. |
| [getAngle()](#getAngle--) | Leírja a mozgási út relatív szögét. |
| [setAngle(float value)](#setAngle-float-) | Leírja a mozgási út relatív szögét. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Megad egy x/y koordinátát, ahonnan a animáció indul (százalékban). Olvasás/írás android.graphics.PointF.

**Visszatérési érték:**  
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Megad egy x/y koordinátát, ahonnan a animáció indul (százalékban). Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Megadja a célhelyet egy animációs mozgási effektushoz (százalékban). Olvasás/írás android.graphics.PointF.

**Visszatérési érték:**  
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Megadja a célhelyet egy animációs mozgási effektushoz (százalékban). Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Leírja a relatív eltolás értékét az animációhoz (százalékban). Olvasás/írás android.graphics.PointF.

**Visszatérési érték:**  
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Leírja a relatív eltolás értékét az animációhoz (százalékban). Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Leírja a forgási középpontot, amelyet a mozgási út X szöggel történő forgatásához használnak. Olvasás/írás android.graphics.PointF.

**Visszatérési érték:**  
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Leírja a forgási középpontot, amelyet a mozgási út X szöggel történő forgatásához használnak. Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Megadja, hogy a mozgási út kiindulópontja mire vonatkozik, például a dia elrendezésére vagy a szülőre. Olvasás/írás [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Visszatérési érték:**  
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Megadja, hogy a mozgási út kiindulópontja mire vonatkozik, például a dia elrendezésére vagy a szülőre. Olvasás/írás [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Megadja a út primitív elemet, amelyet koordináták követnek az animációs mozgáshoz. Olvasás/írás [IMotionPath](../../com.aspose.slides/imotionpath).

**Visszatérési érték:**  
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Megadja a út primitív elemet, amelyet koordináták követnek az animációs mozgáshoz. Olvasás/írás [IMotionPath](../../com.aspose.slides/imotionpath).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Megadja, hogyan mozog a mozgási út, amikor az alakzatot áthelyezik. Olvasás/írás [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Visszatérési érték:**  
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Megadja, hogyan mozog a mozgási út, amikor az alakzatot áthelyezik. Olvasás/írás [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Leírja a mozgási út relatív szögét. Olvasás/írás float.

**Visszatérési érték:**  
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Leírja a mozgási út relatív szögét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |