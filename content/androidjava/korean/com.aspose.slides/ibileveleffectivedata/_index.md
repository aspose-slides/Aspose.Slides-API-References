---
title: IBiLevelEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 양자 레벨(흑백) 효과를 나타내는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ibileveleffectivedata/
---
**구현된 모든 인터페이스:**  
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

불변 객체로, 바이레벨(검정/흰색) 효과를 나타냅니다. 지정된 임계값보다 낮은 휘도를 가진 입력 색상은 검정색으로 변환되고, 지정된 값보다 크거나 같거나 동일한 휘도를 가진 입력 색상은 흰색으로 설정됩니다. 알파 효과 값은 이 효과에 의해 영향을 받지 않습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 임계값을 반환합니다. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


임계값을 반환합니다. 읽기 전용 float.

**반환:**  
float