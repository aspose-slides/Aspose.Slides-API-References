---
title: Rotation3D
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图表的 3D 旋转。
type: docs
url: /zh/com.aspose.slides/rotation3d/
---
**继承:**  
java.lang.Object

**所有已实现的接口:**  
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject  
```
public class Rotation3D implements IRotation3D, IDOMObject
```

表示图表的 3D 旋转。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRotationX()](#getRotationX--) | 返回或设置绕 X 轴的旋转度，即 |
| [setRotationX(byte value)](#setRotationX-byte-) | 返回或设置绕 X 轴的旋转度，即 |
| [getRotationY()](#getRotationY--) | 返回或设置绕 Y 轴的旋转度，即 |
| [setRotationY(int value)](#setRotationY-int-) | 返回或设置绕 Y 轴的旋转度，即 |
| [getPerspective()](#getPerspective--) | 返回或设置 3D 图表的透视值（视场角）（范围 0 到 240）。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 返回或设置 3D 图表的透视值（视场角）（范围 0 到 240）。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | 确定图表坐标轴是否为直角，而不是透视绘制。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | 确定图表坐标轴是否为直角，而不是透视绘制。 |
| [getDepthPercents()](#getDepthPercents--) | 返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围 20% 到 2000%）。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围 20% 到 2000%）。 |
| [getHeightPercents()](#getHeightPercents--) | 指定 3-D 图表的高度，以图表宽度的百分比表示（范围 5% 到 500%）。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 指定 3-D 图表的高度，以图表宽度的百分比表示（范围 5% 到 500%）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

返回或设置绕 X 轴的旋转度，即 3D 图表在 Y 方向的旋转（范围 -90° 到 90°）。该属性对应 ECMA-376 中的 21.2.2.157 rotX（X Rotation）项以及 PowerPoint 2007+ 中的 “Y Rotation” 选项。读/写 byte。

**返回：**  
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

返回或设置绕 X 轴的旋转度，即 3D 图表在 Y 方向的旋转（范围 -90° 到 90°）。该属性对应 ECMA-376 中的 21.2.2.157 rotX（X Rotation）项以及 PowerPoint 2007+ 中的 “Y Rotation” 选项。读/写 byte。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

返回或设置绕 Y 轴的旋转度，即 3D 图表在 X 方向的旋转（范围 0° 到 360°）。该属性对应 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）项以及 PowerPoint 2007+ 中的 “X Rotation” 选项。读/写 int。

**返回：**  
int

### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

返回或设置绕 Y 轴的旋转度，即 3D 图表在 X 方向的旋转（范围 0° 到 360°）。该属性对应 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）项以及 PowerPoint 2007+ 中的 “X Rotation” 选项。读/写 int。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

返回或设置 3D 图表的透视值（视场角）（范围 0 到 240）。如果 RightAngleAxes 属性值为 true，则此属性被忽略。读/写 byte。

**返回：**  
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

返回或设置 3D 图表的透视值（视场角）（范围 0 到 240）。如果 RightAngleAxes 属性值为 true，则此属性被忽略。读/写 byte。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

确定图表坐标轴是否为直角，而不是透视绘制。换言之，它确定坐标轴的角度是否独立于图表的旋转或仰角。读/写 boolean。

**返回：**  
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

确定图表坐标轴是否为直角，而不是透视绘制。换言之，它确定坐标轴的角度是否独立于图表的旋转或仰角。读/写 boolean。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围 20% 到 2000%）。读/写 int。

**返回：**  
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

返回或设置 3D 图表的深度，以图表宽度的百分比表示（范围 20% 到 2000%）。读/写 int。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

指定 3-D 图表的高度，以图表宽度的百分比表示（范围 5% 到 500%）。读/写 int。

**返回：**  
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

指定 3-D 图表的高度，以图表宽度的百分比表示（范围 5% 到 500%）。读/写 int。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**  
com.aspose.slides.IDOMObject