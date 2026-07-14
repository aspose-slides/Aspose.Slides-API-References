---
title: MasterNotesSlideHeaderFooterManager
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 마스터 노트 슬라이드의 바닥글, 날짜-시간, 페이지 번호 자리표시자 및 모든 자식 자리표시자의 동작을 관리하는 매니저를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/masternotesslideheaderfootermanager/
---
**상속:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager), [com.aspose.slides.BaseHandoutNotesSlideHeaderFooterManager](../../com.aspose.slides/basehandoutnotesslideheaderfootermanager)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)  
```
public final class MasterNotesSlideHeaderFooterManager extends BaseHandoutNotesSlideHeaderFooterManager implements IMasterNotesSlideHeaderFooterManager
```

마스터 노트 슬라이드의 바닥글, 날짜-시간, 페이지 번호 자리표시자와 모든 자식 자리표시자의 동작을 관리하는 매니저를 나타냅니다. 자식 자리표시자는 종속 노트 슬라이드에 포함된 자리표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | 마스터 노트 슬라이드 머리글 자리표시자와 모든 자식 머리글 자리표시자의 표시 여부를 변경합니다. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | 마스터 노트 슬라이드 머리글 자리표시자와 모든 자식 머리글 자리표시자에 텍스트를 설정합니다. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 마스터 슬라이드 바닥글 자리표시자와 모든 자식 바닥글 자리표시자의 표시 여부를 변경합니다. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 마스터 슬라이드 페이지 번호 자리표시자와 모든 자식 페이지 번호 자리표시자의 표시 여부를 변경합니다. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 마스터 슬라이드 날짜-시간 자리표시자와 모든 자식 날짜-시간 자리표시자의 표시 여부를 변경합니다. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 마스터 슬라이드 바닥글 자리표시자와 모든 자식 바닥글 자리표시자에 텍스트를 설정합니다. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 마스터 슬라이드 날짜-시간 자리표시자와 모든 자식 날짜-시간 자리표시자에 텍스트를 설정합니다. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public final void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

마스터 노트 슬라이드 머리글 자리표시자와 모든 자식 머리글 자리표시자의 표시 여부를 변경합니다. 자식 자리표시자는 종속 노트 슬라이드에 포함된 자리표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 머리글 자리표시자를 표시하고, false - 숨깁니다. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public final void setHeaderAndChildHeadersText(String text)
```

마스터 노트 슬라이드 머리글 자리표시자와 모든 자식 머리글 자리표시자에 텍스트를 설정합니다. 자식 자리표시자는 종속 노트 슬라이드에 포함된 자리표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

마스터 슬라이드 바닥글 자리표시자와 모든 자식 바닥글 자리표시자의 표시 여부를 변경합니다. 자식 자리표시자는 종속 노트 슬라이드에 포함된 자리표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 바닥글 자리표시자를 표시하고, false - 숨깁니다. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

마스터 슬라이드 페이지 번호 자리표시자와 모든 자식 페이지 번호 자리표시자의 표시 여부를 변경합니다. 자식 자리표시자는 종속 노트 슬라이드에 포함된 자리표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 페이지 번호 자리표시자를 표시하고, false - 숨깁니다. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

마스터 슬라이드 날짜-시간 자리표시자와 모든 자식 날짜-시간 자리표시자의 표시 여부를 변경합니다. 자식 자리표시자는 종속 노트 슬라이드에 포함된 자리표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 날짜-시간 자리표시자를 표시하고, false - 숨깁니다. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

마스터 슬라이드 바닥글 자리표시자와 모든 자식 바닥글 자리표시자에 텍스트를 설정합니다. 자식 자리표시자는 종속 노트 슬라이드에 포함된 자리표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

마스터 슬라이드 날짜-시간 자리표시자와 모든 자식 날짜-시간 자리표시자에 텍스트를 설정합니다. 자식 자리표시자는 종속 노트 슬라이드에 포함된 자리표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |