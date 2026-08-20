---
title: ISoftEdge
second_title: Aspose.Slides Java API 레퍼런스
description: 소프트 엣지 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isoftedge/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface ISoftEdge extends IImageTransformOperation, IAccessiblePVIObject<ISoftEdgeEffectiveData>
```

소프트 엣지 효과를 나타냅니다. 모양의 가장자리는 흐려지지만 채우기는 영향을 받지 않습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRadius()](#getRadius--) | 가장자리에 적용할 블러 반경을 지정합니다. |
| [setRadius(double value)](#setRadius-double-) | 가장자리에 적용할 블러 반경을 지정합니다. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

가장자리에 적용할 블러 반경을 지정합니다. 읽기/쓰기 double.

**반환값:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

가장자리에 적용할 블러 반경을 지정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |