---
title: get_Position()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "그룹화 문자의 위치. 기본값: Bottom"
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() 메서드

그룹화 문자 위치. 기본값: Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## 비고

예:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## 관련 항목

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [IMathGroupingCharacter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)