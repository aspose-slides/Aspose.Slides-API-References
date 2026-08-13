---
title: AddText()
second_title: Aspose.Slides C++ API 레퍼런스
description: HTML 파일에 일반 텍스트를 추가하며, 특수 문자를 HTML 엔티티로 교체합니다. 줄 바꿈 및 공백은 교체되지 않습니다.
type: docs
weight: 92
url: /ko/aspose.slides.export/ihtmlgenerator/addtext/
---
## IHtmlGenerator::AddText(System::String) 메서드

HTML 파일에 일반 텍스트를 추가하며, 특수 문자를 HTML 엔티티로 교체합니다. 줄 바꿈 및 공백은 교체되지 않습니다.

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::String text)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | 추가할 텍스트. |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) 메서드

HTML 파일에 일반 텍스트를 추가하며, 특수 문자를 HTML 엔티티로 교체합니다. 줄 바꿈 및 공백은 교체되지 않습니다.

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 추가할 텍스트. |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) 메서드

HTML 파일에 일반 텍스트를 추가하며, 특수 문자를 HTML 엔티티로 교체합니다. 줄 바꿈 및 공백은 교체되지 않습니다.

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 추가할 텍스트. |
| startIndex | **int32_t** | 추가할 구간의 시작 인덱스. |
| length | **int32_t** | 추가할 구간의 길이. |

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IHtmlGenerator](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)