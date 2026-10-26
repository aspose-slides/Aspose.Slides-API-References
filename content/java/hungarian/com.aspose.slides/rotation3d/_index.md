---
title: Rotation3D
second_title: Aspose.Slides for Java API Referenciája
description: A diagram 3D forgását reprezentálja.
type: docs
url: /hu/com.aspose.slides/rotation3d/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

A diagram 3D forgását reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRotationX()](#getRotationX--) | Visszaadja vagy beállítja a forgatási fokot az X-tengely körül, azaz |
| [setRotationX(byte value)](#setRotationX-byte-) | Visszaadja vagy beállítja a forgatási fokot az X-tengely körül, azaz |
| [getRotationY()](#getRotationY--) | Visszaadja vagy beállítja a forgatási fokot az Y-tengely körül, azaz |
| [setRotationY(int value)](#setRotationY-int-) | Visszaadja vagy beállítja a forgatási fokot az Y-tengely körül, azaz |
| [getPerspective()](#getPerspective--) | Visszaadja vagy beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 240 között). |
| [setPerspective(byte value)](#setPerspective-byte-) | Visszaadja vagy beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 240 között). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Meghatározza, hogy a diagram tengelyei derékszögek-e, vagy perspektívában vannak-e rajzolva. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Meghatározza, hogy a diagram tengelyei derékszögek-e, vagy perspektívában vannak-e rajzolva. |
| [getDepthPercents()](#getDepthPercents--) | Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). |
| [getHeightPercents()](#getHeightPercents--) | Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Visszaadja vagy beállítja a forgatási fokot az X-tengely körül, azaz a Y irányban 3D diagramoknál (-90 és 90 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.157 rotX (X Rotation) elemnek és a PowerPoint 2007+ „Y Rotation” beállításának. **Olvasás/írás byte.**

**Visszatér:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Visszaadja vagy beállítja a forgatási fokot az X-tengely körül, azaz a Y irányban 3D diagramoknál (-90 és 90 fok között). A tulajdonság megfelel az ECMA-376 21.2.157 rotX (X Rotation) elemnek és a PowerPoint 2007+ „Y Rotation” beállításának. **Olvasás/írás byte.**

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Visszaadja vagy beállítja a forgatási fokot az Y-tengely körül, azaz az X irányban 3D diagramoknál (0 és 360 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.158 rotY (Y Rotation) elemnek és a PowerPoint 2007+ „X Rotation” beállításának. **Olvasás/írás int.**

**Visszatér:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Visszaadja vagy beállítja a forgatási fokot az Y-tengely körül, azaz az X irányban 3D diagramoknál (0 és 360 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.158 rotY (Y Rotation) elemnek és a PowerPoint 2007+ „X Rotation” beállításának. **Olvasás/írás int.**

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Visszaadja vagy beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 240 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke igaz. **Olvasás/írás byte.**

**Visszatér:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Visszaadja vagy beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 240 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke igaz. **Olvasás/írás byte.**

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Meghatározza, hogy a diagram tengelyei derékszögek-e, vagy perspektívában vannak-e rajzolva. Más szóval meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgatásától vagy emelkedésétől. **Olvasás/írás boolean.**

**Visszatér:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Meghatározza, hogy a diagram tengelyei derékszögek-e, vagy perspektívában vannak-e rajzolva. Más szóval meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgatásától vagy emelkedésétől. **Olvasás/írás boolean.**

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). **Olvasás/írás int.**

**Visszatér:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). **Olvasás/írás int.**

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). **Olvasás/írás int.**

**Visszatér:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). **Olvasás/írás int.**

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. **Csak olvasható IDOMObject.**

**Visszatér:**
com.aspose.slides.IDOMObject