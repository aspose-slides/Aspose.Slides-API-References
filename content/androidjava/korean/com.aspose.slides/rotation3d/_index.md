---
title: Rotation3D
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 차트의 3D 회전을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/rotation3d/
---
**Inheritance:**  
상속:  
java.lang.Object  

**All Implemented Interfaces:**  
구현된 모든 인터페이스:  
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject  
```
public class Rotation3D implements IRotation3D, IDOMObject
```

차트의 3D 회전을 나타냅니다.  

## Methods

| Method | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | X축을 중심으로 회전 각도를 반환하거나 설정합니다(즉). |
| [setRotationX(byte value)](#setRotationX-byte-) | X축을 중심으로 회전 각도를 반환하거나 설정합니다(즉). |
| [getRotationY()](#getRotationY--) | Y축을 중심으로 회전 각도를 반환하거나 설정합니다(즉). |
| [setRotationY(int value)](#setRotationY-int-) | Y축을 중심으로 회전 각도를 반환하거나 설정합니다(즉). |
| [getPerspective()](#getPerspective--) | 3D 차트의 원근값(시야각)을 반환하거나 설정합니다(0~240 사이). |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D 차트의 원근값(시야각)을 반환하거나 설정합니다(0~240 사이). |
| [getRightAngleAxes()](#getRightAngleAxes--) | 차트 축이 원근으로 그려지는 것이 아니라 직각으로 배치되는지를 결정합니다. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | 차트 축이 원근으로 그려지는 것이 아니라 직각으로 배치되는지를 결정합니다. |
| [getDepthPercents()](#getDepthPercents--) | 차트 너비의 백분율로 3D 차트의 깊이를 반환하거나 설정합니다(20~2000%). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 차트 너비의 백분율로 3D 차트의 깊이를 반환하거나 설정합니다(20~2000%). |
| [getHeightPercents()](#getHeightPercents--) | 차트 너비의 백분율로 3-D 차트의 높이를 지정합니다(5~500%). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 차트 너비의 백분율로 3-D 차트의 높이를 지정합니다(5~500%). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

X축을 중심으로 회전 각도를 반환하거나 설정합니다(즉, 3D 차트의 Y 방향, -90~90도). 이 속성은 ECMA-376의 21.2.2.157 rotX (X Rotation) 항목 및 PowerPoint 2007+의 "Y Rotation" 옵션과 일치합니다. 읽기/쓰기 byte.

**Returns:**  
byte  

### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

X축을 중심으로 회전 각도를 반환하거나 설정합니다(즉, 3D 차트의 Y 방향, -90~90도). 이 속성은 ECMA-376의 21.2.2.157 rotX (X Rotation) 항목 및 PowerPoint 2007+의 "Y Rotation" 옵션과 일치합니다. 읽기/쓰기 byte.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Y축을 중심으로 회전 각도를 반환하거나 설정합니다(즉, 3D 차트의 X 방향, 0~360도). 이 속성은 ECMA-376의 21.2.2.158 rotY (Y Rotation) 항목 및 PowerPoint 2007+의 "X Rotation" 옵션과 일치합니다. 읽기/쓰기 int.

**Returns:**  
int  

### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Y축을 중심으로 회전 각도를 반환하거나 설정합니다(즉, 3D 차트의 X 방향, 0~360도). 이 속성은 ECMA-376의 21.2.2.158 rotY (Y Rotation) 항목 및 PowerPoint 2007+의 "X Rotation" 옵션과 일치합니다. 읽기/쓰기 int.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

3D 차트의 원근값(시야각)을 반환하거나 설정합니다(0~240 사이). RightAngleAxes 속성값이 true인 경우 무시됩니다. 읽기/쓰기 byte.

**Returns:**  
byte  

### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

3D 차트의 원근값(시야각)을 반환하거나 설정합니다(0~240 사이). RightAngleAxes 속성값이 true인 경우 무시됩니다. 읽기/쓰기 byte.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

차트 축이 원근으로 그려지는 것이 아니라 직각으로 배치되는지를 결정합니다. 즉, 차트 축의 각도가 차트 회전 또는 고도와 독립적인지를 나타냅니다. 읽기/쓰기 boolean.

**Returns:**  
boolean  

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

차트 축이 원근으로 그려지는 것이 아니라 직각으로 배치되는지를 결정합니다. 즉, 차트 축의 각도가 차트 회전 또는 고도와 독립적인지를 나타냅니다. 읽기/쓰기 boolean.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

차트 너비의 백분율로 3D 차트의 깊이를 반환하거나 설정합니다(20~2000%). 읽기/쓰기 int.

**Returns:**  
int  

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

차트 너비의 백분율로 3D 차트의 깊이를 반환하거나 설정합니다(20~2000%). 읽기/쓰기 int.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

차트 너비의 백분율로 3-D 차트의 높이를 지정합니다(5~500%). 읽기/쓰기 int.

**Returns:**  
int  

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

차트 너비의 백분율로 3-D 차트의 높이를 지정합니다(5~500%). 읽기/쓰기 int.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject