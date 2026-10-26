---
title: set_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides C++ API 레퍼런스
description: Strikethrough Bottom-Left to Top-Right (default is false). 테두리 상자 왼쪽 아래 모서리에서 오른쪽 위 모서리까지 대각선 횡단선의 숨김 또는 표시 상태를 지정합니다.
type: docs
weight: 183
url: /ko/aspose.slides.mathtext/imathborderbox/set_strikethroughbottomlefttotopright/
---
## IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool) 메서드

Strikethrough Bottom-Left to Top-Right (default is false). 테두리 상자 왼쪽 아래 모서리에서 오른쪽 위 모서리까지 대각선 횡단선의 숨김 또는 표시 상태를 지정합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool value)=0
```

## 비고

예제:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## 참고

* 클래스 [IMathBorderBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)