---
title: IAlphaBiLevelEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Alpha 바이레벨 효과를 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ialphabileveleffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

알파 바이레벨 효과를 나타내는 불변 객체입니다. 임계값보다 작은 알파(불투명도) 값은 0(완전 투명)으로, 임계값 이상인 알파 값은 100%(완전 불투명)으로 변경됩니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 효과 임계값을 반환합니다. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

효과 임계값을 반환합니다. 읽기 전용 float.

**반환:**
float