---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Képviseli a diagram 3D forgatását.
type: docs
url: /hu/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Képviseli a diagram 3D forgatását.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRotationX()](#getRotationX--) | Visszaadja vagy beállítja a forgatási fokot az X-tengely körül, azaz |
| [setRotationX(byte value)](#setRotationX-byte-) | Visszaadja vagy beállítja a forgatási fokot az X-tengely körül, azaz |
| [getRotationY()](#getRotationY--) | Visszaadja vagy beállítja a forgatási fokot a Y-tengely körül, azaz |
| [setRotationY(int value)](#setRotationY-int-) | Visszaadja vagy beállítja a forgatási fokot a Y-tengely körül, azaz |
| [getPerspective()](#getPerspective--) | Visszaadja vagy beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 100 között). |
| [setPerspective(byte value)](#setPerspective-byte-) | Visszaadja vagy beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 100 között). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Meghatározza, hogy a diagram tengelyei derékszögekben legyenek-e, a perspektívában rajzoltak helyett. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Meghatározza, hogy a diagram tengelyei derékszögekben legyenek-e, a perspektívában rajzoltak helyett. |
| [getDepthPercents()](#getDepthPercents--) | Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). |
| [getHeightPercents()](#getHeightPercents--) | Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Megadja egy 3-D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Visszaadja vagy beállítja a forgatási fokot az X-tengely körül, azaz az Y irányban 3D diagramoknál (-90 és 90 fok között). A tulajdonság megfelel a 21.2.2.157 rotX (X Rotation) elemnek az ECMA-376-ban és a PowerPoint 2007+ “Y Rotation” opciójának. Olvasás/írás byte.

**Visszatérési érték:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Visszaadja vagy beállítja a forgatási fokot az X-tengely körül, azaz az Y irányban 3D diagramoknál (-90 és 90 fok között). A tulajdonság megfelel a 21.2.2.157 rotX (X Rotation) elemnek az ECMA-376-ban és a PowerPoint 2007+ “Y Rotation” opciójának. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Visszaadja vagy beállítja a forgatási fokot a Y-tengely körül, azaz az X irányban 3D diagramoknál (0 és 360 fok között). A tulajdonság megfelel a 21.2.2.158 rotY (Y Rotation) elemnek az ECMA-376-ban és a PowerPoint 2007+ “X Rotation” opciójának. Olvasás/írás int.

**Visszatérési érték:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Visszaadja vagy beállítja a forgatási fokot a Y-tengely körül, azaz az X irányban 3D diagramoknál (0 és 360 fok között). A tulajdonság megfelel a 21.2.2.158 rotY (Y Rotation) elemnek az ECMA-376-ban és a PowerPoint 2007+ “X Rotation” opciójának. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Visszaadja vagy beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 100 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke igaz. Olvasás/írás byte.

**Visszatérési érték:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Visszaadja vagy beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 100 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke igaz. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Meghatározza, hogy a diagram tengelyei derékszögekben legyenek-e, a perspektívában rajzoltak helyett. Más szóval meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgatásától vagy emelkedésétől. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Meghatározza, hogy a diagram tengelyei derékszögekben legyenek-e, a perspektívában rajzoltak helyett. Más szóval meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgatásától vagy emelkedésétől. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Visszaadja vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). Olvasás/írás int.

**Visszatérési érték:**
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

**Visszatérési érték:**
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