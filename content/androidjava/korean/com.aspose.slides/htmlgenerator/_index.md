---
title: HtmlGenerator
second_title: Java API를 통한 Android용 Aspose.Slides
description: HTML 생성기.
type: docs
url: /ko/com.aspose.slides/htmlgenerator/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

HTML 생성기.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | 서식이 지정된 HTML 텍스트를 추가합니다. |
| [addHtml(char[] html)](#addHtml-char---) | 서식이 지정된 HTML 텍스트를 추가합니다. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | 서식이 지정된 HTML 텍스트를 추가합니다. |
| [addText(String text)](#addText-java.lang.String-) | 특수 문자를 HTML 엔터티로 변환하여 HTML 파일에 일반 텍스트를 추가합니다. |
| [addText(char[] text)](#addText-char---) | 특수 문자를 HTML 엔터티로 변환하여 HTML 파일에 일반 텍스트를 추가합니다. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | 특수 문자를 HTML 엔터티로 변환하여 HTML 파일에 일반 텍스트를 추가합니다. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | 속성 값을 인용하고 HTML 파일에 추가합니다. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | 속성 값을 인용하고 HTML 파일에 추가합니다. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | 속성 값을 인용하고 HTML 파일에 추가합니다. |
| [getSlideImageSize()](#getSlideImageSize--) | 슬라이드 이미지 크기를 반환합니다. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | 슬라이드 이미지 크기가 지정된 단위를 반환합니다. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | 슬라이드 이미지 크기가 지정된 단위의 CSS 코드를 반환합니다. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | 이전에 렌더링된 슬라이드의 인덱스를 반환하거나, 첫 번째 슬라이드가 렌더링 중이면 -1을 반환합니다. |
| [getSlideIndex()](#getSlideIndex--) | 현재 렌더링 중인 슬라이드의 인덱스를 반환합니다. |
| [getNextSlideIndex()](#getNextSlideIndex--) | 현재 슬라이드 뒤에 렌더링될 슬라이드의 인덱스를 반환하거나, 현재 마지막 슬라이드가 렌더링 중이면 -1을 반환합니다. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

서식이 지정된 HTML 텍스트를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| html | java.lang.String | 추가할 텍스트. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

서식이 지정된 HTML 텍스트를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| html | char[] | 추가할 텍스트. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

서식이 지정된 HTML 텍스트를 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| html | char[] | 추가할 텍스트. |
| startIndex | int | 추가할 부분의 시작 인덱스. |
| length | int | 추가할 부분의 길이. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

특수 문자를 HTML 엔터티로 변환하여 HTML 파일에 일반 텍스트를 추가합니다. 줄 바꿈과 공백은 변환되지 않습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 추가할 텍스트. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

특수 문자를 HTML 엔터티로 변환하여 HTML 파일에 일반 텍스트를 추가합니다. 줄 바꿈과 공백은 변환되지 않습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| text | char[] | 추가할 텍스트. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

특수 문자를 HTML 엔터티로 변환하여 HTML 파일에 일반 텍스트를 추가합니다. 줄 바꿈과 공백은 변환되지 않습니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| text | char[] | 추가할 텍스트. |
| startIndex | int | 추가할 부분의 시작 인덱스. |
| length | int | 추가할 부분의 길이. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

속성 값을 인용하고 HTML 파일에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 속성 값 문자열. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

속성 값을 인용하고 HTML 파일에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | char[] | 속성 값 문자열. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

속성 값을 인용하고 HTML 파일에 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | char[] | 속성 값 문자열. |
| startIndex | int | 추가할 부분의 시작 인덱스. |
| length | int | 추가할 부분의 길이. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

슬라이드 이미지 크기를 반환합니다. 읽기 전용 [SizeF](../../com.aspose.slides.android/sizef).

**반환값:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

슬라이드 이미지 크기가 지정된 단위를 반환합니다. 읽기 전용 [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**반환값:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

슬라이드 이미지 크기가 지정된 단위의 CSS 코드를 반환합니다. 읽기 전용 String.

**반환값:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

이전에 렌더링된 슬라이드의 인덱스를 반환하거나, 첫 번째 슬라이드가 렌더링 중이면 -1을 반환합니다. 읽기 전용 int.

**반환값:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

현재 렌더링 중인 슬라이드의 인덱스를 반환합니다. 읽기 전용 int.

**반환값:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

현재 슬라이드 뒤에 렌더링될 슬라이드의 인덱스를 반환하거나, 현재 마지막 슬라이드가 렌더링 중이면 -1을 반환합니다. 읽기 전용 int.

**반환값:**
int