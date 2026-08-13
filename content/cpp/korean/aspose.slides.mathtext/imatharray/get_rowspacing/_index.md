---
title: get_RowSpacing()
second_title: Aspose.Slides for C++ API 참조
description: "배열 행 사이의 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 이 경우 측정 단위가 포인트이며, Multiple인 경우 측정 단위는 반줄입니다. 기본값: 0"
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() 메서드

배열 행 사이의 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 이 경우 측정 단위가 포인트이며, Multiple인 경우 측정 단위는 반줄입니다. 기본값: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## 비고

예시:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 참고

* 클래스 [IMathArray](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)