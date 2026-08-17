---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: 表示图表的 3D 旋转。
type: docs
url: /zh/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

表示图表的 3D 旋转。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRotationX()](#getRotationX--) | 返回或设置绕 X 轴的旋转角度，即 |
| [setRotationX(byte value)](#setRotationX-byte-) | 返回或设置绕 X 轴的旋转角度，即 |
| [getRotationY()](#getRotationY--) | 返回或设置绕 Y 轴的旋转角度，即 |
| [setRotationY(int value)](#setRotationY-int-) | 返回或设置绕 Y 轴的旋转角度，即 |
| [getPerspective()](#getPerspective--) | 返回或设置 3D 图表的透视值（视场角），范围在 0 到 100 之间。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 返回或设置 3D 图表的透视值（视场角），范围在 0 到 100 之间。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | 确定图表坐标轴是否为直角，而不是透视绘制。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | 确定图表坐标轴是否为直角，而不是透视绘制。 |
| [getDepthPercents()](#getDepthPercents--) | 返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围 20% 到 2000%）。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围 20% 到 2000%）。 |
| [getHeightPercents()](#getHeightPercents--) | 指定 3D 图表的高度，以图表宽度的百分比表示（范围 5% 到 500%）。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 指定 3D 图表的高度，以图表宽度的百分比表示（范围 5% 到 500%）。 |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

返回或设置绕 X 轴的旋转角度，即 3D 图表的 Y 方向（范围 -90 到 90 度）。该属性对应 ECMA-376 中的 21.2.2.157 rotX（X Rotation）项，以及 PowerPoint 2007+ 中的 “Y Rotation” 选项。读/写 byte。

**返回:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

返回或设置绕 X 轴的旋转角度，即 3D 图表的 Y 方向（范围 -90 到 90 度）。该属性对应 ECMA-376 中的 21.2.2.157 rotX（X Rotation）项，以及 PowerPoint 2007+ 中的 “Y Rotation” 选项。读/写 byte。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

返回或设置绕 Y 轴的旋转角度，即 3D 图表的 X 方向（范围 0 到 360 度）。该属性对应 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）项，以及 PowerPoint 2007+ 中的 “X Rotation” 选项。读/写 int。

**返回:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

返回或设置绕 Y 轴的旋转角度，即 3D 图表的 X 方向（范围 0 到 360 度）。该属性对应 ECMA-376 中的 21.2.158 rotY（Y Rotation）项，以及 PowerPoint 2007+ 中的 “X Rotation” 选项。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

返回或设置 3D 图表的透视值（视场角），范围在 0 到 100 之间。如果 RightAngleAxes 属性值为 true，则此设置被忽略。读/写 byte。

**返回:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

返回或设置 3D 图表的透视值（视场角），范围在 0 到 100 之间。如果 RightAngleAxes 属性值为 true，则此设置被忽略。读/写 byte。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

确定图表坐标轴是否为直角，而不是透视绘制。换句话说，它决定坐标轴的角度是否独立于图表的旋转或倾斜。读/写 boolean。

**返回:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

确定图表坐标轴是否为直角，而不是透视绘制。换句话说，它决定坐标轴的角度是否独立于图表的旋转或倾斜。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围 20% 到 2000%）。读/写 int。

**返回:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围 20% 到 2000%）。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

指定 3D 图表的高度，以图表宽度的百分比表示（范围 5% 到 500%）。读/写 int。

**返回:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

指定 3D 图表的高度，以图表宽度的百分比表示（范围 5% 到 500%）。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |