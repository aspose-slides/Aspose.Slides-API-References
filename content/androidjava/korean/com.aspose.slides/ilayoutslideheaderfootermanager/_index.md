---
title: ILayoutSlideHeaderFooterManager
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 레이아웃 슬라이드 푸터, 날짜-시간, 페이지 번호 자리 표시자와 모든 하위 자리 표시자의 동작을 담당하는 관리자를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

레이아웃 슬라이드 푸터, 날짜-시간, 페이지 번호 자리 표시자와 모든 하위 자리 표시자의 동작을 담당하는 관리자를 나타냅니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | 레이아웃 슬라이드 푸터 자리 표시자와 모든 하위 푸터 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 마스터 슬라이드를 사용하고 의존합니다. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | 레이아웃 슬라이드 페이지 번호 자리 표시자와 모든 하위 페이지 번호 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | 레이아웃 슬라이드 날짜-시간 자리 표시자와 모든 하위 날짜-시간 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | 레이아웃 슬라이드 푸터 자리 표시자와 모든 하위 푸터 자리 표시자에 텍스트를 설정합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | 레이아웃 슬라이드 날짜-시간 자리 표시자와 모든 하위 날짜-시간 자리 표시자에 텍스트를 설정합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

레이아웃 슬라이드 푸터 자리 표시자와 모든 하위 푸터 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 마스터 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 푸터 자리 표시자를 표시하고, false - 숨깁니다. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

레이아웃 슬라이드 페이지 번호 자리 표시자와 모든 하위 페이지 번호 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 페이지 번호 자리 표시자를 표시하고, false - 숨깁니다. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

레이아웃 슬라이드 날짜-시간 자리 표시자와 모든 하위 날짜-시간 자리 표시자의 가시성을 변경합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 날짜-시간 자리 표시자를 표시하고, false - 숨깁니다. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

레이아웃 슬라이드 푸터 자리 표시자와 모든 하위 푸터 자리 표시자에 텍스트를 설정합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트입니다. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

레이아웃 슬라이드 날짜-시간 자리 표시자와 모든 하위 날짜-시간 자리 표시자에 텍스트를 설정합니다. 하위 자리 표시자는 종속 슬라이드에 포함된 자리 표시자를 의미합니다. 종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트입니다. |