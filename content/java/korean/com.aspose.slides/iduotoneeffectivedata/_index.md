---
title: IDuotoneEffectiveData
second_title: Aspose.Slides for Java API 레퍼런스
description: Duotone 효과를 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/iduotoneeffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Duotone 효과를 나타내는 불변 객체입니다. 각 픽셀에 대해 clr1과 clr2를 선형 보간하여 해당 픽셀의 새로운 색상을 결정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColor1()](#getColor1--) | 어두운 픽셀에 대한 대상 색상 형식을 반환합니다. |
| [getColor2()](#getColor2--) | 밝은 픽셀에 대한 대상 색상 형식을 반환합니다. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```

어두운 픽셀에 대한 대상 색상 형식을 반환합니다. 읽기 전용 java.awt.Color.

**반환:**  
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```

밝은 픽셀에 대한 대상 색상 형식을 반환합니다. 읽기 전용 java.awt.Color.

**반환:**  
java.awt.Color