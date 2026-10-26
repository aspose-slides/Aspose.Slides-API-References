---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Java API Reference
description: 슬라이드 영역의 크기(자식이 restoredTop일 때 너비, 자식이 restoredLeft일 때 높이)를 지정합니다. 일반 보기에서 영역이 가변 복원 크기(축소되지도 최대화되지도 않음)일 때 적용됩니다.
type: docs
url: /ko/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

슬라이드 영역의 크기(자식이 restoredTop일 때 너비, 자식이 restoredLeft일 때 높이)를 지정합니다. 일반 보기에서 영역이 가변 복원 크기(축소되지도 최대화되지도 않음)일 때 적용됩니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | 슬라이드 영역의 크기(자식이 RestoredTop일 때 너비, 자식이 RestoredLeft일 때 높이)를 지정합니다. |
| [setDimensionSize(float value)](#setDimensionSize-float-) | 슬라이드 영역의 크기(자식이 RestoredTop일 때 너비, 자식이 RestoredLeft일 때 높이)를 지정합니다. |
| [getAutoAdjust()](#getAutoAdjust--) | 애플리케이션 내에서 뷰를 포함하는 창의 크기를 조정할 때 사이드 콘텐츠 영역의 크기가 새로운 크기를 보정해야 하는지 여부를 지정합니다. 읽기/쓰기 boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | 애플리케이션 내에서 뷰를 포함하는 창의 크기를 조정할 때 사이드 콘텐츠 영역의 크기가 새로운 크기를 보정해야 하는지 여부를 지정합니다. 읽기/쓰기 boolean. |
### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

슬라이드 영역의 크기(자식이 RestoredTop일 때 너비, 자식이 RestoredLeft일 때 높이)를 지정합니다. 읽기/쓰기 float.

**반환값:**
float
### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

슬라이드 영역의 크기(자식이 RestoredTop일 때 너비, 자식이 RestoredLeft일 때 높이)를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |
### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

애플리케이션 내에서 뷰를 포함하는 창의 크기를 조정할 때 사이드 콘텐츠 영역의 크기가 새로운 크기를 보정해야 하는지 여부를 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

애플리케이션 내에서 뷰를 포함하는 창의 크기를 조정할 때 사이드 콘텐츠 영역의 크기가 새로운 크기를 보정해야 하는지 여부를 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |