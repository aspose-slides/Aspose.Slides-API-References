---
title: HtmlFormatter
second_title: Aspose.Slides for Java API 레퍼런스
description: HTML 파일 템플릿을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/htmlformatter/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

HTML 파일 템플릿을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | 슬라이드가 하나씩 아래에 배치된 순서대로 구성된 간단한 문서 뷰용 HTML 포매터를 생성하고 반환합니다. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | 슬라이드가 하나씩 차례대로 표시되는 간단한 슬라이드 쇼 HTML 포매터를 생성하고 반환합니다. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | 사용자 정의 콜백 기반 HTML 생성용 포매터를 생성하고 반환합니다. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

슬라이드가 하나씩 아래에 배치된 순서대로 구성된 간단한 문서 뷰용 HTML 포매터를 생성하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| css | java.lang.String | 이 파일에 사용할 CSS를 지정합니다. |
| showSlideTitle | boolean | 슬라이드 이미지 위에 슬라이드 제목이 있는 경우 제목을 추가합니다. |

**반환값:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) 객체.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

슬라이드가 하나씩 차례대로 표시되는 간단한 슬라이드 쇼 HTML 포매터를 생성하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| css | java.lang.String | 사용되는 CCS 파일의 URL을 지정합니다. |
| showSlideTitle | boolean | 슬라이드 이미지 위에 슬라이드 제목이 있는 경우 제목을 추가합니다. |

**반환값:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) 객체.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

사용자 정의 콜백 기반 HTML 생성을 위한 포매터를 생성하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML 파일 생성을 제어하는 콜백 인터페이스입니다. |

**반환값:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) 객체.