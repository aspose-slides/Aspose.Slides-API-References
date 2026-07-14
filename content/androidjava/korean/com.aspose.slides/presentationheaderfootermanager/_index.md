---
title: PresentationHeaderFooterManager
second_title: Android용 Aspose.Slides Java API 참조
description: 프레젠테이션의 모든 바닥글, 날짜-시간 및 페이지 번호 자리표시자 동작을 관리하는 매니저를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/presentationheaderfootermanager/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)  
```
public class PresentationHeaderFooterManager extends BaseHeaderFooterManager implements IPresentationHeaderFooterManager
```

프레젠테이션의 모든 바닥글, 날짜-시간 및 페이지 번호 자리표시자 동작을 관리하는 매니저를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | 헤더 자리표시자 전체의 표시 여부를 변경합니다. notes master, notes slides 및 handout master 포함. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | 바닥글 자리표시자 전체의 표시 여부를 변경합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | 페이지 번호 자리표시자 전체의 표시 여부를 변경합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | 날짜-시간 자리표시자 전체의 표시 여부를 변경합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | 헤더 자리표시자 전체에 텍스트를 설정합니다. notes master, notes slides 및 handout master 포함. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | 바닥글 자리표시자 전체에 텍스트를 설정합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | 날짜-시간 자리표시자 전체에 텍스트를 설정합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | 모든 타이틀 슬라이드와 첫 레이아웃 슬라이드에 대해 바닥글, 날짜-시간 및 페이지 번호 자리표시자 표시 여부를 변경합니다. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public final void setAllHeadersVisibility(boolean isVisible)
```

헤더 자리표시자 전체의 표시 여부를 변경합니다. notes master, notes slides 및 handout master 포함.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 헤더 자리표시자를 표시하고, 그렇지 않으면 숨깁니다. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public final void setAllFootersVisibility(boolean isVisible)
```

바닥글 자리표시자 전체의 표시 여부를 변경합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 바닥글 자리표시자를 표시하고, 그렇지 않으면 숨깁니다. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public final void setAllSlideNumbersVisibility(boolean isVisible)
```

페이지 번호 자리표시자 전체의 표시 여부를 변경합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 페이지 번호 자리표시자를 표시하고, 그렇지 않으면 숨깁니다. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public final void setAllDateTimesVisibility(boolean isVisible)
```

날짜-시간 자리표시자 전체의 표시 여부를 변경합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 날짜-시간 자리표시자를 표시하고, 그렇지 않으면 숨깁니다. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public final void setAllHeadersText(String text)
```

헤더 자리표시자 전체에 텍스트를 설정합니다. notes master, notes slides 및 handout master 포함.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public final void setAllFootersText(String text)
```

바닥글 자리표시자 전체에 텍스트를 설정합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public final void setAllDateTimesText(String text)
```

날짜-시간 자리표시자 전체에 텍스트를 설정합니다. master slides, layout slides, slides, notes master, notes slides 및 handout master 포함.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public final void setVisibilityOnAllTitleSlides(boolean isVisible)
```

모든 타이틀 슬라이드와 첫 레이아웃 슬라이드에 대해 바닥글, 날짜-시간 및 페이지 번호 자리표시자 표시 여부를 변경합니다. 타이틀 슬라이드 – 첫 레이아웃 슬라이드를 기반으로 하는 슬라이드(첫 레이아웃 유형에 관계없이).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 자리표시자를 표시하고, 그렇지 않으면 숨깁니다. |