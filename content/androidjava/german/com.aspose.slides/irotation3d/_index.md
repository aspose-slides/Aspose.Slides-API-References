---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
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
| [getRotationX()](#getRotationX--) | Gibt den Drehwinkel um die X-Achse zurück oder setzt ihn, d. h. |
| [setRotationX(byte value)](#setRotationX-byte-) | Gibt den Drehwinkel um die X-Achse zurück oder setzt ihn, d. h. |
| [getRotationY()](#getRotationY--) | Gibt den Drehwinkel um die Y-Achse zurück oder setzt ihn, d. h. |
| [setRotationY(int value)](#setRotationY-int-) | Gibt den Drehwinkel um die Y-Achse zurück oder setzt ihn, d. h. |
| [getPerspective()](#getPerspective--) | Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt in Perspektive gezeichnet zu werden. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt in Perspektive gezeichnet zu werden. |
| [getDepthPercents()](#getDepthPercents--) | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). |
| [getHeightPercents()](#getHeightPercents--) | Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 und 500 Prozent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 und 500 Prozent). |

### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Gibt den Drehwinkel um die X-Achse zurück oder setzt ihn, d. h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Element 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option „Y Rotation“ in PowerPoint 2007+. Lesen/Schreiben byte.

**Returns:**
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Gibt den Drehwinkel um die X-Achse zurück oder setzt ihn, d. h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Element 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option „Y Rotation“ in PowerPoint 2007+. Lesen/Schreiben byte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Gibt den Drehwinkel um die Y-Achse zurück oder setzt ihn, d. h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Element 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option „X Rotation“ in PowerPoint 2007+. Lesen/Schreiben int.

**Returns:**
int

### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Gibt den Drehwinkel um die Y-Achse zurück oder setzt ihn, d. h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Element 21.2.2.158 rotY (Y Rotation) in ECMA-376 und der Option „X Rotation“ in PowerPoint 2007+. Lesen/Schreiben int.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). Ignoriert, wenn der Wert der RightAngleAxes-Eigenschaft true ist. Lesen/Schreiben byte.

**Returns:**
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder setzt ihn (zwischen 0 und 100). Ignoriert, wenn der Wert der RightAngleAxes-Eigenschaft true ist. Lesen/Schreiben byte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt in Perspektive gezeichnet zu werden. Anders ausgedrückt bestimmt es, ob die Winkel der Diagrammachsen unabhängig von Diagrammdrehung oder -elevation sind. Lesen/Schreiben boolean.

**Returns:**
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt in Perspektive gezeichnet zu werden. Anders ausgedrückt bestimmt es, ob die Winkel der Diagrammachsen unabhängig von Diagrammdrehung oder -elevation sind. Lesen/Schreiben boolean.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). Lesen/Schreiben int.

**Returns:**
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder setzt sie (zwischen 20 und 2000 Prozent). Lesen/Schreiben int.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 und 500 Prozent). Lesen/Schreiben int.

**Returns:**
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 und 500 Prozent). Lesen/Schreiben int.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |