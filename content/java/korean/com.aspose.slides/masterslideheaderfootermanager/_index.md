---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides for Java API 레퍼런스
description: 마스터 슬라이드 푸터, 날짜-시간, 페이지 번호 플레이스홀더 및 모든 자식 플레이스홀더의 동작을 담당하는 관리자를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/masterslideheaderfootermanager/
---
**상속:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**구현된 모든 인터페이스:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

마스터 슬라이드 푸터, 날짜-시간, 페이지 번호 플레이스홀더 및 모든 자식 플레이스홀더의 동작을 담당하는 매니저를 나타냅니다. 자식 플레이스홀더는 종속 레이아웃 슬라이드와 종속 슬라이드에 포함된 플레이스홀더를 의미합니다. 종속 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 의존합니다.
## Methods

| 메서드 | 설명 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 마스터 슬라이드 푸터 플레이스홀더와 모든 자식 푸터 플레이스홀더의 표시 여부를 변경합니다. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 마스터 슬라이드 페이지 번호 플레이스홀더와 모든 자식 페이지 번호 플레이스홀더의 표시 여부를 변경합니다. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 마스터 슬라이드 날짜-시간 플레이스홀더와 모든 자식 날짜-시간 플레이스홀더의 표시 여부를 변경합니다. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 마스터 슬라이드 푸터 플레이스홀더와 모든 자식 푸터 플레이스홀더에 텍스트를 설정합니다. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 마스터 슬라이드 날짜-시간 플레이스홀더와 모든 자식 날짜-시간 플레이스홀더에 텍스트를 설정합니다. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


마스터 슬라이드 푸터 플레이스홀더와 모든 자식 푸터 플레이스홀더의 표시 여부를 변경합니다. 자식 플레이스홀더는 종속 레이아웃 슬라이드와 종속 슬라이드에 포함된 플레이스홀더를 의미합니다. 종속 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 의존합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 푸터 플레이스홀더를 표시하도록 하고, false - 숨깁니다. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


마스터 슬라이드 페이지 번호 플레이스홀더와 모든 자식 페이지 번호 플레이스홀더의 표시 여부를 변경합니다. 자식 플레이스홀더는 종속 레이아웃 슬라이드와 종속 슬라이드에 포함된 플레이스홀더를 의미합니다. 종속 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 의존합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 페이지 번호 플레이스홀더를 표시하도록 하고, false - 숨깁니다. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


마스터 슬라이드 날짜-시간 플레이스홀더와 모든 자식 날짜-시간 플레이스홀더의 표시 여부를 변경합니다. 자식 플레이스홀더는 종속 레이아웃 슬라이드와 종속 슬라이드에 포함된 플레이스홀더를 의미합니다. 종속 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 의존합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 날짜-시간 플레이스홀더를 표시하도록 하고, false - 숨깁니다. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


마스터 슬라이드 푸터 플레이스홀더와 모든 자식 푸터 플레이스홀더에 텍스트를 설정합니다. 자식 플레이스홀더는 종속 레이아웃 슬라이드와 종속 슬라이드에 포함된 플레이스홀더를 의미합니다. 종속 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 의존합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


마스터 슬라이드 날짜-시간 플레이스홀더와 모든 자식 날짜-시간 플레이스홀더에 텍스트를 설정합니다. 자식 플레이스홀더는 종속 레이아웃 슬라이드와 종속 슬라이드에 포함된 플레이스홀더를 의미합니다. 종속 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 의존합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |