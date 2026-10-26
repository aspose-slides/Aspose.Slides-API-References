---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: BeginningCharacter, SeparatorCharacter, EndingCharacter의 증가 방식을 지정합니다. true이면 구분자가 피연산자 높이에 맞게 수직으로 증가합니다. 기본값은 true입니다.
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() 메서드


BeginningCharacter, SeparatorCharacter, EndingCharacter의 증가 방식을 지정합니다. true이면 구분자가 피연산자 높이에 맞게 수직으로 증가합니다. 기본값은 true입니다.

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## 비고


예시: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 관련 항목

* 클래스 [MathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)