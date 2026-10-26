---
title: get_Position()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "바 라인의 위치. 기본값: 위"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() 메서드


바 라인의 위치. 기본값: Top

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## 비고


예제:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 참조

* 열거형 [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [IMathBar](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)