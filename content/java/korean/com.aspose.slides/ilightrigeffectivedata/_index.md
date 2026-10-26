---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 효과적인 라이트 리그 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

효과적인 라이트 리그 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 라이트 방향. |
| [getLightType()](#getLightType--) | 도형에 적용할 수 있는 사전 설정 라이트 오른쪽을 나타냅니다. |
| [getRotation()](#getRotation--) | 회전은 위도 좌표와 경도 좌표, 그리고 위도와 경도 좌표를 축을 중심으로 회전시켜 정의됩니다. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


라이트 방향. 읽기 전용 [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


도형에 적용할 수 있는 사전 설정 라이트 오른쪽을 나타냅니다. 라이트 리그는 3D 씬에 대해 특정 방식으로 배치된 조명 그룹을 나타냅니다. 읽기 전용 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


회전은 위도 좌표와 경도 좌표, 그리고 위도와 경도 좌표를 축을 중심으로 회전시켜 정의됩니다. 반환 배열의 첫 번째 요소는 위도, 두 번째는 경도, 세 번째는 회전입니다.

**Returns:**
float[] - 회전 좌표 (float[] 형태)