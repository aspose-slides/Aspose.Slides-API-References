---
title: get_ExplicitBreak()
second_title: Aspose.Slides C++ API 레퍼런스
description: "Explicit break는 Box 객체의 시작 부분에 줄 바꿈이 있는지 여부를 지정하며, 줄이 Box 객체의 시작에서 래핑됩니다. 현재 수학 텍스트 줄의 정렬 기준으로 사용될 이전 수학 텍스트 줄에 있는 연산자의 번호를 지정합니다. 가능한 값: 1..255 기본값: 0 (명시적 줄 바꿈 없음)"
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() 메서드

명시적 줄바꿈는 Box 객체의 시작 부분에 줄바꿈이 있는지 여부를 지정하며, 줄이 Box 객체의 시작에서 래핑됩니다. 현재 수학 텍스트 줄의 정렬 기준으로 사용될 이전 수학 텍스트 줄에 있는 연산자의 번호를 지정합니다. 가능한 값: 1..255 기본값: 0 (명시적 줄바꿈 없음)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## 비고


예시: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 참고

* 클래스 [IMathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)