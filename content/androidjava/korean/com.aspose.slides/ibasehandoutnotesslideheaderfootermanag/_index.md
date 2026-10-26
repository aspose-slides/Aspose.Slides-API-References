---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 플레이스홀더의 동작을 관리하고, 모든 유형의 유인물 및 노트 슬라이드에 대한 헤더 플레이스홀더를 포함하는 매니저를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

플레이스홀더의 동작을 관리하는 매니저를 나타내며, 모든 유형의 유인물 및 노트 슬라이드에 대한 헤더 플레이스홀더를 포함합니다.

--------------------

COM 호환성을 위해 원래 인터페이스 이름 "IBaseHandoutNotesSlideHeaderFooterManager"가 "IBaseHandoutNotesSlideHeaderFooterManag"(타입 이름 길이는 39자를 초과할 수 없음)으로 잘렸습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | 헤더 플레이스홀더가 존재함을 나타내는 값을 가져옵니다. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | 슬라이드 헤더 플레이스홀더의 표시 여부를 변경합니다. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | 슬라이드 헤더 플레이스홀더에 텍스트를 설정합니다. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

헤더 플레이스홀더가 존재함을 나타내는 값을 가져옵니다. boolean을 읽습니다.

**반환:**  
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

슬라이드 헤더 플레이스홀더의 표시 여부를 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 헤더 플레이스홀더를 표시하고, false - 숨깁니다. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

슬라이드 헤더 플레이스홀더에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |