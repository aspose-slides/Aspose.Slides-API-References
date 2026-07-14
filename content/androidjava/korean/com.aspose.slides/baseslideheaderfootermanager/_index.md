---
title: BaseSlideHeaderFooterManager
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 모든 슬라이드 유형에 대한 바닥글, 날짜-시간, 페이지 번호 자리 표시자 동작을 관리하는 관리자를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/baseslideheaderfootermanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

슬라이드 모든 유형에 대한 바닥글, 날짜-시간, 페이지 번호 자리 표시자 동작을 관리하는 관리자를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | 바닥글 자리 표시자가 존재함을 나타내는 값을 가져옵니다. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | 페이지 번호 자리 표시자가 존재함을 나타내는 값을 가져옵니다. |
| [isDateTimeVisible()](#isDateTimeVisible--) | 날짜-시간 자리 표시자가 존재함을 나타내는 값을 가져옵니다. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | 슬라이드 바닥글 자리 표시자 가시성을 변경합니다. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | 슬라이드 페이지 번호 자리 표시자 가시성을 변경합니다. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | 슬라이드 날짜-시간 자리 표시자 가시성을 변경합니다. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | 슬라이드 바닥글 자리 표시자에 텍스트를 설정합니다. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | 슬라이드 날짜-시간 자리 표시자에 텍스트를 설정합니다. |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

바닥글 자리 표시자가 존재함을 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

페이지 번호 자리 표시자가 존재함을 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

날짜-시간 자리 표시자가 존재함을 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

슬라이드 바닥글 자리 표시자 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 바닥글 자리 표시자를 표시하고, 그 외는 숨깁니다. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

슬라이드 페이지 번호 자리 표시자 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 페이지 번호 자리 표시자를 표시하고, 그 외는 숨깁니다. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

슬라이드 날짜-시간 자리 표시자 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 날짜-시간 자리 표시자를 표시하고, 그 외는 숨깁니다. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

슬라이드 바닥글 자리 표시자에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

슬라이드 날짜-시간 자리 표시자에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |