---
title: get_RowSpacingRule()
second_title: Aspose.Slides for C++ API 참조
description: "배열 요소 사이의 수직 간격 유형 기본값: SingleLineGap"
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/matharray/get_rowspacingrule/
---
## MathArray::get_RowSpacingRule() 메서드


배열 요소 사이의 수직 간격 유형 기본값: SingleLineGap

```cpp
MathRowSpacingRule Aspose::Slides::MathText::MathArray::get_RowSpacingRule() override
```

## 비고


예시: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## 참고

* 열거형 [MathRowSpacingRule](../../mathrowspacingrule/)
* 클래스 [MathArray](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)