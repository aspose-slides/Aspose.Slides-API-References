---
title: set_RowSpacing()
second_title: Aspose.Slides C++용 API 참조
description: "배열 행 사이의 간격은 RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 이 경우 측정 단위가 포인트이며, Multiple인 경우 측정 단위가 반행입니다. 기본값: 0"
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) 메서드

배열 행 사이의 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 이 경우 측정 단위는 포인트이며, Multiple인 경우 측정 단위는 반행입니다. 기본값: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## 비고

예:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## 참고

* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)