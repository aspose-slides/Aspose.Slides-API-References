---
title: CreateMathAccent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 수학 요소에 기본 악센트 문자 값을 적용하는 수학 악센트를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) 메서드

지정된 수학 요소에 기본 악센트 문자 값을 적용한 수학 악센트를 생성합니다

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 악센트를 적용할 수학 요소 |
| accentCharacter | char16_t | 악센트 문자 |

### 반환 값

새 수학 악센트

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) 메서드

지정된 수학 요소에 적용되는 수학 악센트를 생성합니다

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 악센트를 적용할 수학 요소 |
| accentCharacter | char16_t | 악센트 문자 |

### 반환 값

새 수학 악센트

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathAccent](../../imathaccent/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathAccentFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)