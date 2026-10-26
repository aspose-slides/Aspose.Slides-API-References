---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: LightRig을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

LightRig을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 빛 방향. |
| [setDirection(int value)](#setDirection-int-) | 빛 방향. |
| [getLightType()](#getLightType--) | 모양에 적용할 수 있는 사전 설정 라이트 오른쪽을 나타냅니다. |
| [setLightType(int value)](#setLightType-int-) | 모양에 적용할 수 있는 사전 설정 라이트 오른쪽을 나타냅니다. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 위도 좌표, 경도 좌표 및 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. |
| [getRotation()](#getRotation--) | 위도 좌표, 경도 좌표 및 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


빛 방향. 읽기/쓰기 [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


빛 방향. 읽기/쓰기 [LightingDirection](../../com.aspose.slides/lightingdirection).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


모양에 적용할 수 있는 사전 설정 라이트 오른쪽을 나타냅니다. light rig은 3D 장면에 상대적으로 특정 방식으로 배치된 조명 그룹을 나타냅니다. 읽기/쓰기 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


모양에 적용할 수 있는 사전 설정 라이트 오른쪽을 나타냅니다. light rig은 3D 장면에 상대적으로 특정 방식으로 배치된 조명 그룹을 나타냅니다. 읽기/쓰기 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


위도 좌표, 경도 좌표 및 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| latitude | float | 위도 좌표 float |
| longitude | float | 경도 좌표 float |
| revolution | float | 회전 좌표 float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


위도 좌표, 경도 좌표 및 축을 중심으로 하는 회전을 사용하여 회전이 정의됩니다. 반환 배열의 첫 번째 요소는 위도, 두 번째 요소는 경도, 세 번째 요소는 회전입니다.

**Returns:**
float[] - 회전 좌표 (float[])