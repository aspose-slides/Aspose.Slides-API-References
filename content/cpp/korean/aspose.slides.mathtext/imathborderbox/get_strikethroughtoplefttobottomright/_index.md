---
title: get_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Strikethrough Top-Left to Bottom-Right (기본값은 false)입니다. 테두리 상자의 왼쪽 상단 모서리에서 오른쪽 하단 모서리까지 대각선 취소선의 표시 여부를 지정합니다.
type: docs
weight: 196
url: /ko/aspose.slides.mathtext/imathborderbox/get_strikethroughtoplefttobottomright/
---
## IMathBorderBox::get_StrikethroughTopLeftToBottomRight() 메서드

Strikethrough Top-Left to Bottom-Right (기본값은 false). 테두리 상자 왼쪽 상단 모서리에서 오른쪽 하단 모서리까지 대각선 취소선의 표시 여부를 지정합니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughTopLeftToBottomRight()=0
```

## 비고

예:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## 참고

* 클래스 [IMathBorderBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)