---
title: CreateMathAccent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 수학 요소에 기본 억양 문자 값을 적용하는 수학 억양을 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) method

지정된 수학 요소에 기본 억양 문자 값을 적용하는 수학 억양을 생성합니다

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 억양을 적용할 수학 요소 |

### 반환 값

새 수학 억양

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) method

지정된 수학 요소에 억양을 적용하는 수학 억양을 생성합니다

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 억양을 적용할 수학 요소 |
| accentCharacter | char16_t | 억양 문자 |

### 반환 값

새 수학 억양

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathAccent](../../imathaccent/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathAccentFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)