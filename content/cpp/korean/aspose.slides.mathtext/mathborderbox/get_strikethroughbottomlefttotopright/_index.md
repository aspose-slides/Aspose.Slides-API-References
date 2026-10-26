---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Strikethrough Bottom-Left to Top-Right (기본값은 false). 테두리 상자의 좌하단 모서리에서 우상단 모서리까지 그려지는 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.
type: docs
weight: 170
url: /ko/aspose.slides.mathtext/mathborderbox/get_strikethroughbottomlefttotopright/
---
## MathBorderBox::get_StrikethroughBottomLeftToTopRight() 메서드


Strikethrough Bottom-Left to Top-Right (default is false). 숨김 또는 표시 상태를 지정합니다. 이 대각선 취소선은 테두리 상자의 좌하단 모서리에서 우상단 모서리까지 그려집니다.

```cpp
bool Aspose::Slides::MathText::MathBorderBox::get_StrikethroughBottomLeftToTopRight() override
```

## 비고


예제: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## 참고

* 클래스 [MathBorderBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)