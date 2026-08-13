---
title: MathPortion()
second_title: Aspose.Slides for C++ API 레퍼런스
description: MathPortion 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() 생성자


[MathPortion](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## 비고


예시:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## 참조

* 클래스 [MathPortion](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)