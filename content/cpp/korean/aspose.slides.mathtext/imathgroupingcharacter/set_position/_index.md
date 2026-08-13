---
title: set_Position()
second_title: C++용 Aspose.Slides API 레퍼런스
description: "그룹화 문자 위치. 기본값: Bottom"
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/imathgroupingcharacter/set_position/
---
## IMathGroupingCharacter::set_Position(MathTopBotPositions) 메서드


그룹화 문자 위치. 기본값: Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Position(MathTopBotPositions value)=0
```

## 비고


예: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 참고

* 열거형 [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [IMathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)