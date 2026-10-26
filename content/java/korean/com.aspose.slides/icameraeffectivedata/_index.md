---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 효과적인 카메라 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

효과적인 카메라 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata)의 일부로 사용됩니다.

## Methods

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | 카메라 유형. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 카메라 FOV(0-180도, 시야각). |
| [getZoom()](#getZoom--) | 카메라 줌(백분율로 양수 값). |
| [getRotation()](#getRotation--) | 회전은 위도 좌표, 경도 좌표, 그리고 위도와 경도 좌표를 기준으로 축을 중심으로 회전하는 방식으로 정의됩니다. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

카메라 유형. 읽기 전용 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returns:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

카메라 FOV(0-180도, 시야각). 읽기 전용 float.

**Returns:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

카메라 줌(백분율로 양수 값). 읽기 전용 float.

**Returns:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

회전은 위도 좌표, 경도 좌표, 그리고 위도와 경도 좌표를 기준으로 축을 중심으로 회전하는 방식으로 정의됩니다. 반환 배열의 첫 번째 요소는 위도, 두 번째는 경도, 세 번째는 회전 수입니다. 회전이 정의되지 않은 경우 null을 반환합니다.

**Returns:**
float[] - float[] 형식의 회전 값 배열.