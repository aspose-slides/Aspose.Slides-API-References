---
title: Rotation3D
second_title: Aspose.Slides Androidra a Java API hivatkozás
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
| [getRotationX()](#getRotationX--) | Returns or sets the rotation degree around the X-axis, i.e. |
| [setRotationX(byte value)](#setRotationX-byte-) | Returns or sets the rotation degree around the X-axis, i.e. |
| [getRotationY()](#getRotationY--) | Returns or sets the rotation degree around the Y-axis, i.e. |
| [setRotationY(int value)](#setRotationY-int-) | Returns or sets the rotation degree around the Y-axis, i.e. |
| [getPerspective()](#getPerspective--) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determines whether the chart axes are at right angles, rather than drawn in perspective. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determines whether the chart axes are at right angles, rather than drawn in perspective. |
| [getDepthPercents()](#getDepthPercents--) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). |
| [getHeightPercents()](#getHeightPercents--) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Visszatér vagy beállítja a forgási fokot az X tengely körül, vagyis a Y irányban 3D diagramok esetén (-90 és 90 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.157 rotX (X Rotation) elemnek és a PowerPoint 2007+ "Y Rotation" beállításnak. Olvasás/írás byte.

**Visszatér:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Visszatér vagy beállítja a forgási fokot az X tengely körül, vagyis a Y irányban 3D diagramok esetén (-90 és 90 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.157 rotX (X Rotation) elemnek és a PowerPoint 2007+ "Y Rotation" beállításnak. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Visszatér vagy beállítja a forgási fokot a Y tengely körül, vagyis az X irányban 3D diagramok esetén (0 és 360 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.158 rotY (Y Rotation) elemnek és a PowerPoint 2007+ "X Rotation" beállításnak. Olvasás/írás int.

**Visszatér:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Visszatér vagy beállítja a forgási fokot a Y tengely körül, vagyis az X irányban 3D diagramok esetén (0 és 360 fok között). A tulajdonság megfelel az ECMA-376 21.2.2.158 rotY (Y Rotation) elemnek és a PowerPoint 2007+ "X Rotation" beállításnak. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Visszatér vagy beállítja a perspektíva értékét (látószög) 3D diagramokhoz (0 és 240 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke true. Olvasás/írás byte.

**Visszatér:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Visszatér vagy beállítja a perspektíva értékét (látószög) 3D diagramokhoz (0 és 240 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke true. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Meghatározza, hogy a diagram tengelyei derékszögben vannak-e, a perspektívában rajzoltak helyett. Más szóval meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgásától vagy magasságától. Olvasás/írás boolean.

**Visszatér:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Meghatározza, hogy a diagram tengelyei derékszögben vannak-e, a perspektívában rajzoltak helyett. Más szóval meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgásától vagy magasságától. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Visszatér vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). Olvasás/írás int.

**Visszatér:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Visszatér vagy beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Megadja egy 3D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). Olvasás/írás int.

**Visszatér:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Megadja egy 3D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject