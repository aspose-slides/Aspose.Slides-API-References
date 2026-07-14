---
title: IPresentationHeaderFooterManager
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션의 모든 바닥글, 날짜-시간 및 페이지 번호 자리 표시자 동작을 보유하는 관리자를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipresentationheaderfootermanager/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

프레젠테이션의 모든 바닥글, 날짜-시간 및 페이지 번호 자리 표시자 동작을 보유하는 관리자를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 머리글 자리 표시자의 가시성을 변경합니다. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | 마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드를 포함한 모든 바닥글 자리 표시자의 가시성을 변경합니다. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | 마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드를 포함한 모든 페이지 번호 자리 표시자의 가시성을 변경합니다. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | 마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드를 포함한 모든 날짜-시간 자리 표시자의 가시성을 변경합니다. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | 노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 머리글 자리 표시자에 텍스트를 설정합니다. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | 마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드에 모든 바닥글 자리 표시자에 텍스트를 설정합니다. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | 마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드에 모든 날짜-시간 자리 표시자에 텍스트를 설정합니다. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | 모든 제목 슬라이드와 첫 번째 레이아웃 슬라이드에 대한 바닥글, 날짜-시간 및 페이지 번호 자리 표시자의 가시성을 변경합니다. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 머리글 자리 표시자의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 머리글 자리 표시자를 보이게 하고, false - 숨깁니다. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드를 포함한 모든 바닥글 자리 표시자의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 바닥글 자리 표시자를 보이게 하고, false - 숨깁니다. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드를 포함한 모든 페이지 번호 자리 표시자의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 페이지 번호 자리 표시자를 보이게 하고, false - 숨깁니다. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드를 포함한 모든 날짜-시간 자리 표시자의 가시성을 변경합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 날짜-시간 자리 표시자를 보이게 하고, false - 숨깁니다. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

노트 마스터, 노트 슬라이드 및 핸드아웃 마스터를 포함한 모든 머리글 자리 표시자에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드에 모든 바닥글 자리 표시자에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

마스터 슬라이드, 레이아웃 슬라이드 및 일반 슬라이드에 모든 날짜-시간 자리 표시자에 텍스트를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 설정할 텍스트. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

모든 제목 슬라이드와 첫 번째 레이아웃 슬라이드에 대한 바닥글, 날짜-시간 및 페이지 번호 자리 표시자의 가시성을 변경합니다. 제목 슬라이드 – 첫 번째 레이아웃 슬라이드를 기반으로 하는 슬라이드(첫 번째 레이아웃 유형에 관계없이).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| isVisible | boolean | true - 자리 표시자를 보이게 하고, false - 숨깁니다. |