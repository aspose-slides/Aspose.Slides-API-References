---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /ko/com.aspose.slides/icamera/
---```
public interface ICamera
```

Camera를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera 유형 읽기/쓰기 [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Camera 유형 읽기/쓰기 [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180도, 시야) 읽기/쓰기 float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180도, 시야) 읽기/쓰기 float. |
| [getZoom()](#getZoom--) | Camera 줌 (백분율의 양수 값) 읽기/쓰기 float. |
| [setZoom(float value)](#setZoom-float-) | Camera 줌 (백분율의 양수 값) 읽기/쓰기 float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 회전은 위도 좌표, 경도 좌표, 그리고 위도와 경도 좌표를 축으로 하는 회전으로 정의됩니다. |
| [getRotation()](#getRotation--) | 회전은 위도 좌표, 경도 좌표, 그리고 위도와 경도 좌표를 축으로 하는 회전으로 정의됩니다. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Camera 유형 읽기/쓰기 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**반환값:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Camera 유형 읽기/쓰기 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180도, 시야) 읽기/쓰기 float.

**반환값:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Camera FOV (0-180도, 시야) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Camera 줌 (백분율의 양수 값) 읽기/쓰기 float.

**반환값:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Camera 줌 (백분율의 양수 값) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

회전은 위도 좌표, 경도 좌표, 그리고 위도와 경도 좌표를 축으로 하는 회전으로 정의됩니다. 좌표값이 Float.NaN이면 모든 회전이 정의되지 않습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| latitude | float | 위도 값 float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

회전은 위도 좌표, 경도 좌표, 그리고 위도와 경도 좌표를 축으로 하는 회전으로 정의됩니다. 반환 배열의 첫 번째 요소 - 위도, 두 번째 - 경도, 세 번째 - 회전. 회전이 정의되지 않은 경우 null을 반환합니다.

**반환값:**
float[] - 회전 값을 float[] 배열로 반환합니다.