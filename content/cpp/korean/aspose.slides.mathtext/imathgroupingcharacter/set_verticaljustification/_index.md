---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "그룹 문자에 대한 수직 정렬. 객체를 기준선에 대해 정렬하는 방식을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때 Top의 VerticalJustification은 객체의 상단이 기준선에 놓인다는 것을 의미합니다; VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 놓입니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top"
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) 메서드

그룹 문자에 대한 수직 정렬. 객체를 기준선에 대해 정렬하는 방식을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때 Top의 VerticalJustification은 객체의 상단이 기준선에 놓인다는 것을 의미합니다; VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 놓입니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## 비고

예:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 참조

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [IMathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)