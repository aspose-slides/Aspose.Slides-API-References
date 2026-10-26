---
title: Group()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다
type: docs
weight: 235
url: /ko/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() 메서드

이 요소를 하단 중괄호를 사용하여 그룹에 배치합니다

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### 반환값

새 인스턴스 유형 [IMathGroupingCharacter](../../imathgroupingcharacter/)
## 비고



예: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) 메서드

이 요소를 하단 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 그룹에 배치합니다

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| character | char16_t | 하단 중괄호 (U+23DF)와 같은 그룹화 문자 또는 기타 문자 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 그룹화 문자의 위치 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 그룹 문자의 수직 정렬. 객체가 기준선과 어떻게 정렬되는지 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, VerticalJustification이 Top이면 객체의 상단이 기준선에 놓이며, VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 놓입니다. |

### 반환값

새 인스턴스 유형 [IMathGroupingCharacter](../../imathgroupingcharacter/)
## 비고



예: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## 참조

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)