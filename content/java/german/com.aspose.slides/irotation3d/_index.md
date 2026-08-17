---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: Stellt die 3D-Drehung eines Diagramms dar.
type: docs
url: /de/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Stellt die 3D-Drehung eines Diagramms dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRotationX()](#getRotationX--) | Gibt den Rotationsgrad um die X-Achse zurück oder setzt ihn, d. h. |
| [setRotationX(byte value)](#setRotationX-byte-) | Gibt den Rotationsgrad um die X-Achse zurück oder setzt ihn, d. h. |
| [getRotationY()](#getRotationY--) | Gibt den Rotationsgrad um die Y-Achse zurück oder setzt ihn, d. h. |
| [setRotationY(int value)](#setRotationY-int-) | Gibt den Rotationsgrad um die Y-Achse zurück oder setzt ihn, d. h. |
| [getPerspective()](#getPerspective--) | Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Ermittelt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch dargestellt zu werden. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Ermittelt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch dargestellt zu werden. |
| [getDepthPercents()](#getDepthPercents--) | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). |
| [getHeightPercents()](#getHeightPercents--) | Gibt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite an (zwischen 5 und 500 Prozent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Gibt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite an (zwischen 5 und 500 Prozent). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Gibt den Rotationsgrad um die X-Achse zurück oder setzt ihn, d. h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Element 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option „Y Rotation“ in PowerPoint 2007+. Lesen/Schreiben Byte.

**Rückgabewert:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Gibt den Rotationsgrad um die X-Achse zurück oder setzt ihn, d. h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Element 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option „Y Rotation“ in PowerPoint 2007+. Lesen/Schreiben Byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Gibt den Rotationsgrad um die Y-Achse zurück oder setzt ihn, d. h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Element 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option „X Rotation“ in PowerPoint 2007+. Lesen/Schreiben int.

**Rückgabewert:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Gibt den Rotationsgrad um die Y-Achse zurück oder setzt ihn, d. h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Element 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option „X Rotation“ in PowerPoint 2007+. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). Wird ignoriert, wenn der Wert der Eigenschaft RightAngleAxes wahr ist. Lesen/Schreiben Byte.

**Rückgabewert:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). Wird ignoriert, wenn der Wert der Eigenschaft RightAngleAxes wahr ist. Lesen/Schreiben Byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Ermittelt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch dargestellt zu werden. Anders ausgedrückt bestimmt es, ob die Winkel der Diagrammachsen unabhängig von Diagrammdrehung oder -neigung sind. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Ermittelt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch dargestellt zu werden. Anders ausgedrückt bestimmt es, ob die Winkel der Diagrammachsen unabhängig von Diagrammdrehung oder -neigung sind. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). Lesen/Schreiben int.

**Rückgabewert:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Gibt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite an (zwischen 5 und 500 Prozent). Lesen/Schreiben int.

**Rückgabewert:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Gibt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite an (zwischen 5 und 500 Prozent). Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |