---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "그룹 문자의 수직 정렬. 기준선에 대한 객체의 정렬을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, Top인 VerticalJustification은 객체의 상단이 기준선에 놓인다는 것을 의미합니다; VerticalJustification이 Bottom으로 설정된 경우, 객체의 하단이 기준선에 놓입니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top"
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() 메서드

그룹 문자에 대한 수직 정렬. 기준선에 대한 객체의 정렬을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때, Top인 VerticalJustification은 객체의 상단이 기준선에 놓인다는 것을 의미합니다; VerticalJustification이 Bottom으로 설정된 경우, 객체의 하단이 기준선에 놓입니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## 비고

예제:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 참고

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [MathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)