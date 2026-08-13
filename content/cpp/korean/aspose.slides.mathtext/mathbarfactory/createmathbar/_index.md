---
title: CreateMathBar()
second_title: Aspose.Slides C++ API 레퍼런스
description: 요소에 적용하여 수학 바를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) 메서드

요소에 적용하여 수학 바를 생성합니다

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 수학 바를 적용할 수학 요소 |

### 반환 값

새 수학 바 요소

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) 메서드

요소에 적용하여 수학 바를 생성합니다

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 수학 바를 적용할 수학 요소 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 바의 위치 |

### 반환 값

새 수학 바 요소

## 참조

* 열거형 [MathTopBotPositions](../../mathtopbotpositions/)
* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBar](../../imathbar/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBarFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)