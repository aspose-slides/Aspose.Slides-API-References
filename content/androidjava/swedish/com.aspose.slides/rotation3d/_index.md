---
title: Rotation3D
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar 3D-rotation av ett diagram.
type: docs
url: /sv/com.aspose.slides/rotation3d/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Representerar 3D-rotation av ett diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRotationX()](#getRotationX--) | Returnerar eller anger rotationsgraden kring X-axeln, d.v.s. |
| [setRotationX(byte value)](#setRotationX-byte-) | Returnerar eller anger rotationsgraden kring X-axeln, d.v.s. |
| [getRotationY()](#getRotationY--) | Returnerar eller anger rotationsgraden kring Y-axeln, d.v.s. |
| [setRotationY(int value)](#setRotationY-int-) | Returnerar eller anger rotationsgraden kring Y-axeln, d.v.s. |
| [getPerspective()](#getPerspective--) | Returnerar eller anger perspektivvärdet (synfältvinkel) för 3D-diagram (mellan 0 och 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Returnerar eller anger perspektivvärdet (synfältvinkel) för 3D-diagram (mellan 0 och 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Bestämmer om diagramaxlarna är i räta vinklar snarare än ritade i perspektiv. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Bestämmer om diagramaxlarna är i räta vinklar snarare än ritade i perspektiv. |
| [getDepthPercents()](#getDepthPercents--) | Returnerar eller anger djupet på ett 3D-diagram som en procentandel av diagrambredden (mellan 20 och 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Returnerar eller anger djupet på ett 3D-diagram som en procentandel av diagrambredden (mellan 20 och 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Anger höjden på ett 3-D-diagram som en procentandel av diagrambredden (mellan 5 och 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Anger höjden på ett 3-D-diagram som en procentandel av diagrambredden (mellan 5 och 500 procent). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Returnerar eller anger rotationsgraden kring X-axeln, d.v.s. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egendomen matchar 21.2.2.157 rotX (X Rotation)-objektet i ECMA-376 och "Y Rotation"-alternativet i PowerPoint 2007+. Läs/skriv byte.

**Returnerar:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Returnerar eller anger rotationsgraden kring X-axeln, d.v.s. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egendomen matchar 21.2.2.157 rotX (X Rotation)-objektet i ECMA-376 och "Y Rotation"-alternativet i PowerPoint 2007+. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Returnerar eller anger rotationsgraden kring Y-axeln, d.v.s. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egendomen matchar 21.2.2.158 rotY (Y Rotation)-objektet i ECMA-376 och "X Rotation"-alternativet i PowerPoint 2007+. Läs/skriv int.

**Returnerar:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Returnerar eller anger rotationsgraden kring Y-axeln, d.v.s. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egendomen matchar 21.2.2.158 rotY (Y Rotation)-objektet i ECMA-376 och "X Rotation"-alternativet i PowerPoint 2007+. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Returnerar eller anger perspektivvärdet (synfältvinkel) för 3D-diagram (mellan 0 och 240). Ignoreras om RightAngleAxes-egenskapens värde är true. Läs/skriv byte.

**Returnerar:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Returnerar eller anger perspektivvärdet (synfältvinkel) för 3D-diagram (mellan 0 och 240). Ignoreras om RightAngleAxes-egenskapens värde är true. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Bestämmer om diagramaxlarna är i räta vinklar snarare än ritade i perspektiv. Med andra ord avgör den om diagramaxlarnas vinklar är oberoende av diagramrotation eller höjd. Läs/skriv boolean.

**Returnerar:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Bestämmer om diagramaxlarna är i räta vinklar snarare än ritade i perspektiv. Med andra ord avgör den om diagramaxlarnas vinklar är oberoende av diagramrotation eller höjd. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Returnerar eller anger djupet på ett 3D-diagram som en procentandel av diagrambredden (mellan 20 och 2000 procent). Läs/skriv int.

**Returnerar:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Returnerar eller anger djupet på ett 3D-diagram som en procentandel av diagrambredden (mellan 20 och 2000 procent). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Anger höjden på ett 3-D-diagram som en procentandel av diagrambredden (mellan 5 och 500 procent). Läs/skriv int.

**Returnerar:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Anger höjden på ett 3-D-diagram som en procentandel av diagrambredden (mellan 5 och 500 procent). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Endast läsbar IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject