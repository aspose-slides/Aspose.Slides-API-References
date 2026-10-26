---
title: IGlow
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 색상이 흐려진 외곽선이 개체 가장자리 바깥에 추가되는 Glow 효과를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iglow/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Glow 효과를 나타내며, 개체 가장자리 바깥쪽에 색상이 흐려진 외곽선이 추가됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRadius()](#getRadius--) | 반경. |
| [setRadius(double value)](#setRadius-double-) | 반경. |
| [getColor()](#getColor--) | 색상 형식. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

반경. 읽기/쓰기 double.

**반환값:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

반경. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

색상 형식. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**
[IColorFormat](../../com.aspose.slides/icolorformat)