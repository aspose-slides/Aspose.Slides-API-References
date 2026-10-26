---
title: Group()
second_title: Aspose.Slides C++ API 레퍼런스
description: 아래 중괄호를 사용하여 이 요소를 그룹에 배치합니다
type: docs
weight: 248
url: /ko/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() 메서드

이 요소를 아래 중괄호를 사용하여 그룹에 배치합니다

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### 반환값

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## 비고



예시: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) 메서드

이 요소를 아래 중괄호와 같은 그룹화 문자 또는 기타 문자를 사용하여 그룹에 배치합니다

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| character | char16_t | BOTTOM CURLY BRACKET (U+23DF)와 같은 그룹화 문자 또는 기타 문자 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 그룹화 문자의 위치 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 그룹 문자에 대한 수직 정렬. 객체가 기준선에 대해 어떻게 정렬되는지를 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, VerticalJustification이 Top으로 설정되면 객체의 상단이 기준선에 맞춰짐을 의미합니다; VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 맞춰집니다 |

### 반환값

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## 비고



예시: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## 참고

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)