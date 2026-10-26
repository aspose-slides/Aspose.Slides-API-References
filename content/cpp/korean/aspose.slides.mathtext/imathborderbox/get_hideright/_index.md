---
title: get_HideRight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Hide Right Edge (기본값은 false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/imathborderbox/get_hideright/
---
## IMathBorderBox::get_HideRight() 메서드


Hide Right Edge (default is false) - 테두리 상자의 오른쪽 가장자리의 숨김 또는 표시 상태를 지정합니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideRight()=0
```

## 비고


예:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideRight(true);
```

## 참조

* 클래스 [IMathBorderBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)