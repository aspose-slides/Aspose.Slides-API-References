---
title: NormalViewProperties
second_title: Aspose.Slides for Java API 레퍼런스
description: 일반 보기 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/normalviewproperties/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)  
```
public class NormalViewProperties implements INormalViewProperties
```

일반 보기 속성을 나타냅니다. 일반 보드는 세 개의 콘텐츠 영역으로 구성됩니다: 슬라이드 자체, 측면 콘텐츠 영역, 하단 콘텐츠 영역.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //프레젠테이션 파일을 나타내는 프레젠테이션 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | 응용 프로그램이 일반 보기 모드의 콘텐츠 영역 중 어느 곳에서든 윤곽선 콘텐츠를 표시할 때 아이콘을 표시해야 하는지 지정합니다. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | 응용 프로그램이 일반 보기 모드의 콘텐츠 영역 중 어느 곳에서든 윤곽선 콘텐츠를 표시할 때 아이콘을 표시해야 하는지 지정합니다. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | 측면 영역이 충분히 작을 때 수직 분할기가 최소화된 상태에 맞춰야 하는지 지정합니다. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | 측면 영역이 충분히 작을 때 수직 분할기가 최소화된 상태에 맞춰야 하는지 지정합니다. |
| [getVerticalBarState()](#getVerticalBarState--) | 수직 분할 막대가 표시될 상태를 지정합니다. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 수직 분할 막대가 표시될 상태를 지정합니다. |
| [getHorizontalBarState()](#getHorizontalBarState--) | 수평 분할 막대가 표시될 상태를 지정합니다. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 수평 분할 막대가 표시될 상태를 지정합니다. |
| [getPreferSingleView()](#getPreferSingleView--) | 사용자가 세 개의 콘텐츠 영역을 가진 표준 일반 보기 대신 전체 창 단일 콘텐츠 영역을 보기를 선호하는지 지정합니다. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | 사용자가 세 개의 콘텐츠 영역을 가진 표준 일반 보기 대신 전체 창 단일 콘텐츠 영역을 보기를 선호하는지 지정합니다. |
| [getRestoredLeft()](#getRestoredLeft--) | 이 요소는 영역이 가변 복원 크기(축소되지도 확대되지도 않음)일 때 일반 보기의 측면 콘텐츠 영역 크기를 지정합니다. |
| [getRestoredTop()](#getRestoredTop--) | 이 요소는 영역이 가변 복원 크기(축소되지도 확대되지도 않음)일 때 일반 보기의 상단 슬라이드 영역 크기를 지정합니다. |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

응용 프로그램이 일반 보기 모드의 콘텐츠 영역 중 어느 곳에서든 윤곽선 콘텐츠를 표시할 때 아이콘을 표시해야 하는지 지정합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

응용 프로그램이 일반 보기 모드의 콘텐츠 영역 중 어느 곳에서든 윤곽선 콘텐츠를 표시할 때 아이콘을 표시해야 하는지 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

측면 영역이 충분히 작을 때 수직 분할기가 최소화된 상태에 맞춰야 하는지 지정합니다. 읽기/쓰기 boolean.

**반환값:**  
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

측면 영역이 충분히 작을 때 수직 분할기가 최소화된 상태에 맞춰야 하는지 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

수직 분할 막대가 표시될 상태를 지정합니다. A vertical splitter bar separates the slide from the side content region.

**반환값:**  
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

수직 분할 막대가 표시될 상태를 지정합니다. A vertical splitter bar separates the slide from the side content region.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

수평 분할 막대가 표시될 상태를 지정합니다. A horizontal splitter bar separates the slide from the content region below the slide.

**반환값:**  
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

수평 분할 막대가 표시될 상태를 지정합니다. A horizontal splitter bar separates the slide from the content region below the slide.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

사용자가 세 개의 콘텐츠 영역을 가진 표준 일반 보기 대신 전체 창 단일 콘텐츠 영역을 보기를 선호하는지 지정합니다. If enabled, the application may choose to display one of the content regions in the entire window. 읽기/쓰기 boolean.

**반환값:**  
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

사용자가 세 개의 콘텐츠 영역을 가진 표준 일반 보기 대신 전체 창 단일 콘텐츠 영역을 보기를 선호하는지 지정합니다. If enabled, the application may choose to display one of the content regions in the entire window. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

이 요소는 영역이 가변 복원 크기(축소되지도 확대되지도 않음)일 때 일반 보기의 측면 콘텐츠 영역 크기를 지정합니다. 읽기 전용 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**반환값:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

이 요소는 영역이 가변 복원 크기(축소되지도 확대되지도 않음)일 때 일반 보기의 상단 슬라이드 영역 크기를 지정합니다. 읽기 전용 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**반환값:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)