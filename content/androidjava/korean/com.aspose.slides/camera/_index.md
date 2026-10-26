---
title: Camera
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Camera를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/camera/
---
**상속:** [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**  
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)  
```
public final class Camera extends PVIObject implements ICamera
```

카메라를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | 카메라 유형. |
| [setCameraType(int value)](#setCameraType-int-) | 카메라 유형. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 카메라 시야각(FOV) (0-180도, 시야). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | 카메라 시야각(FOV) (0-180도, 시야). |
| [getZoom()](#getZoom--) | 카메라 줌(백분율로 양수 값). |
| [setZoom(float value)](#setZoom-float-) | 카메라 줌(백분율로 양수 값). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 회전은 위도 좌표, 경도 좌표 및 축을 중심으로 하는 회전을 사용하여 정의됩니다. |
| [getRotation()](#getRotation--) | 회전은 위도 좌표, 경도 좌표 및 축을 중심으로 하는 회전을 사용하여 정의됩니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**  
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

카메라 유형. 읽기/쓰기 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**반환값:**  
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

카메라 유형. 읽기/쓰기 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

카메라 시야각(FOV) (0-180도, 시야). 읽기/쓰기 float.

**반환값:**  
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

카메라 시야각(FOV) (0-180도, 시야). 읽기/쓰기 float.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

카메라 줌(백분율로 양수 값). 읽기/쓰기 float.

**반환값:**  
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

카메라 줌(백분율로 양수 값). 읽기/쓰기 float.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

회전은 위도 좌표, 경도 좌표 및 축을 중심으로 하는 회전을 사용하여 정의됩니다. 좌표 값 중 하나가 Float.NaN인 경우, 모든 회전이 정의되지 않습니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

회전은 위도 좌표, 경도 좌표 및 축을 중심으로 하는 회전을 사용하여 정의됩니다. 반환 배열의 첫 번째 요소는 위도, 두 번째 요소는 경도, 세 번째 요소는 회전입니다. 회전이 정의되지 않은 경우 null을 반환합니다.

**반환값:**  
float[]