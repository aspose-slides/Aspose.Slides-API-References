---
title: IDuotoneEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Duotone 효과를 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/iduotoneeffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Duotone 효과를 나타내는 불변 객체입니다. 각 픽셀에 대해 clr1과 clr2를 선형 보간을 통해 결합하여 해당 픽셀의 새 색상을 결정합니다.

## 메서드

| Method | Description |
| --- | --- |
| [getColor1()](#getColor1--) | 어두운 픽셀에 대한 대상 색상 형식을 반환합니다. |
| [getColor2()](#getColor2--) | 밝은 픽셀에 대한 대상 색상 형식을 반환합니다. |

### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```

어두운 픽셀에 대한 대상 색상 형식을 반환합니다. 읽기 전용 java.lang.Integer.

**반환값:**
java.lang.Integer

### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```

밝은 픽셀에 대한 대상 색상 형식을 반환합니다. 읽기 전용 java.lang.Integer.

**반환값:**
java.lang.Integer