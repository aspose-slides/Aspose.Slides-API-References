---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar 3D-rotation av ett diagram.
type: docs
url: /sv/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Representerar 3D-rotation av ett diagram.
## Metoder

| Method | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | Returnerar eller anger rotationsgraden kring X-axeln, d.v.s. |
| [setRotationX(byte value)](#setRotationX-byte-) | Returnerar eller anger rotationsgraden kring X-axeln, d.v.s. |
| [getRotationY()](#getRotationY--) | Returnerar eller anger rotationsgraden kring Y-axeln, d.v.s. |
| [setRotationY(int value)](#setRotationY-int-) | Returnerar eller anger rotationsgraden kring Y-axeln, d.v.s. |
| [getPerspective()](#getPerspective--) | Returnerar eller anger perspektivvärdet (fältvinkeln) för 3D-diagram (mellan 0 och 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Returnerar eller anger perspektivvärdet (fältvinkeln) för 3D-diagram (mellan 0 och 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Bestämmer om diagrammets axlar är i räta vinklar, snarare än ritade i perspektiv. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Bestämmer om diagrammets axlar är i räta vinklar, snarare än ritade i perspektiv. |
| [getDepthPercents()](#getDepthPercents--) | Returnerar eller anger djupet på ett 3D-diagram som procent av diagrammets bredd (mellan 20 och 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Returnerar eller anger djupet på ett 3D-diagram som procent av diagrammets bredd (mellan 20 och 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Anger höjden på ett 3-D-diagram som procent av diagrammets bredd (mellan 5 och 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Anger höjden på ett 3-D-diagram som procent av diagrammets bredd (mellan 5 och 500 procent). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Returnerar eller anger rotationsgraden kring X-axeln, d.v.s. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egenskapen matchar 21.2.2.157 rotX (X Rotation) i ECMA-376 och med "Y Rotation"-alternativet i PowerPoint 2007+. Läs/skriv byte.

**Returnerar:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Returnerar eller anger rotationsgraden kring X-axeln, d.v.s. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egenskapen matchar 21.2.157 rotX (X Rotation) i ECMA-376 och med "Y Rotation"-alternativet i PowerPoint 2007+. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Returnerar eller anger rotationsgraden kring Y-axeln, d.v.s. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egenskapen matchar 21.2.2.158 rotY (Y Rotation) i ECMA-376 och med "X Rotation"-alternativet i PowerPoint 2007+. Läs/skriv int.

**Returnerar:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Returnerar eller anger rotationsgraden kring Y-axeln, d.v.s. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egenskapen matchar 21.2.2.158 rotY (Y Rotation) i ECMA-376 och med "X Rotation"-alternativet i PowerPoint 2007+. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Returnerar eller anger perspektivvärdet (fältvinkeln) för 3D-diagram (mellan 0 och 100). Ignoreras om RightAngleAxes-egenskapens värde är true. Läs/skriv byte.

**Returnerar:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Returnerar eller anger perspektivvärdet (fältvinkeln) för 3D-diagram (mellan 0 och 100). Ignoreras om RightAngleAxes-egenskapens värde är true. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Bestämmer om diagrammets axlar är i räta vinklar, snarare än ritade i perspektiv. Med andra ord avgör den om diagrammets axelvinklar är oberoende av diagramrotation eller höjd. Läs/skriv boolean.

**Returnerar:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Bestämmer om diagrammets axlar är i räta vinklar, snarare än ritade i perspektiv. Med andra ord avgör den om diagrammets axelvinklar är oberoende av diagramrotation eller höjd. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Returnerar eller anger djupet på ett 3D-diagram som procent av diagrammets bredd (mellan 20 och 2000 procent). Läs/skriv int.

**Returnerar:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Returnerar eller anger djupet på ett 3D-diagram som procent av diagrammets bredd (mellan 20 och 2000 procent). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Anger höjden på ett 3-D-diagram som procent av diagrammets bredd (mellan 5 och 500 procent). Läs/skriv int.

**Returnerar:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Anger höjden på ett 3-D-diagram som procent av diagrammets bredd (mellan 5 och 500 procent). Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |