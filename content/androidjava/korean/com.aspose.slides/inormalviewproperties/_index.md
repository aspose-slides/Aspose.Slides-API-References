---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: 정상 보기 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

정상 보기 속성을 나타냅니다. 정상 보기는 슬라이드 자체, 측면 콘텐츠 영역, 그리고 하단 콘텐츠 영역의 세 개 콘텐츠 영역으로 구성됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | 정상 보기 모드의 어느 콘텐츠 영역에서든 개요 콘텐츠를 표시할 때 애플리케이션이 아이콘을 표시해야 하는지 여부를 지정합니다. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | 정상 보기 모드의 어느 콘텐츠 영역에서든 개요 콘텐츠를 표시할 때 애플리케이션이 아이콘을 표시해야 하는지 여부를 지정합니다. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | 측면 영역이 충분히 작을 때 수직 분할기가 최소화된 상태에 스냅하도록 지정합니다. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | 측면 영역이 충분히 작을 때 수직 분할기가 최소화된 상태에 스냅하도록 지정합니다. |
| [getVerticalBarState()](#getVerticalBarState--) | 수직 분할 막대가 표시되어야 하는 상태를 지정합니다. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 수직 분할 막대가 표시되어야 하는 상태를 지정합니다. |
| [getHorizontalBarState()](#getHorizontalBarState--) | 수평 분할 막대가 표시되어야 하는 상태를 지정합니다. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 수평 분할 막대가 표시되어야 하는 상태를 지정합니다. |
| [getPreferSingleView()](#getPreferSingleView--) | 사용자가 세 개의 콘텐츠 영역이 있는 일반 보기 대신 전체 창 단일 콘텐츠 영역을 선호하는지 여부를 지정합니다. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | 사용자가 세 개의 콘텐츠 영역이 있는 일반 보기 대신 전체 창 단일 콘텐츠 영역을 선호하는지 여부를 지정합니다. |
| [getRestoredLeft()](#getRestoredLeft--) | 이 요소는 가변 복원 크기(최소화되지도 최대화되지도 않음)인 경우 정상 보기의 측면 콘텐츠 영역의 크기를 지정합니다. |
| [getRestoredTop()](#getRestoredTop--) | 이 요소는 가변 복원 크기(최소화되지도 최대화되지도 않음)인 경우 정상 보기의 상단 슬라이드 영역의 크기를 지정합니다. |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

정상 보기 모드의 어느 콘텐츠 영역에서든 개요 콘텐츠를 표시할 때 애플리케이션이 아이콘을 표시해야 하는지 여부를 지정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

정상 보기 모드의 어느 콘텐츠 영역에서든 개요 콘텐츠를 표시할 때 애플리케이션이 아이콘을 표시해야 하는지 여부를 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

측면 영역이 충분히 작을 때 수직 분할기가 최소화된 상태에 스냅하도록 지정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

측면 영역이 충분히 작을 때 수직 분할기가 최소화된 상태에 스냅하도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

수직 분할 막대가 표시되어야 하는 상태를 지정합니다. 수직 분할 막대는 슬라이드를 측면 콘텐츠 영역과 구분합니다.

**반환:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

수직 분할 막대가 표시되어야 하는 상태를 지정합니다. 수직 분할 막대는 슬라이드를 측면 콘텐츠 영역과 구분합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

수평 분할 막대가 표시되어야 하는 상태를 지정합니다. 수평 분할 막대는 슬라이드를 슬라이드 아래의 콘텐츠 영역과 구분합니다.

**반환:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

수평 분할 막대가 표시되어야 하는 상태를 지정합니다. 수평 분할 막대는 슬라이드를 슬라이드 아래의 콘텐츠 영역과 구분합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

사용자가 세 개의 콘텐츠 영역이 있는 일반 보기 대신 전체 창 단일 콘텐츠 영역을 선호하는지 여부를 지정합니다. 활성화된 경우 애플리케이션은 하나의 콘텐츠 영역을 전체 창에 표시하도록 선택할 수 있습니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

사용자가 세 개의 콘텐츠 영역이 있는 일반 보기 대신 전체 창 단일 콘텐츠 영역을 선호하는지 여부를 지정합니다. 활성화된 경우 애플리케이션은 하나의 콘텐츠 영역을 전체 창에 표시하도록 선택할 수 있습니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

이 요소는 가변 복원 크기(최소화되지도 최대화되지도 않음)인 경우 정상 보기의 측면 콘텐츠 영역의 크기를 지정합니다. 읽기 전용 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**반환:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

이 요소는 가변 복원 크기(최소화되지도 최대화되지도 않음)인 경우 정상 보기의 상단 슬라이드 영역의 크기를 지정합니다. 읽기 전용 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**반환:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)