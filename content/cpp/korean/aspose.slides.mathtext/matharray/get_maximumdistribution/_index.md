---
title: get_MaximumDistribution()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Maximum Distribution이 true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 간격을 두게 됩니다.
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/matharray/get_maximumdistribution/
---
## MathArray::get_MaximumDistribution() 메서드

최대 분포 true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 간격을 둡니다.

```cpp
bool Aspose::Slides::MathText::MathArray::get_MaximumDistribution() override
```

## 비고

예:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_MaximumDistribution(true);
```

## 참고

* 클래스 [MathArray](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)