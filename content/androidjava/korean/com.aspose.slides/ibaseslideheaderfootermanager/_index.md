---
title: IBaseSlideHeaderFooterManager
second_title: Android용 Aspose.Slides Java API 레퍼런스
description: 모든 슬라이드 유형에 대한 바닥글, date-time, 페이지 번호 자리 표시자의 동작을 관리하는 매니저를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibaseslideheaderfootermanager/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

모든 슬라이드 유형에 대한 바닥글, 날짜-시간, 페이지 번호 자리 표시자의 동작을 관리하는 매니저를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | 바닥글 자리 표시자가 존재함을 나타내는 값을 가져옵니다. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | 페이지 번호 자리 표시자가 존재함을 나타내는 값을 가져옵니다. |
| [isDateTimeVisible()](#isDateTimeVisible--) | 날짜-시간 자리 표시자가 존재함을 나타내는 값을 가져옵니다. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | 슬라이드 바닥글 자리 표시자의 가시성을 변경합니다. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | 슬라이드 페이지 번호 자리 표시자의 가시성을 변경합니다. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | 슬라이드 날짜-시간 자리 표시자의 가시성을 변경합니다. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | 슬라이드 바닥글 자리 표시자에 텍스트를 설정합니다. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | 슬라이드 날짜-시간 자리 표시자에 텍스트를 설정합니다. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

바닥글 자리 표시자가 존재함을 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

페이지 번호 자리 표시자가 존재함을 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

날짜-시간 자리 표시자가 존재함을 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**반환값:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

슬라이드 바닥글 자리 표시자의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 바닥글 자리 표시자를 표시하고, false - 숨깁니다. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

슬라이드 페이지 번호 자리 표시자의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 페이지 번호 자리 표시자를 표시하고, false - 숨깁니다. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

슬라이드 날짜-시간 자리 표시자의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 날짜-시간 자리 표시자를 표시하고, false - 숨깁니다. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

슬라이드 바닥글 자리 표시자에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

슬라이드 날짜-시간 자리 표시자에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |