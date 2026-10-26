---
title: get_HideLeft()
second_title: Aspose.Slides for C++ API 참조
description: 왼쪽 가장자리 숨기기 (기본값은 false) - 테두리 상자의 왼쪽 가장자리 숨김 또는 표시 상태를 지정합니다.
type: docs
weight: 66
url: /ko/aspose.slides.mathtext/imathborderbox/get_hideleft/
---
## IMathBorderBox::get_HideLeft() 메서드

왼쪽 가장자리 숨기기 (default is false) - 테두리 상자 왼쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideLeft()=0
```

## 비고

예시: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideLeft(true);
```

## 참조

* 클래스 [IMathBorderBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)