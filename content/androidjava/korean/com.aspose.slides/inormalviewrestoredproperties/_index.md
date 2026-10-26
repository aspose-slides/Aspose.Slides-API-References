---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Android via Java API Reference
description: 정규 보기에서 슬라이드 영역의 크기(자식이 restoredTop일 때 너비, 자식이 restoredLeft일 때 높이)를 지정하며, 영역이 가변 복원 크기(축소되거나 최대화되지 않은)인 경우에 적용됩니다.
type: docs
url: /ko/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

정규 보기에서 슬라이드 영역의 크기(자식이 restoredTop일 때 너비, 자식이 restoredLeft일 때 높이)를 지정하며, 영역이 가변 복원 크기(축소되거나 최대화되지 않은)인 경우에 적용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | 슬라이드 영역의 크기(자식이 RestoredTop일 때 너비, 자식이 RestoredLeft일 때 높이)를 지정합니다. |
| [setDimensionSize(float value)](#setDimensionSize-float-) | 슬라이드 영역의 크기(자식이 RestoredTop일 때 너비, 자식이 RestoredLeft일 때 높이)를 지정합니다. |
| [getAutoAdjust()](#getAutoAdjust--) | 뷰를 포함하는 창을 리사이즈할 때 새 크기를 보정하도록 측면 콘텐츠 영역의 크기를 조정할지 여부를 지정합니다. 읽기/쓰기 boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | 뷰를 포함하는 창을 리사이즈할 때 새 크기를 보정하도록 측면 콘텐츠 영역의 크기를 조정할지 여부를 지정합니다. 읽기/쓰기 boolean. |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```


뷰를 포함하는 창을 리사이즈할 때 새 크기를 보정하도록 측면 콘텐츠 영역의 크기를 조정할지 여부를 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```


뷰를 포함하는 창을 리사이즈할 때 새 크기를 보정하도록 측면 콘텐츠 영역의 크기를 조정할지 여부를 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |