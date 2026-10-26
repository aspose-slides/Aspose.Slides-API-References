---
title: set_VerticalJustification()
second_title: Aspose.Slides for C++ API 참조
description: "그룹 문자의 수직 정렬. 객체를 기준선에 대해 정렬하는 방식을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, Top의 VerticalJustification은 객체의 위쪽이 기준선에 맞춰짐을 의미합니다; VerticalJustification이 Bottom으로 설정되면 객체의 아래쪽이 기준선에 맞춰집니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top"
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) 메서드

그룹 문자에 대한 수직 정렬. 객체를 기준선에 대해 정렬하는 방식을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, Top의 VerticalJustification은 객체의 위쪽이 기준선에 맞춰짐을 의미합니다; VerticalJustification이 Bottom으로 설정되면 객체의 아래쪽이 기준선에 맞춰집니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## 비고

예:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 관련 항목

* 열거형 [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [MathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)