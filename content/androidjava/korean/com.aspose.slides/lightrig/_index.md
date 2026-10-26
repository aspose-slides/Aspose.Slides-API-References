---
title: LightRig
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: LightRig을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/lightrig/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**  
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)  
```
public final class LightRig extends PVIObject implements ILightRig
```

LightRig을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | 빛 방향. |
| [setDirection(int value)](#setDirection-int-) | 빛 방향. |
| [getLightType()](#getLightType--) | 형태에 적용할 수 있는 미리 설정된 라이트 라이트를 나타냅니다. |
| [setLightType(int value)](#setLightType-int-) | 형태에 적용할 수 있는 미리 설정된 라이트 라이트를 나타냅니다. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 위도 좌표와 경도 좌표, 그리고 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. |
| [getRotation()](#getRotation--) | 위도 좌표와 경도 좌표, 그리고 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

빛 방향. 읽기/쓰기 [LightingDirection](../../com.aspose.slides/lightingdirection).

**반환:**  
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

빛 방향. 읽기/쓰기 [LightingDirection](../../com.aspose.slides/lightingdirection).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

형태에 적용할 수 있는 미리 설정된 라이트 라이트를 나타냅니다. 라이트 리그는 3D 장면에 대해 특정 방식으로 방향이 지정된 조명 그룹을 나타냅니다. 읽기/쓰기 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**반환:**  
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

형태에 적용할 수 있는 미리 설정된 라이트 라이트를 나타냅니다. 라이트 리그는 3D 장면에 대해 특정 방식으로 방향이 지정된 조명 그룹을 나타냅니다. 읽기/쓰기 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

위도 좌표와 경도 좌표, 그리고 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. 좌표 값 중 하나가 Float.NaN이면 모든 회전이 정의되지 않은 것으로 간주됩니다.

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

위도 좌표와 경도 좌표, 그리고 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. 반환 배열의 첫 번째 요소는 위도, 두 번째는 경도, 세 번째는 회전입니다. 회전이 정의되지 않은 경우 null을 반환합니다.

**반환:**  
float[]