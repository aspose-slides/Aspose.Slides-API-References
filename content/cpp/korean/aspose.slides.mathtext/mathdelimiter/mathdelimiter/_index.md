---
title: MathDelimiter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 요소를 단일 기본 인수로 사용하여 MathDelimiter를 초기화합니다
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) 생성자

[MathDelimiter](../)을 지정된 요소를 단일 기본 인수로 사용하여 초기화합니다

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 구분 기호가 적용되는 기본 요소입니다. null일 수 있습니다. |

## 비고



예제: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)