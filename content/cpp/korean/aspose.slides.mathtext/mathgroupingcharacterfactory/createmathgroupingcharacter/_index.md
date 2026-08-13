---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides C++ API 레퍼런스
description: 수학 그룹화 문자를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) 메서드

수학 그룹화 문자를 생성합니다

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 그룹화 문자를 적용할 수학 요소 |
| character | char16_t | 그룹화 문자 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 그룹화 문자의 위치 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 수직 정렬 |

### 반환 값

새 그룹화 문자 요소

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) 메서드

수학 그룹화 문자를 생성합니다

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 그룹화 문자를 적용할 수학 요소 |

### 반환 값

새 그룹화 문자 요소

## 또 보기

* 열거형 [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathGroupingCharacter](../../imathgroupingcharacter/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathGroupingCharacterFactory](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)