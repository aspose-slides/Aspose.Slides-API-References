---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API 참조
description: "그룹 문자에 대한 수직 정렬. 객체를 기준선에 대해 정렬하는 방식을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때 Top의 VerticalJustification은 객체의 상단이 기준선에 놓임을 의미합니다; Bottom으로 설정하면 객체의 하단이 기준선에 놓입니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top"
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() 메서드

그룹 문자에 대한 수직 정렬입니다. 객체를 기준선에 대해 정렬하는 방식을 지정합니다. 예를 들어, 그룹 문자가 객체 위에 있을 때 Top의 VerticalJustification은 객체의 상단이 기준선에 놓임을 의미합니다; Bottom으로 설정하면 객체의 하단이 기준선에 놓입니다. 기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## 비고

예제:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## 참조

* 열거형 [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [IMathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)