---
title: get_RowSpacing()
second_title: Aspose.Slides for C++ API 참조
description: "배열의 행 사이 간격. RowSpacingRule가 3으로 설정된 경우에만 사용됩니다. 이 경우 측정 단위는 포인트이며, Multiple인 경우 측정 단위는 절반 라인입니다. 기본값: 0"
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() 메서드

배열의 행 사이 간격. RowSpacingRule가 3으로 설정된 경우에만 사용됩니다. 이 경우 측정 단위는 포인트이며, Multiple인 경우 측정 단위는 절반 라인입니다. 기본값: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## 비고

예제:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 참고

* 클래스 [MathArray](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)