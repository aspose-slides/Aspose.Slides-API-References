---
title: get_ExplicitBreak()
second_title: Aspose.Slides C++용 API 레퍼런스
description: "Explicit break는 Box 객체 시작 부분에 줄 바꿈이 있는지 여부를 지정하며, 줄이 Box 객체 시작 부분에서 래핑됩니다. 이전 수학 텍스트 줄에 있는 연산자의 번호를 지정하며, 해당 번호가 현재 수학 텍스트 줄의 정렬 기준점으로 사용됩니다. 가능한 값: 1..255 기본값: 0 (명시적 중단 없음)"
type: docs
weight: 118
url: /ko/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() 메서드

Explicit break는 Box 객체 시작 부분에 줄 바꿈이 있는지 여부를 지정하며, 줄이 Box 객체 시작 부분에서 래핑됩니다. 이전 수학 텍스트 줄에 있는 연산자의 번호를 지정하며, 해당 번호가 현재 수학 텍스트 줄의 정렬 기준점으로 사용됩니다. 가능한 값: 1..255 기본값: 0 (명시적 중단 없음)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## 비고

예:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 참조

* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)