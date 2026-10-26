---
title: Backdrop3DScene
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 글로우 및 그림자와 같은 효과가 적용되는 평면을 정의하며, 이는 적용되는 형태와 관련됩니다.
type: docs
url: /ko/com.aspose.slides/backdrop3dscene/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

글로우 및 그림자와 같은 효과가 적용되는 평면을 정의하며, 이는 적용되는 형태와 관련됩니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | 정규 벡터를 반환하거나 설정합니다. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 정규 벡터를 반환하거나 설정합니다. |
| [getAnchorPoint()](#getAnchorPoint--) | 3D 공간의 점을 반환하거나 설정합니다. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3D 공간의 점을 반환하거나 설정합니다. |
| [getUpVector()](#getUpVector--) | 위쪽을 나타내는 벡터를 반환하거나 설정합니다. |
| [setUpVector(float[] value)](#setUpVector-float---) | 위쪽을 나타내는 벡터를 반환하거나 설정합니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

정규 벡터를 반환하거나 설정합니다. 보다 정확히 말하면, 이 속성은 배경 평면의 면에 수직인 벡터를 정의합니다. 벡터는 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

정규 벡터를 반환하거나 설정합니다. 보다 정확히 말하면, 이 속성은 배경 평면의 면에 수직인 벡터를 정의합니다. 벡터는 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

3D 공간의 점을 반환하거나 설정합니다. 이 점은 배경 평면을 고정하는 공간상의 점입니다. 3D 점은 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

3D 공간의 점을 반환하거나 설정합니다. 이 점은 배경 평면을 고정하는 공간상의 점입니다. 3D 점은 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

위쪽을 나타내는 벡터를 반환하거나 설정합니다. 보다 정확히 말하면, 이 속성은 배경 평면의 면에 대한 위쪽을 나타내는 벡터를 정의합니다. 벡터는 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**반환:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

위쪽을 나타내는 벡터를 반환하거나 설정합니다. 보다 정확히 말하면, 이 속성은 배경 평면의 면에 대한 위쪽을 나타내는 벡터를 정의합니다. 벡터는 X, Y, Z 좌표를 정의하는 3개의 float 값 배열로 표현됩니다. 읽기/쓰기 float[].

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float[] |  |