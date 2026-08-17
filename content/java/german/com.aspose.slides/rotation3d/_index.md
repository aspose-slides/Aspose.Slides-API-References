---
title: Rotation3D
second_title: Aspose.Slides für die Java-API-Referenz
description: Stellt die 3D-Drehung eines Diagramms dar.
type: docs
url: /de/com.aspose.slides/rotation3d/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Stellt die 3D-Drehung eines Diagramms dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRotationX()](#getRotationX--) | Gibt den Rotationswinkel um die X-Achse zurück oder legt ihn fest, d. h. |
| [setRotationX(byte value)](#setRotationX-byte-) | Gibt den Rotationswinkel um die X-Achse zurück oder legt ihn fest, d. h. |
| [getRotationY()](#getRotationY--) | Gibt den Rotationswinkel um die Y-Achse zurück oder legt ihn fest, d. h. |
| [setRotationY(int value)](#setRotationY-int-) | Gibt den Rotationswinkel um die Y-Achse zurück oder legt ihn fest, d. h. |
| [getPerspective()](#getPerspective--) | Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder legt ihn fest (zwischen 0 und 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder legt ihn fest (zwischen 0 und 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch dargestellt zu werden. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch dargestellt zu werden. |
| [getDepthPercents()](#getDepthPercents--) | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder legt sie fest (zwischen 20 % und 2000 %). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder legt sie fest (zwischen 20 % und 2000 %). |
| [getHeightPercents()](#getHeightPercents--) | Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 % und 500 %). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 % und 500 %). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Gibt den Rotationswinkel um die X-Achse zurück oder legt ihn fest, d. h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Element 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option „Y Rotation“ in PowerPoint 2007+. Lese-/Schreib-Byte.

**Rückgabe:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Gibt den Rotationswinkel um die X-Achse zurück oder legt ihn fest, d. h. in Y-Richtung für 3D-Diagramme (zwischen -90 und 90 Grad). Die Eigenschaft entspricht dem Element 21.2.2.157 rotX (X Rotation) in ECMA-376 und der Option „Y Rotation“ in PowerPoint 2007+. Lese-/Schreib-Byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Gibt den Rotationswinkel um die Y-Achse zurück oder legt ihn fest, d. h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Element 21.2.158 rotY (Y Rotation) in ECMA-376 und der Option „X Rotation“ in PowerPoint 2007+. Lese-/Schreib-Int.

**Rückgabe:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Gibt den Rotationswinkel um die Y-Achse zurück oder legt ihn fest, d. h. in X-Richtung für 3D-Diagramme (zwischen 0 und 360 Grad). Die Eigenschaft entspricht dem Element 21.2.158 rotY (Y Rotation) in ECMA-376 und der Option „X Rotation“ in PowerPoint 2007+. Lese-/Schreib-Int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder legt ihn fest (zwischen 0 und 240). Ignoriert, wenn der Wert der Eigenschaft RightAngleAxes true ist. Lese-/Schreib-Byte.

**Rückgabe:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Gibt den Perspektivwert (Blickwinkel) für 3D-Diagramme zurück oder legt ihn fest (zwischen 0 und 240). Ignoriert, wenn der Wert der Eigenschaft RightAngleAxes true ist. Lese-/Schreib-Byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch dargestellt zu werden. Mit anderen Worten, es wird bestimmt, ob die Winkel der Achsen unabhängig von Diagrammdrehung oder -neigung sind. Lese-/Schreib-Boolean.

**Rückgabe:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Bestimmt, ob die Diagrammachsen rechtwinklig sind, anstatt perspektivisch dargestellt zu werden. Mit anderen Worten, es wird bestimmt, ob die Winkel der Achsen unabhängig von Diagrammdrehung oder -neigung sind. Lese-/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder legt sie fest (zwischen 20 % und 2000 %). Lese-/Schreib-Int.

**Rückgabe:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Gibt die Tiefe eines 3D-Diagramms als Prozentsatz der Diagrammbreite zurück oder legt sie fest (zwischen 20 % und 2000 %). Lese-/Schreib-Int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 % und 500 %). Lese-/Schreib-Int.

**Rückgabe:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Legt die Höhe eines 3-D-Diagramms als Prozentsatz der Diagrammbreite fest (zwischen 5 % und 500 %). Lese-/Schreib-Int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject