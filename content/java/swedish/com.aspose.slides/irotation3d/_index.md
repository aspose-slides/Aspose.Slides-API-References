---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: Represents 3D rotation of a chart.
type: docs
url: /sv/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Representerar 3D-rotation av ett diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRotationX()](#getRotationX--) | Returnerar eller ställer in rotationsgraden runt X-axeln, d.v.s. |
| [setRotationX(byte value)](#setRotationX-byte-) | Returnerar eller ställer in rotationsgraden runt X-axeln, d.v.s. |
| [getRotationY()](#getRotationY--) | Returnerar eller ställer in rotationsgraden runt Y-axeln, d.v.s. |
| [setRotationY(int value)](#setRotationY-int-) | Returnerar eller ställer in rotationsgraden runt Y-axeln, d.v.s. |
| [getPerspective()](#getPerspective--) | Returnerar eller ställer in perspektivvärdet (fältvinkel) för 3D-diagram (mellan 0 och 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Returnerar eller ställer in perspektivvärdet (fältvinkel) för 3D-diagram (mellan 0 och 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Avgör om diagrammets axlar är i räta vinklar istället för att ritas i perspektiv. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Avgör om diagrammets axlar är i räta vinklar istället för att ritas i perspektiv. |
| [getDepthPercents()](#getDepthPercents--) | Returnerar eller ställer in djupet på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 20 och 2000 procent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Returnerar eller ställer in djupet på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 20 och 2000 procent). |
| [getHeightPercents()](#getHeightPercents--) | Anger höjden på ett 3-D-diagram som en procentandel av diagrammets bredd (mellan 5 och 500 procent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Anger höjden på ett 3-D-diagram som en procentandel av diagrammets bredd (mellan 5 och 500 procent). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```


Returnerar eller ställer in rotationsgraden runt X-axeln, d.v.s. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egendomen matchar med 21.2.2.157 rotX (X Rotation) posten i ECMA-376 och med alternativet "Y Rotation" i PowerPoint 2007+. Läsa/skriva byte.

**Returnerar:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```


Returnerar eller ställer in rotationsgraden runt X-axeln, d.v.s. i Y-riktning för 3D-diagram (mellan -90 och 90 grader). Egendomen matchar med 21.2.157 rotX (X Rotation) posten i ECMA-376 och med alternativet "Y Rotation" i PowerPoint 2007+. Läsa/skriva byte.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```


Returnerar eller ställer in rotationsgraden runt Y-axeln, d.v.s. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egendomen matchar med 21.2.2.158 rotY (Y Rotation) posten i ECMA-376 och med alternativet "X Rotation" i PowerPoint 2007+. Läsa/skriva int.

**Returnerar:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```


Returnerar eller ställer in rotationsgraden runt Y-axeln, d.v.s. i X-riktning för 3D-diagram (mellan 0 och 360 grader). Egendomen matchar med 21.2.2.158 rotY (Y Rotation) posten i ECMA-376 och med alternativet "X Rotation" i PowerPoint 2007+. Läsa/skriva int.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```


Returnerar eller ställer in perspektivvärdet (fältvinkel) för 3D-diagram (mellan 0 och 100). Ignoreras om RightAngleAxes-egendomens värde är true. Läsa/skriva byte.

**Returnerar:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```


Returnerar eller ställer in perspektivvärdet (fältvinkel) för 3D-diagram (mellan 0 och 100). Ignoreras om RightAngleAxes-egendomens värde är true. Läsa/skriva byte.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```


Avgör om diagrammets axlar är i räta vinklar istället för att ritas i perspektiv. Med andra ord avgör den om diagrammets axelvinklar är oberoende av diagramrotation eller elevation. Läsa/skriva boolean.

**Returnerar:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```


Avgör om diagrammets axlar är i räta vinklar istället för att ritas i perspektiv. Med andra ord avgör den om diagrammets axelvinklar är oberoende av diagramrotation eller elevation. Läsa/skriva boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```


Returnerar eller ställer in djupet på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 20 och 2000 procent). Läsa/skriva int.

**Returnerar:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```


Returnerar eller ställer in djupet på ett 3D-diagram som en procentandel av diagrammets bredd (mellan 20 och 2000 procent). Läsa/skriva int.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```


Anger höjden på ett 3-D-diagram som en procentandel av diagrammets bredd (mellan 5 och 500 procent). Läsa/skriva int.

**Returnerar:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```


Anger höjden på ett 3-D-diagram som en procentandel av diagrammets bredd (mellan 5 och 500 procent). Läsa/skriva int.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |