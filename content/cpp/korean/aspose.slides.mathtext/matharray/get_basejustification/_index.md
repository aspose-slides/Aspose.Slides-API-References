---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API 참조
description: "배열이 주변 텍스트에 대해 정렬되는 방식을 지정합니다. 배열 외부의 텍스트는 배열 객체의 아래쪽, 위쪽 또는 중앙에 맞출 수 있습니다. 기본값: Center"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() 메서드

배열이 주변 텍스트에 대해 정렬되는 방식을 지정합니다. 배열 외부의 텍스트는 배열 객체의 아래쪽, 위쪽 또는 중앙에 맞출 수 있습니다. 기본값: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## 비고

예시:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 참고

* 열거형 [MathVerticalAlignment](../../mathverticalalignment/)
* 클래스 [MathArray](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)