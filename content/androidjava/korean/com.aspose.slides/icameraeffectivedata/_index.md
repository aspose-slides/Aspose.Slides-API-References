---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /ko/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

효과적인 카메라 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCameraType()](#getCameraType--) | 카메라 유형. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 카메라 FOV(0-180도, 시야). |
| [getZoom()](#getZoom--) | 카메라 줌(백분율로 나타낸 양수 값). |
| [getRotation()](#getRotation--) | 회전은 위도 좌표와 경도 좌표, 그리고 위도와 경도 좌표를 축으로 하는 회전을 사용하여 정의됩니다. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Camera type. 읽기 전용 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**반환:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV(0-180도, 시야). 읽기 전용 float.

**반환:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera 줌(백분율로 나타낸 양수 값). 읽기 전용 float.

**반환:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


회전은 위도 좌표와 경도 좌표, 그리고 위도와 경도 좌표를 축으로 하는 회전을 사용하여 정의됩니다. 반환 배열의 첫 번째 요소는 위도, 두 번째는 경도, 세 번째는 회전입니다. 회전이 정의되지 않은 경우 null을 반환합니다.

**반환:**
float[] - 회전값 배열, 형식은 float[]입니다.