---
title: IPresetShadowEffectiveData
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프리셋 그림자 효과를 나타내는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ippresetshadoweffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

프리셋 그림자 효과를 나타내는 불변 객체.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDirection()](#getDirection--) | 그림자 방향. |
| [getDistance()](#getDistance--) | 그림자 거리. |
| [getShadowColor()](#getShadowColor--) | 그림자 색상. |
| [getPreset()](#getPreset--) | 프리셋. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

그림자 방향. 읽기 전용 float.

**반환값:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

그림자 거리. 읽기 전용 double.

**반환값:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Integer getShadowColor()
```

그림자 색상. 읽기 전용 java.lang.Integer.

**반환값:**
java.lang.Integer
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

프리셋. 읽기 전용 [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**반환값:**
int