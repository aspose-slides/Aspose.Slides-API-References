---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "배열이 주변 텍스트와 상대적으로 정렬되는 방식을 지정합니다. 배열 외부의 텍스트는 배열 객체의 아래쪽, 위쪽 또는 가운데에 맞출 수 있습니다. 기본값: Center"
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) 메서드


배열이 주변 텍스트와 상대적인 정렬 방식을 지정합니다. 배열 밖의 텍스트는 배열 객체의 아래쪽, 위쪽 또는 가운데에 맞출 수 있습니다. 기본값: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## 비고


예시: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## 관련 항목

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)