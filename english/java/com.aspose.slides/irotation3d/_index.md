---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: Represents 3D rotation of a chart.
type: docs
weight: 1000
url: /java/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Represents 3D rotation of a chart.
## Methods

| Method | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees). |
| [setRotationX(byte value)](#setRotationX-byte-) | Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees). |
| [getRotationY()](#getRotationY--) | Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees). |
| [setRotationY(int value)](#setRotationY-int-) | Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees). |
| [getPerspective()](#getPerspective--) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determines whether the chart axes are at right angles, rather than drawn in perspective. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determines whether the chart axes are at right angles, rather than drawn in perspective. |
| [getDepthPercents()](#getDepthPercents--) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). |
| [getHeightPercents()](#getHeightPercents--) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```


Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees). The property matches with the 21.2.2.157 rotX (X Rotation) item in ECMA-376 and with the "Y Rotation" option in PowerPoint 2007+. Read/write byte.

**Returns:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```


Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees). The property matches with the 21.2.2.157 rotX (X Rotation) item in ECMA-376 and with the "Y Rotation" option in PowerPoint 2007+. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```


Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees). The property matches with the 21.2.2.158 rotY (Y Rotation) item in ECMA-376 and with the "X Rotation" option in PowerPoint 2007+. Read/write int.

**Returns:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```


Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees). The property matches with the 21.2.2.158 rotY (Y Rotation) item in ECMA-376 and with the "X Rotation" option in PowerPoint 2007+. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```


Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100). Ignored if RightAngleAxes property value is true. Read/write byte.

**Returns:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```


Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100). Ignored if RightAngleAxes property value is true. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```


Determines whether the chart axes are at right angles, rather than drawn in perspective. In other words it determines whether the chart angles of axes are independent from chart rotation or elevation. Read/write boolean.

**Returns:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```


Determines whether the chart axes are at right angles, rather than drawn in perspective. In other words it determines whether the chart angles of axes are independent from chart rotation or elevation. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```


Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). Read/write int.

**Returns:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```


Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```


Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). Read/write int.

**Returns:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```


Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

