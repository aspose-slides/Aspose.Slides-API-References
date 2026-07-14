---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 플레이스홀더의 동작을 보유하는 관리자를 나타내며, 모든 유형의 유인물 및 노트 슬라이드에 대한 헤더 플레이스홀더를 포함합니다.
type: docs
url: /ko/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)  
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

플레이스홀더의 동작을 보유하는 관리자를 나타내며, 모든 유형의 유인물 및 노트 슬라이드에 대한 헤더 플레이스홀더를 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | 헤더 자리표시자가 있는지 여부를 나타내는 값을 가져옵니다. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | 슬라이드 헤더 자리표시자의 가시성을 변경합니다. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | 슬라이드 헤더 자리표시자에 텍스트를 설정합니다. |

### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

헤더 자리표시자가 있는지 여부를 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환:**  
boolean

### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

슬라이드 헤더 자리표시자의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 헤더 자리표시자를 보이게 하고, 그 외에는 숨깁니다. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

슬라이드 헤더 자리표시자에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |