---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /ko/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

효과적인 라이트 릭 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 라이트 방향. |
| [getLightType()](#getLightType--) | 형상에 적용할 수 있는 사전 설정 라이트 오른쪽을 나타냅니다. |
| [getRotation()](#getRotation--) | 회전은 위도 좌표와 경도 좌표를 사용하고, 위도 및 경도 좌표에 해당하는 축을 중심으로 회전함으로써 정의됩니다. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


라이트 방향. 읽기 전용 [LightingDirection](../../com.aspose.slides/lightingdirection).

**반환값:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


형상에 적용할 수 있는 사전 설정 라이트 오른쪽을 나타냅니다. 라이트 릭은 3D 장면에 대해 특정 방식으로 배치된 일련의 라이트 그룹을 나타냅니다. 읽기 전용 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**반환값:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


회전은 위도 좌표와 경도 좌표를 사용하고, 위도 및 경도 좌표에 해당하는 축을 중심으로 회전함으로써 정의됩니다. 반환 배열의 첫 번째 요소는 위도, 두 번째 요소는 경도, 세 번째 요소는 회전량입니다.

**반환값:**
float[] - 회전 좌표(float[] 형식)