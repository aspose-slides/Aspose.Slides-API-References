---
title: set_RowSpacing()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "배열 행 사이의 간격입니다. RowSpacingRule이 3으로 설정된 경우에만 사용되며, 이 경우 측정 단위는 포인트이며, Multiple인 경우 측정 단위는 반줄입니다. 기본값: 0"
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) 메서드


배열 행 사이의 간격입니다. RowSpacingRule이 3으로 설정된 경우에만 사용되며, 이 경우 측정 단위는 포인트입니다. Multiple로 설정된 경우에는 측정 단위가 반줄입니다. 기본값: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## 비고


예제: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 관련 항목

* 클래스 [MathArray](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)