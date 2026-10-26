---
title: AddText()
second_title: Aspose.Slides for C++ API 참조
description: HTML 파일에 일반 텍스트를 추가하고, 특수 문자를 HTML 엔터티로 변환합니다. 줄 바꿈과 공백은 변환되지 않습니다.
type: docs
weight: 92
url: /ko/aspose.slides.export/htmlgenerator/addtext/
---
## HtmlGenerator::AddText(System::String) 메서드

HTML 파일에 일반 텍스트를 추가하고, 특수 문자를 HTML 엔터티로 교체합니다. 줄 바꿈 및 공백은 교체되지 않습니다.

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::String text) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 추가할 텍스트. |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) 메서드

HTML 파일에 일반 텍스트를 추가하고, 특수 문자를 HTML 엔터티로 교체합니다. 줄 바꿈 및 공백은 교체되지 않습니다.

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 추가할 텍스트. |

## HtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) 메서드

HTML 파일에 일반 텍스트를 추가하고, 특수 문자를 HTML 엔터티로 교체합니다. 줄 바꿈 및 공백은 교체되지 않습니다.

```cpp
void Aspose::Slides::Export::HtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 추가할 텍스트. |
| startIndex | **int32_t** | 추가할 부분의 시작 인덱스. |
| length | **int32_t** | 추가할 부분의 길이. |

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [HtmlGenerator](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)