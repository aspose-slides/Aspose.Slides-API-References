---
title: CreateMathBar()
second_title: Aspose.Slides for C++ API 참조
description: 요소에 적용하여 수학 바를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) 메서드

요소에 적용하여 수학 바를 생성합니다

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 바를 적용할 수학 요소 |

### 반환값

새 수학 바 요소

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) 메서드

요소에 적용하여 수학 바를 생성합니다

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 바를 적용할 수학 요소 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 바의 위치 |

### 반환값

새 수학 바 요소

## 관련 내용

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBar](../../imathbar/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathBarFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)