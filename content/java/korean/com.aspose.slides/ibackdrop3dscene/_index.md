---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /ko/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

배경 평면은 광선 및 그림자와 같은 효과가 적용되는 도형과의 관계에서 적용되는 평면을 정의합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


법선 벡터를 반환하거나 설정합니다. 보다 정확히 말하면, 이 속성은 배경 평면의 면에 수직인 벡터를 정의합니다. 벡터는 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


법선 벡터를 반환하거나 설정합니다. 보다 정확히 말하면, 이 속성은 배경 평면의 면에 수직인 벡터를 정의합니다. 벡터는 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


3차원 공간의 점을 반환하거나 설정합니다. 이 점은 배경 평면을 고정하는 공간상의 점입니다. 3D 점은 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


3차원 공간의 점을 반환하거나 설정합니다. 이 점은 배경 평면을 고정하는 공간상의 점입니다. 3D 점은 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


위 방향을 나타내는 벡터를 반환하거나 설정합니다. 보다 정확히 말하면, 이 속성은 배경 평면의 면에 대한 위 방향을 나타내는 벡터를 정의합니다. 벡터는 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


위 방향을 나타내는 벡터를 반환하거나 설정합니다. 보다 정확히 말하면, 이 속성은 배경 평면의 면에 대한 위 방향을 나타내는 벡터를 정의합니다. 벡터는 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float[] |  |