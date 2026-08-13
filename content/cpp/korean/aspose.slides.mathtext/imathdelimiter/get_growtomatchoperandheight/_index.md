---
title: get_GrowToMatchOperandHeight()
second_title: C++용 Aspose.Slides API 레퍼런스
description: BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. true일 경우 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. 기본값은 true입니다.
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() 메서드


true일 때 BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장을 지정합니다. 구분자는 피연산자 높이에 맞게 수직으로 성장합니다. 기본값은 true입니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## 비고


예제: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 또한 보기

* 클래스 [IMathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)