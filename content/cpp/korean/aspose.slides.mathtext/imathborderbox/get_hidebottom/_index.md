---
title: get_HideBottom()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하단 가장자리 숨기기(기본값은 false) - 경계 상자의 하단 가장자리 숨김 또는 표시 상태를 지정합니다.
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() 메서드

하단 가장자리 숨기기(기본값은 false) - 가장자리 박스의 하단 가장자리 숨김 또는 표시 상태를 지정합니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```

## 비고

예제:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## 참조

* 클래스 [IMathBorderBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)