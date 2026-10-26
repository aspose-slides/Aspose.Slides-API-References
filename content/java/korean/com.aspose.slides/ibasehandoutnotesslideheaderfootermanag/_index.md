---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides for Java API 레퍼런스
description: 플래이스홀더의 동작을 보유하는 관리자를 나타내며, 모든 유형의 핸드아웃 및 노트 슬라이드에 대한 헤더 플래이스홀더를 포함합니다.
type: docs
url: /ko/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

플래이스홀더의 동작을 보유하는 관리자를 나타내며, 모든 유형의 핸드아웃 및 노트 슬라이드에 대한 헤더 플래이스홀더를 포함합니다.

--------------------

원본 인터페이스 이름 "IBaseHandoutNotesSlideHeaderFooterManager"는 COM 호환성을 위해 (형식 이름 길이는 39자를 초과해서는 안 함) "IBaseHandoutNotesSlideHeaderFooterManag"로 잘립니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | 헤더 플래이스홀더가 존재함을 나타내는 값을 가져옵니다. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | 슬라이드 헤더 플래이스홀더의 가시성을 변경합니다. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | 슬라이드 헤더 플래이스홀더에 텍스트를 설정합니다. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


헤더 플래이스홀더가 존재함을 나타내는 값을 가져옵니다. 부울 값을 읽습니다.

**반환:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


슬라이드 헤더 플래이스홀더의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 헤더 플래이스홀더를 표시하고, false - 숨깁니다. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


슬라이드 헤더 플래이스홀더에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |