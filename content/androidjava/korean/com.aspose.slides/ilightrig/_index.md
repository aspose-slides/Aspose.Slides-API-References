---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
type: docs
url: /ko/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Represents LightRig.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 빛 방향. |
| [setDirection(int value)](#setDirection-int-) | 빛 방향. |
| [getLightType()](#getLightType--) | 형태에 적용할 수 있는 프리셋 오른쪽 조명을 나타냅니다. |
| [setLightType(int value)](#setLightType-int-) | 형태에 적용할 수 있는 프리셋 오른쪽 조명을 나타냅니다. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 위도 좌표, 경도 좌표 및 축에 대한 회전을 사용하여 회전이 정의됩니다. |
| [getRotation()](#getRotation--) | 위도 좌표, 경도 좌표 및 축에 대한 회전을 사용하여 회전이 정의됩니다. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

빛 방향. 읽기/쓰기 [LightingDirection](../../com.aspose.slides/lightingdirection).

**반환:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

빛 방향. 읽기/쓰기 [LightingDirection](../../com.aspose.slides/lightingdirection).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

형태에 적용할 수 있는 프리셋 오른쪽 조명을 나타냅니다. 라이트 릭은 3D 장면에 대해 특정 방식으로 방향이 지정된 조명 그룹을 나타냅니다. 읽기/쓰기 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**반환:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

형태에 적용할 수 있는 프리셋 오른쪽 조명을 나타냅니다. 라이트 릭은 3D 장면에 대해 특정 방식으로 방향이 지정된 조명 그룹을 나타냅니다. 읽기/쓰기 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

위도 좌표, 경도 좌표 및 축에 대한 회전을 사용하여 회전이 정의됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| latitude | float | 위도 좌표 float |
| longitude | float | 경도 좌표 float |
| revolution | float | 회전 좌표 float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

위도 좌표, 경도 좌표 및 축에 대한 회전을 사용하여 회전이 정의됩니다. 반환 배열의 첫 번째 요소 - 위도, 두 번째 - 경도, 세 번째 - 회전.

**반환:**
float[] - 회전 좌표 (float[] 형식)