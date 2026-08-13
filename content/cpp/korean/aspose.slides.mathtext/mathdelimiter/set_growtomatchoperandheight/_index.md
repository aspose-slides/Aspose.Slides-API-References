---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 참조
description: BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true인 경우 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. 기본값은 true입니다.
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) 메서드


BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true일 때, 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. 기본값은 true입니다.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## 비고


Example: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 참조

* 클래스 [MathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)