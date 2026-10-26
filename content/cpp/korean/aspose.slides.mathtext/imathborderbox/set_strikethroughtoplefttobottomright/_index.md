---
title: set_StrikethroughTopLeftToBottomRight()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 좌상단에서 우하단으로 취소선 (기본값은 false). 경계 상자의 좌상단 모서리에서 우하단 모서리까지 그려지는 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.
type: docs
weight: 209
url: /ko/aspose.slides.mathtext/imathborderbox/set_strikethroughtoplefttobottomright/
---
## IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool) 메서드

좌상단에서 우하단으로 취소선 (기본값은 false). 경계 상자의 좌상단 모서리에서 우하단 모서리까지 그려지는 대각선 취소선의 숨김 또는 표시 상태를 지정합니다.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughTopLeftToBottomRight(bool value)=0
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