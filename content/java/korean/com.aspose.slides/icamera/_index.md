---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Camera를 나타냅니다.
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
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, 시야각) 읽기/쓰기 float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, 시야각) 읽기/쓰기 float. |
| [getZoom()](#getZoom--) | Camera zoom (양수 값, 백분율) 읽기/쓰기 float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (양수 값, 백분율) 읽기/쓰기 float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 위도 좌표와 경도 좌표, 그리고 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. |
| [getRotation()](#getRotation--) | 위도 좌표와 경도 좌표, 그리고 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Camera 유형 읽기/쓰기 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**반환:**  
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Camera 유형 읽기/쓰기 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Camera FOV (0-180 deg, 시야각) 읽기/쓰기 float.

**반환:**  
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Camera FOV (0-180 deg, 시야각) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Camera zoom (양수 값, 백분율) 읽기/쓰기 float.

**반환:**  
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Camera zoom (양수 값, 백분율) 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

위도 좌표와 경도 좌표, 그리고 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. 좌표값 중 하나가 Float.NaN이면 모든 회전이 정의되지 않은 것으로 간주됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| latitude | float | 위도 값 float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

위도 좌표와 경도 좌표, 그리고 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. 반환 배열의 첫 번째 요소는 위도, 두 번째는 경도, 세 번째는 회전입니다. 정의된 회전이 없으면 null을 반환합니다.

**반환:**  
float[] - 회전 값을 float[] 배열로 반환합니다.