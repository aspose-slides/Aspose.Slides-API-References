---
title: get_Position()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "그룹화 문자 위치. 기본값: Bottom"
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() 메서드


그룹화 문자 위치. 기본값: Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
```

## 비고


예제: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 참고

* 열거형 [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [MathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)