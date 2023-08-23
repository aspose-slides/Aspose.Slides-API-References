---
title: Rotation3D
second_title: Aspose.Slides for Java API Reference
description: Represents 3D rotation of a chart.
type: docs
url: /com.aspose.slides/rotation3d/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Represents 3D rotation of a chart.
## Methods

| Method | Description |
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


Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees). The property matches with the 21.2.2.157 rotX (X Rotation) item in ECMA-376 and with the "Y Rotation" option in PowerPoint 2007+. Read/write byte.

**Returns:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```


Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees). The property matches with the 21.2.2.157 rotX (X Rotation) item in ECMA-376 and with the "Y Rotation" option in PowerPoint 2007+. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```


Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees). The property matches with the 21.2.2.158 rotY (Y Rotation) item in ECMA-376 and with the "X Rotation" option in PowerPoint 2007+. Read/write int.

**Returns:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```


Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees). The property matches with the 21.2.2.158 rotY (Y Rotation) item in ECMA-376 and with the "X Rotation" option in PowerPoint 2007+. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```


Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 240). Ignored if RightAngleAxes property value is true. Read/write byte.

**Returns:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```


Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 240). Ignored if RightAngleAxes property value is true. Read/write byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```


Determines whether the chart axes are at right angles, rather than drawn in perspective. In other words it determines whether the chart angles of axes are independent from chart rotation or elevation. Read/write boolean.

**Returns:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```


Determines whether the chart axes are at right angles, rather than drawn in perspective. In other words it determines whether the chart angles of axes are independent from chart rotation or elevation. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```


Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). Read/write int.

**Returns:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```


Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```


Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). Read/write int.

**Returns:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```


Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
