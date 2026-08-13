---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true인 경우 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. 기본값은 true입니다.
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) 메서드


BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true인 경우 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. 기본값은 true입니다.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## 비고


예시:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 참고

* 클래스 [IMathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)