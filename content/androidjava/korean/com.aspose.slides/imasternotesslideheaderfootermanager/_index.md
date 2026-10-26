---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 마스터 노트 슬라이드의 바닥글, 날짜-시간, 페이지 번호 자리 표시자와 모든 자식 자리 표시자의 동작을 담당하는 관리자를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

마스터 노트 슬라이드의 바닥글, 날짜-시간, 페이지 번호 자리 표시자와 모든 자식 자리 표시자를 보유하는 동작을 관리하는 매니저를 나타냅니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | 마스터 노트 슬라이드 헤더 자리 표시자와 모든 자식 헤더 자리 표시자의 가시성을 변경합니다. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | 마스터 노트 슬라이드 헤더 자리 표시자와 모든 자식 헤더 자리 표시자에 텍스트를 설정합니다. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 마스터 노트 슬라이드 바닥글 자리 표시자와 모든 자식 바닥글 자리 표시자의 가시성을 변경합니다. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 마스터 노트 슬라이드 페이지 번호 자리 표시자와 모든 자식 페이지 번호 자리 표시자의 가시성을 변경합니다. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 마스터 노트 슬라이드 날짜-시간 자리 표시자와 모든 자식 날짜-시간 자리 표시자의 가시성을 변경합니다. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 마스터 노트 슬라이드 바닥글 자리 표시자와 모든 자식 바닥글 자리 표시자에 텍스트를 설정합니다. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 마스터 노트 슬라이드 날짜-시간 자리 표시자와 모든 자식 날짜-시간 자리 표시자에 텍스트를 설정합니다. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

마스터 노트 슬라이드 헤더 자리 표시자와 모든 자식 헤더 자리 표시자의 가시성을 변경합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 헤더 자리 표시자를 보이게 하고, 그 외 - 숨깁니다. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

마스터 노트 슬라이드 헤더 자리 표시자와 모든 자식 헤더 자리 표시자에 텍스트를 설정합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

마스터 노트 슬라이드 바닥글 자리 표시자와 모든 자식 바닥글 자리 표시자의 가시성을 변경합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 바닥글 자리 표시자를 보이게 하고, 그 외 - 숨깁니다. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

마스터 노트 슬라이드 페이지 번호 자리 표시자와 모든 자식 페이지 번호 자리 표시자의 가시성을 변경합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 페이지 번호 자리 표시자를 보이게 하고, 그 외 - 숨깁니다. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

마스터 노트 슬라이드 날짜-시간 자리 표시자와 모든 자식 날짜-시간 자리 표시자의 가시성을 변경합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 날짜-시간 자리 표시자를 보이게 하고, 그 외 - 숨깁니다. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

마스터 노트 슬라이드 바닥글 자리 표시자와 모든 자식 바닥글 자리 표시자에 텍스트를 설정합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

마스터 노트 슬라이드 날짜-시간 자리 표시자와 모든 자식 날짜-시간 자리 표시자에 텍스트를 설정합니다. 자식 자리 표시자는 종속 노트 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 노트 슬라이드는 마스터 노트 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |