---
title: set_Position()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "바 라인의 위치. 기본값: Top"
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathbar/set_position/
---
## MathBar::set_Position(MathTopBotPositions) 메서드


바 라인의 위치. 기본값: Top

```cpp
void Aspose::Slides::MathText::MathBar::set_Position(MathTopBotPositions value) override
```

## 비고


예제: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## 참고

* 열거형 [MathTopBotPositions](../../mathtopbotpositions/)
* 클래스 [MathBar](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)