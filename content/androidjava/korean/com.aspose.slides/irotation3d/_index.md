---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Represents 3D rotation of a chart.
type: docs
url: /ko/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

차트의 3D 회전을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRotationX()](#getRotationX--) | X축을 중심으로 회전 각도를 반환하거나 설정합니다(즉). |
| [setRotationX(byte value)](#setRotationX-byte-) | X축을 중심으로 회전 각도를 반환하거나 설정합니다(즉). |
| [getRotationY()](#getRotationY--) | Y축을 중심으로 회전 각도를 반환하거나 설정합니다(즉). |
| [setRotationY(int value)](#setRotationY-int-) | Y축을 중심으로 회전 각도를 반환하거나 설정합니다(즉). |
| [getPerspective()](#getPerspective--) | 3D 차트의 원근값(시야각)을 반환하거나 설정합니다(0에서 100 사이). |
| [setPerspective(byte value)](#setPerspective-byte-) | 3D 차트의 원근값(시야각)을 반환하거나 설정합니다(0에서 100 사이). |
| [getRightAngleAxes()](#getRightAngleAxes--) | 차트 축이 원근으로 그려지는 것이 아니라 직각으로 배치되는지 여부를 결정합니다. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | 차트 축이 원근으로 그려지는 것이 아니라 직각으로 배치되는지 여부를 결정합니다. |
| [getDepthPercents()](#getDepthPercents--) | 차트 너비에 대한 백분율로 3D 차트의 깊이를 반환하거나 설정합니다(20‒2000%). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 차트 너비에 대한 백분율로 3D 차트의 깊이를 반환하거나 설정합니다(20‒2000%). |
| [getHeightPercents()](#getHeightPercents--) | 차트 너비에 대한 백분율로 3-D 차트의 높이를 지정합니다(5‒500%). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 차트 너비에 대한 백분율로 3-D 차트의 높이를 지정합니다(5‒500%). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

X축을 중심으로 회전 각도를 반환하거나 설정합니다(즉, 3D 차트에서 Y 방향, -90도에서 90도 사이). 이 속성은 ECMA-376의 21.2.2.157 rotX (X Rotation) 항목 및 PowerPoint 2007+의 “Y Rotation” 옵션과 일치합니다. 읽기/쓰기 byte.

**반환:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

X축을 중심으로 회전 각도를 반환하거나 설정합니다(즉, 3D 차트에서 Y 방향, -90도에서 90도 사이). 이 속성은 ECMA-376의 21.2.2.157 rotX (X Rotation) 항목 및 PowerPoint 2007+의 “Y Rotation” 옵션과 일치합니다. 읽기/쓰기 byte.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Y축을 중심으로 회전 각도를 반환하거나 설정합니다(즉, 3D 차트에서 X 방향, 0‒360도 사이). 이 속성은 ECMA-376의 21.2.2.158 rotY (Y Rotation) 항목 및 PowerPoint 2007+의 “X Rotation” 옵션과 일치합니다. 읽기/쓰기 int.

**반환:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Y축을 중심으로 회전 각도를 반환하거나 설정합니다(즉, 3D 차트에서 X 방향, 0‒360도 사이). 이 속성은 ECMA-376의 21.2.2.158 rotY (Y Rotation) 항목 및 PowerPoint 2007+의 “X Rotation” 옵션과 일치합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

3D 차트의 원근값(시야각)을 반환하거나 설정합니다(0‒100 사이). RightAngleAxes 속성 값이 true이면 무시됩니다. 읽기/쓰기 byte.

**반환:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

3D 차트의 원근값(시야각)을 반환하거나 설정합니다(0‒100 사이). RightAngleAxes 속성 값이 true이면 무시됩니다. 읽기/쓰기 byte.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

차트 축이 원근으로 그려지는 것이 아니라 직각으로 배치되는지 여부를 결정합니다. 다시 말해 차트 축의 각도가 차트 회전이나 고도와 독립적인지 판단합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

차트 축이 원근으로 그려지는 것이 아니라 직각으로 배치되는지 여부를 결정합니다. 다시 말해 차트 축의 각도가 차트 회전이나 고도와 독립적인지 판단합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

차트 너비에 대한 백분율로 3D 차트의 깊이를 반환하거나 설정합니다(20‒2000%). 읽기/쓰기 int.

**반환:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

차트 너비에 대한 백분율로 3D 차트의 깊이를 반환하거나 설정합니다(20‒2000%). 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

차트 너비에 대한 백분율로 3-D 차트의 높이를 지정합니다(5‒500%). 읽기/쓰기 int.

**반환:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

차트 너비에 대한 백분율로 3-D 차트의 높이를 지정합니다(5‒500%). 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |