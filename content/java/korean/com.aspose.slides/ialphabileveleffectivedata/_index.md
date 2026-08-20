---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides for Java API 레퍼런스
description: Alpha Bi-Level 효과를 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ialphabileveleffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

임계값보다 낮은 Alpha (Opacity) 값은 0(완전 투명)으로, 임계값보다 크거나 같은 Alpha (Opacity) 값은 100%(완전 불투명)으로 변경되는 Alpha Bi-Level 효과를 나타내는 불변 객체입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 효과 임계값을 반환합니다. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

효과 임계값을 반환합니다. 읽기 전용 float.

**반환값:**
float