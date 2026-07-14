---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API 참조
description: 효과(예: 글로우와 그림자)가 적용되는 평면을 정의하며, 이는 적용 대상 모양과의 관계를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

플레인은 효과(예: 글로우와 그림자)가 적용되는 평면을 정의하며, 이는 적용 대상 모양과의 관계를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | 정규 벡터를 반환하거나 설정합니다. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 정규 벡터를 반환하거나 설정합니다. |
| [getAnchorPoint()](#getAnchorPoint--) | 3D 공간의 점을 반환하거나 설정합니다. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3D 공간의 점을 반환하거나 설정합니다. |
| [getUpVector()](#getUpVector--) | 위쪽을 나타내는 벡터를 반환하거나 설정합니다. |
| [setUpVector(float[] value)](#setUpVector-float---) | 위쪽을 나타내는 벡터를 반환하거나 설정합니다. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

정규 벡터를 반환하거나 설정합니다. 더 정확히 말하면, 이 속성은 백드롭 평면의 면에 수직인 벡터를 정의합니다. 벡터는 X, Y 및 Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환값:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

정규 벡터를 반환하거나 설정합니다. 더 정확히 말하면, 이 속성은 백드롭 평면의 면에 수직인 벡터를 정의합니다. 벡터는 X, Y 및 Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

3D 공간의 점을 반환하거나 설정합니다. 이 점은 백드롭 평면을 고정하는 공간상의 점입니다. 3D 점은 X, Y 및 Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환값:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

3D 공간의 점을 반환하거나 설정합니다. 이 점은 백드롭 평면을 고정하는 공간상의 점입니다. 3D 점은 X, Y 및 Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

위쪽을 나타내는 벡터를 반환하거나 설정합니다. 더 정확히 말하면, 이 속성은 백드롭 평면의 면에 대해 위쪽을 나타내는 벡터를 정의합니다. 벡터는 X, Y 및 Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환값:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

위쪽을 나타내는 벡터를 반환하거나 설정합니다. 더 정확히 말하면, 이 속성은 백드롭 평면의 면에 대해 위쪽을 나타내는 벡터를 정의합니다. 벡터는 X, Y 및 Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float[] |  |