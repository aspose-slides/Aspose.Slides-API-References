---
title: IAlphaBiLevel
second_title: Aspose.Slides for Java API 참조
description: Alpha Bi-Level 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ialphabilevel/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Alpha Bi-Level 효과를 나타냅니다. 임계값보다 작은 Alpha(불투명도) 값은 0(완전 투명)으로 변경되고, 임계값보다 크거나 같은 Alpha 값은 100%(완전 불투명)으로 변경됩니다.

--------------------

COM에서 인스턴스를 만들려면 ImageTransformOperationFactory를 사용하십시오.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 효과 임계값을 반환합니다. |
| [setThreshold(float value)](#setThreshold-float-) | 효과 임계값을 반환합니다. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

효과 임계값을 반환합니다. 읽기/쓰기 float.

**반환:**  
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

효과 임계값을 반환합니다. 읽기/쓰기 float.

**파라미터:**
| 파라미터 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |