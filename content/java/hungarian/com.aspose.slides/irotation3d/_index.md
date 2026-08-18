---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: Represents 3D rotation of a chart.
type: docs
url: /hu/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

A diagram 3D forgatásának ábrázolása.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRotationX()](#getRotationX--) | Visszaadja vagy beállítja a forgatási fokot az X tengely körül, azaz |
| [setRotationX(byte value)](#setRotationX-byte-) | Visszaadja vagy beállítja a forgatási fokot az X tengely körül, azaz |
| [getRotationY()](#getRotationY--) | Visszaadja vagy beállítja a forgatási fokot az Y tengely körül, azaz |
| [setRotationY(int value)](#setRotationY-int-) | Visszaadja vagy beállítja a forgatási fokot az Y tengely körül, azaz |
| [getPerspective()](#getPerspective--) | Visszaadja vagy beállítja a perspektíva értékét (látómező szöge) 3D diagramokhoz (0 és 100 között). |
| [setPerspective(byte value)](#setPerspective-byte-) | Visszaadja vagy beállítja a perspektíva értékét (látómező szöge) 3D diagramokhoz (0 és 100 között). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Meghatározza, hogy a diagram tengelyei derékszögűek-e, vagy perspektívában vannak-e. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Meghatározza, hogy a diagram tengelyei derékszögűek-e, vagy perspektívában vannak-e. |
| [getDepthPercents()](#getDepthPercents--) | Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). |
| [getHeightPercents()](#getHeightPercents--) | Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```


Visszaadja vagy beállítja a forgatási fokot az X tengely körül, azaz a Y irányban 3D diagramoknál (-90 és 90 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.157 rotX (X Rotation) elemnek, valamint a PowerPoint 2007+ „Y Rotation” beállításának. Olvasás/írás byte.

**Visszatér:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```


Visszaadja vagy beállítja a forgatási fokot az X tengely körül, azaz a Y irányban 3D diagramoknál (-90 és 90 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.157 rotX (X Rotation) elemnek, valamint a PowerPoint 2007+ „Y Rotation” beállításának. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```


Visszaadja vagy beállítja a forgatási fokot az Y tengely körül, azaz az X irányban 3D diagramoknál (0 és 360 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.158 rotY (Y Rotation) elemnek, valamint a PowerPoint 2007+ „X Rotation” beállításának. Olvasás/írás int.

**Visszatér:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```


Visszaadja vagy beállítja a forgatási fokot az Y tengely körül, azaz az X irányban 3D diagramoknál (0 és 360 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.158 rotY (Y Rotation) elemnek, valamint a PowerPoint 2007+ „X Rotation” beállításának. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```


Visszaadja vagy beállítja a perspektíva értékét (látómező szöge) 3D diagramokhoz (0 és 100 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke true. Olvasás/írás byte.

**Visszatér:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```


Visszaadja vagy beállítja a perspektíva értékét (látómező szöge) 3D diagramokhoz (0 és 100 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke true. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```


Meghatározza, hogy a diagram tengelyei derékszögűek-e, vagy perspektívában vannak-e. Más szóval, meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgatásától vagy emelésétől. Olvasás/írás boolean.

**Visszatér:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```


Meghatározza, hogy a diagram tengelyei derékszögűek-e, vagy perspektívában vannak-e. Más szóval, meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgatásától vagy emelésétől. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```


Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). Olvasás/írás int.

**Visszatér:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```


Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```


Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). Olvasás/írás int.

**Visszatér:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```


Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |